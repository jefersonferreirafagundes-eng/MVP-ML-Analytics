# MVP — Engenharia de Dados aplicada ao Desempenho Acadêmico

Projeto de Engenharia de Dados voltado à análise de variáveis associadas à nota final de estudantes.

## Objetivo

Construir um pipeline completo de dados em nuvem, com ingestão, persistência, qualidade, modelagem, transformação e análise, buscando responder quais variáveis apresentam maior associação com a nota final.

## Arquitetura

Fonte → Bronze → Silver → Gold → Analytics

- **Bronze:** dados brutos.
- **Silver:** dados tratados, tipados e validados.
- **Gold:** dados prontos para análise e variáveis derivadas.
- **Analytics:** EDA, estatística, regressão e Machine Learning.

## Variáveis esperadas

- age
- gender
- study_hours_per_day
- sleep_hours
- phone_usage_hours
- social_media_hours
- youtube_hours
- gaming_hours
- final_grade

## Como executar no Databricks

1. Faça upload do CSV.
2. Abra o notebook `MVP_Engenharia_Dados_Desempenho_Alunos.ipynb`.
3. Altere `DATA_PATH` na seção de configuração.
4. Execute as células em sequência.
5. Preencha os dados oficiais da fonte e licença.
6. Registre screenshots das etapas exigidas no enunciado.
7. Revise a seção de conclusões com os resultados efetivamente calculados.

## Dependências analíticas

- PySpark
- pandas
- numpy
- matplotlib
- scipy
- scikit-learn
- statsmodels

## Observação metodológica

O projeto identifica associações e capacidade preditiva. Resultados observacionais não devem ser interpretados automaticamente como causalidade.

