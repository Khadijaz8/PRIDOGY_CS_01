# PRODIGY_CS_01
Ceaser Cipher<br>
<br>Author  Khadija Ijaz<br>
This HTML and JavaScript code creates a simple currency converter web application. Here's a breakdown of what each part of the code does:

### HTML (index.html)
- The HTML structure defines a form for the currency converter.
- It includes input fieldsg for entering the amount to convert and dropdown menus for selecting the currencies to convert from and to.
- The result of the conversion is displayed below the form.
- External CSS and JavaScript files are linked.

### CSS (cc.css)
- Defines the styling for various elements of the currency converter form, including input fields, dropdown menus, buttons, and the overall layout.

### JavaScript (cc.js)
- Defines constants and variables to store elements of the HTML document, such as dropdowns, buttons, and messages.
- Sets up event listeners for changes in the dropdown menus and button clicks.
- Fetches exchange rate data from an API (`https://v6.exchangerate-api.com`) based on the selected currencies.
- Updates the flag images based on the selected currencies.
- Calculates and displays the converted amount based on the exchange rate.
- Initializes the application by loading exchange rate data when the window loads.

### Additional Notes
- The currency conversion rates are obtained from the `exchangerate-api.com` API.
- Flag images representing countries are displayed alongside the currency dropdown menus.
- Default values for currency dropdowns are set to USD and PKR (United States Dollar and Pakistani Rupee).
- Styling is done using CSS to make the interface visually appealing.
