# 🚚 Mini Projeto 4 – Análise de Dados de Logística

## Objetivo
Monitorar a performance operacional de entregas de uma empresa de logística, avaliando prazos, canais de distribuição, sazonalidade e desempenho de vendedores/regiões, com filtro por ano (2019 e 2020).

## Principais análises realizadas
- Indicadores gerais: **54 mil entregas totais**, das quais 47 mil dentro do prazo
- Total de entregas no prazo por canal de entrega (ranking entre 17 canais)
- Percentual de entregas por equipe/região: Norte, Sudeste, Nordeste, Sul, Centro-Oeste, além de canais como Internet, Televendas, Distribuidores e Venda Direta
- Sazonalidade: total de entregas por mês ao longo do ano
- Percentual de entregas por status: **Antecipado, No Prazo e Atrasado**
- Ranking dos Top 5 vendedores por total de entregas, com avaliação (rating) de 1 a 5 estrelas
- Total de entregas em atraso, detalhado por cidade (ID_Cidade)

## Principais insights
- A maior parte das entregas é feita de forma **antecipada** (acima de 60%), indicando boa eficiência operacional
- A região **Norte** concentra o maior percentual de entregas por equipe
- Há forte sazonalidade: picos de entregas entre fevereiro e junho, com queda acentuada no fim do ano
- Algumas cidades específicas concentram grande parte dos atrasos (destaque para a cidade de ID 17, com 142 entregas atrasadas)

## Técnicas e recursos utilizados
- Cartões de indicadores (KPIs)
- Gráfico de área para entregas no prazo por canal
- Gráfico de barras horizontais para percentual por equipe/canal
- Gráfico de linha para sazonalidade mensal
- Tabelas com ranking (Top 5 vendedores) e detalhamento por cidade
- Segmentação (slicer) por ano
