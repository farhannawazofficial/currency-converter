# Currency Converter

## Introduction

The Currency Converter is a simple and user-friendly web application designed to convert an amount from one currency to another based on current exchange rates. This tool can be especially useful for travelers, businesses, and anyone dealing with multiple currencies.

## Features

- **Real-time Exchange Rates**: Fetches the latest exchange rates to ensure accurate conversions.
- **Wide Range of Currencies**: Supports conversion between a large number of currencies worldwide.
- **User-Friendly Interface**: Easy to use with a clean and intuitive design.
- **Offline Mode**: Allows for conversions using the last fetched rates when offline.

## Installation

### Prerequisites

- Node.js
- npm (Node Package Manager)

### Steps

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/currency-converter.git
    ```

2. Navigate to the project directory:
    ```bash
    cd currency-converter
    ```

3. Install the required dependencies:
    ```bash
    npm install
    ```

## Usage

1. Run the application:
    ```bash
    npm start
    ```

2. Open your web browser and navigate to `http://localhost:3000`.

3. Follow the on-screen instructions to select the currencies and enter the amount for conversion.

## Example

1. Start the application:
    ```bash
    npm start
    ```

2. In your web browser, navigate to:
    ```
    http://localhost:3000
    ```

3. Use the interface to select the source and target currencies, enter the amount, and click "Convert."

## Configuration

You can configure the application by editing the `config.json` file:

```json
{
    "defaultSourceCurrency": "USD",
    "defaultTargetCurrency": "EUR",
    "apiKey": "your_api_key_here"
}




This `README.md` file provides a clear and concise guide for users to understand, install, and use the Currency Converter application built with JavaScript.

