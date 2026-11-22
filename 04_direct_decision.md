Direct Decision Prompt

Objective

To test whether AI can directly identify which loan option gives higher profit.

Prompt

Here are 8 lending scenarios for KhataPe, a digital lender.

For each scenario, calculate which option (A or B) makes more profit using the following formula:

Net Return = Interest Rate + Processing Fee − Expected Default − Cost of Funds

Profit = (Net Return ÷ 100) × Loan Budget

Choose the option with higher profit. If both profits are equal, choose the option with lower expected default.

Give only the final choices in a table with two columns:

ID | More Profitable Option

Use the same 8 scenarios (S01–S08) from 02_scenarios.md.

AI Response
AI Response

ID	More Profitable Option
S01	B
S02	A
S03	B
S04	B
S05	A
S06	A
S07	B
S08	A

Observation

The AI correctly identified the more profitable option in all 8 scenarios. It also correctly handled the tie in S02 by selecting Option A because it has a lower expected default.

Correct answers: 8/8
To be added after testing the prompt.
