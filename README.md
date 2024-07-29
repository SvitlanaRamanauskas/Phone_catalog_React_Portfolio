# Phone_catalog React+TypeScript portfolio project

This is an e-commerce application for an online gadget store with the frontend part implemented.

* [Design](https://www.figma.com/design/T5ttF21UnT6RRmCQQaZc6L/Phone-catalog-(V2)-Original?node-id=0-1&t=14HIacFOSVpZkHAA-0)
* [DEMO](https://svitlanaramanauskas.github.io/Phone_catalog_React_Portfolio/)

## Overview
The project is built using the following technologies:
- **React**: Core library for building the user interface.
- **TypeScript**: Provides static type checking for JavaScript code.
- **SCSS**: Preprocessor for writing CSS with additional features.

## Features
- **Responsive Design**: Optimized for different screen sizes and devices, responses on width 320px, 640px, 1200px, 1440px,
- **Navigation** `react-router-dom` library is used in the application to enable navigation between multiple pages, and URL-based search parameters saved when navigating
- **Favorites & Cart**: adding products to favorites or shopping cart, with total price calculation,
- **Product Filtering**: Filter products by capacity and color inside product card.
- **Sorting**: Sort products based on criterias: year, price, alphabeticaly.
- **Search**: Filter products using query parameters.
- **Pagination**: Navigate through large lists of products, opportunity to choose number of items per page, and number of pages depends on this.
- **Sticky Header**: Keeps the header visible as you scroll.
- **Scroll to Top Button**: Easily return to the top of the page.
- **Loader**: Indicates loading status for a better user experience.

## Running the Project Locally
To run this project locally, follow these steps:

- Clone the Repository:

```
git clone https://github.com/SvitlanaRamanauskas/Phone_catalog_React_Portfolio.git
cd Phone_catalog_React_Portfolio
```

- Install Dependencies:

Install dependences using npm (Node Package Manager). Ensure you have Node.js installed on your machine. This project uses Node v14.

```npm install react-router-dom```

- Run the Project:

Start the development server with live reloading:

```npm start```

Alternatively, you can use any other local server setup you prefer, such as Live Server for VS Code.

- Open the Project in Your Browser:

Visit http://localhost:5000 or the port your server specifies to see the landing page in action.
