# Priscila - Dashboard Executivo | Ciclo de Obrigacoes

**Versao:** 1.0.0

## Sobre

Dashboard executivo para analise automatica de planilhas Excel do Ciclo de Obrigacoes.
Upload do arquivo `.xlsx` direto no navegador, sem backend. Cada aba da planilha vira uma visao com KPIs, insights, graficos e tabela detalhada.

## Estrutura do Projeto

```
Priscila/
  index.html              # Aplicacao principal (HTML + CSS + JS)
  xlsx.full.min.js         # Biblioteca SheetJS para leitura de Excel
  chart.umd.js             # Biblioteca Chart.js para graficos
  Ciclo de Obrigacoes 2025-2026_v00.xlsx  # Planilha exemplo
  README.md                # Este arquivo
```

## Como Usar

1. Abra o `index.html` no navegador
2. Arraste ou selecione o arquivo Excel
3. Navegue pelas abas, aplique filtros e exporte CSV

## Funcionalidades

- Leitura de Excel 100% no cliente (SheetJS)
- Deteccao automatica de cabecalho e tipos de coluna
- Normalizacao inteligente de status
- 6 KPIs dinamicos por aba
- 4 graficos interativos (Chart.js): status, tendencia mensal, responsaveis, qualidade
- Filtros por ano, mes, status, responsavel e categoria
- Busca textual na tabela
- Paginacao e ordenacao por coluna
- Exportacao CSV filtrado
- Insights automaticos por aba
- Dicionario de colunas inferido
- Layout responsivo (desktop, tablet, mobile)

## Historico de Versoes

### v1.0.0 (2026-02-11)
- Correcao critica: paths dos scripts vendor (`./vendor/` -> `./`)
- Dashboard executivo completo com upload de Excel
- KPIs, graficos, filtros, tabela paginada e exportacao CSV
- Deteccao automatica de colunas-chave (status, responsavel, data, categoria)
- Insights e dicionario de colunas por aba
- Layout responsivo

## Tecnologias

- HTML5 / CSS3 / JavaScript (vanilla, sem frameworks)
- [SheetJS](https://sheetjs.com/) - leitura de Excel
- [Chart.js](https://www.chartjs.org/) - graficos interativos

## Requisitos

- Navegador moderno (Chrome, Firefox, Edge, Safari)
- Nenhum servidor necessario - basta abrir o `index.html`
