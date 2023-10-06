# Build a Book Catallog


### Live Link: https://book-catalog-mocha.vercel.app

# 
## Application Routes:
### Application Routes:
#### User:
* api/v1/auth/signup (POST)
* api/v1/auth/signin (POST)
* api/v1/users (GET)
* api/v1/users/:id (Single GET) Include 

* api/v1/users/:id(PATCH)

* api/v1/users/:id (DELETE) 
* api/v1/profile/ (GET)

#### Category :
* api/v1/categories/create-category (POST)
* api/v1/categories/ (GET)
* api/v1/categories/:id (Single GET) 
* api/v1/categories/:id (PATCH)
* api/v1/categories/:id (DELETE) Include 

#### Books :
* api/v1/books/create-book(POST)
* api/v1/books (GET)
* api/v1/books/08f7edd5-dc74-47f1-9942-39f31ad0d6a3/category 
* api/v1/books/:id (GET)
* api/v1/books/:id (PATCH)
* api/v1/books/:id (DELETE)

#### Orders : 
* api/v1/orders/create-order (POST)
* api/v1/orders (GET)
* api/v1/orders/:orderId (GET)
* api/v1/orders/:id(GET)