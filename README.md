# 💌 LoveChat App

A simple **real-time one-to-one chat application** built with modern web technologies.
This project is designed as a beginner-friendly yet functional chat platform where users can send and receive messages instantly.

---

## 🚀 Features

* 🔐 **User Authentication** (Firebase Auth)
* 💬 **One-to-One Real-time Messaging**
* ⚡ **Firebase Firestore Database** for storing chats
* 🎨 **Modern UI** built with Vite + TailwindCSS
* 📱 **Responsive Design** – works on both mobile and desktop

---

## 🛠️ Tech Stack

* **Frontend:** Vite, React (or plain JS if you didn’t use React), TailwindCSS
* **Backend/Database:** Firebase Firestore
* **Authentication:** Firebase Auth
* **Hosting:** Firebase Hosting (optional)

---

## 📂 Project Structure

```
LoveChat-app/
│── public/        # Static assets
│── src/           # Main application code
│   ├── components/ # UI components
│   ├── pages/      # App pages
│   └── utils/      # Helper functions
│── index.html     # Entry point
│── package.json   # Dependencies & scripts
│── vite.config.js # Vite configuration
│── firebase.json  # Firebase configuration
```

---

## ⚡ Getting Started

### 1️⃣ Clone the repository

```bash
git clone https://github.com/ayu-haker/LoveChat-app.git
cd LoveChat-app
```

### 2️⃣ Install dependencies

```bash
npm install
```

### 3️⃣ Setup Firebase

* Go to [Firebase Console](https://console.firebase.google.com/)
* Create a new project
* Enable **Authentication** (Email/Password or Google Sign-In)
* Enable **Firestore Database**
* Copy your Firebase config and replace it in your project (`src/firebase.js` or similar file)

### 4️⃣ Run the app locally

```bash
npm run dev
```

### 5️⃣ Build for production

```bash
npm run build
```

---

## 📸 Screenshots (Optional)

> *(You can add screenshots or a demo GIF of your app here)*

---

## 🌐 Live Demo

👉 \[Your Deployed Link Here]

---

## 🤝 Contributing

Pull requests are welcome! If you’d like to contribute, fork the repo and submit a PR.

---

## 📜 License

This project is licensed under the **MIT License** – feel free to use and modify.

---
