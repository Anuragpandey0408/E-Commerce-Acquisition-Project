# E-Commerce Acquisition Project

![Project Banner](https://miro.medium.com/v2/resize:fit:1142/1*2ApVG8ae9FImPgkPLvKAZA.png)

## Project Overview

The **E-Commerce Acquisition Project** is a web scraping application focused on scraping review data from **Flipkart**. It extracts user reviews and comments about products and displays them on a web interface. The goal is to gather insights from customer feedback in a structured and accessible format using a Flask-based web application.

---

## Features

- Scrapes product reviews from **Flipkart**.
- Collects data such as review comments, ratings, and product details.
- Stores the scraped data in **MongoDB** for easy retrieval.
- Displays the data on a Flask web app using **HTML** and **CSS**.
- Provides an intuitive and user-friendly interface for exploring customer reviews.

---

## Technologies Used

- ![Python](https://img.shields.io/badge/Python-3.9+-blue) 
- ![Flask](https://img.shields.io/badge/Flask-v2.0-lightgrey)
- **MongoDB** for database
- **BeautifulSoup** and **Requests** for web scraping
- **HTML/CSS** for frontend design

---

## How It Works

1. **Web Scraping**:
   - The project uses **BeautifulSoup** and **Requests** to scrape customer review data from Flipkart product pages.
   - The data is structured and stored in **MongoDB** for easy retrieval.

2. **Flask Application**:
   - The Flask app fetches the scraped review data from MongoDB.
   - The data is displayed in an organized format on the frontend, making it easy for users to browse through reviews.

3. **Frontend**:
   - A simple and clean user interface using **HTML** and **CSS** allows users to explore the product reviews.
   - The data includes user reviews, ratings, and other relevant details.

   ![Flask App Interface](static/images/flask_app_interface.png)

---

## Installation and Setup

To get started with the project, follow these steps:

### Prerequisites
- **Python 3.x** installed
- **MongoDB** installed and running locally or on a cloud service like MongoDB Atlas
- **Flask**, **BeautifulSoup**, and **Requests** installed

### Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/AnuragPandey0408/E-Commerce-Acquisition-Project.git
   cd E-Commerce-Acquisition-Project

2. **Create a virtual environment (optional but recommended)**:
   python -m venv venv
   source venv/bin/activate  # For Linux/Mac
   venv\Scripts\activate     # For Windows

3.  **Install dependencies:**:
     pip install -r requirements.txt

4.  **Set up MongoDB**:
     Make sure MongoDB is running locally, or set up a cloud MongoDB service.
     Update the connection details in the Flask app if necessary.

5.   **Run the Flask application**:
     python app.py

6. **Access the web app**:
   Open your browser and go to http://127.0.0.1:5000/.
   The web app should display product reviews scraped from Flipkart.

   ## Visual Insights

The Flask app pulls data directly from MongoDB and organizes it into easy-to-read reviews.

**Example Output**:
![Example Reviews](static/images/example_reviews.png)  <!-- Replace with actual image path -->

---

## Future Work

1. **Sentiment Analysis**:
   - Implement sentiment analysis on the scraped reviews to classify them as positive, negative, or neutral.

2. **Pagination**:
   - Add pagination for handling large numbers of reviews.

3. **Advanced Search**:
   - Enable users to search for products based on specific criteria such as ratings, keywords, or review length.

4. **Email Alerts**:
   - Allow users to sign up for email notifications when new reviews for a product are available.



