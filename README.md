# 🔐 Password Generator App

[![GitHub Pages](https://img.shields.io/badge/Live%20Demo-Click%20Here-blue?logo=github)](https://pedri-8.github.io/password-generator-app)

A modern password generator built using React, Vite, and Tailwind CSS. Easily generate strong, customizable passwords with options for length, numbers, and symbols.

---

## 🚀 Features

- Adjustable password length (6–100 characters)
- Option to include numbers and special characters
- Copy to clipboard functionality
- Responsive design with Tailwind CSS
- Deployable on GitHub Pages

---

## 🛠 Tech Stack

- React (via Vite)
- Tailwind CSS
- GitHub Pages for deployment

---

## 💻 Getting Started

```bash
git clone https://github.com/Pedri-8/password-generator-app.git
cd password-generator-app
npm install
npm run dev
```

---

## 🌐 Deployment

```bash
npm run build
npm run deploy
```

Ensure your `vite.config.js` contains:

```js
export default defineConfig({
  base: '/password-generator-app/',
  plugins: [react()],
})
```

---

## 🔗 Live Demo

👉 https://pedri-8.github.io/password-generator-app

---

## 🙌 Credits

Based on the [Chai aur React](https://github.com/hiteshchoudhary/chai-aur-react/tree/main/05passwordGenerator) series by [Hitesh Choudhary](https://github.com/hiteshchoudhary).  
Customized and deployed by [Snehashis (Pedri-8)](https://github.com/Pedri-8).

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
