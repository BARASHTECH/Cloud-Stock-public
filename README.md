# Cloud Stock

Cloud Stock is a web application designed for managing inventory across multiple e-commerce platforms, including Ozon, Ymarket, and Wildberries. The application allows users to track product stocks, manage orders, and handle returns efficiently.

## Features

- **Multi-Platform Integration**: Connects with Ozon, Ymarket, and Wildberries APIs to fetch and update product information.
- **Real-Time Inventory Management**: Automatically updates stock levels based on returned orders and new orders.
- **User-Friendly Interface**: Provides a clean and intuitive interface for managing products and viewing stock levels.
- **Asynchronous Processing**: Utilizes asynchronous programming to handle API requests and database operations efficiently.
- **Django Framework**: Built on Django, leveraging its powerful ORM and admin capabilities.

## Technologies Used

- **Backend**: Python, Django
- **Frontend**: HTML, CSS, JavaScript
- **Database**: PostgreSQL (or any other database supported by Django)
- **Asynchronous Tasks**: Celery for background task processing
- **APIs**: Integration with Ozon, Ymarket, and Wildberries APIs


## Usage

- **Login**: Access the application using the login page.
- **Manage Products**: Add, update, and delete products from the inventory.
- **View Orders**: Monitor orders from different platforms and manage returns.
- **Stock Updates**: The application automatically updates stock levels based on returned orders.

## Contributing

Contributions are welcome! 

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the Django community for their support and documentation.
- Special thanks to the API providers for Ozon, Ymarket, and Wildberries for their robust APIs.
