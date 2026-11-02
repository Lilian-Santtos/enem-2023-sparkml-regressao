# Desigualdade Educacional no Brasil — ENEM 2023

Projeto desenvolvido para a disciplina de Processamento de Dados Massivos, ministrada pelo professor Alexandre Roriz.

## Objetivo

Investigar a associação entre características socioeconômicas dos participantes e o desempenho em Matemática no ENEM 2023, utilizando Apache Spark ML e regressão linear.

## Dados utilizados

- Fonte: INEP — Microdados do ENEM 2023
- Registros originais: 3.933.955
- Registros selecionados: 2.692.427
- Variável prevista: nota de Matemática
- Características utilizadas: renda familiar, escolaridade dos responsáveis, acesso à internet e tipo de escola

## Tecnologias

Python, PySpark, Spark ML e Google Colab.

## Resultados

O modelo definitivo de regressão Ridge apresentou:

- RMSE: 114,32 pontos
- MAE: 89,93 pontos
- R²: 0,2462

Os resultados indicam associação entre condições socioeconômicas e desempenho educacional, mas não estabelecem relações de causalidade.

## Execução

O notebook foi desenvolvido no Google Colab e contém os procedimentos de ingestão, tratamento, análise, modelagem e avaliação.

O download dos dados utiliza como fonte principal o endereço oficial do INEP. Quando essa transferência não estiver disponível, existe uma alternativa configurável por meio do Google Drive.

**Fonte oficial:** [https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados/enem](https://download.inep.gov.br/microdados/microdados_enem_2023.zip)

Os arquivos da base não estão incluídos no repositório.
