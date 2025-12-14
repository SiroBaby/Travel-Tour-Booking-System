# Travel Tour Booking System

A modern full-stack travel tour booking platform built with Next.js and TypeScript. 

## 📋 Overview

This Travel Tour Booking System is a comprehensive web application that allows users to browse, book, and manage travel tours.  The project features a modern, responsive user interface built with Next.js and a robust backend API.

## 🏗️ Project Structure

```
Travel-Tour-Booking-System/
├── my-next-app/          # Frontend application (Next.js)
│   ├── app/              # Next.js 13+ app directory
│   ├── public/           # Static assets
│   └── package.json      # Frontend dependencies
│
└── my-backend/           # Backend API
    ├── src/              # Source code
    ├── prisma/           # Database schema and migrations
    ├── public/           # Public assets
    ├── dist/             # Compiled output
    └── package.json      # Backend dependencies
```

## ✨ Features

- 🔍 Browse and search travel tours
- 📅 Book tours with real-time availability
- 👤 User authentication and profile management
- 💳 Secure booking and payment processing
- 📱 Responsive design for mobile and desktop
- 🎨 Modern UI with optimized fonts (Geist)
- 🗄️ Database management with Prisma ORM

## 🚀 Getting Started

### Prerequisites

- Node. js (v16 or higher)
- npm, yarn, pnpm, or bun
- PostgreSQL or your preferred database

### Frontend Setup

1. Navigate to the frontend directory:
```bash
cd my-next-app
```

2. Install dependencies:
```bash
npm install
# or
yarn install
# or
pnpm install
```

3. Run the development server:
```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application. 

### Backend Setup

1. Navigate to the backend directory:
```bash
cd my-backend
```

2. Install dependencies:
```bash
npm install
```

3. Set up your environment variables:
```bash
cp .env.example .env
```

4. Configure your database connection in the `.env` file

5. Run Prisma migrations:
```bash
npx prisma migrate dev
```

6. Start the backend server:
```bash
npm run dev
```

## 🛠️ Tech Stack

### Frontend
- **Framework**: Next. js 13+ (App Router)
- **Language**: TypeScript
- **Styling**: CSS Modules / Tailwind CSS
- **Font Optimization**: next/font with Geist font family

### Backend
- **Runtime**: Node.js
- **Language**: TypeScript
- **ORM**: Prisma
- **Database**: PostgreSQL (or your configured database)

## 📝 Development

### Frontend Development

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

### Backend Development

The backend source code is located in `my-backend/src/`. Make sure to compile TypeScript after making changes:

```bash
npm run build
```

## 📚 Learn More

### Next.js Resources
- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial
- [Next.js GitHub repository](https://github.com/vercel/next.js)

### Prisma Resources
- [Prisma Documentation](https://www.prisma.io/docs)
- [Prisma Schema Reference](https://www.prisma.io/docs/reference/api-reference/prisma-schema-reference)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!  Feel free to check the issues page. 

## 👨‍💻 Author

**SiroBaby**
- GitHub:  [@SiroBaby](https://github.com/SiroBaby)
```
