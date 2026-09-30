# Findora AI — Campus Lost & Found Platform

Findora AI is a full-stack web application designed to automate lost-and-found operations across college campuses. It combines user verification, item registration, media storage, and automated notification workflows.

---

## 🌟 Key Features

* 🔐 **Secure Authentication:** User signup & login using JWT tokens and Bcrypt password hashing.
* 📸 **Image Upload Handling:** Seamless file upload integration backed by Cloudinary and Multer.
* 📧 **Automated Notifications:** Email alerts dispatched via Nodemailer when matches are identified.
* 📊 **Dashboard & Metrics:** Interactive statistics powered by Recharts.
* 🎨 **Responsive Interface:** Modern, clean UI built with React 19, Vite, and Tailwind CSS v4.

---

## 🛠️ Tech Stack

* **Frontend:** React 19, Vite, Tailwind CSS v4, Lucide React, Recharts
* **Backend:** Node.js, Express.js (v5)
* **Database:** SQLite / PostgreSQL
* **Cloud Services:** Cloudinary, Nodemailer, BcryptJS, JWT

---

## 🚀 Getting Started

### Prerequisites
* Node.js (v18 or higher)
* npm (v9 or higher)

### Environment Setup
Create a `.env` file in the `backend/` directory based on `.env.example`:

```env
PORT=5000
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

### Installation & Running

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Tamilselvan3660/findora-ai.git
   cd findora-ai
   ```

2. **Install & Run Backend:**
   ```bash
   cd backend
   npm install
   npm start
   ```

3. **Install & Run Frontend:**
   ```bash
   cd ../frontend
   npm install
   npm run dev
   ```

---

## 👤 Author

* **Tamilselvan** — [@Tamilselvan3660](https://github.com/Tamilselvan3660)
* Email: [selvantamil84786@gmail.com](mailto:selvantamil84786@gmail.com)
