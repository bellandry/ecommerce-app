# Next Js Full Stack Ecommerce Website.

This is a full stack Nextjs app with a beautiful and amazing design ui.

## Core features

- Learn how to start a next js project from scratch
- Learn how to set SEO to Next Js Project
- Learn how to set up Tailwind Css and Next Js Project
- Learn how to create React components with Tailwind CSS
- Learn how to create React components with framer motion
- Learn how to Test your app with Jest, Cypress
- Learn how to build consume API

## Quick start

To spin up this example loccaly, follow these steps

### Clone

Use the `git clone` CLI to clone template directly to your machine

### Set up env file

1. You will need to setup Next js [Next Js ](https://nextjs.org)

```bash
    NEXT_PUBLIC_SERVER_URL=
```

## Project Dev Steps

1. Environment Setup

   Create a env file on the root of project

   Note that this version consume API from a backend APP, the

```bash
    NEXT_PUBLIC_API_URL
```

    PUT THIS INSIDE

```bash

    NEXT_PUBLIC_SERVER_URL=http://localhost:3000
    NEXT_PUBLIC_API_URL=http://localhost:3001
    NEXTAUTH_SECRET=NEXTAUTH_SECRET

    # Stripe integration
    NEXT_PUBLIC_STRIPE_CLIENT_KEY=
    STRIPE_SECRET_KEY=

    # Paypal integration
    NEXT_PUBLIC_PAYPAL_CLIENT_ID=
    PAYPAL_CLIENT_SECRET=
```

### Run project on local

```bash
    npm install
    npm run dev
```
