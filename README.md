# E-commerce Platform

## Description

A comprehensive e-commerce platform that integrates a web interface, a robust API, and a mobile application. It enables customers to browse products, add items to their cart, and complete secure purchases, while also providing an administrative dashboard for managing products, orders, and inventory.

## Features

- **Product Catalog:** Browse and search for products in real time.
- **Shopping Cart:** Seamless cart management with real-time updates.
- **Secure Checkout:** Integration with secure payment gateways for smooth transactions.
- **Order Management:** Track order statuses and view purchase history.
- **Mobile Integration:** A native mobile app for shopping on the go.

## Technologies

- **Turborepo:** Monorepo management for organizing the web, API, and mobile modules.
- **Next.js:** Responsive web interface.
- **NestJS:** Scalable and modular API.
- **React Native:** Native mobile application.
- **Prisma ORM:** Efficient database management and migrations.

## Prerequisites

- Node.js (LTS version)
- npm or yarn
- React Native environment (Android Studio/Xcode)
- A database (e.g., PostgreSQL, MySQL)

## Installation and Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/gam3r_store.git
   cd gam3r_store
   ```

2. **Install dependencies:**

   ```bash
   npm install
   # or
   yarn install
   ```

3. **Database Setup:**

   - Update the `.env` file with your database credentials.
   - Run Prisma migrations:

     ```bash
     npx prisma migrate dev
     ```

4. **Running the Application:**

   - **API (NestJS):**

     ```bash
     cd apps/backend
     npm run start:dev
     ```

   - **Frontend (Next.js):**

     ```bash
     cd apps/frontend
     npm run dev
     ```

   - **Mobile (React Native):**

     ```bash
     cd apps/mobile
     npx react-native run-android  # for Android
     npx react-native run-ios      # for iOS
     ```

## Contribution

Contributions are welcome. To contribute:

1. Fork the project.
2. Create a branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes.
4. Push your branch (`git push origin feature/your-feature-name`) and open a Pull Request.

## Contact

For questions or suggestions, contact: [matvno@gmail.com](mailto:matvno@gmail.com)

---