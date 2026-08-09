# Global-Economic-Indicators-Dashboard
Power BI • DAX • World Bank API • Business Intelligence

The project demonstrates how public economic data can be transformed into executive-ready dashboards that support data exploration, comparative analysis, and evidence-based decision-making.

# Executive Summary

An end-to-end Power BI analytics solution integrating multiple World Bank REST APIs with external economic datasets through Power Query and semantic modeling to analyze global economic performance, demographic trends, and regional development.

# Business Problem

Economic data is often dispersed across multiple databases, making it difficult to compare countries, identify regional patterns, and understand long-term economic trends.

This dashboard was developed to create an intuitive decision-support tool that allows users to:
- Compare countries by economic output
- Explore regional economic differences
- Visualize long-term trends
- Interactively drill into individual countries
- Support exploratory economic analysis

# Data

## Source
- World Bank Open Data
- World Development Indicators (WDI)

## Data Pipeline

This project demonstrates an enterprise-style Power BI architecture by integrating multiple live World Bank API endpoints with supporting datasets.

Data Sources:

- 🌍 World Bank Country API
- 📈 GDP API
- 💰 GDP Per Capita API
- 👥 Population API
- 📄 Country Metadata CSV
- 📈 NASA Global Temperature Dataset

All sources are transformed through Power Query, integrated into a centralized semantic model, and surfaced through an interactive Power BI dashboard.

## Primary Indicators
- GDP
- GDP per Capita
- Population
- Population Density
- Region
- Year

# Dashboard Features

## Executive Overview

Provides a high-level summary of global economic indicators including GDP, population, regional distribution, and historical trends.

<img src="https://github.com/abenyarko/Global-Economic-Indicators-Dashboard/blob/main/global-economic-dashboard.png" width="700">

## Interactive Country Analysis

Users can filter countries and explore detailed economic trends through interactive visualizations and drill-through functionality.

<img src="https://github.com/abenyarko/Global-Economic-Indicators-Dashboard/blob/main/global-economic-dashboard-meta.png" width="700">

# Skills Demonstrated

- REST API Integration
- Power Query ETL
- Semantic Modeling
- Data Engineering
- DAX Measures
- KPI Development
- Geographic Analytics
- Time-Series Analysis
- Interactive Reporting

# Technologies

- Power BI
- DAX
- Power Query
- REST APIs
- World Bank API
- Semantic Modeling
- Data Modeling
- ETL
- Geographic Visualization

# Business Impact

This dashboard demonstrates how publicly available economic data can be transformed into an interactive business intelligence solution that supports comparative analysis and executive reporting.

The project illustrates best practices in dashboard design, interactive reporting, and communicating complex global datasets through accessible visualizations.
