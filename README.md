
# Pixify



Pixify is an AI-powered image generation platform that allows users to transform their ideas into stunning visuals. Users can generate images using text prompts, manage credits, and make secure payments through Stripe.

---
<img width="1696" height="836" alt="image" src="https://github.com/user-attachments/assets/ed14dc9b-05fb-4aa7-8071-99ce0942a4a0" />

## 🌐 Live Demo [https://pixifyclient.vercel.app](https://pixifyclient.vercel.app) 

---

## 🛠 Tech Stack

### Frontend
- **React** (Vite) – UI framework for building interactive components
- **Tailwind CSS** – Styling and responsive design
- **Vercel** – Deployment platform for frontend
- **Environment Variables**:
  - `VITE_BACKEND_URL` – Backend API URL
  - `VITE_STRIPE_PUBLISHABLE_KEY` – Stripe publishable key

### Backend
- **Node.js + Express.js** – REST API server
- **MongoDB Atlas + Mongoose** – Database for storing users, payments, and usage data
- **Stripe** – Payment processing
- **ClipDrop API** – AI image generation
- **Render** – Deployment platform for backend
- **Environment Variables**:
  - `MONGODB_URI` – MongoDB connection string
  - `JWT_SECRET` – JWT authentication secret
  - `CLIPDROP_API_KEY` – ClipDrop API key
  - `STRIPE_SECRET_KEY` – Stripe secret key

---

## ⚡ Features
- Generate AI-powered images from text prompts
- User authentication with JWT
- Stripe-based credit purchase system
- Responsive UI with Tailwind CSS
- Real-time feedback and image previews

---

## 📦 Installation

### Backend
```bash
cd server
npm install
npm run start
````

### Frontend

```bash
cd client
npm install
npm run dev   # For local development
npm run build # For production
```

---

## 🌍 Deployment

* **Backend** → Deploy to [Render](https://render.com)
* **Frontend** → Deploy to [Vercel](https://vercel.com)
* Set environment variables in respective platforms for security

---

## 🔗 API Endpoints

| Endpoint                      | Method | Description                   |
| ----------------------------- | ------ | ----------------------------- |
| `/api/auth/register`          | POST   | Register a new user           |
| `/api/auth/login`             | POST   | Login and get JWT token       |
| `/api/image/generate-image`   | POST   | Generate AI image from prompt |
| `/api/payment/create-session` | POST   | Create Stripe payment session |

---

## 💡 Usage

1. Visit the live frontend: [Pixify Client](https://pixifyclient.vercel.app)
2. Sign up or log in
3. Purchase credits via Stripe
4. Enter a prompt to generate AI-powered images
5. Download or share your generated images

---

## 📂 Folder Structure

```
Pixify/
├─ client/        # Frontend (React + Vite)
├─ server/        # Backend (Node.js + Express)
├─ .gitignore
├─ package.json
└─ README.md
```

---

## 📄 License

MIT License

---

Made with ❤️ by [ADVAYA1](https://github.com/ADVAYA1)


---

If you want, I can also make a **shorter, visually appealing version with badges** for GitHub that looks professional at first glance.  

Do you want me to do that?
```
