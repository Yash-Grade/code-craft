<h1 align="center">🚀 Code Craft - SaaS Online Code Editor</h1>

<p align="center">
A modern SaaS-based online code editor built with Next.js 15, Convex, Clerk, TypeScript, and Tailwind CSS.
</p>

![Project Screenshot](/public/screenshot-for-readme.png)

## ✨ Features

- 🔐 Secure authentication using Clerk
- 💻 Online code editor with multi-language support
- 🎨 Multiple VS Code-inspired editor themes
- ⚡ Real-time code execution
- 📜 Code execution history
- 👤 User profile dashboard
- 🌍 Community code sharing
- 🔍 Search and filtering
- 📊 Statistics dashboard
- 📱 Responsive design
- ☁️ Convex backend integration

---

## 🛠 Tech Stack

- Next.js 15
- TypeScript
- Tailwind CSS
- Convex
- Clerk Authentication
- Monaco Editor

---

## 📂 Environment Variables

Create a `.env.local` file and add:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=
```

For Convex Dashboard, add:

```env
CLERK_WEBHOOK_SECRET=
LEMON_SQUEEZY_WEBHOOK_SECRET=
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/YashGrade/code-craft.git
```

Install dependencies

```bash
npm install
```

Run Convex

```bash
npx convex dev
```

Start the development server

```bash
npm run dev
```

Open:

```
http://localhost:3000
```

---



## 📄 License

This project is licensed under the MIT License.