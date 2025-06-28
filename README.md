# CTK Shop

## Project Description and Purpose
CTK Shop is a simple example e-commerce web application with a playful dog-themed style. It serves as an online storefront that lists sample products (such as fashion bracelets and accessories), allowing users to browse items, view details, and add them to a cart. The homepage features a fun tagline ("Get Doggy Stickers!"), and each product page shows an image, description, price, and an "Add to Cart" button. This project is intended as a demonstration or template for building a modern online shop, illustrating how to use web technologies (like Next.js/React) to create a responsive, user-friendly shopping experience. Developers can use or customize CTK Shop as a starting point for learning about e-commerce site development or to bootstrap a small store project.

## Installation Instructions
To set up CTK Shop locally, follow these steps:
1. <b>Prerequisites</b>: Ensure you have Node.js (version 14 or later) and npm (Node Package Manager) installed on your system.
2. <b>Clone the repository</b>: Open a terminal and run `git clone`
    `https://github.com/0xthomasit/ctk_shop.git` to copy the project files.
3. <b>Change into the project directory</b>: Run cd `ctk_shop` to enter the project's root folder.
4. <b>Install dependencies</b>: Execute `npm install` (or `yarn install` if you use Yarn) to download and install the required Node.js packages.
5. <b>(If applicable) Configure environment variables</b>: If the project requires any API keys or configuration (e.g. for payment gateways), set them up in a `.env` file or according to project documentation. (For a basic demo, no special configuration is needed).

After completing these steps, the project will be ready for local development.

## Usage Guide
Once installed, you can run CTK Shop and interact with it as follows:
* <b>Start the development server</b>: In the project directory, run `npm run dev` to launch the development build. This will start a local web server (typically on http://localhost:3000).
* <b>View in a browser</b>: Open your web browser and navigate to http://localhost:3000 (or live at https://ctk-shop.vercel.app/). You should see the CTK Shop homepage with the title "Get Doggy Stickers!" and a list of products.
* <b>Browse products</b>: Click on any product listed on the homepage to go to its detail page. Each product page shows a larger image, a title, a description (for example, "Gold boho bangle bracelet with multicolor tassels."), and the price.
* <b>Add to Cart</b>: On a product page, you can adjust the quantity and click Add To Cart to add the item to your shopping cart. (In this demo project, the cart functionality is handled locally in the browser session).
* <b>Checkout (if implemented)</b>: If the project includes checkout functionality or cart review, follow the on-screen instructions to view your cart or proceed to checkout. Otherwise, the "Add To Cart" button will demonstrate basic cart behavior without an actual payment flow.
* <b>Production build</b>: To prepare for production, run `npm run build` to create an optimized build of the site, and then `npm start` to serve the built application on a production server.

## Technologies Used
CTK Shop is built using modern web development technologies. The main tools and libraries include:
* <b>Next.js</b>: A React framework that enables server-side rendering and static site generation. Next.js is used to build the page structure, routing, and rendering logic of the shop.
* <b>React</b>: A JavaScript library for building user interfaces. React components are used to create the product listings, detail pages, and cart interactions.
* <b>Javascript</b>: The programming language used throughout the project for logic and UI rendering.
* <b>Package Manager (npm or Yarn)</b>: Used to install and manage project dependencies defined in `package.json`.
* <b>CSS</b>: Standard CSS (and possibly CSS modules or a library) for styling the application’s layout and appearance. (The demo may use simple built-in styles or a framework like Tailwind CSS for design).
* <b>GraphQL</b>: a query language for APIs, used to query the backend and retrieve exactly the requested data.
* <b>Insomnia</b>: an open-source desktop application for designing, debugging, and testing APIs, used here to test and interact with the GraphQL API.
* <b>Vercel (Deployment)</b>: The site is deployed on the Vercel platform (via ctk-shop.vercel.app), which is optimized for hosting Next.js applications.
