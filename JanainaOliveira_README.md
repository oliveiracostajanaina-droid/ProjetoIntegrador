# README - Avaliação dos Intercâmbios N e NE para Apoio a Liberação de Intervenções

## Objetivo

Este projeto analisa, para o periodo de 2023 a 2025, quais meses apresentaram os menores e maiores valores medios de intercambio envolvendo os subsistemas Norte e Nordeste e como esses periodos se relacionam com o comportamento da geracao por fonte.

## Organizacao dos arquivos

Para reproduzir a analise, mantenha o notebook e os tres arquivos CSV na mesma pasta:

- `BALANCO_ENERGIA_SUBSISTEMA_2023.csv`
- `BALANCO_ENERGIA_SUBSISTEMA_2024.csv`
- `BALANCO_ENERGIA_SUBSISTEMA_2025.csv`
- notebook da analise (`.ipynb`)

Os arquivos CSV contem dados horarios de carga, intercambio e geracao por fonte e subsistema.

## Bibliotecas utilizadas

Pandas, NumPy, Matplotlib, Seaborn e Plotly Express.

Tambem sao utilizados `sys` e `pathlib`, da biblioteca padrao do Python.

## Sequencia para reproduzir a analise

Execute o notebook do inicio ao fim, seguindo a ordem das secoes.

## Observacao

Os resultados representam padroes observados entre 2023 e 2025 e devem ser utilizados como referencia para o planejamento. A analise nao determina, isoladamente, a viabilidade de intervencoes, que depende tambem das condicoes eletricas e sistemicas do SIN.
