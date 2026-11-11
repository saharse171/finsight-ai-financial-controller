# FinSight AI – Test Results

## Testing Environment

- Platform: n8n Cloud
- AI Model: GPT-5 mini
- Calculation Language: JavaScript
- Test Data: Synthetic financial figures

## Test Case 1 – Budget vs. Actual Analysis

**Input Data**

| Metric | Amount |
|---|---:|
| Actual Revenue | 1,200,000 |
| Actual Operating Expenses | 850,000 |
| Budget Revenue | 1,100,000 |
| Budget Operating Expenses | 800,000 |

**Expected Calculation Results**

| Metric | Expected Result |
|---|---:|
| Actual Operating Profit | 350,000 |
| Budget Operating Profit | 300,000 |
| Actual Profit Margin | 29.17% |
| Budget Profit Margin | 27.27% |
| Revenue Variance | +100,000 |
| Revenue Variance % | +9.09% |
| Expense Variance | +50,000 |
| Expense Variance % | +6.25% |
| Operating Profit Variance | +50,000 |
| Operating Profit Variance % | +16.67% |

**Status:** Passed in the prototype test.

## Test Case 2 – Cash Flow & Liquidity Analysis

**Input Data**

| Metric | Amount |
|---|---:|
| Opening Cash | 300,000 |
| Total Cash Inflows | 400,000 |
| Total Cash Outflows | 500,000 |
| Minimum Required Cash | 150,000 |

**Expected Calculation Results**

| Metric | Expected Result |
|---|---:|
| Net Cash Flow | -100,000 |
| Closing Cash | 200,000 |
| Liquidity Surplus | 50,000 |
| Liquidity Status | Sufficient |

**Status:** Passed in the dedicated calculation tool test.

## Important Notes

- All test figures are synthetic.
- Results validate the calculation logic for the tested scenarios.
- These tests do not constitute production validation or an audit.
- Additional edge-case and integration testing is required before production deployment.
