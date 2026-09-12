# Customer Support Operations — SLA Compliance Analytics

## Overview
An Operations Analyst project analyzing customer support ticket performance, focused on SLA compliance, escalation trends, and service desk efficiency. Built using Microsoft Excel and Power BI, covering the full analytical lifecycle from raw data cleaning through executive-ready dashboarding.

## Tools Used
Microsoft Excel · Power BI · Power Query · DAX

## Business Context
Support operations teams are measured on how consistently they meet promised response and resolution times (SLAs). This project simulates that exact operational reporting need tracking not just ticket volume, but whether the team is meeting its commitments to customers, and where breakdowns occur.

## Key Metrics Designed
- **SLA Compliance Rate** — percentage of resolved tickets that met their promised resolution time
- **Escalation Rate** — percentage of tickets requiring hand-off to a senior tier
- **Average Resolution Time** — mean time to resolve a ticket, by priority level
- **Backlog** — count of unresolved tickets at any given point
- **Reopen Rate** — percentage of tickets reopened after being marked resolved
- **Average CSAT Score** — customer satisfaction rating on resolved tickets

## What This Project Includes
- Data cleaning of a 3,200+ record support ticket dataset, including a resolved-datetime data integrity check
- A custom SLA compliance measure using SUMPRODUCT logic to compare two columns row-by-row (Resolution Time vs SLA Target)
- 6 Pivot Tables analyzing performance by Team, Agent, City, Channel, Category, and Priority
- A 242-day operational tracker
- A 3-page interactive Power BI dashboard: Executive Summary, Team & Agent Performance, and Category & Channel Analysis
- Drill-down analysis identifying a specific underperforming agent and the operational pattern behind it
- Ad hoc analysis identifying the highest and lowest SLA-compliant Category-Priority combinations
- A validated Excel-to-Power BI discrepancy: identified and corrected a DAX measure that handled blank values differently than Excel, which was silently inflating the calculated SLA compliance rate
- Documented findings and actionable recommendations for management

## Files in This Repository
- `Customer_Support_Operations_SLA_Compliance_Analytics.xlsx` — full Excel analysis
- `Customer_Support_Operations_SLA_Compliance_Analytics.pbix` — interactive Power BI dashboard

## How to View
Download the `.xlsx` file to review the full analysis, or open the `.pbix` file in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free) to interact with the dashboard.

---
*Demonstrates hands-on experience in operations reporting, SLA analysis, and process efficiency measurement using Excel and Power BI.*
