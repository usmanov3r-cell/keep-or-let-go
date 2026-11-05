# Keep or Let Go: early repayment calculator

**Live tool:** https://usmanov3r-cell.github.io/keep-or-let-go/

When a customer asks to repay a loan early, should the lender try to keep them, or let them go?

This calculator compares two values for one contract:

- **Keeping:** the margin the contract still earns (rate minus funding cost), minus expected loss, the cost of the offer and, for a refinancing, a credit decision.
- **Letting go:** the repaid cash lent out again at a risk-adjusted margin after a delay, minus the upfront fees refunded to the customer, plus any compensation the lender may charge.

Start from one of six example cases, move the sliders, and see why the verdict comes out as it does. It also shows the break-even offer (the most a lender can give away), and whether an offer pays across everyone it is made to, including customers who would have stayed anyway.

The companion framework is in [Early_Repayment_Signal_or_Event.pdf](Early_Repayment_Signal_or_Event.pdf).

## Scope and limits

- Built for banks and instalment lenders. Short-term and payday products work differently.
- A simplified contribution model to support thinking, not a validated pricing engine.
- Example values are illustrative, not data from any lender. Not financial or legal advice.
- Early repayment rules (EU Directive 2008/48/EC Art. 16, CJEU Lexitor C-383/18, Directive (EU) 2023/2225) and national conditions differ by market: check locally.

## How it is built

One HTML file with plain JavaScript. No data leaves the browser.

R · Contract lifecycle and retention · v1.1, November 2026
