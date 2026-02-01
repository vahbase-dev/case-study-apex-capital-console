# 01 — Workbook Architecture and Data Flow

## Goal
Keep the workbook deterministic, readable, and easy to audit.

## Layering
- Inputs: assumptions, portfolio, timelines, fees
- Calc: cashflows, returns, distributions, scenario transforms
- Outputs: summary tables for dashboard and exports
- Dashboard: KPI cards and charts for decision-making

## Principles
- single source of truth for assumptions
- consistent units and time basis
- named ranges for key drivers
- no hidden circular logic
