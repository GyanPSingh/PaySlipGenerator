# PaySlipGenerator
When a user input’s the employee's details: first name, last name, annual salary (natural numbers) and super rate (0% - 12% inclusive), payment start date, the program should generate payslip information with name, pay period, gross income, income tax, net income and superannuation . Example calculation for a calendar month is as follows: pay period = per calendar month gross-income = annual-salary / 12 months income-tax = based on the tax table provided below net-income = gross-income - income-tax super = gross-income x super-rate Notes: All calculation results should be rounded to the whole dollar. If >= 50 cents round up to the next dollar increment, otherwise round down. The following rates for 2017-18 apply from 1 July 2017 (The tax table is from ATO: https://www.ato.gov.au/Rates/Individual-income-tax-rates) Taxable income Tax on this income 0 – $18,200 Nil $18,201 – $37,000 19c for each $1 over $18,200 $37,001 – $87,000 $3,572 plus 32.5c for each $1 over $37,000 $87,001 – $180,000 $19,822 plus 37c for each $1 over $87,000 $180,001 and over $54,232 plus 45c for each $1 over $180,000
