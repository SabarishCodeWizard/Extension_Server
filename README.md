# Extension_Server


The Flask server is a lightweight web application that serves as the backend for the Product Info Scraper Chrome extension. It provides a RESTful API endpoint that accepts POST requests containing product URLs to scrape product information from various e-commerce websites.

**Flask Server Documentation**

**Overview**

This Flask server provides an API for scraping product information from various e-commerce websites. It utilizes Selenium for web scraping and returns JSON responses to client requests.

**Features**

Supports scraping from multiple e-commerce platforms including Flipkart, Amazon, and Meesho.
Utilizes headless browsing for efficient scraping.
Implements CORS support for cross-origin requests.
Provides a simple and intuitive API interface.

**Usage**

Ensure Python and Flask are installed.
Clone the repository and navigate to the project directory.
Install dependencies using pip install -r requirements.txt.
Run the Flask server with python app.py.
Send POST requests to http://localhost:5000/scrape with a JSON payload containing the URL to scrape.

**Endpoints**

POST /scrape: Scrapes product information from the provided URL and returns a JSON response with the product title and MRP.

**Dependencies**

Flask: Web framework for building the API.
Selenium: Web scraping library for navigating and extracting data from web pages.
Flask-CORS: Flask extension for handling Cross-Origin Resource Sharing (CORS) headers.

**Project Structure**

app.py: Main Flask application file containing route definitions and server configuration.
scraper.py: Module for performing web scraping using Selenium.
README.md: Project documentation providing setup instructions and usage details.
requirements.txt: List of Python dependencies required for the project.

**Contributing**

Fork the repository.
Create a new branch (git checkout -b feature/your-feature).
Make your changes and commit them (git commit -am 'Add new feature').
Push to the branch (git push origin feature/your-feature).
Create a new Pull Request.

License
This project is licensed under the MIT License - see the LICENSE file for details.
