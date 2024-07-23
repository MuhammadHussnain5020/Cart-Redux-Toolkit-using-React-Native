# Cart-Redux-Toolkit-using-React-Native

```markdown
# Cart using Redux Toolkit

A React Native application that demonstrates how to manage a shopping cart using Redux Toolkit. This project includes features to add items to the cart, remove items from the cart, and view the cart with item details.

## Features

- **Product List**: Displays a list of products with options to add or remove them from the cart.
- **Cart**: Shows items in the cart with an option to remove each item.
- **State Management**: Utilizes Redux Toolkit for state management of the cart.

## Technologies Used

- **React Native**: For building the mobile application.
- **Redux Toolkit**: For state management.
- **React Navigation**: For navigating between different screens.

## Project Structure

- **`src/`**: Contains all the source code.
  - **`redux/`**: Contains Redux-related code.
    - **`cartSlice.js`**: Defines Redux slice for managing cart state.
  - **`components/`**: Contains React components.
    - **`ProductList.js`**: Component for listing products with add/remove functionality.
    - **`Cart.js`**: Component for displaying items in the cart with remove functionality.
  - **`App.js`**: Main application entry point.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/cart-using-redux-toolkit.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd cart-using-redux-toolkit
   ```

3. **Install dependencies:**

   ```bash
   npm install
   ```

4. **Run the application:**

   ```bash
   npm start
   ```

   Follow the instructions to open the app in a simulator or on a device.

## Usage

- **Product List**: Navigate to the product list to view available products. You can add or remove items from the cart.
- **Cart**: Navigate to the cart to view items added to the cart. You can also remove items from the cart.

## Redux Toolkit Setup

The Redux store and cart slice are configured as follows:

- **`redux/cartSlice.js`**: Contains actions and reducers for managing cart state, including adding and removing items.
- **`App.js`**: Configures the Redux store and provides it to the application using the `Provider` component.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or suggestions, please contact:

- Name: Muhammad Hussnain
- Email: muhammadhusnain5020@gmail.com
