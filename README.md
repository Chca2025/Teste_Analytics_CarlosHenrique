Teste Analise de dados
---

Objetivo
---
Este é um projeto para testar os conceitos básicos de análise de dados, 
tendo como principais pontos a geração de dados simulados, limpeza e classificação das informações, 
análise exploratória com geração de gráficos, identificação de insights e consultas em banco de dados SQL.

Estrutura
---
analise_venda.ipynb
analise_exploratoria.ipynb
consultas_sql.sql              
data_clean.csv                
dados_sujos.csv
relatorio_insights.md
README.md

Como Executar
---
Execute primeiro o analise_venda.ipynb para criar os dados de venda, simular dados sujos, fazer a limpeza e organização das informações
Depois rode o analise_exploratoria.ipynb, onde são gerados os gráficos e apresentados os insights encontrados
Obs: Execute as células em sequência para visualizar todos os resultados corretamente.

Dependências
---
python
pandas
matplotlib
random
datetime
sqlite3

OBS
---
Na consulta SQL há uma observação sobre produtos mais vendidos.
O teste solicitava identificar os produtos que mais venderam no mês de junho de 2024, 
contudo a consulta foi realizada com dados do ano de 2023, conforme as informações geradas na primeira etapa do projeto.
