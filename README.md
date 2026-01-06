# Stocks

A. Time & execution rules

- Trade based on disclosure date
- Execute at:
  + next market open after disclosure (recommended)
- Ignore disclosures if:
  + already processed
  + ticker has no price data

B. Eligibility rule (your key idea)

- Execute trade only if `0 ≤ (execution_date − disclosure_date) ≤ 5 trading days`

C. Capital rules

- Starting cash (e.g. $100,000)
- Fractional shares allowed ✅
- No margin / no leverage
- If insufficient cash → scale trade down proportionally
