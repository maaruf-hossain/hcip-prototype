# hcip-prototype

V7 is the most updated html file

Temporarily Housed At: https://frightened-aqua-itqwzvwfqh.edgeone.app/ 

HCIP DESCRIPTION
Housing Credit Intelligence Platform (HCIP)
Overview
The Housing Credit Intelligence Platform (HCIP) is a lightweight internal web application that provides structured intelligence on residential properties across New York City. It consolidates market indicators, property‑level data, and credit‑related signals into a single interface optimized for fast lookup and consistent analysis.

HCIP is intended for internal research, planning, and operational decision‑making.

Product Summary
HCIP delivers three primary capabilities:

Address‑Level Intelligence  
Query any NYC address to generate a structured intelligence report containing estimated value, property classification, and credit‑signal outputs.

Market Conditions Monitoring  
Daily indicators such as mortgage rate benchmarks, conforming loan limits, and borough‑level activity trends.

Scenario and Signal Modeling  
Internal logic that produces credit‑related signals and scenario‑based outputs to contextualize financing environments.

Key Features
Search & Report Generation  
Single‑field address search returning a structured intelligence report.

Recent Activity Feed  
Displays the latest queried addresses and borough distribution.

Market Pulse Panel  
Shows current rate benchmarks, median days‑on‑market, and other macro indicators.

Borough Filtering  
Manhattan, Brooklyn, Queens, Bronx, and Staten Island filtering for activity and signals.

API Endpoints  
Programmatic access to intelligence reports and market data (environment‑dependent).

Architecture Overview
HCIP is organized into three core layers:

Data Layer  
Aggregates external market data sources and internal property datasets.

Intelligence Engine  
Applies valuation logic, signal scoring, and scenario transformations.

Web Application Layer  
Lightweight front‑end responsible for search, rendering, and user interaction.

This separation allows the intelligence logic to evolve independently of the UI.

Intended Usage
HCIP supports internal teams needing:

Property‑Level Insights for research or planning

Market Condition Snapshots for operational decisions

Scenario‑Based Interpretation of financing environments

Consistent Intelligence Outputs across boroughs and property types

HCIP is informational only and not intended for underwriting or financial advice
