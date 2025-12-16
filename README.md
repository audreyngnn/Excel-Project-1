# Retail Range Optimisation – Excel Digital Twin

An Excel-based simulation of how a Range Optimisation Analyst optimises product range and shelf space in a large retailer.

## Overview

**Category:** Pet Food (Dry Dog Food)  
**Data:** 30 SKUs, 8 stores, 129 store–SKU records (4-week period)  
**Output:** Store-specific range recommendations, facings, and delist decisions

## Scoring Model

SKUs scored using normalised metrics (0–1):
```
TotalScore = Σ(Weight × Metric_Normalised)
```

**Base weights (Current State):**
- UPSPW (velocity): 30%
- GMROS (space efficiency): 30%
- Sales: 25%
- Gross Margin %: 15%

## Scenarios

Four scenarios test different strategies by adjusting weights:

1. **Current State** – Baseline performance
2. **Space Constrained** – Maximise velocity under −20% space
3. **Premium Focus** – Favour GMROS & margin quality *(recommended)*
4. **Value Focus** – Maximise volume & traffic

## Key Results (Premium Focus)

vs. Baseline over 4 weeks:
- **Sales:** −17% ($364k → $303k)
- **Margin %:** Improved slightly
- **Range:** −35% (129 → 84 SKUs)
- **GMROS:** +4–5% improvement

**Insight:** Trades volume for a simpler, more profitable range aligned with premium positioning.

## Files

`Range_Optimisation_Framework_Complete.xlsx` contains:
- **Scenario Comparison** – Weight configurations
- **Scenario Outcomes** – KPI comparisons
- **Decision Framework** – Scoring logic, removal criteria, facing rules
- **Example Recommendation** – Worked Premium Focus scenario with store-specific actions

## Use Cases

- Portfolio piece for Range Planning / Category Management roles
- Interview discussion tool demonstrating trade-off analysis
- Template for testing range strategies in Excel

## Extensions

- Add price/promotion scenarios
- Test new product introductions
- Incorporate OOS forecasting

---

*Built to demonstrate practical range optimisation skills using Excel only.*
