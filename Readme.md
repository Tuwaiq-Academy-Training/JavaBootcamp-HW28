### User:
- id - username - password - role(CUSTOMER-ADMIN) (Add All Required Validation)

### Order:
- id - quantity - totalPrice - dateReceived - status(new-inProgress-completed) (Add All Required Validation)

### Product:
- id - name - price (Add All Required Validation)


### Notes:
- Customer - Order (One to Many)
- Product - Order (One to Many)
- All CRUD required
- In Add order endpoint: calculate the total price , status by defalut new  
- In Delete endpoint, check order status if its in progress or complete throw an exception
- Create endpoint that change order status(only admin can change it)
- Get order - customer - product by Id
- Get all customer orders
