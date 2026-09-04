# 🏙️ Smart City Mobility Intelligence Platform

<h3 align="center">Integrated Urban Mobility Analytics for Delhi & Bengaluru</h3>

<p align="center">
  An interactive Power BI platform for exploring traffic, public transport, metro systems,
  ride-hailing, bike-sharing, weather, demographics, and smart mobility across two major Indian cities.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-Desktop-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
  <img src="https://img.shields.io/badge/DAX-Analytics-512BD4?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Power%20Query-Data%20Transformation-217346?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Delhi-India-E95420?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Bengaluru-India-0F9D58?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Smart%20City-Mobility%20Analytics-4285F4?style=for-the-badge"/>
</p>

---

## 📌 Table of Contents

- [🌆 Project Overview](#-project-overview)
- [🎯 Objectives](#-objectives)
- [🏙️ Cities Covered](#️-cities-covered)
- [🚦 Mobility Domains](#-mobility-domains)
- [📊 Power BI Report](#-power-bi-report)
- [🗂️ Report Pages](#️-report-pages)
- [📥 Data Sources](#-data-sources)
- [🚌 Transit Analytics](#-transit-analytics)
- [🚇 Metro Analytics](#-metro-analytics)
- [🚦 Traffic Analytics](#-traffic-analytics)
- [🚕 Ride-Hailing Analytics](#-ride-hailing-analytics)
- [🚲 Bike-Sharing](#-bike-sharing)
- [🌦️ Weather Analytics](#️-weather-analytics)
- [👥 Demographic Analytics](#-demographic-analytics)
- [⚖️ Delhi vs Bengaluru](#️-delhi-vs-bengaluru)
- [📈 KPIs](#-kpis)
- [🧮 DAX & Power Query](#-dax--power-query)
- [🏗️ Architecture](#️-architecture)
- [🔄 Data Flow](#-data-flow)
- [✨ Key Features](#-key-features)
- [📁 Repository Structure](#-repository-structure)
- [🚀 Getting Started](#-getting-started)
- [💡 Questions Explored](#-questions-explored)
- [🎓 Skills Demonstrated](#-skills-demonstrated)
- [⚠️ Limitations](#️-limitations)
- [🔮 Future Scope](#-future-scope)
- [📚 Project Resources](#-project-resources)
- [👨‍💻 Author](#-author)

---

# 🌆 Project Overview

The **Smart City Mobility Intelligence Platform** is an interactive **Microsoft Power BI** solution developed to analyze urban mobility across **Delhi and Bengaluru**.

The project integrates multiple mobility-related datasets into a unified analytical environment, enabling users to explore transportation patterns through interactive dashboards, KPIs, charts, maps, filters, and comparative analysis.

The platform covers:

- 🚦 Traffic
- 🚌 Public bus transportation
- 🚇 Metro transportation
- 🚕 Ride-hailing
- 🚲 Bike-sharing
- 🌦️ Weather
- 👥 Demographics
- 🗺️ Mobility infrastructure
- 📊 Executive-level mobility indicators
- ⚖️ Delhi vs Bengaluru comparison

The project demonstrates how heterogeneous urban datasets can be transformed into an interactive **Business Intelligence and data visualization platform**.

---

# 🎯 Objectives

The primary objectives of the project are:

### 🚌 1. Public Transport Analysis

Analyze bus routes, stops, trips, service patterns, and transportation network characteristics.

### 🚇 2. Metro Analysis

Explore metro stations, lines, routes, ridership-related information, passes, smart cards, and tokens.

### 🚦 3. Traffic Analysis

Analyze traffic density, traffic volume, average speed, travel time, road characteristics, and congestion-related indicators.

### 🚕 4. Ride-Hailing Analysis

Explore booking activity, operators, vehicle types, trip distances, fares, and revenue-related information.

### 🌦️ 5. Weather Context

Examine mobility indicators alongside temperature, humidity, and weather conditions.

### 👥 6. Demographic Context

Use population and demographic information to provide additional context for mobility analysis.

### ⚖️ 7. City Comparison

Compare mobility characteristics of Delhi and Bengaluru through a dedicated comparison dashboard.

### 📊 8. Executive Reporting

Present important mobility indicators through concise, interactive executive dashboards.

---

# 🏙️ Cities Covered

The platform contains analytical views for two major Indian metropolitan cities.

| City | Coverage |
|---|---|
| 🇮🇳 **Delhi** | Traffic, Bus, Metro, Ride-Hailing, Weather, Demographics, Smart Mobility |
| 🇮🇳 **Bengaluru** | Traffic, Bus, Metro, Ride-Hailing, Weather, Demographics, Smart Mobility |

Bengaluru is implemented directly within the Power BI report through dedicated city-specific dashboards.

---

# 🚦 Mobility Domains

The platform follows a multi-modal mobility analysis approach.

```text
                    SMART CITY
                MOBILITY INTELLIGENCE
                         │
       ┌─────────────────┼─────────────────┐
       │                 │                 │
       ▼                 ▼                 ▼
    🚦 Traffic       🚌 Transit        🚇 Metro
       │                 │                 │
       └─────────────────┼─────────────────┘
                         │
                         ▼
                  🚕 Shared Mobility
                         │
                 ┌───────┴───────┐
                 ▼               ▼
            Ride-Hailing    Bike-Sharing
                 │               │
                 └───────┬───────┘
                         ▼
                 🌦️ Weather Context
                         │
                         ▼
                  👥 Demographics
                         │
                         ▼
                📊 Executive Insights
                         │
                         ▼
                ⚖️ City Comparison
