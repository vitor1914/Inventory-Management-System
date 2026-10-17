# 📦 Sistema de Gestão de Estoque | Inventory Management System

🇧🇷 Português | 🇺🇸 English

## 🇧🇷 Português

### Sobre o projeto

Este projeto consiste em um Sistema de Gestão de Estoque desenvolvido no Google Planilhas, com o objetivo de organizar produtos, fornecedores, entradas, saídas e níveis de estoque em um único ambiente.

A solução utiliza fórmulas automatizadas e um dashboard visual para acompanhar indicadores importantes, facilitar o controle de mercadorias e identificar produtos que precisam de reposição.

### Funcionalidades

- Cadastro e organização de produtos.
- Cadastro de fornecedores.
- Registro de entradas de mercadorias.
- Registro de saídas, vendas e perdas.
- Cálculo automático do saldo de estoque.
- Cálculo do valor financeiro do estoque.
- Identificação de produtos abaixo do estoque mínimo.
- Dashboard com indicadores e gráficos.
- Alertas visuais para reposição de produtos.

### Tecnologias utilizadas

- Google Planilhas
- Fórmulas e funções de planilhas
- Tabelas e gráficos
- Dashboard e indicadores de desempenho

### Estrutura do sistema

| Aba | Descrição |
|---|---|
| PRODUTOS | Cadastro de produtos, custos, preços e estoque mínimo |
| FORNECEDORES | Cadastro e contatos dos fornecedores |
| ENTRADAS | Registro de compras e recebimentos |
| SAÍDAS | Registro de vendas, perdas e outras saídas |
| ESTOQUE | Saldo atual, movimentações e alertas |
| DASHBOARD | Indicadores, gráficos e acompanhamento visual |

### Indicadores do projeto

Com os dados de demonstração cadastrados:

- Produtos cadastrados: 3
- Valor total do estoque: R$ 595,00
- Produtos para reposição: 2
- Valor total das entradas: R$ 830,00

*Os indicadores são calculados automaticamente a partir dos dados registrados nas abas.*

### Principais cálculos

**Saldo atual**

```excel
=E2-F2
```

**Valor em estoque**

```excel
=G2*J2
```

**Identificação de reposição**

```excel
=SE(G2<=H2;"REPOR ESTOQUE";"OK")
```

### Objetivos de aprendizagem

- Organização e estruturação de dados.
- Automatização de cálculos em planilhas.
- Controle de estoque e movimentações.
- Criação de indicadores de desempenho.
- Visualização de dados por meio de gráficos.
- Desenvolvimento de soluções para problemas operacionais.

### Possíveis melhorias futuras

- Inclusão de novos indicadores no dashboard.
- Criação de relatórios mensais.
- Análise de produtos com maior saída.
- Projeção de necessidades de reposição.
- Integração futura com SQL e Python.

---

## 🇺🇸 English

### About the project

This project is an Inventory Management System developed in Google Sheets to organize products, suppliers, stock entries, stock withdrawals, and inventory levels in a single workspace.

The solution uses automated spreadsheet formulas and a visual dashboard to monitor key performance indicators, improve inventory control, and identify products that need replenishment.

### Features

- Product registration and organization.
- Supplier management.
- Stock entry and purchase tracking.
- Sales, losses, and stock withdrawal tracking.
- Automatic inventory balance calculation.
- Inventory valuation.
- Low-stock identification.
- Dashboard with KPIs and charts.
- Visual replenishment alerts.

### Technologies

- Google Sheets
- Spreadsheet formulas and functions
- Tables and charts
- Dashboard and performance indicators

### Workbook structure

| Sheet | Description |
|---|---|
| PRODUTOS | Product catalog, costs, prices, and minimum stock |
| FORNECEDORES | Supplier information and contact details |
| ENTRADAS | Purchases and incoming inventory |
| SAÍDAS | Sales, losses, and other stock withdrawals |
| ESTOQUE | Current balances, movements, and alerts |
| DASHBOARD | KPIs, charts, and visual monitoring |

### Project metrics

Using the sample data:

- Registered products: 3
- Total inventory value: BRL 595.00
- Products requiring replenishment: 2
- Total incoming inventory value: BRL 830.00

*Metrics are automatically calculated from the data recorded in the workbook.*

### Key calculations

**Current inventory balance**

```excel
=E2-F2
```

**Inventory value**

```excel
=G2*J2
```

**Replenishment status**

```excel
=IF(G2<=H2,"REPLENISH STOCK","OK")
```

### Learning objectives

- Data organization and structuring.
- Spreadsheet calculation automation.
- Inventory and stock movement management.
- KPI development.
- Data visualization using charts.
- Practical problem-solving through spreadsheet solutions.

### Future improvements

- Additional dashboard indicators.
- Monthly inventory reports.
- Best-selling product analysis.
- Stock replenishment forecasting.
- Future integration with SQL and Python.

---

## Autor | Author

**Data Analytics Portfolio Project**

Desenvolvido como projeto prático de análise de dados e automação de processos utilizando Google Planilhas.

Developed as a practical data analytics and process automation project using Google Sheets.
