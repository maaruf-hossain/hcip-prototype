# hcip-prototype

V7 is the most updated html file

Temporarily Housed At: https://frightened-aqua-itqwzvwfqh.edgeone.app/ 

HCIP DESCRIPTION
Housing Credit Intelligence Platform (HCIP)
Overview
The Housing Credit Intelligence Platform (HCIP) is a lightweight web application that provides structured intelligence on residential properties across New York City. It centralizes market indicators, property‑level data, and credit‑related signals into a single interface designed for fast lookup and consistent analysis.

The platform is intended for internal use and supports research, planning, and operational decision‑making.

Product Summary
HCIP delivers three core capabilities:

Address‑level intelligence  
Users can query any NYC address to generate a property intelligence report containing estimated value, property type classification, and credit‑signal outputs.

Market conditions monitoring  
The interface surfaces daily indicators such as mortgage rate averages, conforming loan limits, and borough‑level activity trends.

Scenario and signal modeling  
The system applies internal logic to produce credit‑related signals and scenario‑based outputs that help contextualize financing conditions.

Key Features
Search and Report Generation  
Single‑field address search that returns a structured intelligence report.

Recent Activity Feed  
Displays the latest addresses queried across the platform, useful for monitoring usage patterns and borough distribution.

Market Pulse Panel  
Shows current rate benchmarks, median days‑on‑market, and other macro indicators.

Borough Filtering  
Enables users to view activity and signals scoped to Manhattan, Brooklyn, Queens, Bronx, or Staten Island.

API Endpoints  
Programmatic access to intelligence reports and market data (if enabled in the environment).

Architecture Overview
HCIP is structured into three primary layers:

Data Layer  
Aggregates external market data sources and internal property datasets.

Intelligence Engine  
Applies valuation logic, signal scoring, and scenario transformations.

Web Application Layer  
A lightweight front‑end that handles search, rendering, and user interaction.

This separation allows the intelligence logic to evolve independently of the UI.

Intended Usage
HCIP is designed for internal teams who need:

Property‑level insights for research or planning

Market condition snapshots for operational decision‑making

Scenario‑based interpretation of financing environments

Consistent, repeatable intelligence outputs across boroughs and property types

The platform is informational and not intended for underwriting or financial advice.
