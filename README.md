[![author](https://img.shields.io/badge/author-BrunoMelo-red.svg)](https://www.linkedin.com/in/bruno-melo-223817125/) [![](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-365/) [![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg)](http://perso.crans.org/besson/LICENSE.html) [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/BrunoMeloSlv)

<p align="center">
  <img src="https://i0.wp.com/sanarmed.com/wp-content/uploads/2024/03/media-86.jpeg?fit=2089%2C1175&ssl=1" alt="imagem maneira relacionada ao projeto"height=400px >
</p>

# Panorama do COVID-19 no Brasil

Análise exploratória dos dados públicos da pandemia no Brasil (até junho de 2020)

## Sobre o projeto

Este projeto realiza uma análise exploratória dos dados públicos da COVID-19 no Brasil, utilizando dados do repositório Our World in Data (OWID). O objetivo é compreender a evolução da doença no país, identificar padrões, tendências e gerar insights relevantes por meio de visualizações gráficas.

## Conteúdo do repositório

* projeto2_bruno_melo.ipynb → Notebook principal com toda a análise.
* README.md → Este arquivo.

## Tecnologias utilizadas

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

## Estrutura da análise
* Obtenção e preparação dos dados
  - Importação do dataset owid-covid-data.csv.
  - Tradução das colunas para português.
  - Verificação de tipos de dados, valores ausentes e intervalos temporais.
* Análise exploratória inicial
  - Visualização das primeiras e últimas linhas do dataset.
  -  Identificação de países com maior número de casos e óbitos até a data final (junho de 2020).
  - Análise de dados faltantes por coluna.
* Visualização dos 5 países com mais óbitos
  - Gráfico de barras horizontais mostrando os países com maior número acumulado de mortes por COVID-19 até junho de 2020.
  - Gráfico de linha temporal mostrando a evolução dos óbitos ao longo do tempo nos 5 países mais afetados.
* Foco no Brasil (em desenvolvimento)
  - O notebook está estruturado para permitir análises específicas sobre o Brasil, podendo ser expandido com:
  - Evolução de casos e óbitos.
  - Taxas de mortalidade e incidência.

## Insights (até junho de 2020)

* Estados Unidos, Itália, Reino Unido, Espanha e França foram os países com maior número absoluto de óbitos até meados de 2020.
* Dados ausentes: variáveis relacionadas a testagem apresentam mais de 70% de valores faltantes.
* Intervalo temporal: os dados vão de 31/12/2019 a 15/06/2020.






