\# Projeto de Análise de Dados - Calculadora de Viabilidade de Livro



Este repositório contém um projeto desenvolvido para prever os custos e a margem de lucro na publicação/reimpressão de um livro, permitindo avaliar a viabilidade financeira de um projeto editorial.



\---



\## Descrição do Código em Python



O arquivo `calculadora\_viabilidade.ipynb` é um script interativo que solicita ao usuário informações essenciais sobre os custos de produção de um livro:



\- \*\*Entradas do usuário:\*\*

&#x20; - Nome do livro

&#x20; - Quantidade da tiragem (número de exemplares)

&#x20; - Preço de capa/venda por unidade

&#x20; - Custos fixos (revisão, diagramação, ilustração)

&#x20; - Custos variáveis (custo de impressão por exemplar e preço do papel)



\- \*\*Cálculos realizados:\*\*

&#x20; 1. Custo total da tiragem = `custo\_impressao \* tiragem`

&#x20; 2. Investimento fixo total = `revisao + diagramacao + ilustracao + preco\_papel`

&#x20; 3. Custo total do projeto = `custo\_tiragem + investimento\_fixo`

&#x20; 4. Receita total esperada = `preco\_venda \* tiragem`

&#x20; 5. Lucro bruto = `receita\_total - custo\_total`

&#x20; 6. Percentual de margem de lucro = `(lucro / receita\_total) \* 100`



\- \*\*Resultado:\*\*

&#x20; O programa exibe o resumo financeiro detalhado e avalia se o projeto é viável com base na margem de lucro calculada.



\---



\## Como Executar o Arquivo Executável (`executar.sh`)



O arquivo `executar.sh` é um script Shell desenvolvido para automatizar a execução do ambiente Linux / WSL.



\### Passo a passo para execução no terminal Linux/WSL:



1\. \*\*Abra o terminal\*\* do Linux ou WSL (Ubuntu).

2\. \*\*Navegue até o diretório\*\* onde o repositório foi clonado/baixado:

&#x20;  ```bash

&#x20;  cd /caminho/para/o/repositorio

