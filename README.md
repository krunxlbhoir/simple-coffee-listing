# Simple Coffee Listing

## 📝 Project Description
A dynamic web application showcasing a list of coffee products. This project was built using React to demonstrate core concepts like state management, data fetching from an external API, conditional rendering, and reusable components.

## 🚀 Demo
You can see a live version of the project here:
https://krunxlbhoir.github.io/simple-coffee-listing/

## 💻 Technologies Used
* React 18
* JavaScript (ES6+)
* HTML5
* CSS3 (using CSS Variables for styling)

## ✨ Features
* **Reusable Card Component:** Displays product details including name, price, rating, and availability.
* **Conditional Tags:** Renders "Popular" and "Sold out" tags based on product data.
* **External Data Fetching:** Loads coffee data from a remote JSON API.
* **Filtering:** Users can toggle a checkbox to view only currently available products.
* **Defensive Rendering:** Includes robust handling for missing data fields (e.g., price and rating).

## ⚙️ How to Run Locally
To run the coffee listing app on your development machine:

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/krunxlbhoir/simple-coffee-listing.git](https://github.com/krunxlbhoir/simple-coffee-listing.git)
    ```

2.  **Navigate to the Project Directory:**
    ```bash
    cd simple-coffee-listing
    ```

3.  **Install Dependencies:**
    This command reads the `package.json` file and installs necessary libraries (React, react-dom, react-scripts).
    ```bash
    npm install
    ```

4.  **Start the Development Server:**
    The application will automatically open in your web browser (usually at `http://localhost:3000`).
    ```bash
    npm start
    ```

## 🏗️ Deployment
This project is configured to be deployed via GitHub Pages. After pushing your code to the `main` branch, run the following commands (requires the `gh-pages` package to be set up in `package.json`):

```bash
npm run deploy
