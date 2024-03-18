# Currency Converter with Custom Hooks

This project demonstrates the use of custom hooks in React.js to manage stateful logic and encapsulate reusable functionalities, focusing on fetching currency information from an API and dynamically converting currency amounts.

## Introduction to Custom Hooks

Custom hooks are a powerful feature introduced in React.js that allows developers to extract reusable stateful logic from components into reusable functions. By encapsulating common functionalities in custom hooks, developers can improve code organization, promote reusability, and simplify the management of complex stateful behaviors across multiple components.

### Core Concepts of Custom Hooks

1. **Reusability**: Custom hooks enable developers to encapsulate and reuse stateful logic across multiple components without duplicating code. This promotes code reusability and reduces redundancy in React.js applications.

2. **Separation of Concerns**: By extracting stateful logic into custom hooks, developers can separate concerns within components, making them more focused on presentation and behavior. This separation enhances code readability and maintainability.

3. **Composition**: Custom hooks can be composed together to create complex stateful behaviors from simpler hooks. This compositional approach allows developers to build sophisticated functionalities by combining smaller, reusable hooks.

4. **Hook Naming Convention**: Custom hooks should be prefixed with `use` to indicate that they are hooks and follow the same rules as built-in React hooks. This naming convention helps developers identify and differentiate custom hooks from regular functions.

## Purpose of Custom Hooks in the Currency Converter Project

The purpose of custom hooks in the currency converter project is to encapsulate the logic for fetching currency information from an external API and managing the state associated with currency conversion. By abstracting this logic into a custom hook, developers can reuse it across different components within the project.

### How Custom Hooks Work in the Project

In this project, the `useCurrencyInfo` custom hook is responsible for fetching currency information based on the selected currency code and managing the associated state. It utilizes React's built-in `useState` and `useEffect` hooks to handle state and perform side effects respectively.

The `useCurrencyInfo` hook fetches currency data from an external API using the provided currency code and returns the fetched data. This data is then used in the main component (`App`) to populate currency options and perform currency conversions based on user input.

## Project Structure

### Custom Hook

The `useCurrencyInfo` custom hook is defined in the `hooks` directory. It encapsulates the logic for fetching currency information and managing the associated state.

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

