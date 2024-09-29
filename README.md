# Desgin-an-api
Assginment 1 in Backend Classes

Desgin an api For 

1 : Create User
POST/users
body :
{
  "name": "Surajit Mandal",
  "email": "surajit@gmail.com",
  "password": "password123",
  "address": {
    "street": "3/D Panchanan Tala",
    "city": "Rishra",
    "state": "West Bengal",
    "zip": "712248"
  },
  "phone": "891010493"
}


2: Get All Users
GET/users

3. Get Specific User Profile
GET/users/{user_id}

4. Update User Profile
PATCH /users/{user_id}
   body :
   {
  "name": "Arun Mandal",
   user_id:1 }

6. Get All Products
GET/products

7. Get Specific Product
GET/products/{product_id}

8. Add Product to Cart
POST/cart
{
  "user_id": "1",
  "product_id": "1",
  "product_name": "Potato",
  "quantity": 1
}

9. Remove Product from Cart
DELETE/cart

10. Create an Order
POST/orders
body :
{
order_name:
order_no:
user_id:
}

12. Cancel an Order
DELETE/orders
body :
{
 "order_id": "1001",
}

