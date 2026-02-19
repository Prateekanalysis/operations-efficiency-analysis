# Operations Efficiency & SLA Performance (Python + Excel)

A Germany-relevant operations analytics project: throughput, cycle time, SLA hit rate, bottleneck detection by shift/hour.

## How to run

1) Generate ops dataset:
```bash
python src/00_generate_ops_data.py
```
2) Build KPI tables + charts:
```bash
python src/01_ops_kpi_analysis.py
```
3) Create Excel ops KPI pack:
```bash
python src/02_build_excel_pack.py
```
Outputs are saved in `reports/` and `excel-dashboard/`.


## KPIs

- Avg cycle time (minutes)
- SLA hit rate %
- Throughput (orders/day)
- Backlog proxy (created vs completed)
- Productivity by shift and hour


## Use case story

Simulates an order-processing workflow to identify bottlenecks (peak hours, specific shifts) and propose improvements.
Great for Business Analyst roles because it links analysis → operational recommendations.

## Resume bullets (copy/paste)

- Analyzed operations throughput and SLA performance; identified bottlenecks by shift and peak-hour windows using Python.
- Built automated KPI reporting in Excel to monitor cycle time, SLA %, and productivity trends for operational decision-making.

