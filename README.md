## Descrição do Código em Python

O arquivo `calculadora_de_viabilidade_de_livro_nicoll_siqueira_da_rosa.py` é um script interativo que solicita ao usuário informações essenciais sobre os custos de produção de um livro:

- **Entradas do usuário:**
  - Nome do livro
  - Quantidade da tiragem (número de exemplares)
  - Preço de capa/venda por unidade
  - Custos fixos (revisão, diagramação, ilustração)
  - Custos variáveis (custo de impressão por exemplar e preço do papel)

- **Cálculos realizados:**
  1. Custo total da tiragem = `custo_impressao * tiragem`
  2. Investimento fixo total = `revisao + diagramacao + ilustracao + preco_papel`
  3. Custo total do projeto = `custo_tiragem + investimento_fixo`
  4. Receita total esperada = `preco_venda * tiragem`
  5. Lucro bruto = `receita_total - custo_total`
  6. Percentual de margem de lucro = `(lucro / receita_total) * 100`

- **Resultado:**
  O programa exibe o resumo financeiro detalhado e avalia se o projeto é viável com base na margem de lucro calculada.


### Passo a passo para execução no terminal Linux/WSL:

1. Abra o terminal do Linux ou WSL (Ubuntu).
2. Navegue até o diretório onde o repositório foi clonado/baixado:
   ```bash
   cd /caminho/para/o/repositorio