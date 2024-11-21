# Explorando o `.describe()` do Pandas

O `.describe()` é uma função extremamente poderosa do Pandas que fornece um resumo estatístico básico de seus dados, ajudando a identificar padrões e potenciais problemas em análises exploratórias.

## 📋 O que é o `.describe()`?

O `.describe()` gera uma visão geral com estatísticas descritivas de colunas numéricas (e categóricas, opcionalmente), como:

- **Contagem** (`count`): Número de valores não nulos.  
- **Média** (`mean`): Média aritmética dos valores.  
- **Desvio padrão** (`std`): Medida de dispersão em relação à média.  
- **Mínimo e Máximo** (`min`, `max`): Valores mínimo e máximo.  
- **Quartis** (`25%`, `50%` - mediana, `75%`): Divisões dos dados em percentis.  

