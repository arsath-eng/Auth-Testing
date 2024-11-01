# 🔐 Auth.js v5 Next.js Authentication Project

<div align="center">

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Auth.js](https://img.shields.io/badge/Auth.js-000000?style=for-the-badge&logo=auth0&logoColor=white)

A comprehensive authentication solution built with Next.js and Auth.js v5, featuring multiple sign-in methods and MongoDB integration.

</div>

## 📋 Table of Contents
- [Overview](#-overview)
- [Features](#-features)
- [Prerequisites](#-prerequisites)
- [Installation](#-installation)
- [Project Structure](#-project-structure)
- [Configuration](#-configuration)
- [Running the Project](#-running-the-project)
- [Screenshots](#-screenshots)
- [Contributing](#-contributing)
- [License](#-license)

## 🌟 Overview

This project demonstrates a modern authentication implementation using Auth.js v5 in a Next.js application. It provides a secure and scalable solution for handling user authentication with various providers and MongoDB integration.

## ✨ Features

- 🔒 Secure authentication with Auth.js v5
- 🚀 Built with Next.js 14+ and TypeScript
- 📱 Social login integration:
  - Google Sign-In
  - GitHub Authentication
- 💾 MongoDB database integration
- 🎨 Styled with Tailwind CSS
- 🔐 Protected routes and middleware
- 📱 Responsive design

## 🔧 Prerequisites

Before getting started, ensure you have the following installed:

- Node.js (v18 or higher)
- npm or yarn package manager
- MongoDB Atlas account or local MongoDB installation
- Git

## 🚀 Installation

1. **Clone the repository:**
```bash
git clone https://github.com/arsath-eng/Auth-Testing.git
```

2. **Navigate to the project directory:**
```bash
cd auth-project
```

3. **Install dependencies:**
```bash
npm install
# or
yarn install
```

## 📁 Project Structure

```
AUTH-PROJECT/
├── 📂 .next/                  # Next.js build output
├── 📂 action/                 # Server actions
├── 📂 app/                    # Next.js app directory
│   ├── api/                   # API routes
│   ├── auth/                  # Authentication pages
│   └── ...                    # Other app routes
├── 📂 components/             # Reusable React components
├── 📂 lib/                    # Utility functions and configurations
│   ├── db.ts                  # Database connection
│   ├── getSession.ts         # Session management
│   └── utils.ts              # Helper functions
├── 📂 models/                 # MongoDB models
│   └── User.ts               # User model definition
├── 📂 public/                 # Static assets
├── 📄 .env                    # Environment variables
├── 📄 auth.ts                # Auth.js configuration
├── 📄 middleware.ts          # Next.js middleware
└── 📄 [Other config files]   # Various configuration files
```

## ⚙️ Configuration

1. **Create a `.env` file in the root directory with the following variables:**

```env
# MongoDB Connection
MONGO_URI='mongodb+srv://your-connection-string'

# Auth.js Secret
AUTH_SECRET='your-secret-key'

# GitHub OAuth
GITHUB_CLIENT_ID='your-github-client-id'
GITHUB_CLIENT_SECRET='your-github-client-secret'

# Google OAuth
GOOGLE_CLIENT_ID='your-google-client-id'
GOOGLE_CLIENT_SECRET='your-google-client-secret'
```

2. **Configure OAuth Providers:**
   - Set up OAuth applications in [GitHub Developer Settings](https://github.com/settings/developers)
   - Configure OAuth consent in [Google Cloud Console](https://console.cloud.google.com)

## 🚀 Running the Project

1. **Start the development server:**
```bash
npm run dev
# or
yarn dev
```

2. **Open your browser and navigate to:**
```
http://localhost:3000
```

## 📸 Screenshots
<p align="center">
  <img src="screenshot/1-admin.png" alt="Project Banner" width="800"/>
</p>

```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">

Made with ❤️ by [Arsath]

</div>
