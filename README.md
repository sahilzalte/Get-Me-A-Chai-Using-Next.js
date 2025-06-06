# ☕ Get Me A Chai - Patreon Clone

A full-stack Patreon-inspired platform that allows users to support creators by sending payments. Built with **Next.js**, **Tailwind CSS**, **MongoDB**, and **Razorpay** integration for seamless and secure transactions.

---

## 📌 Features

- 🔐 **GitHub OAuth Authentication**
- 🧑‍💻 **User Dashboard** with donation and profile tracking
- 💳 **Razorpay Payment Integration**
- ⚡ **Real-time Payment Handling** with callback support
- 📱 **Responsive Design** for mobile and desktop
- 🌐 **MongoDB Database** for storing user and donation info securely

---

## 🛠️ Tech Stack

- **Frontend**: Next.js, React, Tailwind CSS
- **Backend**: Next.js API Routes, MongoDB
- **Auth**: GitHub OAuth using `next-auth`
- **Payments**: Razorpay SDK
- **Database**: MongoDB Atlas

## Configure Environment Variables

Create a .env.local file based on .env.example:
```
GITHUB_ID=your_github_oauth_id
GITHUB_SECRET=your_github_oauth_secret
RAZORPAY_KEY_ID=your_razorpay_key
RAZORPAY_KEY_SECRET=your_razorpay_secret
MONGODB_URI=your_mongodb_connection_string
NEXTAUTH_SECRET=your_nextauth_secret
```

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```
