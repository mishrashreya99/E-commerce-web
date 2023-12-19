# MERN Ecommerce

## Description
An ecommerce store built with MERN stack, utilizing third-party APIs. This ecommerce store enables three main different flows or implementations:

- Buyers browse the store categories, products, and brands.
- Sellers or Merchants manage their brand component.
- Admins manage and control the entire store components.

## Features
- Node provides the backend environment for this application.
- Express middleware is used to handle requests and routes.
- Mongoose schemas to model the application data.
- React for displaying UI components.
- Redux to manage the application's state.
- Redux Thunk middleware to handle asynchronous redux actions.

## Database Seed
The seed command will create an admin user in the database. The email and password are passed with the command as arguments. For example:
npm run seed:db [email-***@****.com] [password-******]
For more information, see code here.
## Demo
This application is deployed on Render. Please check it out 😄 here.

See admin dashboard demo.

Install
bash
Copy code
git clone (https://github.com/mishrashreya99/E-commerce-web.git)
cd project
npm install
Setup
Create a .env file that includes:

MONGO_URI & JWT_SECRET
PORT & BASE_SERVER_URL & BASE_API_URL & BASE_CLIENT_URL
MAILCHIMP_KEY & MAILCHIMP_LIST_KEY => Mailchimp configuration
MAILGUN_KEY & MAILGUN_DOMAIN & MAILGUN_EMAIL_SENDER => Mailgun configuration
GOOGLE_CLIENT_ID & GOOGLE_CLIENT_SECRET & GOOGLE_CALLBACK_URL => Google Auth configuration
FACEBOOK_CLIENT_ID & FACEBOOK_CLIENT_SECRET & FACEBOOK_CALLBACK_URL => Facebook Auth configuration
AWS_ACCESS_KEY_ID & AWS_SECRET_ACCESS_KEY & AWS_REGION & AWS_BUCKET_NAME => AWS configuration
Start Development

npm run dev
Simple Build for Production

npm run build
Run Build for Production

npm start

## Languages & Tools
Node
Express
Mongoose
React
Webpack
Code Formatter

## About
An ecommerce store built with Mern-stack. Visit mern-store.onrender.com.

## License
MIT license


