# English Version

## Overview

This project presents a Business Intelligence solution designed to analyze commercial performance and geographic distribution within an automotive product line. The dashboard integrates sales indicators, inventory replenishment behavior, and regional revenue concentration to transform transactional data into strategic insights that support commercial and operational decision-making.

The solution provides an integrated view of sales performance and market penetration, enabling organizations to identify growth opportunities, optimize inventory planning, and strengthen regional commercial strategies.

## Objectives

* Analyze sales performance over time.
* Monitor the relationship between sales demand and inventory replenishment.
* Identify top-performing products and strategic categories.
* Evaluate regional market contribution to overall business performance.
* Support commercial planning through data-driven insights.
* Enhance decision-making related to inventory allocation and market expansion.

## Business Context

In highly competitive markets, understanding sales performance and its relationship with inventory replenishment is essential to ensuring product availability, maximizing revenue, and identifying regional growth opportunities.

This project was developed to provide an integrated business perspective through two complementary dashboards: a commercial performance dashboard and a geographic market distribution analysis. Together, these views enable the identification of consumption trends, evaluation of inventory planning efficiency, and understanding of each region's contribution to overall business performance.

## Dashboard Structure & Analytical Views

### 1. Sales Performance Dashboard

A business-focused view designed to monitor key commercial indicators, track market behavior, and support strategic decision-making.

#### Key Metrics

* Total Sales within the selected period.
* Average Sales value.
* Inventory replenishment volume (Purchases).
* Ranking of top-performing products.
* Percentage contribution of strategic product offerings (Core Offers).

#### Features

* Monthly monitoring of sales evolution.
* Comparison between market demand and inventory replenishment.
* Identification of products driving the highest revenue generation.
* Segmentation by business lines and product categories.

#### Trend Analysis

* Area charts comparing sales performance against purchasing activity over time.
* Evaluation of inventory turnover efficiency.
* Identification of seasonality patterns and significant demand fluctuations.

### 2. Regional Distribution Map

A geographic analytical view designed to identify consumption patterns and revenue concentration across different markets.

#### Key Metrics

* Sales volume by state.
* Geographic distribution of revenue.
* Regional contribution to commercial performance.
* Market penetration by product segment.

#### Features

* Spatial visualization of sales concentration.
* Comparative analysis across different regions.
* Product segmentation by category:

  * Imported;
  * Domestic;
  * Electric;
  * Passenger;
  * Premium;
  * Utility.
* Direct SKU search functionality for portfolio-specific analysis.

#### Geographic Analysis

* Identification of strategically important markets.
* Assessment of commercial coverage across regions.
* Support for expansion planning and distribution strategies.

## Technologies & Tools

* **Power BI:** Development of dashboards and interactive visualizations.
* **DAX:** Creation of commercial KPIs, sales calculations, and Time Intelligence measures.
* **Power Query (M Language):** ETL processes, data standardization, and cleansing procedures.
* **Dimensional Modeling (Star Schema):** Structuring of the analytical model to improve performance and scalability.
* **Bing/TomTom Map Integration:** Geographic representation of commercial data using state-level boundaries.

## Technical Challenges Overcome

* **Temporal Granularity Alignment:**

  * Integration of separate fact tables, such as sales and inventory purchases, through a unified calendar dimension to ensure analytical consistency.

* **Geospatial Optimization:**

  * Standardization and preparation of geographic datasets to guarantee accurate map rendering and eliminate location ambiguities.

* **Strategic KPI Modeling:**

  * Development of dynamic metrics to measure the contribution of priority offerings within the product portfolio.

* **Analytical Scalability:**

  * Construction of a robust data model capable of supporting detailed analyses and complex segmentations without compromising performance.

## Key Insights

* **Improved Inventory Efficiency:**

  * Identification of periods in which sales growth was not accompanied by proportional increases in purchases, indicating more efficient inventory utilization.

* **Strategic Category Dominance:**

  * Recognition of the product segments responsible for the highest commercial contribution, supporting portfolio optimization initiatives.

* **Regional Revenue Concentration:**

  * Identification of the markets with the greatest impact on overall business performance, enabling more targeted commercial actions.

* **Enhanced Decision-Making:**

  * Delivery of reliable KPIs to support initiatives related to inventory planning, commercial strategy, and regional expansion.

## Repository Structure

```text
commercial-performance-dashboard/
├── Commercial-Performance-Dashboard.pbix
├── README.md
└── images/
    ├── sales-dashboard.png
    └── regional-distribution-map.png
```

---

*This project is part of my portfolio in Business Intelligence and Commercial Analytics, demonstrating my ability to transform sales data into strategic insights that support business growth and data-driven decision-making.*

---

# Versão em Português

## Overview

Este projeto apresenta uma solução de Business Intelligence desenvolvida para analisar a performance comercial e a distribuição geográfica de uma linha de produtos do setor automotivo. O dashboard integra indicadores de vendas, comportamento de reposição de estoque e concentração regional de receita, transformando dados transacionais em insights estratégicos para apoiar decisões comerciais e operacionais.

