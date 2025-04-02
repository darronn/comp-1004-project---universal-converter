# comp-1004-project---universal-converter
Universal Converter Tool

Overview
The Universal Converter Tool is a web-based application that allows users to perform three types of conversions:
Number Base Conversion – Converts numbers between Binary, Decimal, Hexadecimal, and Octal.
Unit Conversion – Converts common units like length (meters, kilometers, miles) and weight (kilograms, pounds, grams).
Currency Conversion – Converts currency values using real-time exchange rates from Exchangerate-API.
Batch Currency Conversion – Processes multiple currency conversion requests from a JSON file.

Features

User-Friendly Interface: Simple and intuitive design for easy conversion.
Real-Time Currency Exchange Rates: Uses an external API to fetch live exchange rates.
Batch Processing: Supports bulk currency conversions through a JSON file upload.
Downloadable Results: Users can save their conversion history in a JSON file.

Installation & Usage

1. Running Locally
Simply open the univeralconverter.html file to use this tool
2. Using the Currency Converter
Select the currencies you want to convert between.
Enter the amount to convert.
Click the "Convert" button to get the real-time conversion.
3. Using Batch Processing
Upload a JSON file containing an array of conversion requests in the following format:

[
  {"amount": 100, "from": "USD", "to": "EUR"},
  {"amount": 50, "from": "GBP", "to": "USD"}
]

Click "Process Batch" to execute the conversions.
Download the results as a JSON file for reference.

Technologies Used
HTML, CSS, JavaScript – For frontend development.
Exchangerate-API – For real-time currency exchange rates.
Future Improvements
Implement additional unit conversions.
Add error handling for API failures.
Enhance the UI with better styling and animations.
