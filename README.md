# Fintech Unit Economics & Growth ROI Model (Excel)

**Which marketing channels pay back fastest, and what does that mean for next year's plan?**

A driver-based FP&A model for **PayNest**, a fictional fintech. Every assumption sits on one Inputs tab, so changing spend, churn or margin flows through all 355 formulas, from channel unit economics to a 12-month forecast, a budget-vs-actual close and a leadership summary.

*Hafsah Alhassan · Built in Microsoft Excel · Sample data only. No real company data is used.*

📊 [Download the model (Excel)](PayNest_Unit_Economics_Model.xlsx)

---

## Key findings (sample data)
- **Partnerships is the strongest channel:** LTV:CAC of 10.0x with a 3.3-month payback.
- **Social Ads is the weakest:** LTV:CAC of 4.0x and an 8.3-month payback. It is the first channel to fall below the 3.0x threshold if monthly churn rises above 4%.
- **Blended:** CAC of $153, LTV of $1,000, LTV:CAC of 6.5x, payback of 5.1 months.
- **Forecast:** the business reaches 14,526 customers by December 2027 and turns operating profit positive in May 2027.
- **Q1 close:** new customers came in about 4% below plan while marketing spend stayed on budget, so each customer cost more and operating profit missed plan by about 10%.

**Recommendation:** shift budget toward Partnerships and watch Social Ads closely, because churn is the biggest risk to channel returns.

## How the model is built
| Tab | What it does |
|---|---|
| **README** | Purpose, colour legend and how the tabs connect |
| **Inputs** | Channel spend and customers acquired, revenue per customer, gross margin, churn, fixed costs, growth rates |
| **Unit Economics** | CAC, gross profit per customer, LTV, LTV:CAC and payback by channel, with a recommendation flag |
| **Forecast** | 12-month customer, revenue, marketing spend and operating profit forecast |
| **Budget vs Actual** | Monthly Q1 budget vs sample actuals, variances, status flags and written commentary |
| **Sensitivity** | LTV:CAC at monthly churn from 2% to 6% |
| **Summary** | One-page leadership view with key metrics, a formula-driven recommendation and charts |

## Key formulas
- **CAC** = channel spend ÷ new customers acquired
- **LTV** = (revenue per customer × gross margin) ÷ monthly churn
- **LTV:CAC** = LTV ÷ CAC (above 3.0x is generally considered healthy)
- **Payback (months)** = CAC ÷ monthly gross profit per customer
- **New customers in the forecast** = forecast channel spend ÷ that channel's CAC
- **Variance** = actual − budget, flagged when larger than 5%

## Screenshots
<p>
  <img src="images/unit_economics.png" width="49%" alt="Unit economics by channel with LTV:CAC chart">
  <img src="images/summary.png" width="49%" alt="Leadership summary with recommendation and payback chart">
</p>

## Model conventions
Blue text = inputs you can change · Black = formulas · Green = links to other tabs · Yellow fill = key assumptions.

## Try it
Open the Inputs tab and raise monthly churn from 3% to 5%. LTV, payback, the 12-month profit and the written recommendation all update automatically.
