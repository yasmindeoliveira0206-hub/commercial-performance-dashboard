# Commercial Performance & Regional Distribution Dashboard 

This repository presents a Business Intelligence solution designed to analyze commercial performance and geographic distribution within an automotive product line. The project integrates sales indicators, inventory replenishment behavior, and regional revenue concentration to transform transactional data into strategic insights that support commercial and operational decision-making.

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

---

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

---

*This project is part of my portfolio in Business Intelligence, Commercial Analytics, and Data Visualization, demonstrating my ability to transform sales data into strategic insights that drive business performance.*



____________________________________________________________

# Commercial Performance & Regional Distribution Dashboard 

Este repositório apresenta uma solução de Business Intelligence desenvolvida para analisar a performance comercial e a distribuição geográfica de uma linha de produtos do setor automotivo. O projeto integra indicadores de vendas, comportamento de reposição de estoque e concentração regional de receita, transformando dados transacionais em insights estratégicos para apoiar decisões comerciais e operacionais.

## Contexto do Negócio

Em um mercado altamente competitivo, compreender o desempenho das vendas e sua relação com o abastecimento de estoque é fundamental para garantir disponibilidade de produtos, maximizar receita e identificar oportunidades de expansão regional.

Este projeto foi desenvolvido para oferecer uma visão integrada do negócio por meio de dois painéis complementares: um dashboard de performance comercial e uma análise espacial da distribuição de mercado. Juntos, esses recursos permitem identificar tendências de consumo, avaliar a eficiência do planejamento de estoque e compreender a participação das diferentes regiões na composição dos resultados da empresa.

## Estrutura dos Dashboards & Visões Analíticas

### 1. Análise de Performance Comercial (Sales Dashboard)

Visão voltada ao acompanhamento dos principais indicadores de vendas, monitoramento do comportamento do mercado e suporte à tomada de decisão estratégica.

#### Principais Métricas

* Total de vendas realizadas no período (Total Sales).
* Valor médio das vendas (Average Sales).
* Volume de compras para reposição de estoque (Purchases).
* Ranking dos produtos com maior participação nas vendas.
* Participação percentual das ofertas estratégicas (Core Offers).

#### Funcionalidades

* Monitoramento mensal da evolução das vendas.
* Comparação entre demanda comercial e abastecimento de estoque.
* Identificação dos produtos responsáveis pela maior geração de receita.
* Segmentação por linhas de negócio e categorias de produtos.

#### Análise de Tendência

* Utilização de gráficos de área para comparar o comportamento das vendas e das compras ao longo do tempo.
* Avaliação da eficiência do giro de estoque por período.
* Identificação de sazonalidades e variações relevantes na demanda.

---

### 2. Mapa de Distribuição Regional (Distribution Map)

Visão analítica geográfica desenvolvida para identificar padrões de consumo e concentração de receita nos diferentes mercados regionais.

#### Principais Métricas

* Volume de vendas por estado.
* Distribuição geográfica da receita.
* Participação regional na composição dos resultados comerciais.
* Penetração de mercado por segmento de produto.

#### Funcionalidades

* Visualização espacial da concentração de vendas.
* Análise comparativa entre diferentes regiões do país.
* Segmentação por tipo de produto:

  * Imported;
  * Domestic;
  * Electric;
  * Passenger;
  * Premium;
  * Utility.
* Pesquisa direta por SKU para análises específicas de portfólio.

#### Análise Geográfica

* Identificação dos mercados com maior relevância estratégica.
* Avaliação da cobertura comercial da operação.
* Suporte ao planejamento de expansão e distribuição.

## Tecnologias e Ferramentas

* **Power BI:** Desenvolvimento dos dashboards e construção das visualizações interativas.
* **DAX:** Criação de medidas para cálculo de indicadores comerciais, médias de vendas e inteligência temporal.
* **Power Query (M Language):** Processos de ETL, padronização de dados e tratamento de inconsistências cadastrais.
* **Modelagem Dimensional (Star Schema):** Estruturação do modelo analítico para otimização de desempenho.
* **Mapas Integrados (Bing/TomTom):** Representação espacial dos dados comerciais com base em divisões geográficas estaduais.

## Desafios Técnicos Superados

* **Alinhamento de Granularidade Temporal:**

  * Integração de tabelas de fatos distintas, como vendas e compras de estoque, utilizando uma dimensão calendário única para garantir análises consistentes.

* **Otimização de Análises Geográficas:**

  * Estruturação e padronização dos dados regionais para assegurar a correta renderização dos mapas e evitar ambiguidades de localização.

* **Modelagem de Indicadores Estratégicos:**

  * Desenvolvimento de métricas dinâmicas para mensurar a representatividade das ofertas prioritárias dentro do mix de produtos.

* **Escalabilidade Analítica:**

  * Construção de um modelo eficiente, capaz de suportar análises detalhadas e segmentações complexas sem perda de desempenho.

## Principais Insights Obtidos

* **Eficiência no Giro de Estoque:**

  * Identificação de períodos em que o crescimento das vendas não foi acompanhado por aumentos proporcionais nas compras, indicando melhor aproveitamento do estoque disponível.

* **Predominância de Categorias Estratégicas:**

  * Determinação dos segmentos responsáveis pela maior participação no volume comercial, orientando decisões sobre mix de produtos.

* **Concentração Regional de Receita:**

  * Identificação dos estados com maior relevância para os resultados da empresa, permitindo direcionar esforços comerciais de forma mais assertiva.

* **Aprimoramento da Tomada de Decisão:**

  * Disponibilização de indicadores confiáveis para apoiar ações relacionadas a estoque, planejamento comercial e expansão regional.

---

*Este projeto faz parte do meu portfólio em Business Intelligence, Analytics Comercial e Visualização de Dados, demonstrando minha capacidade de transformar informações de vendas em insights estratégicos que impulsionam resultados de negócio.*
