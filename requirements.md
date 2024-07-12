### Buyer and Seller Calculator WordPress Plugin Requirements

#### Overview:
The plugin will calculate various costs for buyers and sellers in the USA based on taxes and other costs specific to each location. Users will only need to input prices, and the tax information will be applied automatically using an API. The calculator will be presented in two tabs: one for the Buyer Calculator and one for the Seller Calculator.

#### Features:

1. **Tabs for Buyer and Seller Calculators:**
   - The page will have two tabs: one for the Buyer Calculator and one for the Seller Calculator.

2. **Location-Based Tax Calculation:**
   - The plugin will use an API to fetch tax rates for each state and city in the USA.

3. **Dropdown Selection:**
   - Two dropdown menus: one for selecting a state and another for selecting a city within the chosen state.
   - The dropdowns will be searchable.

#### Seller Calculator Fields:
- **Purchase Price:** Input field for the purchase price of the property.
- **Total Commission %:** Input field for the total commission percentage.
- **Survey Cost:** Input field for the survey cost.
- **State/County Transfer Tax:** Input field for the state or county transfer tax.
- **City Transfer Tax:** Input field for the city transfer tax.
- **Prior Year Full Tax Bill:** Input field for the prior year's full tax bill.
- **Attorney Fee:** Input field for the attorney fee.
- **Property Taxes %:** Input field for the property tax percentage.
- **Mortgage Payoff Amount:** Input field for the mortgage payoff amount.
- **Miscellaneous Costs:** Input field for any miscellaneous costs.
- **Closing Cost Credits:** Input field for closing cost credits.
- **Compute Button:** Button to compute the total costs.

#### Buyer Calculator Fields:
- **Home Price:** Input field for the home price.
- **Down Payment %:** Input field for the down payment percentage.
- **Interest Rate %:** Input field for the interest rate percentage.
- **Loan Term (years):** Input field for the loan term in years.
- **Hazard Insurance:** Input field for the hazard insurance cost.
- **Property Taxes %:** Input field for the property tax percentage.
- **City Transfer Tax:** Input field for the city transfer tax.
- **Closing Date:** Input field for the closing date.
- **Compute Button:** Button to compute the total costs.

#### Requirements:

1. **API Integration:**
   - Identify and integrate an API that provides tax rates for every location in the USA.

2. **User Interface:**
   - **State Dropdown:** Searchable dropdown to select a state.
   - **City Dropdown:** Searchable dropdown to select a city, populated based on the selected state.
   - **Form Fields:** Various input fields for user data entry.
   - **Tabs:** Two tabs for switching between buyer and seller calculators.

3. **Technologies:**
   - **JavaScript and jQuery:** For dropdown functionality, form validation, and API integration.
   - **HTML:** For structuring the form and tabs.
   - **CSS:** For styling the form and tabs.

4. **Validation:**
   - Ensure all input fields are validated to prevent incorrect data entry.
   - Provide error messages for invalid inputs.

5. **Result Display:**
   - Display the calculated results in a user-friendly manner.
   - Include options to view detailed breakdowns of the calculations.

#### Reference Files:
- **styles.css:** Contains styles for form layout, button styling, and overall design consistency.
- **scripts.js:** Contains functions for input validation, currency formatting, and calculation logic for both seller and buyer calculators.

#### Next Steps:
1. **Research and Identify an API** that provides tax rates for all locations in the USA.
2. **Design the User Interface** with the necessary fields and dropdowns.
3. **Implement the Dropdown Functionality** using jQuery to ensure cities are dynamically populated based on the selected state.
4. **Create the Tab Structure** for switching between buyer and seller calculators.
5. **Integrate the API** for fetching and applying tax rates based on user-selected locations.

Please review these requirements and let me know if there are any changes or additions needed. Once you confirm, I'll proceed with the next steps.