A solução oferece uma visão integrada do desempenho comercial e da penetração de mercado, permitindo identificar oportunidades de crescimento, otimizar o planejamento de estoque e fortalecer estratégias regionais de vendas.

## Objetivo

* Analisar a performance comercial ao longo do tempo.
* Monitorar a relação entre demanda de vendas e reposição de estoque.
* Identificar produtos e categorias estratégicas com maior desempenho.
* Avaliar a contribuição regional para os resultados do negócio.
* Apoiar o planejamento comercial por meio de insights orientados por dados.
* Aprimorar decisões relacionadas à alocação de estoque e expansão de mercado.

## Business Context

Em um mercado altamente competitivo, compreender o desempenho das vendas e sua relação com o abastecimento de estoque é fundamental para garantir disponibilidade de produtos, maximizar receita e identificar oportunidades de expansão regional.

Este projeto foi desenvolvido para oferecer uma visão integrada do negócio por meio de dois painéis complementares: um dashboard de performance comercial e uma análise espacial da distribuição de mercado. Juntos, esses recursos permitem identificar tendências de consumo, avaliar a eficiência do planejamento de estoque e compreender a participação das diferentes regiões na composição dos resultados da empresa.

## Dashboard Structure & Analytical Views

### 1. Análise de Performance Comercial

Visão voltada ao acompanhamento dos principais indicadores de vendas, monitoramento do comportamento do mercado e suporte à tomada de decisão estratégica.

#### Principais Métricas

* Total de vendas realizadas no período.
* Valor médio das vendas.
* Volume de compras para reposição de estoque.
* Ranking dos produtos com maior participação nas vendas.
* Participação percentual das ofertas estratégicas (Core Offers).

#### Funcionalidades

* Monitoramento mensal da evolução das vendas.
* Comparação entre demanda comercial e abastecimento de estoque.
* Identificação dos produtos responsáveis pela maior geração de receita.
* Segmentação por linhas de negócio e categorias de produtos.

#### Análise de Tendência

* Comparação entre vendas e compras ao longo do tempo.
* Avaliação da eficiência do giro de estoque.
* Identificação de sazonalidades e oscilações relevantes na demanda.

### 2. Mapa de Distribuição Regional

Visão geográfica desenvolvida para identificar padrões de consumo e concentração de receita nos diferentes mercados regionais.

#### Principais Métricas

* Volume de vendas por estado.
* Distribuição geográfica da receita.
* Participação regional nos resultados comerciais.
* Penetração de mercado por segmento de produto.

#### Funcionalidades

* Visualização espacial da concentração de vendas.
* Análise comparativa entre diferentes regiões.
* Segmentação por categoria:

  * Imported;
  * Domestic;
  * Electric;
  * Passenger;
  * Premium;
  * Utility.
* Pesquisa direta por SKU.

#### Análise Geográfica

* Identificação dos mercados mais relevantes.
* Avaliação da cobertura comercial.
* Suporte ao planejamento de expansão e distribuição.

## Tecnologias e Ferramentas

* **Power BI:** Desenvolvimento dos dashboards e visualizações interativas.
* **DAX:** Criação de indicadores comerciais e medidas de inteligência temporal.
* **Power Query (M Language):** Processos de ETL, padronização e tratamento dos dados.
* **Modelagem Dimensional (Star Schema):** Estruturação do modelo analítico para otimização de desempenho.
* **Integração com Bing/TomTom:** Representação geográfica dos dados comerciais.

## Desafios Técnicos Superados

* **Alinhamento de Granularidade Temporal:**

  * Integração de tabelas de fatos distintas por meio de uma dimensão calendário única.

* **Otimização das Análises Geográficas:**

  * Padronização dos dados regionais para garantir a correta renderização dos mapas.

* **Modelagem de Indicadores Estratégicos:**

  * Desenvolvimento de métricas dinâmicas para mensurar a representatividade das ofertas prioritárias.

* **Escalabilidade Analítica:**

  * Construção de um modelo capaz de suportar análises detalhadas sem comprometer a performance.

## Principais Insights

* **Eficiência no Giro de Estoque:**

  * Identificação de períodos em que o crescimento das vendas não foi acompanhado por aumentos proporcionais nas compras.

* **Predominância de Categorias Estratégicas:**

  * Determinação dos segmentos responsáveis pela maior participação nos resultados comerciais.

* **Concentração Regional de Receita:**

  * Identificação dos mercados com maior impacto nos resultados do negócio.

* **Aprimoramento da Tomada de Decisão:**

  * Disponibilização de indicadores confiáveis para apoiar iniciativas relacionadas a estoque, estratégia comercial e expansão regional.

## Estrutura do Repositório

```text
commercial-performance-dashboard/
├── Commercial-Performance-Dashboard.pbix
├── README.md
└── images/
    ├── sales-dashboard.png
    └── regional-distribution-map.png
```

---

*Este projeto integra meu portfólio em Business Intelligence e Analytics Comercial, demonstrando minha capacidade de transformar dados de vendas em insights estratégicos que apoiam o crescimento do negócio e a tomada de decisão baseada em dados.*
