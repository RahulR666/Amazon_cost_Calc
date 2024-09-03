# Amazon_cost_Calc

Amazon Cost Calc is a web application developed to track and monitor Amazon product prices, alerting users to price changes and deals. The application is built using Python, with a Django backend managing user alerts and price tracking, and BeautifulSoup and Requests for web scraping.

## Features

- **Price Tracking**: Monitors the prices of selected Amazon products and alerts users when prices drop.
- **User Alerts**: Sends notifications to users when the product price falls below a specified threshold.
- **Web Scraping**: Uses BeautifulSoup and Requests to extract and update product pricing data from Amazon.
- **Django Backend**: Manages user data, product tracking, and alerts efficiently.

## Tools, Frameworks, and Libraries

### Programming Language
- **Python**: The primary language used for developing the application.

### Libraries and Frameworks
- **Django**: Web framework used for backend development, handling user management and alert systems.
- **BeautifulSoup**: Library for web scraping, used to extract product details and pricing from Amazon.
- **Requests**: HTTP library used to send requests to Amazon's website and retrieve product data.

### Tools
- **HTML/CSS**: Used for creating the front-end interface.
- **JavaScript**: Enhances user interactions on the client side.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/amazon-cost-calc.git
    cd amazon-cost-calc
    ```

2. **Set up the environment**:
    ```bash
    python -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    pip install -r requirements.txt
    ```

3. **Set up the database**:
    - Run the following commands to set up the Django database:
    ```bash
    python manage.py migrate
    python manage.py createsuperuser
    ```

4. **Run the application**:
    ```bash
    python manage.py runserver
    ```
    - Access the application via `http://127.0.0.1:8000` in your web browser.

## How It Works

- Users add products they want to track by entering the Amazon product URL.
- The application scrapes the product's price and stores it in the database.
- If the product's price drops below the user's specified threshold, an alert is triggered, notifying the user via the application or email.

## Future Enhancements

- Add support for tracking product availability and shipping times.
- Implement a user dashboard for managing multiple tracked products.
- Improve scraping efficiency and handling of Amazon's anti-bot measures.

## Contributing

Contributions are welcome! Feel free to submit a Pull Request or open an Issue to discuss potential improvements or bug fixes.

## Contact

For any inquiries, please contact [rahulrathnam666@gmail.com](mailto:rahulrathnam666@gmail.com).

