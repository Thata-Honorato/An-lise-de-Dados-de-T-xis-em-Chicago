# Sprint 7 – Projeto: Análise de Dados de Táxis em Chicago

## Descrição do Projeto

Neste projeto, foi realizada uma análise exploratória de dados e testes de hipóteses utilizando informações de corridas de táxi em Chicago. O objetivo é compreender padrões de uso, identificar bairros mais populares como destino e avaliar o impacto das condições meteorológicas na duração das corridas.

O projeto utiliza três conjuntos de dados CSV fornecidos:

1. `/datasets/project_sql_result_01.csv` – número de corridas por empresa de táxi entre 15 e 16 de novembro de 2017 (`trips_amount`).  
2. `/datasets/project_sql_result_04.csv` – média de corridas que terminaram em cada bairro de Chicago em novembro de 2017 (`dropoff_location_name` e `average_trips`).  
3. `/datasets/project_sql_result_07.csv` – dados sobre viagens do Loop para o Aeroporto Internacional O'Hare, incluindo hora de início, condições meteorológicas e duração (`start_ts`, `weather_conditions`, `duration_seconds`).

---

## Etapas do Projeto

### Passo 4 – Análise Exploratória de Dados

1. Importar os arquivos CSV no Python.  
2. Estudar os dados:  
   - Verificar os tipos de dados de cada coluna.  
   - Identificar valores ausentes ou inconsistentes.  
3. Analisar os bairros de Chicago:  
   - Identificar os 10 principais bairros em termos de destinos.  
   - Construir gráficos para visualização:  
     - Empresas de táxi e número de corridas.  
     - Top 10 bairros por número de corridas como destino.  
4. Interpretar os gráficos:  
   - Tirar conclusões baseadas nos padrões observados.  
   - Explicar insights importantes e tendências.

### Passo 5 – Teste de Hipóteses

1. Utilizar o dataset `/datasets/project_sql_result_07.csv`.  
2. Formular a hipótese:

   **Hipótese:** "A duração média das corridas do Loop para o Aeroporto Internacional O'Hare muda nos sábados chuvosos."  

3. Definir o nível de significância (alfa) por conta própria.  
4. Explicar:  
   - Hipótese nula e alternativa.  
   - Critério estatístico utilizado para testar a hipótese e justificativa.  
5. Calcular e interpretar os resultados, tirando conclusões sobre a influência das condições meteorológicas na duração das corridas.

---

## Critérios de Avaliação

O projeto será avaliado com base nos seguintes pontos:

- Recuperação e importação correta dos dados.  
- Manipulação e fatias de dados corretamente realizadas.  
- Agrupamento e combinação de dados usando métodos adequados.  
- Formulação clara das hipóteses nula e alternativa.  
- Escolha adequada do critério para teste de hipóteses e justificativa.  
- Interpretação correta dos resultados e conclusões consistentes.  
- Comentários e explicações detalhadas em cada etapa do projeto.

Todos os notebooks originais estão hospedados na plataforma TripleTen e não podem ser alterados.  
- Este repositório documenta o projeto e o aprendizado adquirido.
