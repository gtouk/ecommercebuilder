# Ecommercebuilder

## Overview
This project is a custom e-commerce website builder designed specifically for local stores. It allows store owners to create, customize, and manage their online stores easily, while providing visitors with a seamless browsing experience. The platform includes features like a store directory, customizable templates, analytics, and admin moderation tools.

## Tech Stack
- **Frontend**: Next.js + Tailwind CSS
- **Backend**: Node.js/Express + Strapi (CMS)
- **Database**: PostgreSQL
- **Hosting**: Vercel (frontend) + Cloudinary (images)
- **Payments**: Stripe
- **Additional Tools**:
  - Google Maps API (for store location features)
  - Nodemailer (for email notifications)

## Setup Instructions
### Prerequisites
- Node.js (v20.x recommended)
- PostgreSQL
- Git
- Vercel CLI (for deployment)
- Accounts for Stripe, Cloudinary, Google Maps API, and an email service (for Nodemailer)

### Installation

#### 1. **Clone the Repository**:
  ```sh
   git clone https://github.com/gtouk/ecommercebuilder.git
```
```sh
   cd ecommercebuilder
```

 #### 2. **Frontend Setup**
 ```sh
  cd frontend
```
**install packages**
```sh
  npm install
```
```sh
  npm run dev
```

 Open http://localhost:3000 to view the frontend.

#### 3. **Backend Setup**
```sh
  cd backend/strapi
```
- Configure PostgreSQL in config/database.js
```sh
  npm run develop
```

 Access the admin panel at http://localhost:1337/admin.
