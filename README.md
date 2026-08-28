# Análise Financeira com Python - ClearBank

Projeto desenvolvido para realizar a leitura, validação e análise de transações financeiras armazenadas em um arquivo CSV.

A solução principal utiliza recursos nativos do Python para processar os dados, identificar registros inválidos, calcular indicadores financeiros mensais e detectar transações consideradas suspeitas.

## Funcionalidades

O projeto realiza:

- Leitura do arquivo `transacoes.csv`
- Validação das transações
- Separação entre registros válidos e inválidos
- Agrupamento das transações por mês
- Cálculo de créditos e débitos
- Cálculo do saldo mensal
- Cálculo do valor médio das transações
- Identificação do maior e menor valor de cada mês
- Identificação de transações acima de R$ 10.000,00
- Geração do arquivo `relatorio.json`

Também foram desenvolvidas análises opcionais utilizando Pandas e Matplotlib.

## Tecnologias utilizadas

- Python
- CSV
- JSON
- Datetime
- Pandas
- Matplotlib
- Google Colab

## Arquivos do projeto

- `desafio-final.ipynb` - notebook principal com toda a análise
- `transacoes.csv` - base de dados utilizada
- `relatorio.json` - relatório gerado pela execução do programa
- `grafico.png` - gráfico com os valores de crédito e débito por mês

## Como executar

1. Abra o arquivo `desafio-final.ipynb` no Google Colab.
2. Faça o upload do arquivo `transacoes.csv`.
3. Execute as células do notebook na ordem apresentada.
4. O programa fará a validação e análise das transações.
5. Ao final serão gerados os arquivos `relatorio.json` e `grafico.png`.

## Resultados

Foram analisados 27 registros no arquivo CSV:

- 20 transações válidas
- 7 transações inválidas
- 4 meses analisados
- 2 transações acima do limite de R$ 10.000,00

A análise alternativa com Pandas apresentou os mesmos resultados obtidos pela solução principal.
