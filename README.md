# API on Go Programming
This is basic concept of Go Programming implemented on API Concept

## Features
Get All Data
Get One Data
Update Data
Delete Data

## API Example
### Show All Books
#### URL
```
localhost:8000/api/books
```
#### Response
```json
[
    {
        "id": "1",
        "isbn": "438227",
        "title": "Book One",
        "author": {
            "firstname": "John",
            "lastname": "Doe"
        }
    },
    {
        "id": "2",
        "isbn": "454555",
        "title": "Book Two",
        "author": {
            "firstname": "Steve",
            "lastname": "Smith"
        }
    }
]
```
