## Laravel CRUD API with Auth
Basic Laravel CRUD API application included with Authentication Module & Product Module. It's included with JWT authentication.

----

### Language & Framework Used:
1. PHP
1. Laravel

### Architecture Used:
1. Interface-Repository Pattern
1. Model Based Eloquent Query
1. JWT Auth - https://github.com/tymondesigns/jwt-auth

### API List:
##### Authentication Module
1. [x] Register User API with Token
1. [x] Login API with Token
1. [x] Authenticated User Profile
1. [x] Refresh Data
1. [x] Logout

##### Product Module
1. [x] Product List
1. [x] Product List [Public]
1. [x] Create Product
1. [x] Edit Product
1. [x] View Product
1. [x] Delete Product

### How to Run:
1. Clone Project - 

```bash
git clone https://github.com/shawon3719/Wedevs_product_CRUD_backend.git
```
2. Go to the project drectory by `cd your-directory` & Run the 
2. Create `.env` file & Copy `.env.example` file to `.env` file
3. Create a database called - `laravel_basic_crud`.
4. Now migrate and seed database to complete whole project setup by running this-
``` bash
php artisan migrate
```
after that,
5. Run the server - 
``` bash
php artisan serve
```
6. Open Browser - 
http://127.0.0.1:8000 

API is running now. you can use these API using postman or clone and run [frontend in react for the API](https://github.com/shawon3719/wedevs_product_crud_frontend)


