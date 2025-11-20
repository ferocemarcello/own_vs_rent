# Buy vs. Rent Calculator

This project is a comprehensive "Buy vs. Rent" calculator that helps users determine the financial implications of buying a home versus renting over a specified period. It provides a detailed, year-by-year comparison of net worth, including investments and expenses, to help users make an informed decision.

The live version of this calculator is available at: [https://ferocemarcello.github.io/own_vs_rent/](https://ferocemarcello.github.io/own_vs_rent/)

## How to Use

1.  **Open the `index.html` file in your web browser, or visit the live link above.**
2.  **Adjust the input fields** in the "Purchase Inputs", "Rental Inputs", and "Investment Inputs" sections to match your financial situation and market conditions.
3.  **Click the "Calculate" button** to see the results.

The calculator will display:
*   A summary of the owner's and renter's net worth after the analysis period.
*   A line chart comparing the growth of net worth over time for both scenarios.
*   A line chart comparing the cumulative expenses (sunk costs) for both scenarios.
*   A detailed, year-by-year breakdown of the financials for both the owner and the renter.
*   A summary of the total sunk costs for both scenarios.

## How It Works

The calculator simulates the financial outcome of buying a home versus renting over a set period. It compares the final net worth of an **Owner** against a **Renter** by tracking two main assets for each:

*   **Property Equity (Owner only):** The value of the home, which appreciates (or depreciates) over time.
*   **Investment Portfolio:** A separate investment account (like stocks or bonds) that both the Owner and Renter contribute to and which grows at a specified yearly rate.

### Final Calculation (End of Period)

At the end of the "Analysis Period," the calculator simulates a final liquidation to compare net worth:

1.  The **Owner** "sells" the house. The **Selling Costs** are tracked as an expense but **NOT deducted** from the final Net Worth.
2.  Both the **Owner** and **Renter** "liquidate" their investment portfolios.
3.  The **Capital Gains Tax** is calculated only on the "growth" (gains) of their portfolios.
4.  **Final Net Worth = (Full Home Value) + (Net Portfolio Value)**

### One-Time Expenses

One-time expenses for the owner—specifically **Initial Buying Costs**, **End of Term (Refinancing) Costs**, and **Final Selling Costs**—are **NOT** deducted from the Owner's Net Worth or Investment Portfolio in this simulation. These costs are still tracked in the "Total Expenses" graph and the "Cost Summary" panel to show the true cost of ownership, but they do not negatively impact the final asset value.

## Technologies Used

*   **HTML:** The structure of the web page.
*   **[Tailwind CSS](https://tailwindcss.com/):** For styling the user interface.
*   **[Chart.js](https://www.chartjs.org/):** For creating the comparison charts.
*   **JavaScript:** For the calculation logic and interactivity.

## Author

**Feroce Marcello**

*   [LinkedIn](https://www.linkedin.com/in/ferocemarcello/)
*   [GitHub](https://github.com/ferocemarcello)
*   [Stack Overflow](https://stackoverflow.com/users/10589694/marcello-feroce)
*   [Email](mailto:ferocemarcello@gmail.com)
*   [PayPal](https://www.paypal.com/paypalme/ferocemarcelloNorway)
