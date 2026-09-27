# ClearEMI — Loan EMI Calculator

ClearEMI is a professional, responsive loan EMI calculator built with HTML, CSS and vanilla JavaScript. It calculates monthly EMI, total interest, total repayment, principal-to-interest breakup, and a yearly amortization schedule.

## Features

- Principal/loan amount slider.
- Annual interest-rate slider.
- Tenure slider from 1 to 30 years.
- Instant EMI calculation using the reducing-balance formula.
- Principal, interest and total payable breakdown.
- Visual principal/interest donut chart made with CSS.
- Yearly amortization schedule.
- Quick loan amount buttons.
- Dark-mode toggle.
- Responsive layout for phones and desktops.
- No database, backend, login or external API.

## Formula

`EMI = P × r × (1 + r)^n / ((1 + r)^n − 1)`

- `P` = principal amount.
- `r` = monthly interest rate, annual rate divided by 12 and 100.
- `n` = number of monthly payments.

This is a static frontend estimate. Actual lender calculations can differ because of fees, taxes, insurance, rounding, rate type, prepayments and other terms.

## Run locally

Open `index.html` in a browser. No installation is required.

## Design reference

The interface uses common calculator patterns found on major Indian banking websites: adjustable loan amount, interest-rate and tenure controls; immediate EMI, total interest and total payable results; and an amortization view. The layout and branding are original and are not a copy of any bank’s protected design or branding.

## Suggested GitHub description

> A professional vanilla JavaScript loan EMI calculator with instant repayment estimates, principal-interest visualization, yearly amortization schedule, quick loan presets, and dark mode.

## Disclaimer

For planning purposes only. Verify final rates, fees and repayment terms with the relevant lender before making a financial decision.
