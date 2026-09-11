# 💰 Mini Projeto 5 – Dashboard de Análise Financeira

## Objetivo
Construir um painel financeiro para acompanhar receitas, despesas e margem de lucro de uma empresa ao longo do tempo, detalhando a composição de cada componente financeiro e identificando segmentos de valor.

## Principais análises realizadas
- Indicadores gerais: **Total de Receitas (R$ 1,92 Mi)**, **Total de Despesas (R$ 1,15 Mi)** e **Margem de Lucro (39,96%)**
- Segmentação automática ("Principais Segmentos") classificando a base em 7 grupos por média de valor e tamanho de população
- Tabela detalhada de Receitas x Despesas por ano (2019, 2020 e 2022), abrindo cada componente (Salários, Marketing, Impostos, Tecnologia, Segurança, Administrativo / Vendas, Licenciamento, Aluguéis, Publicidade, Investimentos, Franquias)
- Total de receitas por componente, com destaque para **Vendas** como principal fonte
- Total de despesas por componente ao longo do tempo, com linha de referência (média de R$ 192.152,83)

## Principais insights
- **Vendas** é de longe o maior componente de receita, muito à frente de Licenciamento e Aluguéis
- As despesas com **Administrativo** e **Tecnologia** lideram os custos, com tendência de queda acentuada nos demais componentes
- A margem de lucro de ~40% indica uma operação financeiramente saudável no período analisado
- Houve crescimento tanto de receitas quanto de despesas entre 2019 e 2022, mantendo a margem em patamar estável

## Técnicas e recursos utilizados
- Visual de **segmentação/clusterização** (Principais Segmentos) para agrupar dados por valor
- Tabela matricial com hierarquia (Tipo → Componente) e totais por ano
- Gráfico de barras para receitas por componente
- Gráfico de área com linha de referência (média) para despesas ao longo do tempo
- Cartões de KPI para métricas financeiras principais
