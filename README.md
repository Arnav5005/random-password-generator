# 🔐 Random Password Generator (React)

A simple and interactive random password generator built using React.  
Users can generate passwords by selecting length, numbers, and special characters, with an easy copy-to-clipboard feature.

---

## 🚀 Features

- Adjustable password length (8–20)
- Toggle numbers inclusion
- Toggle special characters inclusion
- Auto-generates password on option change
- One-click copy to clipboard
- Built using modern React Hooks

---

## 🛠️ Tech Stack

- React
- JavaScript (ES6+)
- CSS / Tailwind utility classes

### React Hooks Used
- `useState`
- `useCallback`
- `useEffect`
- `useRef`

---

## 🧠 How It Works

- `Math.random()` generates a random number between **0 (inclusive)** and **1 (exclusive)**
- The random value is scaled based on the selected character set
- Password updates automatically whenever options change

---

## 📂 Project Structure

PASSWORD-GENERATOR/
└── random-password-generator/
├── node_modules/
├── public/
├── src/
│ ├── assets/
│ ├── App.css
│ ├── App.jsx
│ └── main.jsx
├── .gitignore
├── eslint.config.js
├── index.html
├── package-lock.json
├── package.json
├── vite.config.js
├── LICENSE
└── README.md

---

## ▶️ Run Locally

```bash
git clone https://github.com/your-username/random-password-generator.git
cd random-password-generator
npm install
npm run dev
