# Retail Range Optimisation in Excel

## 1. Key Metrics for S003

From your S003 sheet (4‑week view):

| Product                   | Sales | Margin | GM%   | UPSPW | DOS | OOS | GMROS | Facings |
|---------------------------|-------|--------|-------|-------|-----|-----|-------|---------|
| Arnott’s Milk Arrowroot   | 216   | 81     | 37.5  | 15    | 16  | 2   | 162   | 2       |
| Arnott’s Scotch Fingers   | 175.5 | 70.2   | 40    | 11.2  | 14  | 3   | 280.8 | 1       |
| Coles Milk Arrowroot      | 159.5 | 79.75  | 50    | 13.8  | 18  | 1   | 159.5 | 2       |
| Woolworths Milk Arrowroot | 189   | 94.5   | 50    | 17.5  | 21  | 0   | 189   | 2       |
| Arnott’s Choc Ripple      | 164   | 78     | 47.6  | 10    | 13  | 4   | 312   | 1       |

Key observations:

- **Velocity (UPSPW)**  
  - Highest: Woolworths Arrowroot (17.5), Arnott’s Milk (15), Coles (13.8).  
  - Lower: Scotch Fingers (11.2), Choc Ripple (10).  

- **Days of Supply**  
  - All are in roughly acceptable band 13–21 days; Scotch Fingers at 14 is not “excess inventory”.  

- **Out‑of‑stock**  
  - Worst: Choc Ripple (4), then Scotch Fingers (3), then Arnott’s Milk (2).  

- **Profit / space**  
  - GMROS: Choc Ripple (312) > Scotch Fingers (280.8) > Woolworths (189) > Arnott’s Milk (162) > Coles (159.5).  

So now Scotch Fingers is **not** over‑stocked; it is a **mid‑velocity, high‑GMROS SKU with some OOS issues**. Choc Ripple is **lowest velocity, highest OOS, but best GMROS**.


<br>


## 2. Which SKU to remove?

For a small regional store with tight space, look at:

- Velocity (UPSPW) – want to avoid the slowest.  
- OOS – persistent availability issues are bad for shopper experience.  
- GMROS – want to protect the best users of space.  

Trade‑off:

- **Remove Choc Ripple**:  
  - Pros: Lowest velocity, highest OOS (4), not part of the core “Arrowroot” decision tree.  
  - Cons: Highest GMROS (very efficient per facing), some customers may value the premium choc option.  

- **Remove Scotch Fingers**:  
  - Pros: Slightly better velocity than Choc Ripple but still below others; 3 OOS.  
  - Cons: Very strong GMROS, part of core Arnott’s biscuit range.  

Given DOS is fine for both and space per SKU is only 1 facing each, the **cleanest rationalisation** is:

> **Remove Arnott’s Choc Ripple** – it is the slowest SKU and has the worst availability (4 OOS), despite strong GMROS.

This reduces range complexity while preserving the main Arrowroot cluster and a strong Arnott’s presence.


<br>


## 3. Lost sales and margin (Choc Ripple)

From the table:

- Sales (4 weeks) = **$164**  
- Margin (4 weeks) = **$78**  
- Facings = **1** → shelf ≈ 0.25 m (if 0.25 m/facing).  

Impact per 4 weeks:

- **Lost sales** ≈ $164.  
- **Lost margin** ≈ $78.  
- **Freed shelf space** ≈ 0.25 m.  
- Inventory_on_hand in raw data = 30 units → at 10 UPSPW, ≈ 3 weeks to clear (less if you discount).


<br>


## 4. What to do with freed space?

Two realistic options:

### Option A – Reallocate to high‑velocity, high‑margin SKUs

Best candidates:

- **Woolworths Milk Arrowroot**: highest UPSPW (17.5), high GM% (50), strong GMROS (189), private label strategic.  
- **Arnott’s Milk Arrowroot**: good velocity and brand equity.  

Suggested:

- Increase **Woolworths Milk Arrowroot** facings from 2 → 3.  
- Keep Arnott’s Milk, Scotch Fingers, and Coles at current facings.  

Expected effect:

- Higher availability and visibility on the best‑performing, high‑margin, private‑label SKU; likely more than offsets the lost $78 margin from Choc Ripple over time, especially if extra facing lifts UPSPW a few units.[2]

### Option B – Add a new “gap‑filling” SKU

If insight shows a missing need state (e.g., gluten‑free, family value pack), you could add:

- New SKU with estimated UPSPW 12–15, GM% ~50%, 1 facing.  
- Target margin > $78 per 4 weeks to beat Choc Ripple.  

This is more speculative; for interview/story, Option A is easier to defend without consumer data.


<br>


## 5. Pricing and OOS considerations

- All SKUs are priced about $0.10 above competitor; you keep that narrative:  
  - Maintain small premium on Arnott’s branded.  
  - Make **Woolworths Arrowroot** the clear value anchor (you could close the gap slightly if regional shoppers are price‑sensitive).[3]

- For OOS reduction:  
  - Choc Ripple’s 4 OOS become irrelevant once delisted.  
  - Focus on tightening replenishment for Arnott’s Milk and Scotch Fingers so their OOS counts (2 and 3) fall – e.g., minor DOS increase or better forecasting.[4][5]


<br>


## 6. Conclusion

For S003, I recommend **removing Arnott’s Choc Ripple**. It is the slowest SKU in the set (10 UPSPW) and has the highest out‑of‑stock count (4 events in 4 weeks), which hurts shopper experience. Although its GMROS is strong, it only uses one facing and contributes $78 margin over 4 weeks, which can be more than recovered by reallocating its 0.25 m of space to Woolworths Milk Arrowroot, our highest‑velocity, high‑margin private‑label SKU. This keeps a strong Arnott’s presence via Milk Arrowroot and Scotch Fingers, simplifies the range for a small regional store, and focuses space on the best performers while improving availability.[6][2]

[4](https://partnerhub.woolworthsgroup.com.au/s/article/Replenishment-Reports-and-Dashboard)
[5](https://partnerhub.woolworthsgroup.com.au/s/article/Woolworths-Group-Supply-Standards)
[6](https://datawiz.io/en/blog/essential-supermarket-metrics-supermarket-kpis)
