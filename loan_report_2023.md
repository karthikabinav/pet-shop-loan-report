# Pet Shop Loan Balance Report 2023

## Loan Terms
- **Principal**: $45,000
- **Disbursed**: March 2023 (3rd month)
- **Monthly Interest Rate**: 5.12% (compounded monthly)
- **Weekly Payment**: 12% of weekly profit
- **Profit Source**: `/data/Pet Care 2023 Weekly Financials.csv`

## Weekly Profits Extracted
**Weeks 1-52 total profit 2023**: $342,870  
**12% yearly payment if paying all year**: $41,144.40

**Relevant period (March–Dec)**:  
Profit weeks 10-52 = $285,115  
Payments 12% = $34,213.80

## Scenario A: Conservative (start at Week 10 = 6/3/2023, interest applied AFTER monthly payments)

| Month | Weekly Profits Total | 12% Payment | Balance Before Interest | Balance After 5.12% Interest |
|---|---|---|---|---|
| March | $26,709 | $3,205.08 | $41,794.92 | $43,934.82 |
| April | $26,023 | $3,122.76 | $40,812.06 | $42,901.64 |
| May | $31,946 | $3,833.52 | $39,068.12 | $41,068.40 |
| June | $26,661 | $3,199.32 | $37,869.08 | $39,807.98 |
| July | $33,305 | $3,996.60 | $35,811.38 | $37,644.92 |
| August | $25,925 | $3,111.00 | $34,533.92 | $36,302.06 |
| September | $27,240 | $3,268.80 | $33,033.26 | $34,724.56 |
| October | $32,626 | $3,915.12 | $30,809.44 | $32,386.89 |
| November | $27,456 | $3,294.72 | $29,092.17 | $30,581.69 |
| December | $27,224 | $3,266.88 | $27,314.81 | $28,713.33 |

**Estimated remaining balance end of 2023: $28,713.33**

---

## Scenario B: Include Week 9 (27/2-5/3, partial March)

| Month | Weekly Profits Total | 12% Payment | Balance After Payment | Balance After Interest |
|---|---|---|---|---|
| March | $33,049 | $3,965.88 | $41,034.12 | $43,135.07 |
| April | $26,023 | $3,122.76 | $40,012.31 | $42,060.94 |
| May | $31,946 | $3,833.52 | $38,227.42 | $40,184.66 |
| June | $26,661 | $3,199.32 | $36,985.34 | $38,878.99 |
| July | $33,305 | $3,996.60 | $34,882.39 | $36,668.37 |
| August | $25,925 | $3,111.00 | $33,557.37 | $35,275.51 |
| September | $27,240 | $3,268.80 | $32,006.71 | $33,645.45 |
| October | $32,626 | $3,915.12 | $29,730.33 | $31,252.52 |
| November | $27,456 | $3,294.72 | $27,957.80 | $29,389.24 |
| December | $27,224 | $3,266.88 | $26,122.36 | $27,459.83 |

**Remaining end 2023 (incl week9): $27,459.83**

---

## Scenario C: Interest FIRST, then subtract payments (same weeks 10-52)

| Month | Balance after interest then payment |
|---|---|
| Mar | $44,098.92 |
| Apr | $43,234.02 |
| May | $41,614.09 |
| Jun | $40,545.41 |
| Jul | $38,624.73 |
| Aug | $37,491.32 |
| Sep | $36,142.07 |
| Oct | $34,077.43 |
| Nov | $32,527.47 |
| Dec | $30,926.00 |

**Remaining: $30,926.00**

---

## Scenario D: Simple Interest (no compounding, just 5.12% x 10 months on principal)

Total interest = 45000 * 0.0512 * 10 = $23,040  
Balance without payments = $68,040  
Minus payments $34,213.80 = **$33,826.20**

---

## Summary Answer
Depending on exact timing assumption:

- **Most likely model (payments first, then monthly compounding, start Week 10)** → **$28,713.33 remaining end of 2023**
- If you count the partial week at end of Feb/start Mar (Week 9) → **$27,459.83**
- If interest is applied before each month's payments → **$30,926.00**
- Simple non-compounding interest → **$33,826.20**
- If **no payments were made**, after 10 months compounding you would owe **$74,142.30**

You paid a total of **$34,213.80** over 43 weeks (Mar–Dec). Without interest you'd still owe **$10,786.20**. Interest added about **$17,927 more** to the debt, bringing owed to ~$28.7k.

*Weekly profit March-Dec average ≈ $6,632 per week; average weekly payment ≈ $796.*
