
# Database Tables


-Users : Admin , Customers

-Orders

-menu

-payment

-restaurant

-table




## API Reference

#### Login/Register

```http
  POST /auth/register/
```
```http
  POST /auth/login/
```
```http
  POST /auth/token/refresh/
```
#### Menu

```http
  GET /menu-items/
```
```http
  POST /menu-items/:
```
```http
  PUT /menu-items/id
```
```http
  DELETE /menu-items/id
```

#### Order

```http
  GET /api/orders
```
```http
  POST /api/orders
```
```http
  PUT /api/orders/id
```
#### Payments

```http
  GET /api/payments/id
```
```http
  POST /api/payments
```





