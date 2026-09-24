# Atividade Prática: PySpark

Repositório dedicado à resolução e estudo de exercícios utilizando **PySpark**, contendo os códigos e respostas desenvolvidos para a atividade acadêmica. O objetivo da atividade é praticar conceitos de processamento de grandes volumes de dados com Spark, trabalhando com operações como seleção, filtragem, agrupamento, criação de colunas e junção de DataFrames.

Além da implementação dos códigos, a atividade também aborda conceitos importantes do Spark, como **schema**, **transformações e ações**, **lazy evaluation** e **shuffle**.

## Tecnologias Utilizadas

- **Python** / **PySpark**
- **Google Colab** — ambiente de desenvolvimento e execução
- **Apache Spark** — processamento dos dados
- **Git & GitHub** — controle de versão e entrega do projeto

---

## Base de Dados

A atividade utiliza uma base contendo mais de **4 milhões de registros de corridas de táxi de Nova York**, disponibilizada para realização dos exercícios.

O principal arquivo utilizado é:

- `nyc_tripdata_2024_sample_4M.csv`

Também é utilizada a tabela:

- `taxi_zone_lookup.csv`

Essa segunda base permite relacionar os códigos de localização das corridas com informações como o **Borough** e a **Zone** correspondente.

---

## Estrutura do Repositório

O projeto está organizado da seguinte forma:

- `*.ipynb` — Notebook contendo a resolução das questões da atividade, incluindo os códigos desenvolvidos em PySpark e as respostas das questões descritivas.

---

## Conteúdos Trabalhados

Durante a atividade foram utilizados diferentes recursos do PySpark, como:

- carregamento de arquivos CSV;
- utilização e definição de schemas;
- seleção de colunas com `select`;
- filtragem de registros com `filter`;
- contagem de registros com `count`;
- agrupamento de dados com `groupBy`;
- funções de agregação;
- criação de novas colunas;
- ordenação de resultados;
- operações de `join` entre DataFrames;
- transformações e ações;
- *lazy evaluation*;
- *shuffle* e seu impacto no desempenho.

---

## Como Executar o Projeto

Como o código foi desenvolvido utilizando o **Google Colab**, ele pode ser executado de duas formas:

### 1. Diretamente pelo navegador

- Clique no arquivo `.ipynb` correspondente dentro deste repositório.
- Clique na opção **"Open in Colab"**, caso esteja disponível.

Outra opção é acessar o [Google Colab](https://colab.research.google.com/), selecionar a aba **GitHub** e inserir o link deste repositório.

### 2. Localmente

Clone o repositório na máquina:

```bash
git clone LINK_DO_REPOSITORIO
