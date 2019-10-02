### Prerequisites
-  [.NET Core SDK](https://dotnet.microsoft.com/download)
-  [MongoDB](https://www.mongodb.com/what-is-mongodb)

### Description
This is a web API that performs Create, Read, Update, and Delete (CRUD) operations on a MongoDB NoSQL database.

### Run the project
```bash
dotnet run
```

### Build the project
```bash
dotnet build
```

### Install nuget packages
```bash
dotnet restore
```

### Run the tests
```bash
dotnet test
```

## API Documentation
[Postman API Documentation](https://documenter.getpostman.com/view/6831940/SVtN3BSY)

| Method  | Description| Route |
| ------------- | ------------- | ------------- |
| GET |  Get all books | `/api/books` |
| POST | Create a book | `/api/books` |
| GET |  Get a specific book | `/api/books/:bookId` |
| PUT |  Update a specific book | `/api/books/:bookId` |
| DELETE | Delete a specific book |`/api/books/:bookId` |

## Author

*   **Ryan Simiyu** 

## Notes
[ASP.NET Core and MongoDB Documentation](https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-mongo-app?view=aspnetcore-3.0&tabs=visual-studio-code#create-the-aspnet-core-web-api-project)
