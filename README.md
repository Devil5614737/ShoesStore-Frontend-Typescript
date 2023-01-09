# Introduction

This Ecommerce Web App is a fully functional online store that allows users to browse and purchase products. It is built using a modern tech stack, including [Next.js](https://nextjs.org/), [Node.js](https://nodejs.org/), [MongoDB](https://www.mongodb.com/), [TypeScript](https://www.typescriptlang.org/), [Tailwind CSS](https://tailwindcss.com/), and [Stripe](https://stripe.com/).

## Features

Users can log in to the app and add items to their shopping cart. When they are ready to check out, they can pay for their items using Stripe, a secure and widely-used payment processing platform. Additionally, users can save items to their favorites list for later reference.

## Demo

A demo of the app can be found [here](https://shoes-store-frontend-typescript.vercel.app/).

![Screenshot of Ecommerce App](https://portfolio-next-js-iota.vercel.app/_next/image?url=%2Fassets%2Fecommerce2.png&w=1920&q=75)

## How to use

To use the app, first ensure that you have Node.js and MongoDB installed on your system. Then, follow these steps:

1. Clone the repository:
```bash
git clone https://github.com/your-username/ecommerce-app.git

2. Navigate to the project directory:
```bash
cd ecommerce-app

3. Install the dependencies
```bash
npm install

4.Create a .env file in the root of the project and add the following environment variables:
```bash
MONGO_URI=<your-mongodb-uri>
STRIPE_SECRET_KEY=<your-stripe-secret-key>

5.Start the development server:
```bash
npm run dev

The app should now be running on http://localhost:3000.
