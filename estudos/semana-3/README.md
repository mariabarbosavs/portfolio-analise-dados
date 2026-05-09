# Projeto 1 — Exploração Inicial de Gastos Pessoais com Pandas

## Sobre o projeto

Este projeto faz parte da minha terceira semana de estudos em Análise de Dados.

O objetivo foi realizar uma primeira exploração de um dataset de gastos pessoais utilizando Python e Pandas, com foco em leitura de arquivos, inspeção inicial dos dados, entendimento das colunas e seleção das informações mais relevantes para análise.

## Tecnologias utilizadas

- Python
- Pandas
- Jupyter Notebook
- CSV
- GitHub

## Técnicas praticadas

- Leitura de arquivo CSV com `pd.read_csv()`
- Inspeção inicial com `head()`, `info()` e `describe()`
- Verificação de linhas e colunas com `shape`
- Análise dos tipos de dados com `dtypes`
- Seleção de colunas
- Primeiras análises manuais com soma, média, mínimo e máximo
- Agrupamento inicial por categoria

## Sobre o dataset

O dataset contém registros simulados de gastos pessoais.

Cada linha representa um lançamento de gasto, com informações como:

- data
- descrição
- categoria
- valor
- forma de pagamento
- cidade
- parcelamento
- observação

## Principais descobertas

Durante a exploração inicial, identifiquei que:

- O dataset possui 121 linhas e 9 colunas.
- A coluna `valor` é a principal coluna numérica para análise financeira.
- As colunas `data`, `categoria` e `valor` são as mais relevantes para uma análise inicial.
- A coluna `observacao` possui alguns campos vazios, mas isso não prejudica a análise inicial.
- O comando `describe()` apresentou estatísticas apenas das colunas numéricas.
- A estrutura do dataset permite análises futuras por categoria, cidade, forma de pagamento e período.

## Próximos passos

Nas próximas etapas, pretendo:

- Tratar valores ausentes
- Remover possíveis duplicatas
- Criar gráficos
- Analisar gastos por categoria
- Analisar gastos por forma de pagamento
- Melhorar a documentação do projeto

## Status do projeto

Primeira versão concluída.