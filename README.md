
# Go Bookstore
A simple RESTful API built with Go, Gin, and Mux for managing a bookstore's resources.

## Getting Started
**Prerequisites**
* Go - Install the latest version available from the official website
* Git - To clone the repository

## Installing
1. Clone the repository:

```console
git clone https://github.com/your-username/yoour-repo-name.git
cd go-bookstore
```
2. Install the required packages:
Copy code
```console
go get -v
```
3. Run the application:
```console
go run cmd/main/main.go
```

## API Endpoints
**Create a Book**

* Endpoint: `POST /book/`
* Request Body:

```json
{
  "title": "Book Title",
  "author": "Author Name",
  "publication": "Publisher Name"
}
```
* Response:
```json
{
  "id": "0123456789",
  "title": "Book Title",
  "author": "Author Name",  
  "publication": "Publisher Name"
}
```
**Get a list of Books**
* Endpoint: `GET /book/`
**Get a Book by ID**
* Endpoint: `GET /book/{bookId}`
**Update a Book by ID**
* Endpoint: `PUT /book/{bookId}`
**Delete a Book by ID**
* Endpoint: `DELETE /book/{bookId}`

## Contributing
Feel free to submit a pull request or open an issue to contribute to the project. Make sure to include a detailed description of the changes and any relevant context.

## License
This project is open source and licensed under the [MIT License](https://opensource.org/license/mit).

## Contact
If you have any questions, feel free to reach out to the maintainer at [kingdavidao11@gmail.com](mailto:kingdavidao11@gmail.com).