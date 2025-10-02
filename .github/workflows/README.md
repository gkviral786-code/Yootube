# 🎬 YouTube Clone (with Auth) - GitHub Ready

This is a **sample project** like YouTube built with:
- **Backend** → Node.js (Express, SQLite, JWT, FFmpeg)
- **Frontend** → Next.js (React, video.js)
- **Features**:
  - User Signup/Login (JWT Auth)
  - Upload video (only logged in users)
  - Convert to HLS with FFmpeg
  - Video list with players

---

## 🚀 Setup Instructions

### Backend (Express + SQLite)
```bash
cd backend
npm install
npm start
```
> Make sure **FFmpeg** is installed on your system.

### Frontend (Next.js + video.js)
```bash
cd frontend
npx create-next-app .
npm install video.js
npm run dev
```

---

## 🌐 Usage
- Open `http://localhost:3000/signup` → Create new account  
- Open `http://localhost:3000/login` → Login (stores token in browser localStorage)  
- Open `http://localhost:3000/upload` → Upload video (title + file)  
- Open `http://localhost:3000/` → Watch uploaded videos  

---

## 📌 Notes
- `.gitignore` is included (so node_modules & DB won’t be pushed).
- Replace `SECRET` in backend with environment variable for production.
- Use HTTPS in production.

---

## 🇵🇰 اردو میں ہدایات

1. Backend چلانے کے لیے:
   - `cd backend`
   - `npm install`
   - `npm start`  
   ⚠️ شرط: FFmpeg انسٹال ہونا چاہیے۔

2. Frontend چلانے کے لیے:
   - `cd frontend`
   - `npx create-next-app .`
   - `npm install video.js`
   - `npm run dev`

3. پھر اپنے براوزر میں:
   - `/signup` → سائن اپ کریں
   - `/login` → لاگ ان کریں
   - `/upload` → ویڈیو اپلوڈ کریں
   - `/` → ویڈیو لسٹ دیکھیں

---

## 📂 GitHub Upload
```bash
cd my-youtube-clone-github-ready
git init
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git
git add .
git commit -m "Initial commit - YouTube Clone with Auth"
git push -u origin main
```
