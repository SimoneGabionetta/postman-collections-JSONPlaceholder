# JSONPlaceholder API - Postman Collection

This project was developed as part of the API Testing with Postman course at the Tester Global Community, taught by Vinicius Pessoni.
The objective was to learn about manual API testing using the Postman tool.

## Table of Contents

- [Step-by-step](#Step-by-step)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)

## Step-by-step

1. Choose Public API: JSONPlaceholder
2. Endpoints da API JSONPlaceholder
4. Create the collection in Postman
5. Add requests to the collection
6. Test the collection 



## Usage

1. Clone the repository:

```bash
git clone https://github.com/SimoneGabionetta/postman-collections-JSONPlaceholder
```

2. Import the JSON collection into Postman.

3. Use the provided endpoints to make requests to the JSONPlaceholder API.
```bash
   Base URL :  https://jsonplaceholder.typicode.com
```
   

## API Endpoints
The API provides the following endpoints:

```markdown
GET - Returns a list of posts.
URL: https://jsonplaceholder.typicode.com/posts

GET - Get a specific post.
URL: https://jsonplaceholder.typicode.com/posts/{id}
ID do post: 1-100

POST - Create a new post.
URL: https://jsonplaceholder.typicode.com/posts
Body:
   {
    "title": "foo",
    "body": "bar",
    "userId": 1
  }

PUT - Update a specific post.
URL: https://jsonplaceholder.typicode.com/posts/{id}
Body:
  {
    "id": 1,
    "title": "updated title",
    "body": "updated body",
    "userId": 1
  }

PATCH- Partially update a specific post.
URL:https://jsonplaceholder.typicode.com/posts/{id}
Body :
  {
    "title": "partial update"
  }
DELETE - Delete a specific post.
URL:https://jsonplaceholder.typicode.com/posts/{id}
```

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request to the repository.

