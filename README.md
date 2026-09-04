# 🏙️ Smart City Mobility Intelligence Platform

<p align="center">
  <strong>Integrated Urban Mobility Analytics for Delhi & Bengaluru</strong>
</p>

<p align="center">
  An interactive Power BI platform for exploring traffic, public transport, metro systems,
  ride-hailing, bike-sharing, weather, demographics, and smart mobility across two major Indian cities.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-Desktop-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI"/>
  <img src="https://img.shields.io/badge/DAX-Analytics-512BD4?style=for-the-badge" alt="DAX"/>
  <img src="https://img.shields.io/badge/Power%20Query-Data%20Transformation-217346?style=for-the-badge" alt="Power Query"/>
  <img src="https://img.shields.io/badge/Delhi-India-E95420?style=for-the-badge" alt="Delhi"/>
  <img src="https://img.shields.io/badge/Bengaluru-India-0F9D58?style=for-the-badge" alt="Bengaluru"/>
  <img src="https://img.shields.io/badge/Smart%20City-Mobility%20Analytics-4285F4?style=for-the-badge" alt="Smart City Mobility Analytics"/>
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
- [🇮🇳 Bengaluru Data](#-bengaluru-data)
- [🇮🇳 Delhi Data](#-delhi-data)
- [🚌 Transit Analytics](#-transit-analytics)
- [🚇 Metro Analytics](#-metro-analytics)
- [🚦 Traffic Analytics](#-traffic-analytics)
- [🚕 Ride-Hailing Analytics](#-ride-hailing-analytics)
- [🚲 Bike-Sharing Analytics](#-bike-sharing-analytics)
- [🌦️ Weather Analytics](#️-weather-analytics)
- [👥 Demographic Analytics](#-demographic-analytics)
- [⚖️ Delhi vs Bengaluru](#️-delhi-vs-bengaluru)
- [📈 Key KPIs](#-key-kpis)
- [🧮 DAX & Power Query](#-dax--power-query)
- [🏗️ System Architecture](#️-system-architecture)
- [🔄 Data Flow](#-data-flow)
- [✨ Key Features](#-key-features)
- [🎨 Visualization Techniques](#-visualization-techniques)
- [📁 Repository Structure](#-repository-structure)
- [🚀 Getting Started](#-getting-started)
- [💡 Questions Explored](#-questions-explored)
- [🎓 Skills Demonstrated](#-skills-demonstrated)
- [🌍 Potential Applications](#-potential-applications)
- [⚠️ Limitations](#️-limitations)
- [🔮 Future Scope](#-future-scope)
- [📚 Project Resources](#-project-resources)
- [🏆 Project Highlights](#-project-highlights)
- [💼 Project Value](#-project-value)
- [👨‍💻 Author](#-author)

---

# 🌆 Project Overview

The **Smart City Mobility Intelligence Platform** is an interactive **Microsoft Power BI** solution developed to analyze and explore urban mobility across **Delhi and Bengaluru**.

The project brings together multiple mobility-related datasets into a unified Business Intelligence environment. It allows users to explore transportation patterns through interactive dashboards, KPI cards, charts, maps, filters, and comparative analysis.

The platform covers multiple dimensions of urban mobility, including:

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

The project demonstrates how heterogeneous urban datasets can be prepared, modeled, analyzed, and visualized through Power BI.

---

# 🎯 Objectives

The main objectives of the project are:

### 🚌 1. Public Transport Analysis

Analyze bus routes, stops, trips, service information, route distribution, and transportation network characteristics.

### 🚇 2. Metro Analysis

Explore metro stations, lines, routes, ridership-related information, passes, smart card usage, and token usage.

### 🚦 3. Traffic Analysis

Analyze traffic density, traffic volume, average speed, travel time, road characteristics, road capacity, and congestion-related indicators.

### 🚕 4. Ride-Hailing Analysis

Explore ride-hailing bookings, operators, vehicle types, trip distances, fares, and revenue-related information.

### 🚲 5. Shared Mobility Analysis

Include bike-sharing information as an additional mobility dimension.

### 🌦️ 6. Weather Context

Analyze temperature, humidity, and weather conditions alongside mobility-related indicators.

### 👥 7. Demographic Context

Use population and demographic information to provide additional context for urban mobility analysis.

### ⚖️ 8. City Comparison

Provide a dedicated analytical view comparing mobility characteristics of Delhi and Bengaluru.

### 📊 9. Executive Reporting

Present important mobility indicators through interactive executive dashboards and intelligence pages.

---

# 🏙️ Cities Covered

The platform provides dedicated analytical views for two major Indian metropolitan cities.

| City | Mobility Coverage |
|---|---|
| 🇮🇳 **Delhi** | Traffic, Bus, Metro, Ride-Hailing, Weather, Demographics, Smart Mobility |
| 🇮🇳 **Bengaluru** | Traffic, Bus, Metro, Weather, Demographics, Smart Mobility |

The Power BI report contains dedicated Bengaluru dashboards for executive, transit, traffic, metro, smart mobility, and executive intelligence analysis.

A dedicated **Delhi vs Bengaluru** page is also included for cross-city comparison.

---

# 🚦 Mobility Domains

The platform follows a multi-dimensional urban mobility analysis approach.

```text
                         SMART CITY
                     MOBILITY INTELLIGENCE
                              │
        ┌─────────────────────┼─────────────────────┐
        │                     │                     │
        ▼                     ▼                     ▼
    🚦 TRAFFIC            🚌 TRANSIT            🚇 METRO
        │                     │                     │
        │              ┌──────┴──────┐              │
        │              │             │              │
        │            ROUTES        STOPS          LINES
        │              │             │              │
        └──────────────┼─────────────┼──────────────┘
                       │
                       ▼
                🚕 SHARED MOBILITY
                       │
              ┌────────┴────────┐
              ▼                 ▼
        RIDE-HAILING       BIKE-SHARING
              │                 │
              └────────┬────────┘
                       │
                       ▼
                🌦️ WEATHER
                       │
                       ▼
                👥 DEMOGRAPHICS
                       │
                       ▼
              📊 EXECUTIVE INSIGHTS
                       │
                       ▼
              ⚖️ CITY COMPARISON
```

---

# 📊 Power BI Report

The primary analytical component of the project is the Power BI report:

```text
Smart-City Mobility-Intelligence-Platform-Final.pbix
```

The report contains **16 report pages** covering different mobility domains and city-specific analysis.

The report combines interactive visualizations, KPI cards, charts, maps, filters, slicers, and analytical views.

---

# 🗂️ Report Pages

The Power BI report contains the following **16 pages**:

| # | Report Page | Main Focus |
|---:|---|---|
| 01 | **Data Acquisition and Integration** | Data and integration overview |
| 02 | **Executive Dashboard** | Overall mobility overview |
| 03 | **Bengaluru Executive Dashboard** | Bengaluru executive overview |
| 04 | **Transit Analytics Dashboard** | Public bus transportation |
| 05 | **Bengaluru Transit Analytics** | Bengaluru bus analytics |
| 06 | **Traffic Analytics** | Traffic and road mobility |
| 07 | **Bengaluru Traffic Analytics** | Bengaluru traffic analytics |
| 08 | **Metro Analytics Dashboard** | Metro transportation |
| 09 | **Bengaluru Metro Analytics Dashboard** | Bengaluru metro analytics |
| 10 | **Smart Mobility Dashboard** | Integrated smart mobility |
| 11 | **Bengaluru Smart Mobility** | Bengaluru smart mobility |
| 12 | **Executive Intelligence** | Executive-level mobility intelligence |
| 13 | **Bengaluru Executive Intelligence** | Bengaluru executive intelligence |
| 14 | **Ride Hailing Dashboard** | Ride-hailing analysis |
| 15 | **Ride Hailing Delhi** | Delhi ride-hailing analysis |
| 16 | **Delhi vs Bengaluru** | Cross-city comparison |

---

# 📥 Data Sources

The project repository contains datasets for both Delhi and Bengaluru.

The datasets are organized into separate city folders:

```text
Bengaluru Data/
Delhi Data/
```

The data covers multiple mobility dimensions rather than relying on a single transportation source.

---

# 🇮🇳 Bengaluru Data

The `Bengaluru Data/` directory contains the following datasets:

| Dataset | Purpose |
|---|---|
| `Banglore_traffic_Dataset.csv` | Bengaluru traffic analysis |
| `Bengaluru_Bus_aggregated.csv` | Aggregated bus information |
| `Bengaluru_Bus_routes.csv` | Bus route information |
| `Bengaluru_Bus_stops.csv` | Bus stop information |
| `Bengaluru_Demographics.csv` | Demographic analysis |
| `Bengaluru_Weather_2025.csv` | Weather analysis |
| `NammaMetro_Ridership_Dataset.csv` | Metro ridership analysis |
| `bengaluru_metro_network.csv` | Metro network information |
| `bengaluru_metro_stations.csv` | Metro station information |
| `Bike-Sharing.zip` | Bike-sharing dataset |
| `Bengaluru-Metro-Network-Dataset-main.zip` | Metro network dataset package |

---

# 🇮🇳 Delhi Data

The `Delhi Data/` directory contains the following datasets:

| Dataset | Purpose |
|---|---|
| `Delhi_Demographics.xlsx` | Demographic analysis |
| `Delhi_Weather_2025.csv` | Weather analysis |
| `delhi_traffic_features.csv` | Traffic feature data |
| `delhi_traffic_target.csv` | Traffic target data |
| `DMRC_GTFS.zip` | Delhi Metro GTFS dataset |
| `Delhi GTFS.zip` | Delhi public transport GTFS dataset |
| `Delhi Traffic Dataset.zip` | Delhi traffic dataset |
| `Bike-Sharing.zip` | Bike-sharing dataset |

---

# 🚌 Transit Analytics

Public transportation is one of the core components of the platform.

The transit dashboards provide analytical views related to:

- Bus routes
- Bus stops
- Trips
- Service information
- Route distribution
- Stop activity
- Transportation network structure

## Transit Analysis Flow

```text
                 BUS TRANSPORTATION
                         │
          ┌──────────────┼──────────────┐
          ▼              ▼              ▼
        ROUTES          STOPS          TRIPS
          │              │              │
          └──────────────┼──────────────┘
                         ▼
                SERVICE INFORMATION
                         │
                         ▼
                 TRANSIT ANALYTICS
                         │
                         ▼
                 POWER BI DASHBOARD
```

## Bengaluru Transit

The report includes a dedicated **Bengaluru Transit Analytics** page.

It provides analysis based on Bengaluru bus routes, stops, aggregated bus information, and related transportation data.

## Delhi Transit

Delhi transit information is represented through the available GTFS-based transportation datasets and corresponding Power BI analysis.

---

# 🚇 Metro Analytics

Metro transportation is analyzed separately from general bus transit.

The metro dashboards cover information related to:

- Metro stations
- Metro lines
- Metro routes
- Ridership
- Pass usage
- Smart card usage
- Token usage
- Metro network distribution

## Metro Analysis Flow

```text
                   METRO DATA
                       │
         ┌─────────────┼─────────────┐
         ▼             ▼             ▼
       LINES        STATIONS       ROUTES
         │             │             │
         └─────────────┼─────────────┘
                       ▼
                  RIDERSHIP
                       │
          ┌────────────┼────────────┐
          ▼            ▼            ▼
        PASSES      SMART CARD    TOKENS
          │            │            │
          └────────────┼────────────┘
                       ▼
                 METRO ANALYTICS
```

Dedicated metro pages are available for:

- Delhi
- Bengaluru

---

# 🚦 Traffic Analytics

The traffic dashboards focus on urban road transportation.

### Key analytical areas include:

- Traffic density
- Traffic volume
- Average speed
- Travel time
- Road type
- Road capacity
- Capacity utilization
- Congestion-related indicators
- Time-of-day patterns
- Speed and distance relationships

## Traffic Analysis Flow

```text
                    TRAFFIC DATA
                         │
         ┌───────────────┼───────────────┐
         ▼               ▼               ▼
       VOLUME          SPEED          TRAVEL TIME
         │               │               │
         └───────────────┼───────────────┘
                         ▼
                  ROAD CHARACTERISTICS
                         │
                         ▼
                  CAPACITY ANALYSIS
                         │
                         ▼
                  TRAFFIC ANALYTICS
```

## Bengaluru Traffic

The report includes a dedicated **Bengaluru Traffic Analytics** page.

It provides city-specific analysis of Bengaluru traffic-related information.

## Delhi Traffic

The report includes the main **Traffic Analytics** page for traffic analysis based on the available Delhi traffic datasets.

---

# 🚕 Ride-Hailing Analytics

Ride-hailing is included as an additional shared-mobility dimension.

The ride-hailing dashboards analyze information related to:

- Bookings
- Operators
- Vehicle types
- Trip distance
- Fare
- Revenue-related indicators
- Booking patterns
- Trip characteristics

## Ride-Hailing Analysis

```text
                    RIDE-HAILING
                         │
        ┌────────────────┼────────────────┐
        ▼                ▼                ▼
    OPERATORS        VEHICLES          BOOKINGS
        │                │                │
        └────────────────┼────────────────┘
                         ▼
                 TRIP CHARACTERISTICS
                         │
                  ┌──────┴──────┐
                  ▼             ▼
              DISTANCE         FARE
                  │             │
                  └──────┬──────┘
                         ▼
                 RIDE-HAILING
                   ANALYTICS
```

The Power BI report contains:

- **Ride Hailing Dashboard**
- **Ride Hailing Delhi**

---

# 🚲 Bike-Sharing Analytics

Bike-sharing datasets are included within the project repository as part of the broader shared-mobility analysis.

Bike-sharing provides an additional transportation dimension alongside:

- Public transportation
- Metro
- Ride-hailing
- Traffic

The bike-sharing datasets provide additional context when studying urban mobility.

---

# 🌦️ Weather Analytics

Weather information is included as contextual data within the mobility analysis.

The project contains weather datasets with indicators such as:

- Temperature
- Humidity
- Weather conditions
- Date/time observations

Weather can be analyzed alongside mobility indicators.

```text
                      WEATHER
                         │
          ┌──────────────┼──────────────┐
          ▼              ▼              ▼
     TEMPERATURE      HUMIDITY      CONDITIONS
          │              │              │
          └──────────────┼──────────────┘
                         ▼
                  MOBILITY CONTEXT
                         │
            ┌────────────┴────────────┐
            ▼                         ▼
         TRAFFIC                  TRANSIT
```

> Weather-related relationships shown in the dashboards represent analytical observations and should not automatically be interpreted as causal relationships.

---

# 👥 Demographic Analytics

Demographic data provides additional context for understanding urban mobility.

The project includes demographic datasets containing information related to:

- Population
- Population distribution
- Population density
- Urban/rural characteristics

Demographic information can be considered alongside transportation infrastructure and mobility indicators.

---

# ⚖️ Delhi vs Bengaluru

The **Delhi vs Bengaluru** page provides a dedicated cross-city comparison.

The purpose of this page is to bring mobility-related indicators for both cities into a common analytical view.

### Comparison Areas

- 🚦 Traffic
- 🚌 Public transport
- 🚇 Metro
- 🚕 Ride-hailing
- 🚲 Shared mobility
- 🌦️ Weather
- 👥 Demographics
- 📊 Mobility indicators

## Comparison Concept

```text
              ┌─────────────────┐
              │      DELHI      │
              └────────┬────────┘
                       │
                       ▼
                COMMON ANALYSIS
                       │
                       ▼
              ┌─────────────────┐
              │    BENGALURU    │
              └─────────────────┘
                       │
                       ▼
               COMPARATIVE VIEW
```

The comparison dashboard allows users to identify differences and similarities across the available mobility dimensions.

---

# 📈 Key KPIs

The Power BI report uses KPI cards and analytical measures to summarize important mobility indicators.

## 🚦 Traffic KPIs

- Average Speed
- Traffic Volume
- Traffic Density
- Travel Time
- Road Capacity
- Capacity Utilization

## 🚌 Transit KPIs

- Total Routes
- Total Stops
- Total Trips
- Route Distribution
- Stop Activity

## 🚇 Metro KPIs

- Metro Stations
- Metro Lines
- Ridership
- Pass Usage
- Smart Card Usage
- Token Usage

## 🚕 Ride-Hailing KPIs

- Bookings
- Trip Distance
- Fare
- Revenue-related indicators
- Vehicle Type
- Operator Activity

## 🌦️ Weather Indicators

- Average Temperature
- Average Humidity
- Weather Conditions

## 👥 Demographic Indicators

- Population
- Population Density
- Urban/Rural Distribution

---

# 🧮 DAX & Power Query

## DAX

**DAX (Data Analysis Expressions)** is used within Power BI for analytical calculations and measures.

DAX supports calculations such as:

- Aggregations
- KPIs
- Ratios
- Conditional measures
- Analytical metrics
- Dashboard calculations

---

## Power Query

**Power Query** is used as part of the data preparation and transformation workflow.

Typical operations include:

- Data import
- Data cleaning
- Data transformation
- Column transformations
- Data type handling
- Dataset preparation
- Data integration

---

# 🏗️ System Architecture

The architecture diagram illustrates the overall project workflow, from source datasets and data preparation to Power BI analysis and dashboard presentation.

<p align="center">
  <img src="Urban_Pulse_Architecture_Diagram.png" alt="Smart City Mobility Intelligence Platform Architecture" width="1000"/>
</p>

## Architecture Overview

```text
                 ┌──────────────────────────┐
                 │       SOURCE DATA        │
                 └────────────┬─────────────┘
                              │
       ┌──────────────────────┼──────────────────────┐
       │                      │                      │
       ▼                      ▼                      ▼
  Traffic Data          Transit Data           Metro Data
       │                      │                      │
       ├──────────────────────┼──────────────────────┤
       │                      │                      │
       ▼                      ▼                      ▼
 Weather Data           Demographics         Ride-Hailing
       │                      │                      │
       └──────────────────────┼──────────────────────┘
                              │
                              ▼
                 ┌──────────────────────────┐
                 │       POWER QUERY        │
                 │ Data Preparation &       │
                 │ Transformation           │
                 └────────────┬─────────────┘
                              │
                              ▼
                 ┌──────────────────────────┐
                 │       POWER BI           │
                 │       DATA MODEL         │
                 └────────────┬─────────────┘
                              │
                              ▼
                 ┌──────────────────────────┐
                 │          DAX             │
                 │ Measures & Calculations  │
                 └────────────┬─────────────┘
                              │
                              ▼
                 ┌──────────────────────────┐
                 │  INTERACTIVE REPORTING   │
                 └────────────┬─────────────┘
                              │
              ┌───────────────┼───────────────┐
              │               │               │
              ▼               ▼               ▼
           DELHI          BENGALURU       COMPARISON
              │               │               │
              └───────────────┼───────────────┘
                              │
                              ▼
                    EXECUTIVE INSIGHTS
```

---

# 🔄 Data Flow

The project follows a structured Business Intelligence workflow.

```text
┌───────────────────────┐
│    SOURCE DATASETS    │
└───────────┬───────────┘
            │
            ▼
┌───────────────────────┐
│     DATA IMPORT       │
└───────────┬───────────┘
            │
            ▼
┌───────────────────────┐
│ DATA PREPARATION      │
│ & TRANSFORMATION      │
└───────────┬───────────┘
            │
            ▼
┌───────────────────────┐
│    DATA MODELING      │
└───────────┬───────────┘
            │
            ▼
┌───────────────────────┐
│   DAX CALCULATIONS    │
└───────────┬───────────┘
            │
            ▼
┌───────────────────────┐
│ POWER BI VISUALS      │
└───────────┬───────────┘
            │
            ▼
┌───────────────────────┐
│ INTERACTIVE DASHBOARDS│
└───────────┬───────────┘
            │
            ▼
┌────────────────────────┐
│ EXECUTIVE & COMPARATIVE│
│        ANALYSIS        │
└────────────────────────┘
```

---

# ✨ Key Features

## 🌆 Multi-City Analytics

Dedicated analytical views for:

- Delhi
- Bengaluru

## 🚦 Multi-Modal Mobility

The platform combines:

- Traffic
- Bus
- Metro
- Ride-hailing
- Bike-sharing
- Weather
- Demographics

## 📊 Interactive Power BI Reporting

The report uses:

- Slicers
- Filters
- KPI cards
- Charts
- Maps
- Comparative visuals

## 🗺️ Geographic Visualization

Transportation infrastructure can be explored through geographic visuals, including:

- Bus stops
- Metro stations
- Mobility locations

## 🚌 Transit Intelligence

Analysis of:

- Routes
- Stops
- Trips
- Service information

## 🚇 Metro Intelligence

Analysis of:

- Metro lines
- Stations
- Routes
- Ridership
- Passes
- Smart cards
- Tokens

## 🚦 Traffic Intelligence

Analysis of:

- Traffic volume
- Traffic density
- Average speed
- Travel time
- Road capacity
- Capacity utilization
- Time-related traffic patterns

## 🚕 Ride-Hailing Intelligence

Analysis of:

- Bookings
- Operators
- Vehicle types
- Distance
- Fare
- Revenue-related indicators

## ⚖️ Comparative Intelligence

Dedicated:

**Delhi vs Bengaluru**

comparison page.

## 📊 Executive Reporting

Executive dashboards consolidate important mobility indicators into high-level analytical views.

---

# 🎨 Visualization Techniques

The Power BI report uses multiple visualization techniques.

### 📌 KPI Cards

Used to highlight important numerical indicators.

### 📊 Bar & Column Charts

Used for category comparisons, rankings, and distributions.

### 📈 Line Charts

Used for temporal and trend-oriented analysis.

### 🗺️ Maps

Used to represent transportation infrastructure geographically.

### 🎯 Gauges

Used for selected performance-oriented indicators.

### 🎛️ Slicers

Used to allow users to interactively filter dashboard content.

---

# 📁 Repository Structure

```text
Smart-City-Mobility-Intelligence-Platform/
│
├── 📂 Bengaluru Data/
│   ├── Banglore_traffic_Dataset.csv
│   ├── Bengaluru-Metro-Network-Dataset-main.zip
│   ├── Bengaluru_Bus_aggregated.csv
│   ├── Bengaluru_Bus_routes.csv
│   ├── Bengaluru_Bus_stops.csv
│   ├── Bengaluru_Demographics.csv
│   ├── Bengaluru_Weather_2025.csv
│   ├── Bike-Sharing.zip
│   ├── NammaMetro_Ridership_Dataset.csv
│   ├── bengaluru_metro_network.csv
│   └── bengaluru_metro_stations.csv
│
├── 📂 Delhi Data/
│   ├── Bike-Sharing.zip
│   ├── DMRC_GTFS.zip
│   ├── Delhi GTFS.zip
│   ├── Delhi Traffic Dataset.zip
│   ├── Delhi_Demographics.xlsx
│   ├── Delhi_Weather_2025.csv
│   ├── delhi_traffic_features.csv
│   └── delhi_traffic_target.csv
│
├── 📊 Smart-City Mobility-Intelligence-Platform-Final.pbix
│
├── 🖼️ Urban_Pulse_Architecture_Diagram.png
│
├── 📄 Documentation.docx
│
├── 📊 Presentation.pptx
│
├── 📜 README.md
│
└── ⚙️ .gitattributes
```

---

# 🚀 Getting Started

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/littlestuart07/Smart-City-Mobility-Intelligence-Platform.git
```

## 2️⃣ Navigate to the Project

```bash
cd Smart-City-Mobility-Intelligence-Platform
```

## 3️⃣ Install Power BI Desktop

Install **Microsoft Power BI Desktop** on a compatible Windows system.

## 4️⃣ Open the Power BI Report

Open:

```text
Smart-City Mobility-Intelligence-Platform-Final.pbix
```

using Power BI Desktop.

## 5️⃣ Explore the Report

Navigate through the report pages to explore:

- Executive dashboards
- Bengaluru executive analysis
- Transit analytics
- Bengaluru transit analytics
- Traffic analytics
- Bengaluru traffic analytics
- Metro analytics
- Bengaluru metro analytics
- Smart mobility
- Bengaluru smart mobility
- Executive intelligence
- Bengaluru executive intelligence
- Ride-hailing analysis
- Delhi ride-hailing analysis
- Delhi vs Bengaluru comparison

---

# 💡 Questions Explored

The platform can be used to explore a wide range of urban mobility questions.

## 🚦 Traffic

- How does traffic vary throughout the day?
- How does average speed change?
- How does travel time vary?
- Which areas show higher traffic activity?
- How does traffic volume relate to road capacity?
- How does capacity utilization vary?

## 🚌 Transit

- How are bus routes distributed?
- How many stops and trips are represented?
- Which stops show higher activity?
- What characteristics can be observed in the bus network?
- How does bus transportation differ between cities?

## 🚇 Metro

- How are metro stations distributed?
- How are metro lines represented?
- How does ridership vary?
- How are passes represented?
- How are smart cards and tokens represented?
- What characteristics can be observed in the metro network?

## 🚕 Ride-Hailing

- How does booking activity vary?
- Which operators are represented?
- Which vehicle types are used?
- How does trip distance relate to fare?
- How do ride-hailing characteristics vary?

## 🚲 Bike-Sharing

- What role does bike-sharing data provide within the broader mobility analysis?
- How can shared mobility be considered alongside public transportation and traffic?

## 🌦️ Weather

- How do temperature and humidity vary?
- What mobility patterns are visible under different weather conditions?
- What relationships can be observed between weather and transportation indicators?

## 👥 Demographics

- What demographic context is available for the cities?
- How can population and density information provide additional context for mobility analysis?

## ⚖️ City Comparison

- How do Delhi and Bengaluru differ across mobility indicators?
- How do their transportation networks compare?
- What differences are visible across traffic, transit, and metro analysis?
- How do the available mobility dimensions compare across the two cities?

---

# 🎓 Skills Demonstrated

This project demonstrates practical skills in:

## 📊 Business Intelligence

- Dashboard development
- KPI design
- Interactive reporting
- Data storytelling
- Analytical presentation

## 🧮 Data Analytics

- Aggregation
- Trend analysis
- Comparative analysis
- Multi-dimensional analysis
- Relationship analysis

## 🟨 Microsoft Power BI

- Report development
- Data modeling
- Interactive visualizations
- Dashboard design
- Geographic visualization
- Report navigation

## 🧮 DAX

- Measures
- Aggregations
- Analytical calculations
- KPI calculations
- Conditional calculations

## 🔄 Power Query

- Data import
- Data cleaning
- Data transformation
- Data preparation
- Data integration

## 🗺️ Geospatial Visualization

- Bus stop mapping
- Metro station mapping
- Transportation infrastructure visualization

## 🚦 Urban Mobility Analytics

- Traffic analysis
- Public transport analysis
- Metro analysis
- Ride-hailing analysis
- Shared mobility analysis

---

# 🌍 Potential Applications

The analytical framework demonstrated by this project can support use cases such as:

## 🏙️ Smart City Planning

Understanding mobility characteristics across urban areas.

## 🚦 Traffic Analysis

Studying traffic levels, speeds, travel times, road characteristics, and capacity-related indicators.

## 🚌 Public Transport Planning

Understanding bus routes, stops, trips, and service patterns.

## 🚇 Metro Analysis

Analyzing metro infrastructure and ridership-related information.

## 🚕 Shared Mobility Analysis

Understanding ride-hailing and bike-sharing activity.

## 📊 Transportation Reporting

Providing consolidated mobility indicators through interactive dashboards.

## 🎓 Academic & Research Projects

Demonstrating how heterogeneous urban datasets can be integrated into an interactive Business Intelligence environment.

---

# ⚠️ Limitations

## 1. Dataset Dependency

The quality of the analysis depends on the quality, completeness, consistency, and coverage of the underlying datasets.

## 2. Historical / Provided Data

The platform is based on the datasets included in the project and should not be interpreted as a guaranteed real-time representation of city transportation.

## 3. Correlation vs Causation

Relationships observed between variables such as weather and mobility should not automatically be interpreted as causal relationships.

## 4. Geographic Coverage

Insights depend on the geographic coverage available within the source datasets.

## 5. Data Availability

Different mobility domains may have different levels of data coverage, granularity, and availability.

## 6. Analytical Platform

The project is primarily a Business Intelligence and visualization platform rather than a complete operational transportation management system.

## 7. No Real-Time Claim

The project does not claim to provide live traffic monitoring or real-time transportation control.

---

# 🔮 Future Scope

The platform can be extended in several directions.

## 📡 Real-Time Data Integration

Future versions could connect live feeds from:

- Traffic systems
- Public transport
- Metro systems
- Ride-hailing platforms
- Shared mobility systems

## 🤖 Predictive Analytics

Future versions could incorporate predictive models for:

- Traffic forecasting
- Ridership forecasting
- Demand prediction
- Mobility trend prediction

## 🗺️ Advanced Geospatial Analytics

Future versions could introduce:

- Congestion hotspot analysis
- Transit accessibility analysis
- Station catchment analysis
- Mobility corridor analysis
- Route optimization

## 🌐 Additional Cities

The framework can be extended to cities such as:

- Mumbai
- Chennai
- Hyderabad
- Pune
- Kolkata
- Ahmedabad

## 🔌 Additional Mobility Data

Future versions could incorporate:

- Parking
- Electric vehicles
- EV charging stations
- Road incidents
- Pedestrian mobility
- Cycling infrastructure

## 📱 Mobile Reporting

The dashboards could be further optimized for mobile and smaller-screen devices.

---

# 📚 Project Resources

The repository contains additional project materials.

## 📊 Power BI Report

```text
Smart-City Mobility-Intelligence-Platform-Final.pbix
```

Main interactive Power BI report.

## 📄 Documentation

```text
Documentation.docx
```

Supporting project documentation.

## 📊 Presentation

```text
Presentation.pptx
```

Project presentation material.

## 🖼️ Architecture Diagram

```text
Urban_Pulse_Architecture_Diagram.png
```

Visual representation of the project architecture and workflow.

---

# 🏆 Project Highlights

| Capability | Status |
|:---|:---:|
| 🇮🇳 Delhi Analytics | ✅ |
| 🇮🇳 Bengaluru Analytics | ✅ |
| 🚦 Traffic Analytics | ✅ |
| 🚌 Bus Analytics | ✅ |
| 🚇 Metro Analytics | ✅ |
| 🚕 Ride-Hailing Analytics | ✅ |
| 🚲 Bike-Sharing Data | ✅ |
| 🌦️ Weather Analytics | ✅ |
| 👥 Demographic Analysis | ✅ |
| 🗺️ Geographic Visualization | ✅ |
| 📊 Executive Dashboards | ✅ |
| ⚖️ Delhi vs Bengaluru | ✅ |
| 🧮 DAX Analytics | ✅ |
| 🔄 Power Query | ✅ |
| 📈 Interactive Power BI Report | ✅ |
| 🏗️ Architecture Documentation | ✅ |

---

# 💼 Project Value

The core value of the platform is the integration of multiple urban mobility dimensions into one analytical environment.

Instead of studying traffic, buses, metro systems, ride-hailing, bike-sharing, weather, and demographics independently, the platform provides a consolidated view for exploring patterns and relationships across these dimensions.

```text
                    MULTIPLE DATASETS
                           │
                           ▼
                  DATA PREPARATION
                           │
                           ▼
                     DATA MODEL
                           │
                           ▼
                    DAX ANALYTICS
                           │
                           ▼
                  POWER BI REPORT
                           │
        ┌──────────────────┼──────────────────┐
        ▼                  ▼                  ▼
     TRAFFIC            TRANSIT             METRO
        │                  │                  │
        └──────────────────┼──────────────────┘
                           │
                    SMART MOBILITY
                           │
                ┌──────────┴──────────┐
                ▼                     ▼
          RIDE-HAILING          BIKE-SHARING
                │                     │
                └──────────┬──────────┘
                           ▼
                  WEATHER + DEMOGRAPHICS
                           │
                           ▼
                   EXECUTIVE INSIGHTS
                           │
                           ▼
                  DELHI vs BENGALURU
```

---

# 🔍 Why This Project Matters

Urban mobility is a multi-dimensional problem.

Transportation patterns cannot always be understood through a single mobility mode. Traffic, public transportation, metro systems, ride-hailing, bike-sharing, weather, demographics, and transportation infrastructure can all provide useful context.

This project demonstrates how **Business Intelligence, data preparation, data modeling, DAX, Power Query, and interactive visualization** can be combined to create a unified urban mobility analytics environment.

The platform provides a structured way to explore:

```text
Traffic
   +
Public Transport
   +
Metro
   +
Ride-Hailing
   +
Bike-Sharing
   +
Weather
   +
Demographics
   =
Urban Mobility Intelligence
```

---

# 📌 Project Summary

| Category | Details |
|---|---|
| **Project** | Smart City Mobility Intelligence Platform |
| **Cities** | Delhi & Bengaluru |
| **Primary Technology** | Microsoft Power BI |
| **Analytics** | DAX |
| **Data Preparation** | Power Query |
| **Report Pages** | 16 |
| **Major Domains** | Traffic, Transit, Metro, Ride-Hailing, Bike-Sharing, Weather, Demographics |
| **Main Output** | Interactive Power BI Report |

---

# 👨‍💻 Author

## Suyash Agrawaal

**Smart City Mobility Intelligence Platform**

---

# ⭐ Support

If you find this project useful for learning about:

- Power BI
- DAX
- Power Query
- Business Intelligence
- Data Visualization
- Smart Cities
- Urban Mobility Analytics

consider giving the repository a ⭐.

---

<p align="center">
  <strong>🏙️ Smart City Mobility Intelligence Platform</strong>
  <br/>
  Delhi • Bengaluru • Traffic • Transit • Metro • Ride-Hailing • Smart Mobility
</p>

<p align="center">
  Built with ❤️ using Microsoft Power BI
</p>
