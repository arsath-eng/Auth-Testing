

# Auth.js v5 

This Next.js project was bootstrapped with `create-next-app`.

## Overview

This course provides a comprehensive guide to implementing authentication in your applications using Auth.js v5. The course covers various aspects, including setting up Next.js with MongoDB, integrating Google Sign-In, and more.

## Prerequisites

- Node.js
- npm or yarn
- MongoDB

## Installation

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
   ```
   or
   ```bash
   yarn install
   ```

4. **Configuration:**
   Create a `.env` file in the root directory and add the necessary environment variables:
   ```
   MONGO_URI='mongodb+srv:...........'
   AUTH_SECRET='..........'
   GITHUB_CLIENT_ID='............'
   GITHUB_CLIENT_SECRET='................'
   GOOGLE_CLIENT_ID='................'
   GOOGLE_CLIENT_SECRET='...............'
   ```

## Folder Structure

```
AUTH-PROJECT/
├── .next/
├── action/
├── app/
├── components/
├── lib/
│   ├── db.ts
│   ├── getSession.ts
│   └── utils.ts
├── models/
│   └── User.ts
├── node_modules/
├── public/
├── .env
├── .eslintrc.json
├── .gitignore
├── auth.ts
├── components.json
├── middleware.ts
├── next-env.d.ts
├── next.config.mjs
├── package-lock.json
├── package.json
├── postcss.config.mjs
├── README.md
├── tailwind.config.ts
└── tsconfig.json
```

## Running the Project

1. **Start the development server:**
   ```bash
   npm run dev
   ```
   or
   ```bash
   yarn dev
   ```



