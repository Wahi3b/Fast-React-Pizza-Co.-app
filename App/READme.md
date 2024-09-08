Welcome to the repository for the Fast React Pizza Co. app! This React application showcases our diverse menu of pizzas, allowing users to view details about our offerings, including ingredients and prices. The app dynamically renders pizza information and displays different content based on whether the pizzas are sold out or not.

Features
Dynamic Pizza Listing: Utilizes React's component-based structure to dynamically generate a list of pizza offerings based on provided data.
Conditional Rendering: Implements logic to handle sold-out items and operation hours, enhancing the user interface and user experience.
React Component Architecture: Structures the application into reusable components such as Header, Menu, Pizza, Footer, and Order.
Technologies Used
React: A JavaScript library for building user interfaces.
JavaScript (ES6+): Modern JavaScript features for cleaner and more efficient code.
HTML/CSS: Basic building blocks for web development, used to structure and style the application's frontend.
Project Structure

/
├── public/
│ └── index.html # Main HTML file
└── src/
├── index.js # Entry point for React application
├── App.js # Root React component
├── components/ # Folder for React components
│ ├── Header.js # Component for the header section
│ ├── Menu.js # Component for rendering the pizza menu
│ ├── Pizza.js # Component for individual pizzas
│ ├── Footer.js # Footer component with dynamic greetings based on time
│ └── Order.js # Component shown during business hours for placing orders
└── index.css # Stylesheet for the application
Setup and Installation
Clone the repository:

Components:
Header: Displays the application's title.

Menu: Renders the list of available pizzas or a message if the menu is still being prepared.

Pizza: Represents individual pizza items. If a pizza is sold out, it will not be displayed.

Footer: Shows opening hours or an order prompt depending on the current time.

Order: Displayed during business hours to encourage users to place orders.
