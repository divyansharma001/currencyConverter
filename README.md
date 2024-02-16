# Currency Converter App

This is a simple currency converter web application built using React. Users can input an amount, select the source currency (From), choose the target currency (To), and then convert the amount accordingly. Additionally, users can swap the source and target currencies with a single click.

## Features

- **Currency Conversion:** Convert an input amount from one currency to another.
- **Currency Swap:** Quickly swap the source and target currencies.
- **Background Image:** The app features a dynamic background image to enhance the user interface.

## Screenshots

![Currency Converter App](./screenshots/app_screenshot.png)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/currency-converter-app.git
   ```

2. Navigate to the project directory:

   ```bash
   cd currency-converter-app
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

## Usage

1. Start the development server:

   ```bash
   npm start
   ```

2. Open your browser and go to [http://localhost:3000](http://localhost:3000) to view the app.

## How to Use

1. Enter the amount you want to convert in the "From" input box.
2. Select the source currency (From) from the dropdown list.
3. Click the "Swap" button to swap the source and target currencies.
4. The "To" input box displays the converted amount in the selected target currency.
5. Click the "Convert" button to perform the currency conversion.

## Technologies Used

- React
- JavaScript
- Tailwind CSS
- API (useCurrencyInfo hook for fetching currency exchange rates)

## Acknowledgments

- Background image by [Pexels](https://www.pexels.com/photo/259132/pexels-photo-259132/)
- Currency exchange rates provided by [useCurrencyInfo](./hooks/useCurrencyInfo.js)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
