# 📊 Dashboard de Eventos - Power BI

Este projeto apresenta uma análise interativa dos **eventos realizados pela organização**, utilizando o Power BI para visualização de dados, identificação de padrões e apoio à tomada de decisões estratégicas.

## ✅ Objetivo

Fornecer uma visão gerencial e operacional sobre os eventos realizados, permitindo:

- Acompanhamento da **quantidade de eventos por período**;
- Análise por **tipos de evento, status e responsável**;
- Identificação dos **principais organizadores e públicos-alvo**;
- Visualização da **linha do tempo dos eventos** e sua distribuição.

## 🧩 Funcionalidades do Dashboard

- **Visão geral** com KPIs principais: total de eventos, eventos concluídos, em andamento e cancelados;
- **Filtros interativos**: por ano, tipo de evento, status, responsável e público-alvo;
- **Gráficos de barras e linhas**: evolução dos eventos ao longo do tempo;
- **Mapa** (caso ativado): para exibição geográfica dos eventos;
- **Tabela detalhada** com todas as informações filtráveis.

## 🗂️ Estrutura dos Dados

A base de dados é composta por colunas como:

- `Evento`: Nome do evento
- `Data de Realização`
- `Tipo de Evento`
- `Status do Evento`
- `Responsável`
- `Público-Alvo`
- `Departamento`
- `Quantidade de Participantes`
- `Localização` (se aplicável)

## 🛠️ Tecnologias Utilizadas

- **Power BI Desktop**
- **Power Query** (para transformação de dados)
- **DAX** (para medidas e cálculos personalizados)

## 📈 Indicadores Criados (DAX)

- Total de Eventos
- Eventos por Status
- Eventos por Responsável
- Eventos por Ano
- Eventos por Público-Alvo
