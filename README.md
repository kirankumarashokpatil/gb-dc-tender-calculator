# GB Dynamic Containment (DC) Tender Calculator

A free, interactive tool designed for analysts and traders operating in the Great Britain (GB) energy market.

This single-page application simulates the **National Grid ESO (NG-ESO)** auction process for frequency response products. It breaks down the 24-hour day into the 6 standard **EFA (Electricity Forward Agreement)** blocks and allows users to test various bidding strategies against embedded historical clearing data.

## 🎯 Why This Tool Exists

Bidding into frequency response markets requires precision. If you bid too aggressively during off-peak windows (like EFA 2), you risk rejection and yield zero revenue for 4 hours. 

This tool lets you instantly visualize the outcome of "Pay-As-Clear" mechanics. If your bid is equal to or lower than the NG-ESO clearing price, you are awarded the contract at the full clearing price. It automatically calculates your Daily, Annual, and Annualised-per-MW revenue yields.

## 🚀 Usage

1. Open `index.html` in your browser.
2. Enter your asset's total MW capacity.
3. Adjust your bids (£/MW/h) for EFA blocks 1 through 6.
4. Watch the status instantly switch between `CLEARED` and `REJECTED` and monitor your annualized revenue run-rate.

---
*Authored by Kirankumar Patil*
