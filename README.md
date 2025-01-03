This application helps calculate your net income from your gross salary, while also providing insights into tax deductions, pension contributions, and education fund contributions over time. It can project how much of your contributions will be returned to you in cases of retirement, disability, or to your heirs in the event of death.

# Website

Visit the Calc application online at https://calc.lugassy.net.

# Features

## User Interface
* Gender Selection: Choose between male or female using icons at the top.
* Children: Select or input the number of children using a range slider (0-10).
* Monthly Salary: Adjust your monthly salary in NIS using a range slider (5,880 to 100,000, default is 12,536).
* Age Range: Use a range slider (18-100) to set:
* Start Age: When you began working (default is 20).
* Retirement Age: Default is 67 for men and 65 for women.
* Death Age: Default is 81 for men and 84 for women.
* Note: Start Age must be less than Retirement and Death Age.

## Salary Slip Table
* Columns: Month, Year, Until Retirement, and values in NIS for:
* Gross Salary
* Income Tax
* National Insurance
* Health Tax
* Pension Contributions
* Education Fund Contributions
* Net Salary

### Calculations
* Income Tax: Calculated annually based on taxYearTiers and employer contributions exceeding the ceiling.
* National Insurance & Health Tax: Calculated based on btlTiers.
* Pension and Education Fund Contributions: Calculated based on specific percentages and ceilings.
* Severance Pay: Calculated based on tenure.

## Salary Slip Insights
* Tax deductions per month, year, and until retirement for children, pension contributions, eligible settlements, and additional credit points.
* Child allowance from National Insurance.
* Severance pay range based on tenure.

## Retirement Income Table
* Calculate years of work and contribution months.
* Predict future value for pensions and education funds.
* Estimate monthly pension income based on conversion factors.
* Consideration of lump sum withdrawal for severance pay.

## Disability and Death Tables
* Disability: Calculate pension and National Insurance based on disability percentage.
* Death: Calculate income from pension and National Insurance for spouses and children.

## Advanced Settings
* Options for contributions, lump sum withdrawals, disability percentage, eligible settlements, additional credit points, conversion factors, average yield, and management fees.

# Versions
## Version 1.1.0
* Save as image using canvas (not uploaded to server).
* Dark mode support.
* Improved mobile display, especially for advanced settings.
* Option to input values in addition to sliding.

## Version 1.2.0
* Add current age, pension, and/or education fund values for economic independence calculations.

# Version 1.2.1
* Employer contributions to pension above 2,351 NIS/month taxed.
* Employer contributions to severance pay above 41,500 NIS/month taxed.
* Updated list of preferred settlments.

# Getting Started
Visit https://calc.lugassy.net and explore to manage your financial projections effectively.
