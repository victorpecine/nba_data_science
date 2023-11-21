# Análise de dados NBA
Este projeto foi desenvolvido utilizando **Python** e **Google Colab**.
O objetivo foi treinar técnicas de *web scraping*, tratamento e visualização de dados a partir de estatísticas e outras informações do jogador Nikola Jokic, pivô do Denver Nuggets e campeão e MVP das finais de NBA em 2023.

## 🗹 Bibliotecas
 - Pandas
 - Numpy
 - Plotly
 - Matplotlib

## 🗹 Web scraping
As informações sobre jogos, adversários, placares e estatísticas de jogo entre os anos de 2016 e 2023 foram obtidas no site da ESPN e o scraping foi realizado com o webdriver do Chrome.

## 🗹 Data wrangling
Foi necessário tratar as informações para identificar dados nulos, padronizar textos com Regex e outros elementos como placares, nome dos times adversários e o dia da semana que o respectivo jogo aconteceu.

## 🗹 Data visualization
Após todo o tratamento de dados, esses foram salvos no formato csv. Dessa forma, a etapa de visualização foi realizada no Google Looker Studio.
A paleta de cores do Denver Nuggets (time aonde o Jokic joga) foi utilizada com base para o desenvolvimento.
O [dashboard](https://lookerstudio.google.com/reporting/de74e062-266a-4e94-bf2d-1101ff2d7327) foi elaborado de forma interativa para que o usuário possa fazer seleções e extrair informações variadas.
