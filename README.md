# Currency Converter with Custom Hooks

This project demonstrates the usage of custom hooks in React.js to fetch currency information from an API and convert currency amounts dynamically.

## Purpose of Custom Hooks

Custom hooks in React.js provide a way to reuse stateful logic across components. They allow developers to extract common functionalities into reusable functions, promoting code organization and reducing repetition.

### How Custom Hooks Work

In this project, the `useCurrencyInfo` hook is created to fetch currency information based on the selected currency. It utilizes React's `useState` and `useEffect` hooks to manage state and perform side effects respectively.

The `useCurrencyInfo` hook fetches currency data from an external API and returns the currency information based on the provided currency code. This information is then used in the main component to populate currency options and perform conversions.

## Project Structure

### Custom Hook

The `useCurrencyInfo` custom hook is defined in the `hooks` directory. It fetches currency information using the provided currency code and returns the data.

### Components

- `InputBox`: This component represents an input box for entering currency amounts and selecting currency types.

### Main Component

The `App` component in `app.jsx` utilizes the custom hook `useCurrencyInfo` to fetch currency information and perform currency conversions. It provides input fields for entering currency amounts and selecting currency types, along with a button to trigger the conversion.

## Usage

To use the currency converter:

1. Clone the repository.
2. Install dependencies using `npm install`.
3. Start the development server with `npm start`.
4. Open the application in your browser.

## Dependencies

This project utilizes React.js for building the user interface and managing state. Additionally, it uses the `@fawazahmed0/currency-api` library for fetching currency data.

## Credits

- Currency data provided by [Fawaz Ahmed](https://github.com/fawazahmed0/currency-api).
- Built with [React.js](https://reactjs.org/).

