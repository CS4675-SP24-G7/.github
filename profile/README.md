# Consumer Product Feedback System

## Requirements

-   Chrome Browser Installed
-   Python

## Installation

On both `amazon-review-crawler` and `CPFS` directory, `requirements.txt` is provided to install neccessary modules for our application.

Navigate to `amazon-review-crawler` and `CPFS` directory and run the following command for each:

    pip install -r requirements.txt

It will take sometimes to install all dependencies.

## Run Application

### Amazon Review Crawler

Amazon Review Crawler serves as an API, providing the ability to crawl Amazon, Reddit sites and interacting with Firebase Realtime Database.

Navigate to `amazon-review-crawler`, run the following command:

    python app.py

This terminal will run the application on PORT 8080

### CPFS

CPFS is a simple user interface, using the Amazon Review Crawler API.

Navigate to `CPFS`, run the following command:

    python manage.py runserver 8081

Since 8080 is obtained by the API, we must run this UI on PORT 8081.

Navigate to your [http://localhost:8081] to access application UI.

We have crawl and save data into database for the below items for testing purposes:

Good Products:

-   Ring Indoor Cam: [https://www.amazon.com/dp/B0B6GLQJMV](https://www.amazon.com/dp/B0B6GLQJMV)
-   Nike Shoe: [https://www.amazon.com/dp/B01AMT0EYU](https://www.amazon.com/dp/B01AMT0EYU)
-   Echo Dot 3: [https://www.amazon.com/dp/B07N8RPRF7](https://www.amazon.com/dp/B07N8RPRF7)
-   Google TV Stick: [https://www.amazon.com/dp/B08KRV7S22](https://www.amazon.com/dp/B08KRV7S22)
-   Bottle: [https://www.amazon.com/dp/B01KXHIWL8](https://www.amazon.com/dp/B01KXHIWL8)

Bad Products:

-   [https://www.amazon.com/dp/B01LOTMMRE](https://www.amazon.com/dp/B01LOTMMRE)
-   [https://www.amazon.com/dp/B09MVKTYQB](https://www.amazon.com/dp/B09MVKTYQB)
