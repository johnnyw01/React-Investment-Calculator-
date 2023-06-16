# React-Investment-Calculator-
This is a React application that calculates the growth of an investment over a specified duration based on user input.

## Installation
1. Clone the repository: `git clone https://github.com/example/investment-calculator.git`
2. Navigate to the project directory: `cd investment-calculator`
3. Install the dependencies: `npm install`

## Usage
1. Start the development server: `npm start`
2. Open your browser and navigate to `http://localhost:3000`

## Description
The application consists of the following components:

### Header
The `Header` component displays the logo and title of the investment calculator.

### UserInput
The `UserInput` component allows the user to input their current savings, yearly contribution, expected interest rate, and investment duration. It provides a form with the following fields:

* Current Savings: The current amount of savings in dollars.
* Yearly Savings: The amount of money the user plans to contribute annually.
* Expected Interest: The expected interest rate of the investment per year.
* Investment Duration: The number of years the investment will be made for.

The user can enter the values in the input fields and submit the form to calculate the investment results. The form also includes a "Reset" button to clear the input fields.

### ResultsTable
The `ResultsTable` component displays a table of the calculated investment results based on the user's input. It shows the following information for each year:

* Year: The year number.
* Total Savings: The total savings at the end of the year.
* Interest (Year): The interest earned during the year.
* Total Interest: The total interest earned since the start of the investment.
* Invested Capital: The total capital invested since the start of the investment.

### App
The `App` component is the main component that combines the Header, UserInput, and ResultsTable components. It manages the state of the user input and handles the calculation of investment results. If no investment calculation has been performed yet, it displays a message indicating that no investment has been calculated. Otherwise, it renders the ResultsTable component with the calculated data.

## Dependencies
The application uses the following dependencies:

* React: A JavaScript library for building user interfaces.
* react-dom: Provides DOM-specific methods for React.
* react-scripts: Configuration and scripts for Create React App.
  These dependencies are automatically installed when you run `npm install`.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.