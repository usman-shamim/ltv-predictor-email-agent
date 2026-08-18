# LTV Predictor + Targeted Email Agent

**Analyzes customer purchase history, calculates lifetime value, sends personalized emails based on segment.**

- **Target:** Stores with 500+ customers
- **Price:** PKR 45,000 setup + PKR 5,000/month

## What It Does

Extracts customer data from Shopify, calculates lifetime value and purchase segments (VIP, Regular, At-Risk) using Claude AI, then sends personalized emails based on each segment.

## Build Plan

| Day | Task |
|-----|------|
| 1 | Extract customer data from Shopify |
| 2 | Create LTV calculation + segmentation |
| 3 | Create email templates |
| 4 | Automate sending |
| 5 | Demo + GitHub |

## Structure

```
ltv-predictor-email-agent/
├── workflow.json          # n8n workflow export
├── README.md
└── .gitignore
```