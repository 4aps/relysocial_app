# 🌐 Rely Social App

A fully functional and visually appealing **social media application**, built with modern web technologies like **React**, **TypeScript**, and **Appwrite**. This project demonstrates real-world full-stack implementation with features like authentication, post interaction, responsive design, and efficient data handling.

---

## 📋 Table of Contents

- [🤖 Introduction](#-introduction)  
- [⚙️ Tech Stack](#-tech-stack)  
- [🔋 Features](#-features)  
- [🤸 Quick Start](#-quick-start)  
- [🕸️ Snippets](#-snippets)  
- [🚀 More](#-more)

---

## 🤖 Introduction

**Rely Social App** is a modern social media platform where users can create, explore, like, save, and manage posts. It offers a clean interface, smooth performance through **React Query**, and robust backend services via **Appwrite**. Built with scalability and responsiveness in mind, the app delivers a mobile-friendly experience with intuitive navigation and strong user privacy features.

---

## ⚙️ Tech Stack

- **React.js**
- **Appwrite** (BaaS)
- **React Query (Tanstack Query)**
- **TypeScript**
- **Tailwind CSS**
- **Shadcn/UI**

---

## 🔋 Features

- 🔐 **Authentication System** – Secure user login and signup with data protection
- 🧭 **Explore Page** – Discover trending content and top creators
- ❤️ **Like & Save Posts** – Interact with posts and manage your favorites
- 📄 **Post Details Page** – View full post content with related suggestions
- 🙍 **User Profiles** – View and manage profile information and liked posts
- 🧑‍🤝‍🧑 **Browse Users** – Explore other users and their activity
- ✍️ **Create Post** – Drag & drop post creation with file storage
- ✏️ **Edit Post** – Modify post content anytime
- 📱 **Responsive UI + Bottom Bar** – Mobile-friendly navigation and layout
- ⚡ **React Query** – Caching, parallel queries, and mutations for performance
- 🔙 **Appwrite Backend** – Handles auth, database, storage, and collections

And much more — including clean code architecture and modular design.

---

## 🤸 Quick Start

### ✅ Prerequisites

Ensure the following are installed:

- **Git**
- **Node.js**
- **npm**

### 📦 Install Dependencies

```bash
npm install

```
🛠️ Set Up Environment Variables
Create a .env file at the root of your project with the following content:

```
VITE_APPWRITE_URL=
VITE_APPWRITE_PROJECT_ID=
VITE_APPWRITE_DATABASE_ID=
VITE_APPWRITE_STORAGE_ID=
VITE_APPWRITE_USER_COLLECTION_ID=
VITE_APPWRITE_POST_COLLECTION_ID=
VITE_APPWRITE_SAVES_COLLECTION_ID=
```

Replace the placeholders with your actual Appwrite credentials.

▶️ Run the App

```
npm start
```

Visit http://localhost:3000 in your browser.

🕸️ Snippets
Important files and helpers used in the project:

```

globals.css

tailwind.config.js

queryKeys.ts

constants/index.ts

useDebounce.ts

utils.ts

types/index.ts

```


Special Thanks to JSM and Team!

