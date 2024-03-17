## React Currency Converter App

This is a React application that allows users to convert currency between different currencies.

### Screenshots
![Home Page](Image link)


### Features

* Convert between various currencies using exchange rates.
* Swap between "From" and "To" currencies with a single click.
* User-friendly interface with clear labels and input fields.

### Installation

1. Clone this repository.
2. Install dependencies:

```bash
npm install
```

### Usage

1. Start the development server:

```bash
npm start
```

2. Open http://localhost:3000 in your browser.

### Explanation

This application utilizes React components and hooks to achieve its functionality. Here's a breakdown of the key aspects:

* **useState Hook:** Manages the state of various elements like the amount, currencies, and converted amount.
* **useCurrencyInfo Hook:** Fetches and stores exchange rate data for different currencies.
* **Inputbox Component:** A reusable component for handling currency selection and amount input.
* **convert Function:** Calculates the converted amount based on the selected currencies and exchange rate.
* **swap Function:** Swaps the "From" and "To" currencies and their corresponding values.

### Contributing

We welcome contributions to this project! Feel free to fork the repository and submit pull requests with your improvements.

### License

This project is licensed under the MIT License. See the LICENSE file for details.
