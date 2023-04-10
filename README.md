# Projeto de previsão de ações

Objetivo geral: Esse trabalho tem como intuito fazer um modelo preditivo do preço de determinadas ações.
Relevância: Existem várias aplicações relevantes para criar um modelo preditivo para o preço das ações, incluindo decisões de investimento, gerenciamento de riscos, otimização de portfólio e estratégias de negociação.
- Os investidores podem usar modelos preditivos para tomar decisões informadas sobre compra e venda de ações
- Investidores e gestores podem utilizar esses modelos para gerenciamento de risco, identificando áreas de alto risco e prever a probabilidade de um preço de ação subir ou descer. Com essas informações, os investidores podem tomar decisões sobre diversificação ou proteção.
- Agentes ativos no mercado financeiro podem usar os modelos para desenvolver estratégias de negociação

Foram escolhidas ações das seguintes empresas:

*   [Magalu](https://github.com/brendasfarias/trabindividual1/blob/main/images/MGLU3.png) (MGLU3)
*   [Banco do Brasil](https://github.com/brendasfarias/trabindividual1/blob/main/images/BBAS3.png) (BBAS3)
*   [Embraer](https://github.com/brendasfarias/trabindividual1/blob/main/images/EMBR3.png) (EMBR3)
*   [Itaú](https://github.com/brendasfarias/trabindividual1/blob/main/images/ITUB4.png) (ITUB4)
*   [Americanas](https://github.com/brendasfarias/trabindividual1/blob/main/images/AMER3.png) (AMER3)

Os dados foram importados com uma biblioteca que se conecta à API do Yahoo, chamada Yahoo Finance. A base de dados tem uma indexação por datas, facilitando bastante o processo de geração de gráficos, e possui as seguintes colunas:

**Open** - Preço de abertura

**High** - Maior valor alcançado na data

**Low** - Menor valor alcançado na data

**Close** - Valor de fechamento da ação

**Adj Close** - Fechamento ajustado, após distribuição de dividendos e outras operações

**Volume**  - Quantas ações foram negociadas (Tanto compras quanto vendas)

A biblioteca seaborn é usada para visualização de dados em Python, especialmente gráficos estatísticos.
A biblioteca smt (Sensitivity Model Toolbox) é uma coleção de ferramentas de análise de sensibilidade e calibração de modelos.
A biblioteca pmdarima instala a biblioteca pmdarima (AutoRegressive Integrated Moving Average), que é usada para modelagem e previsão de séries temporais em Python.
A biblioteca statsmodels é usada para análise estatística em Python, incluindo modelagem e previsão de séries temporais, regressão linear, análise de dados de painel e outros métodos estatísticos avançados.

A partir de séries temporais e o modelo SARIMAX, foram feitas as análise exploratórias e as previsões do preço das ações para cada uma das empre0sas escolhidas. 
Conclui-se que o modelo é limitado devido a complexidade do mercado financeiro, e que a possibilidade de integrar uma quantidade maior de dados micro e macroeconômicos poderia ser um passo interessante.
