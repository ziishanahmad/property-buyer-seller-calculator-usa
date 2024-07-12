### Requirements for the Buyer and Seller Calculator Plugin



#### Features:

1. **Tabs for Buyer and Seller Calculators:**
   - Two tabs on the page: one for the Buyer Calculator and one for the Seller Calculator.

2. **Location-Based Tax Calculation:**
   - Integrate an API to fetch real estate tax rates for each state and city in the USA.

3. **Dropdown Selection:**
   - Two searchable dropdown menus: one for selecting a state and another for selecting a city within the chosen state.

4. **Buyer and Seller Calculator Fields:**
   - **Seller Calculator:**
     - Purchase Price
     - Total Commission %
     - Survey Cost
     - State/County Transfer Tax
     - City Transfer Tax
     - Prior Year Full Tax Bill
     - Attorney Fee
     - Property Taxes %
     - Mortgage Payoff Amount
     - Miscellaneous Costs
     - Closing Cost Credits
     - Compute Button
   - **Buyer Calculator:**
     - Home Price
     - Down Payment %
     - Interest Rate %
     - Loan Term (years)
     - Hazard Insurance
     - Property Taxes %
     - City Transfer Tax
     - Closing Date
     - Compute Button

5. **Proration Calculations:**
   - Calculate proration based on the time the seller lived in the property before the sale.
   - Use a standard proration rate (e.g., 105% or 110%) depending on the location to account for tax increases.

6. **Validation:**
   - Ensure all input fields are validated to prevent incorrect data entry.
   - Provide error messages for invalid inputs.

7. **Result Display:**
   - Display the calculated results in a user-friendly manner.
   - Include options to view detailed breakdowns of the calculations.

#### API Integration:

Given the need for comprehensive real estate tax data, **Avalara API** is recommended due to its robust support for various types of tax calculations, including real estate transaction taxes.

### Next Steps:

1. **Sign Up for Avalara**: Create an account on Avalara's website and obtain your API key.
2. **Review Documentation**: Familiarize yourself with Avalara’s API documentation to understand how to make requests and handle responses for property-related taxes.
3. **Develop API Integration**: Write the necessary code to integrate the Avalara API into your WordPress plugin.
4. **Implement Proration Calculations**: Incorporate proration logic based on the example provided.
5. **Test the Integration**: Thoroughly test the integration to ensure accuracy and reliability in tax calculations.

Please confirm if these requirements are accurate and if you'd like to proceed with integrating the Avalara API.
