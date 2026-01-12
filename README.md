# Insurance Premium Proposal & Competitive Pricing Analysis

### Group Employee Insurance – Workers’ Compensation, Loss of License, Leisure Accident

## Project Overview

This project develops a premium proposal for a large collaboration of companies requiring employee insurance coverage against miscellaneous personal injuries. The analysis covers **Workers’ Compensation**, **Loss of License**, and **Leisure Accident** insurance products and is based on historical claims experience and employee exposure data.

The project replicates a real-world **non-life insurance pricing tender**, combining actuarial risk premium estimation with competitive cost and margin benchmarking to produce a transparent and commercially viable insurance offer.

---

## Objectives

* Estimate **pure risk premiums per employee** for each insurance product.
* Convert pure premiums into **gross premiums** using explicit cost and margin assumptions.
* Benchmark pricing against competitors with higher operating costs.
* Produce a **single aggregated premium proposal** for the collaboration.

---

## Data Sources

* **Claims statistics (2007–2017)**

  * Product type: Workers’ Compensation, Loss of License, Leisure Accident
  * Ultimate claim cost (paid amounts + remaining case reserves)
* **Employee exposure data** (annual headcount)
* **Pricing assumptions**

  * Competitor cost ratio: **15%**
  * Competitor target margin: **5%**
  * Our cost ratio: **7%**
  * Our margin: **5%**
* **Pricing headcount**: 16,224 employees (last known period)

---

## Methodology

1. **Claims Experience Analysis**
   Claims were filtered to the 2007–2017 period and aggregated by product. Claim costs were measured on an ultimate basis to reflect expected total losses.

2. **Pure Premium Calculation**
   Product-level pure premiums were calculated by dividing total claim costs by total employee exposure (employee-years).

3. **Gross Premium and Competitive Benchmarking**
   Pure premiums were grossed up using competitor and company-specific cost and margin assumptions, enabling direct comparison of per-employee and annual premiums.

4. **Final Premium Proposal**
   Per-employee gross premiums were multiplied by the last known employee count to derive the final annual premium offer.

---

## Key Results

| Product               | Pure Premium (NOK) | Our Gross Premium (NOK) | Annual Premium (NOK) |
| --------------------- | -----------------: | ----------------------: | -------------------: |
| Leisure Accident      |                386 |                     439 |            7,116,336 |
| Loss of License       |              3,498 |                   3,975 |           64,490,400 |
| Workers’ Compensation |              1,111 |                   1,263 |           20,482,800 |
| **Total**             |                    |                         |       **92,089,536** |

---

## Competitor Comparison

|                      |        Competitor |                Our Proposal |
| -------------------- | ----------------: | --------------------------: |
| Total Annual Premium | NOK 101.3 million |        **NOK 92.1 million** |
| Customer Saving      |                   | **≈ NOK 9.2 million (≈9%)** |

The pricing advantage is driven entirely by a lower operating cost ratio while maintaining the same margin level as competitors.

---

## Key Takeaways

* Loss of License is the dominant driver of the total risk premium.
* Operational efficiency enables a materially lower customer price.
* The final proposal delivers **transparent, experience-based pricing** aligned with real-world insurance tender practices.

---

## Tools & Skills

* **Excel**: Data cleaning, PivotTables, premium calculations
* **Actuarial Pricing**: Frequency–severity analysis, pure premium estimation
* **Insurance Analytics**: Cost ratios, margin loading, competitive benchmarking
* **Business Communication**: Stakeholder-ready premium proposal

---

## Disclaimer

This project is based on anonymised and educational case data and is intended for academic and portfolio demonstration purposes only.
