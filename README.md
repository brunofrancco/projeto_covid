# projeto_covid

# Análise e Previsão dos Casos de COVID-19 no Brasil

Este projeto tem como objetivo analisar a evolução dos casos confirmados de COVID-19 no Brasil e realizar previsões baseadas em dados históricos. Utilizando técnicas estatísticas, modelagem de séries temporais e visualizações interativas, exploramos padrões, tendências e projeções para auxiliar na compreensão da dinâmica da pandemia.

---

## Sobre os Dados

- **Fonte**: Dados diários de casos confirmados, óbitos e recuperações, organizados por país e região  
- **Filtros aplicados**:  
  - Dados exclusivos do Brasil  
  - Período analisado inicia-se no primeiro dia com registros de casos confirmados  

---

## O que foi feito?

- **Limpeza e preparação:** Ajustamos os nomes das colunas para facilitar o trabalho, removendo espaços e caracteres especiais e padronizando tudo para minúsculas.
- **Visualizações iniciais:** Plotamos a evolução dos casos confirmados e o número diário de novos casos para captar tendências e variações.
- **Cálculo da taxa de crescimento:** Calculamos como a doença cresceu, tanto em média durante o período, quanto diariamente, ajudando a entender se a pandemia acelerava ou desacelerava.
- **Análise sazonal:** Usamos técnicas de decomposição para separar a série temporal em partes — tendência geral, padrões semanais e variações aleatórias.
- **Previsão futura:** Aplicamos o modelo ARIMA, reconhecido para séries temporais, para projetar o número de casos confirmados para os próximos 200 dias, com gráficos interativos que facilitam a visualização.

---

## Como rodar o projeto

1. Baixe ou clone o repositório.
2. Prepare seu ambiente Python com as bibliotecas necessárias (Pandas, Plotly, Statsmodels, etc.).
3. Carregue o dataset `covid_19_data.csv` na pasta `data/`.
4. Execute o notebook principal para acompanhar toda a análise e ver os gráficos gerados.

---

## O que você vai ver nos gráficos?

- A curva dos casos acumulados mostrando o crescimento da pandemia.
- A linha dos novos casos diários, que revela picos e quedas ao longo do tempo.
- A decomposição que evidencia padrões semanais e tendências.
- A previsão com ARIMA, com o passado e o futuro lado a lado para fácil comparação.

---

## Por que esse projeto é importante?

Entender a evolução e projetar o futuro da COVID-19 ajuda a informar decisões de saúde pública e políticas de contenção. Além disso, serve como exemplo prático do uso de análise de séries temporais em dados reais e sensíveis.

---



Obrigado por visitar e explorar este projeto!
