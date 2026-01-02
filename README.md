A lightweight, browser-based tool designed to perform instant currency conversions. The application connects to an open-source financial API to retrieve the latest exchange rates, ensuring accuracy for the user. It handles the core logic of mapping base currencies to target currencies and dynamically updating the DOM with the calculated results.

Key Features:

Live Data Fetching: Utilizes the fetch() API to pull real-time exchange rates from api.frankfurter.app.

Asynchronous Logic: Implements async/await syntax for smooth, non-blocking API requests.

User Validation: Includes logic to prevent invalid inputs (e.g., negative numbers or empty fields).

Supported Currencies: Currently configured for USD, INR, EUR, and JPY.

Tech Stack:

HTML5

CSS

JavaScript (Fetch API, JSON parsing)
