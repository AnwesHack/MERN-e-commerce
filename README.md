# ShopNest – Full-Stack MERN E-Commerce Platform

ShopNest is a full-stack e-commerce application built using the MERN stack, featuring secure user authentication, product management, shopping cart functionality, order tracking, and an integrated admin dashboard.

## Tech Stack

- **Frontend:** React.js, Redux Toolkit, Context API
- **Backend:** Node.js, Express.js
- **Database:** MongoDB, Mongoose
- **Authentication:** JWT
- **Payments:** Razorpay
- **Cloud Storage:** Cloudinary, Multer

## Key Features

- Secure JWT-based user authentication and authorization.
- Product browsing and shopping cart management.
- Admin dashboard for product and order management.
- User profiles with order history.
- Razorpay payment integration.
- Secure product image uploads using Cloudinary and Multer.
- RESTful APIs with middleware-based routing.

## Installation & Setup

**1. Clone the repository**
```bash
git clone <repository-url>
cd ShopNest
```

**2. Install dependencies**
```bash
npm run build
```

**3. Configure Environment Variables**

Create a `.env` file inside the `backend/` directory:

```env
PORT=5000
NODE_ENV=development
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
RAZORPAY_KEY_ID=your_key_id
RAZORPAY_KEY_SECRET=your_key_secret
```

**4. Seed Database**
```bash
npm run seed
```

**5. Start the Application**
```bash
npm run dev
```

## Deployment

Configured for single-service deployment on Render, with the Express backend serving the production React frontend.

## API Testing

Includes a Postman collection (`ShopNest_Postman_Collection.json`) for testing authentication, product, admin, and order-related APIs.
