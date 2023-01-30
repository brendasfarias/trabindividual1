# Projeto de previsão de ações

#### Esse trabalho tem como intuito fazer um modelo preditivo do preço de determinadas ações que eu acompanho.

Foram escolhidas ações das seguintes empresas:



*   [Magalu](https://github.com/brendasfarias/trabindividual1/blob/main/images/MGLU3.png) (MGLU3)
*   [Banco do Brasil](https://github.com/brendasfarias/trabindividual1/blob/main/images/BBAS3.png) (BBAS3)
*   [Embraer](https://github.com/brendasfarias/trabindividual1/blob/main/images/EMBR3.png) (EMBR3)
*   [Itaú](https://github.com/brendasfarias/trabindividual1/blob/main/images/ITUB4.png) (ITUB4)
*   [Americanas](https://github.com/brendasfarias/trabindividual1/blob/main/images/AMER3.png) (AMER3)

A ideia é fazer uma análise exploratória utilizando a biblioteca Plotly, afim de simular um gráfico típico de plataformas de investimentos, o modelo de *candlesticks*

Os dados foram importados com uma biblioteca que se conecta à API do Yahoo, chamada *Yahoo Finance*

A base de dados tem uma indexação por datas, facilitando bastante o processo de geração de gráficos, e possui as seguintes colunas:



*   Open - Preço de abertura
*   High - Maior valor alcançado na data
*   Low - Menor valor alcançado na data
*   Close - Valor de fechamento da ação
*   Adj Close - Fechamento ajustado, após distribuição de dividendos e outras operações
*   Volume - Quantas ações foram negociadas (Tanto compras quanto vendas)


OBS.: Os valores das ações já estão em BRL
