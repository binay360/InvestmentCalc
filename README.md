Investment Calculator

Overview:

A simple Angular application that calculates the growth of investments over time. Users can input initial investment, duration, expected return rate, and annual investment to get a detailed yearly breakdown of investment performance.

Features:

Calculate Investment Growth: Compute annual growth based on user inputs.
Yearly Breakdown: Detailed results for each year, including interest earned and total investment value.
Clear Results: Option to reset the results data.

How It Works:

The InvestmentService class handles the calculations:

calculatedInvestmentResults(data: InvestmentInput): Computes the annual growth of the investment.
cleanTable(value: boolean): Resets the results data if value is true.
