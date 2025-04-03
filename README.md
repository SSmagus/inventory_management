# Inventory Management System

## Overview
An inventory management system built using **TypeScript**,  **Next.js**, **PostgreSQL**, **Tailwind CSS**, and **Prisma**. This web application allows users to efficiently track and manage inventory with a modern and responsive UI.

## Features
- **User Authentication** (Login & Signup)
- **Product Management** (Add, Edit)
- **Real-time Stock Tracking**
- **Category & Supplier Management**
- **Dashboard with Analytics**
- **Search & Filter Functionalities**

## Tech Stack
- **Frontend:** Next.js, Tailwind CSS
- **Backend:** Next.js API Routes
- **Database:** PostgreSQL
- **ORM:** Prisma
- **Deployment:** Vercel


## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/SSmagus/inventory_management.git
   cd inventory_management
   ```

2. Install dependencies:
   ```sh
   npm install
   ```

3. Set up the database:
   - Ensure PostgreSQL is installed and running.
   - Create a `.env` file and configure the database URL:
     ```
     DATABASE_URL=postgresql://user:password@localhost:5432/inventory_db
     ```
   - Run database migrations:
     ```sh
     npx prisma migrate dev
     ```

4. Start the development server:
   ```sh
   npm run dev
   ```
5. Start the Client side:
   ```sh
   npm run dev
   ```

## Deployment
- The project can be deployed on **Vercel** with automatic CI/CD.
- Ensure environment variables are set in the deployment settings.

## Contributing
1. Fork the repository
2. Create a new branch (`feature-branch`)
3. Commit changes
4. Push to your branch and submit a PR


