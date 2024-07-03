# rn-assignment6-11083414

### STUDENT ID: 11083414

### Fifth React Native Project

## Here's a brief overview of the project

## Project Description:

### This is a simple React Native project that displays a home screen and a cart screen.

#### The home screen displays a list of products in the shop and the cart screen displays a list of products in the cart. The user can add products to the cart by clicking on the "Add to Cart button" and can view what is in the cart by clicking on "Go to Cart".

## The project entails:
### 1. A home screen that displays a list of products in the shop.

### 2. A cart screen that displays a list of products in the cart.

### 3. A button that allows the user to add products to the cart.

### 4. A button that allows the user to view the cart.

## The components of the project includes:

#### View: is a container element.

#### Text: a component used to display text

#### Scrollview: a view component used for scrolling.

#### TextInput: a component used for inputing text into the app via a keyboard

#### Stylesheet: a component used for styling elements.

#### Button: creates a button

#### Image: Displays images

#### FlatList: rendering flatlists(a single dimension of data)

#### Navigation: navigate between screens(stack navigator)

#### Scrollview: scroll through a component.

## Explaination of Design Choices
#### Navigation is handled by React Navigation to switch between screens.

#### State management is handled using React's useState and useEffect hooks.

#### Data storage is managed using AsyncStorage to persist cart data.

#### AsyncStorage is used to persist the cart data. This ensures that the cart contents are saved even if the app is closed. The loadCart function retrieves the cart data from AsyncStorage when the component mounts, and the addToCart function updates the cart data in AsyncStorage whenever an item is added to the cart.

#### loadCart: Retrieves the cart data from AsyncStorage and updates the state.

#### addToCart: Adds a product to the cart, updates the state, and saves the updated cart to AsyncStorage.

#### clearCart: Clears the cart data from both the state and AsyncStorage.

#### Component-based architecture ensures modularity and reusability.


## Application Screenshots

![alt text](<MyApp/assets/Screenshot 1.jpeg>)
![alt text](<MyApp/assets/Screenshot 2.jpeg>)
![alt text](<MyApp/assets/Screenshot 3.jpeg>)
![alt text](<MyApp/assets/Screenshot 4.jpeg>)
![alt text](<MyApp/assets/Screenshot 5.jpeg>)
![alt text](<MyApp/assets/Screenshot 6.jpeg>)