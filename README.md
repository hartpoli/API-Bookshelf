# Bookshelf API

This is a RESTful API for managing books in a bookshelf. It allows users to perform CRUD (Create, Read, Update, Delete) operations on the books in the bookshelf.

## Features

The API supports the following features:

- Add a new book to the bookshelf
- Retrieve a specific book from the bookshelf
- Retrieve a list of all books in the bookshelf
- Update the information of a book in the bookshelf
- Delete a book from the bookshelf

## Technologies Used

The API is built using the following technologies:

- Node.js
- Express.js
- MongoDB

## Getting Started

To get started with the API, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/bookshelf-api.git`
2. Install the dependencies: `npm install`
3. Set up the MongoDB database. You can use a local installation or a cloud-based service such as MongoDB Atlas.
4. Create a `.env` file in the root directory of the project, and add the following environment variables:


5. Start the server: `npm start`

## API Endpoints

The following API endpoints are available:

| Endpoint           | HTTP Method | Description                               |
| ------------------|-------------|-------------------------------------------|
| `/books`           | GET         | Retrieve a list of all books in the bookshelf |
| `/books/:id`       | GET         | Retrieve a specific book from the bookshelf   |
| `/books`           | POST        | Add a new book to the bookshelf              |
| `/books/:id`       | PUT         | Update the information of a book in the bookshelf |
| `/books/:id`       | DELETE      | Delete a book from the bookshelf             |

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
