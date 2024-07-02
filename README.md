# Redux Cart Management Example

This is a simple example of using Redux to manage the state of a shopping cart in a React application.

## Introduction

This project demonstrates a basic implementation of Redux for managing the state of a shopping cart in a React application. It includes functionality for adding and removing items from the cart, as well as calculating the total amount.

##State Management Explained

- Store: 
The Redux store is configured in store.js. It combines reducers and creates the store used by the React application.

- Reducer: 
The cart reducer in cartReducer.js handles the cart state, including adding and removing items and updating the total amount.

- Actions: 
Action creators in actions.js define the actions for adding and removing items from the cart.

- Connecting to React: 
The Redux store is connected to the React app in index.js using the Provider component. The Cart component uses useSelector to access state and useDispatch to dispatch actions.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Kahmori/ReduxStore.git
