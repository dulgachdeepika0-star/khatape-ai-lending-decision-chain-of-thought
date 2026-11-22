# khatape-ai-lending-decision-chain-of-thought
Fictional FinTech case study: comparing direct answers with chain-of-thought prompting for a digital lender's monthly loan decision. Includes synthetic scenarios, prompts, AI working, error checks and a scorecard.
Answer Key
AI Response

ID	Higher Interest Rate
S01	A
S02	B
S03	A
S04	B
S05	A
S06	A
S07	B
S08	B

Observation

AI successfully identified the option with the higher interest rate in all 8 scenarios using direct simple prompting.
ID	A Net Return (%)	A Profit (₹ crore)	B Net Return (%)	B Profit (₹ crore)	Correct Choice
S01	6	3.00	7	3.50	B
S02	6	2.40	6	2.40	A
S03	5	3.00	6	3.60	B
S04	5	1.50	10	3.00	B
S05	7	5.60	6	4.80	A
S06	9	2.25	8	2.00	A
S07	7	4.90	9	6.30	B
S08	8	3.60	7	3.15	A

Explanation

* S01: Option B gives higher profit.
* S02: Both options give equal profit. Option A has lower expected default.
* S03: Option B gives higher profit.
* S04: Option B gives higher profit.
* S05: Option A gives higher profit.
* S06: Option A gives higher profit.
* S07: Option B gives higher profit.
* S08: Option A gives higher profit.

Dataset Check

* Higher-interest option earns less profit in S01, S03 and S06.
* Equal profit occurs in S02.
* All calculations follow the given decision rules.
