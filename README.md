# Currency Converter App

This is a React-based currency converter application that allows users to convert between different currencies using up-to-date exchange rates.

## Features

- Convert between multiple currencies.
- Swap between "From" and "To" currencies with a single click.
- Responsive design.
- Handles empty input gracefully.

## Usage

1. **From**: Select the currency you want to convert from and enter the amount.
2. **To**: Select the currency you want to convert to.
3. **Swap**: Click the swap button to switch the "From" and "To" currencies.
4. **Convert**: Click the "Convert" button to see the converted amount.

## Code Structure

- `src/App.js`: Main application component.
- `src/components/InputBox.js`: Reusable input box component for entering amount and selecting currency.
- `src/hooks/useCurrencyInfo.js`: Custom hook for fetching currency exchange rates.

## Dependencies

- React
- Tailwind CSS
- `@fawazahmed0/currency-api`: For fetching exchange rates