# Admin Dashboard

This is the **Admin Dashboard** for a full-stack e-commerce platform, built using modern web technologies. It provides an interface for managing products, categories, orders, and more.

## 🚀 Tech Stack

- **Next.js 13 (App Router)** – Server-side rendering & routing
- **React** – Component-based UI
- **Tailwind CSS** – Utility-first styling
- **Prisma** – ORM for database management
- **Supabase** – Database
- **Clerk** – Authentication & User Management
- **Stripe** – Payment processing

## 📌 Features

- Secure authentication with Clerk
- Product & category management
- Orders & payments tracking
- Dynamic dashboard with real-time data
- Dark mode support
- Seamless navigation with Next.js App Router

## 🛠️ Setup & Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ecommerce-admin.git
   cd ecommerce-admin
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   Create a `.env` file in the root directory and add:
   ```env
   CLERK_SECRET_KEY=your_clerk_secret_key
   NEXT_PUBLIC_CLERK_SIGN_IN_URL=your_clerk_sign_in_url
   NEXT_PUBLIC_CLERK_SIGN_UP_URL=your_clerk_sign_up_url
   NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=your_clerk_after_sign_in_url
   NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=your_clerk_after_sign_up_url
   NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
   STRIPE_API_KEY=your_stripe_api_key
   DATABASE_URL=your_database_url
   NEXTAUTH_SECRET=your_secret
   ```

4. Run database migrations:
   ```bash
   npx prisma migrate dev
   ```

5. Start the development server:
   ```bash
   npm run dev
   ```

6. Open `http://localhost:3000` in your browser.

## 🌍 Deployment

This project can be deployed easily on **Vercel**. Ensure all environment variables are set up in your Vercel dashboard.

## 📸 Screenshots
![image](https://github.com/user-attachments/assets/31b2fea0-9db7-450b-b3aa-18f941d55f30)
![image](https://github.com/user-attachments/assets/43367578-28dc-4f96-9b57-bf04b05d1528)

## 💡 Inspiration

This project was inspired by [this tutorial](https://www.youtube.com/watch?v=5miHyP6lExg) by CodeWithAntonio, which guided the development of a full-stack e-commerce platform using modern web technologies.

## 🌟 License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to fork, modify, and use this project!
