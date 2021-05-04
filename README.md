# EZeebuy eCommerce Platform

> eCommerce platform built with the MERN stack & Redux.

## HomeScreen
![image](https://user-images.githubusercontent.com/60813213/116999941-fb6f2280-acfd-11eb-8639-697fa0c9df1d.png)

## User Profile
![image](https://user-images.githubusercontent.com/60813213/117000167-4852f900-acfe-11eb-9c29-a6f1d4a0db01.png)

## Admin Product Screen
![image](https://user-images.githubusercontent.com/60813213/117000354-92d47580-acfe-11eb-8ea8-4bde994e04c4.png)

## LoginScreen
![image](https://user-images.githubusercontent.com/60813213/117000471-c0b9ba00-acfe-11eb-83b0-039cbf3cb460.png)


## Features

- Full featured shopping cart
- Product reviews and ratings
- Top products carousel
- Product search feature
- Admin Order details page
- Mark orders as delivered option
- User profile with orders
- Admin product management
- Admin user management
- Checkout process (shipping, payment method, etc)
- PayPal / credit card integration
- Database seeder (products & users)



## Usage



### Env Variables

Create a .env file in then root and add the following

```
NODE_ENV = development
PORT = 5000
MONGO_URI = your mongodb uri
JWT_SECRET = you jwt key
PAYPAL_CLIENT_ID = your paypal client id
```

### Install Dependencies (frontend & backend)

```
npm install
cd frontend
npm install
```

### Run

```
# Run frontend (:3000) & backend (:5000)
npm run dev

# Run backend only
npm run server
```

## Build & Deploy

```
# Create frontend prod build
cd frontend
npm run build
```



### Seed Database

You can use the following commands to seed the database with some sample users and products as well as destroy all data

```
# Import data
npm run data:import

# Destroy data
npm run data:destroy
```

```
Sample User Logins

admin@example.com (Admin)
123456

divas.srk.gupta@gmail.com (Customer)
123456


```


