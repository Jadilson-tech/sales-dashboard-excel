# Dashboard de Vendas em Excel

## Descrição

Projeto desenvolvido em Microsoft Excel com foco em organização de dados, aplicação de funções de busca e construção de um dashboard interativo para análise de vendas.

---

## Estrutura dos Dados

O arquivo é composto por três abas principais:

### Colaboradores
- ID_Colaborador
- Nome

### Vendas
- ID_Venda
- Data
- ID_Colaborador
- Produto
- Categoria
- Quantidade
- Valor_Unitario
- Total

### Dashboard_Vendas
- Tabelas dinâmicas
- Gráficos
- Segmentações de dados (filtros)

---

## Técnicas e Recursos Utilizados

- Tabelas estruturadas
- Relacionamento entre tabelas via ID
- Funções de busca:
  - PROCX
  - PROCV
- Tratamento de erro com SEERRO
- Tabelas dinâmicas
- Gráficos dinâmicos
- Segmentação de dados (Slicers)

---

## Funções Aplicadas

### PROCX
Utilizado para buscar o nome do colaborador a partir do ID, sem depender da posição da coluna.

### PROCV
Utilizado como comparação, realizando busca vertical com dependência da posição das colunas.

### SEERRO
Aplicado para tratar erros e evitar exibição de valores como #N/D.

---

## Análises Realizadas

- Ranking de vendas por colaborador
- Vendas por categoria
- Filtro por período
- Interação dinâmica com filtros

---

## Como Utilizar

1. Abrir o arquivo Excel
2. Acessar a aba Dashboard_Vendas
3. Utilizar os filtros disponíveis
4. Analisar os gráficos e resultados

---

## Objetivo

Demonstrar conhecimento em:

- Manipulação de dados no Excel
- Uso de funções de busca
- Construção de relatórios dinâmicos
- Criação de dashboards interativos

---

## Observações

Este projeto simula um cenário real de análise de vendas, com foco em organização, clareza e aplicação prática.

---

## Autor

**Jadilson José Tavares**

![Dashboard de Vendas](dashboard.png)
