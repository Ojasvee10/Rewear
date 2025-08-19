# ♻️ ReWear - Sustainable Fashion Platform

[![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)

A full-stack MERN (MongoDB, Express.js, React, Node.js) web application built with **Next.js** that promotes sustainable fashion by allowing users to donate, swap, and upcycle clothing items. ReWear aims to reduce textile waste and build a community around conscious consumerism.

![ReWear Screenshot](https://via.placeholder.com/800x400.png?text=ReWear+App+Screenshot) *// Replace with an actual screenshot of your app*

## ✨ Features

-   **User Authentication & Profiles**: Secure signup and login with personalized user dashboards.
-   **Item Listings**: Users can post clothing items for donation or swap with images, descriptions, and categories.
-   **Swap Marketplace**: Browse and search through items posted by other community members.
-   **Swap Requests**: Initiate and manage swap requests with an integrated messaging system.
-   **Favorites System**: Save interesting items for later.
-   **Admin Dashboard**: Moderate listings and manage users (if applicable).
-   **Fully Responsive Design**: Seamless experience on desktop, tablet, and mobile.

## 🛠️ Tech Stack

-   **Frontend**: Next.js 14 (App Router), React, Tailwind CSS, NextAuth.js
-   **Backend**: Next.js API Routes, Node.js, Express.js
-   **Database**: MongoDB with Mongoose ODM
-   **Storage**: Cloudinary (for image uploads) or AWS S3
-   **Authentication**: Next-Auth.js (with JWT or OAuth providers)
-   **Deployment**: Vercel (Frontend) / Railway/Render (Backend) or a full-stack platform

## 🚀 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

-   Node.js (v18 or higher)
-   npm, yarn, pnpm, or bun
-   A MongoDB database (local or [MongoDB Atlas](https://www.mongodb.com/atlas/database))
-   Cloudinary account (for image uploads) *[Optional]*

### Installation

1.  **Clone the repository**

    git clone https://github.com/Ojasvee10/ReWear.git
    cd ReWear
    ```

2.  **Install dependencies**
    npm install
    # or
    yarn install
    # or
    pnpm install
    ```

3.  **Environment Setup**
    Create a `.env.local` file in the root directory and configure the following variables:
    # Database
    MONGODB_URI=your_mongodb_connection_string

    # Authentication (Next-Auth)
    NEXTAUTH_SECRET=your_nextauth_secret_here
    NEXTAUTH_URL=http://localhost:3000

    # Optional: For Image Uploads (Cloudinary)
    CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
    CLOUDINARY_API_KEY=your_cloudinary_api_key
    CLOUDINARY_API_SECRET=your_cloudinary_api_secret

    # Optional: OAuth Providers (Google, GitHub, etc.)
    GOOGLE_CLIENT_ID=your_google_oauth_client_id
    GOOGLE_CLIENT_SECRET=your_google_oauth_client_secret
    ```

4.  **Run the development server**

    npm run dev
    # or
    yarn dev
    # or
    pnpm dev
    ```

5.  **Open your browser**
    Navigate to [http://localhost:3000](http://localhost:3000) to view the application.

## 📁 Project Structure (Next.js App Router)

ReWear/
├── app/ # Next.js 14 App Router directory
│ ├── api/ # API routes (backend endpoints)
│ ├── auth/ # Authentication pages & logic
│ ├── dashboard/ # User dashboard pages
│ ├── listings/ # Item listing pages
│ ├── globals.css # Global styles
│ ├── layout.tsx # Root layout
│ └── page.tsx # Homepage
├── components/ # Reusable React components
│ ├── ui/ # Basic UI components (Button, Card, etc.)
│ └── layout/ # Layout components (Header, Footer, Navbar)
├── lib/ # Utility libraries & configurations
│ ├── auth.ts # NextAuth configuration
│ ├── mongoose.ts # MongoDB connection
│ └── utils.ts # Helper functions
├── models/ # Mongoose models & schemas
│ ├── User.ts
│ ├── Listing.ts
│ └── SwapRequest.ts
└── public/ # Static assets

text

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

Please read `CONTRIBUTING.md` for details on our code of conduct.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

-   Inspiration from platforms like ThredUP, Depop, and Vinted.
-   Thanks to the Next.js and MongoDB communities for excellent documentation.
-   Icons provided by [Lucide React](https://lucide.dev/).

---

## 📫 Contact

Ojasvee- [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ojasvee-auti-1b1b3b1b/) - ojasveegupta10@gmail.com

Project Link: [https://github.com/Ojasvee10/ReWear](https://github.com/Ojasvee10/ReWear)

