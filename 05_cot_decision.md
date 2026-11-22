Chain-of-Thought Decision Prompt

Objective

To test whether asking AI to calculate step by step improves the accuracy of lending decisions.

Prompt

Here are 8 lending scenarios for KhataPe, a digital lender.

For each scenario, compare Option A and Option B.

Follow these steps:

1. Calculate the Net Return for Option A.
2. Calculate the Profit for Option A.
3. Calculate the Net Return for Option B.
4. Calculate the Profit for Option B.
5. Compare both profits.
6. Choose the option with higher profit.
7. If both profits are equal, choose the option with lower expected default.

Use these formulas:

Net Return = Interest Rate + Processing Fee − Expected Default − Cost of Funds.

Profit = (Net Return ÷ 100) × Loan Budget.

Show the calculations in a clear table with a brief explanation for each scenario.

Use the same 8 scenarios (S01–S08) from 02_scenarios.md.

AI Working
AI Working – Step-by-Step Calculations

Formulas

Net Return = Interest Rate + Processing Fee − Expected Default − Cost of Funds

Profit = (Net Return ÷ 100) × Loan Budget

Scenario Calculations

S01

* Option A: 24 + 2 − 10 − 10 = 6%
* A Profit = 6/100 × 50 = ₹3 crore
* Option B: 20 + 1 − 4 − 10 = 7%
* B Profit = 7/100 × 50 = ₹3.5 crore
* Decision: Option B

S02

* Option A: 18 + 2 − 4 − 10 = 6%
* A Profit = 6/100 × 40 = ₹2.4 crore
* Option B: 20 + 1 − 5 − 10 = 6%
* B Profit = 6/100 × 40 = ₹2.4 crore
* Both profits are equal. Option A has lower expected default.
* Decision: Option A

S03

* Option A: 25 + 2 − 12 − 10 = 5%
* A Profit = 5/100 × 60 = ₹3 crore
* Option B: 19 + 1 − 4 − 10 = 6%
* B Profit = 6/100 × 60 = ₹3.6 crore
* Decision: Option B

S04

* Option A: 16 + 1 − 3 − 9 = 5%
* A Profit = 5/100 × 30 = ₹1.5 crore
* Option B: 22 + 2 − 4 − 10 = 10%
* B Profit = 10/100 × 30 = ₹3 crore
* Decision: Option B

S05

* Option A: 20 + 2 − 5 − 10 = 7%
* A Profit = 7/100 × 80 = ₹5.6 crore
* Option B: 18 + 1 − 3 − 10 = 6%
* B Profit = 6/100 × 80 = ₹4.8 crore
* Decision: Option A

S06

* Option A: 28 + 2 − 11 − 10 = 9%
* A Profit = 9/100 × 25 = ₹2.25 crore
* Option B: 20 + 1 − 3 − 10 = 8%
* B Profit = 8/100 × 25 = ₹2 crore
* Decision: Option A

S07

* Option A: 19 + 2 − 4 − 10 = 7%
* A Profit = 7/100 × 70 = ₹4.9 crore
* Option B: 26 + 2 − 9 − 10 = 9%
* B Profit = 9/100 × 70 = ₹6.3 crore
* Decision: Option B

S08

* Option A: 20 + 1 − 3 − 10 = 8%
* A Profit = 8/100 × 45 = ₹3.6 crore
* Option B: 27 + 2 − 12 − 10 = 7%
* B Profit = 7/100 × 45 = ₹3.15 crore
* Decision: Option A

Final Answer

ID	A Profit (₹ crore)	B Profit (₹ crore)	Correct Choice
S01	3.00	3.50	B
S02	2.40	2.40	A
S03	3.00	3.60	B
S04	1.50	3.00	B
S05	5.60	4.80	A
S06	2.25	2.00	A
S07	4.90	6.30	B
S08	3.60	3.15	A

Conclusion: The calculations show that Option B is more profitable in S01, S03, S04 and S07. Option A is more profitable in S05, S06 and S08. In S02, both options have equal profit, so Option A is selected because it has a lower expected default.
To be added after testing the prompt.
