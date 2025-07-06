# Melongram 🍈

A modern, full-stack real-time chat application built with React, Node.js, Express, MongoDB, and Socket.io. Features authentication, theming, and image upload with Cloudinary.

## 🚀 Live Demo

👉 [Try Melongram Live](https://melongram-gw2c.onrender.com/)

---

## Features

- Real-time chat with Socket.io
- User authentication (JWT, cookies)
- Profile and settings management
- Responsive, modern UI (React + Tailwind CSS + DaisyUI)
- Image upload via Cloudinary
- Light/dark theme support
- Skeleton loading states

## Tech Stack

- **Frontend:** React, Vite, Tailwind CSS, DaisyUI
- **Backend:** Node.js, Express, Socket.io
- **Database:** MongoDB (Mongoose)
- **Image Hosting:** Cloudinary

## Getting Started

### Prerequisites

- Node.js (v18+ recommended)
- MongoDB Atlas account
- Cloudinary account

### Installation

1. **Clone the repository:**

   ```sh
   git clone https://github.com/xpress-dev/melongram.git
   cd melongram
   ```

2. **Setup environment variables:**

   - Copy `.env.example` to `.env` in the `backend` folder and fill in your credentials.

3. **Install dependencies:**

   ```sh
   cd backend && npm install
   cd ../frontend && npm install
   ```

4. **Run the app locally:**
   - Start backend:
     ```sh
     cd backend
     npm run dev
     ```
   - Start frontend (in a new terminal):
     ```sh
     cd frontend
     npm run dev
     ```
   - Visit [http://localhost:5173](http://localhost:5173)

## Folder Structure

```
backend/
  src/
    controllers/
    lib/
    middleware/
    models/
    routes/
    seeds/
frontend/
  src/
    components/
    constants/
    lib/
    pages/
    store/
```

## Environment Variables

See `backend/.env.example` for required variables:

- `MONGODB_URI`
- `PORT`
- `JWT_SECRET`
- `CLOUDINARY_CLOUD_NAME`
- `CLOUDINARY_API_KEY`
- `CLOUDINARY_API_SECRET`

## License

This project is licensed under the MIT License.

---

Made with ❤️ by xpress-dev
