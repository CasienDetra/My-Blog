---
date: "2025-06-14T20:26:46+07:00"
draft: true
title: "Setup Tailwind React"
---

# 🌀 Modern Tailwind CSS Configuration with React

Tailwind CSS is a utility-first CSS framework that has become a popular choice for styling React applications. In this guide, we’ll walk through the modern setup for using Tailwind with React in 2025 using tools like **Vite** or **Create React App (CRA)**.

---

## 🛠️ Prerequisites

Before we begin, make sure you have:

- Node.js (v18+ recommended)
- npm or yarn
- A React project set up with either Vite or CRA

---

## ⚡ Option 1: Setting Up Tailwind with Vite (Recommended)

Vite is a fast build tool for modern React development.

### 1. Create a Vite React Project

```bash
npm create vite@latest my-app -- --template react
cd my-app
npm install
2. Install Tailwind CSS and Dependencies

npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

go to index.css file and type @import "tailwindcss";
