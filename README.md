# 📊 Análise de Encargos em Planos de Saúde

Este projeto em Python realiza uma análise exploratória de dados (EDA) com foco em encargos cobrados por seguros de saúde. O notebook foi desenvolvido para ser executado no Google Colab e trabalha com uma base de dados em CSV chamada `seguros.csv`.

## 🚀 O que o projeto faz

- Carrega dados de um arquivo CSV com informações sobre clientes e encargos de planos de saúde.
- Calcula os **encargos mensais** a partir do valor anual.
- Formata os valores monetários para o padrão brasileiro.
- Ordena os dados para destacar os planos mais caros e mais baratos.
- Realiza validações como:
  - Checagem de valores nulos
  - Tipagem das colunas
  - Estatísticas descritivas dos dados
- Exibe os dados mais relevantes para facilitar a visualização.

## 📦 Bibliotecas utilizadas

- `pandas`
- `matplotlib` *(incluído nos gráficos)*
- `seaborn` *(incluído nos gráficos)*
- `google.colab` *(para upload dos arquivos)*

## 🖼️ Exemplos de visualização

- Gráficos de distribuição do IMC
- Comparação entre fumantes e não fumantes
- Análise de regiões com maiores encargos

## 📁 Como usar

1. Acesse o [Google Colab](https://colab.research.google.com)
2. Faça upload do notebook e do arquivo `seguros.csv`
3. Execute as células na ordem

## 🧠 Insights possíveis

- Quais perfis de cliente tendem a pagar mais pelos planos?
- Existe diferença entre gêneros, regiões ou entre fumantes e não fumantes?
- Como o número de filhos impacta os encargos?

---

Feito com 💙 para facilitar a análise de custos em seguros de saúde.
