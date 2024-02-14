# Currency Converter

This simple HTML webpage provides a user interface for converting currency from USD to INR using the ExchangeRate-API. Users can input the amount in US dollars and click the "Convert" button to get the equivalent amount in Indian Rupees (INR).

## Usage

To use the currency converter, open the HTML file in a web browser. Enter the amount in US dollars, click the "Convert" button, and the equivalent amount in Indian Rupees will be displayed below the form.

```bash
# Example: Open the HTML file in a web browser
firefox currency_converter.html
```

## Webpage Styling

The webpage is styled with a blue background and enlarged text for better visibility. The style is defined using CSS in the `<style>` section of the HTML.

## JavaScript Functionality

The conversion logic is implemented using JavaScript. The `convert()` function is triggered when the form is submitted. It checks if the input is empty and displays an alert if necessary. If the input is valid, it fetches the latest exchange rates from "https://api.exchangerate-api.com/v4/latest/USD" and calculates the equivalent amount in Indian Rupees.

## HTML Elements

- **Input Field (`amt`)**: Users can enter the amount in US dollars.
- **Submit Button**: Clicking the "Convert" button triggers the conversion process.
- **Conversion Result (`ans`)**: The converted amount in Indian Rupees is displayed below the form.

## Notes

- The conversion uses the ExchangeRate-API, so an internet connection is required.
- The webpage is designed for simplicity and ease of use.
- Feel free to modify the code to suit your needs or integrate additional features.

If you encounter any issues or have suggestions for improvement, please let us know.
