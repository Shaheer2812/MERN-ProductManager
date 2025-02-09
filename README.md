# Product Management System

A full-stack web application for managing products, built using **React**, **Django**, **MongoDB**, and **Axios**. The system allows users to **add, view, delete**, and **update** products with images, ensuring seamless CRUD functionality.

## Features
- **Full CRUD functionality**: Users can create, read, update, and delete products.
- **Image Support**: Each product includes an image URL.
- **REST API**: Django serves as the backend API.
- **React Frontend**: A responsive UI built with React.
- **Axios for API Calls**: Handles data fetching and submission efficiently.
- **MongoDB Database**: Stores product details persistently.

## Technologies Used

### Frontend:
- React
- JavaScript
- Axios
- CSS

### Backend:
- Django (Django REST Framework)
- Python
- MongoDB

## API Endpoints

| Method | Endpoint | Description |
|--------|---------|-------------|
| GET | `/api/products` | Fetch all products |
| POST | `/api/products` | Add a new product |
| PUT | `/api/products/:id` | Update a product |
| DELETE | `/api/products/:id` | Delete a product |

## Usage
1. Open the React app in the browser.
2. View existing products fetched from the backend.
3. Add a new product with a name, price, and image URL.
4. Delete a product by clicking the delete button.
5. Modify product details via the update feature.

## Future Improvements
- Implement user authentication.
- Enhance UI with better styling.
- Improve error handling and validation.
