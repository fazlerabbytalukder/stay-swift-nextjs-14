<div align="center">

# StaySwift — Hotel Booking App

A hotel booking app built with Next.js 14, Auth.js and MongoDB.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Site-6A3FD1?style=for-the-badge&logo=vercel&logoColor=white)](https://stay-swift-nextjs-14.vercel.app)

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![Auth.js](https://img.shields.io/badge/Auth.js-7C3AED?style=flat-square&logo=auth0&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

</div>

## ✨ Features

- Browse hotels and view their details
- Book a stay and manage reservations on the **Bookings** page
- Authentication with **Auth.js (NextAuth v5)**, MongoDB adapter and bcrypt-hashed credentials
- Separate layouts for the auth and app areas using route groups
- Server-side data access with Mongoose models and service helpers

## 🧰 Tech Stack

| Area | Tools |
| --- | --- |
| Framework | Next.js 14 (App Router) |
| UI | Tailwind CSS |
| Auth | Auth.js, @auth/mongodb-adapter, bcryptjs |
| Database | MongoDB, Mongoose |

## 🗺️ Main Routes

| Route | Description |
| --- | --- |
| `/` | Home |
| `/hotels` | Hotel listing |
| `/bookings` | My bookings |
| `/login` | Log in |
| `/register` | Create an account |

## 🚀 Getting Started

```bash
git clone https://github.com/fazlerabbytalukder/stay-swift-nextjs-14.git
cd stay-swift-nextjs-14
npm install
npm run dev
```

Add your MongoDB connection string and Auth secret to `.env.local` before running.

Then open `http://localhost:3000` in your browser.

## 👤 Author

**Fazle Rabby Talukder** — Frontend Developer

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white)](https://fazlerabbytalukder.vercel.app/) [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/fazle-rabby-talukder/) [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/fazlerabbytalukder)

If you find this project useful, consider giving it a ⭐!
