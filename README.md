# DBSight Forgot Password 🔐

Standalone frontend page for handling password reset flow in DBSight.  
Deployed independently on Vercel for simplicity and scalability.

---

## 🧠 What This Does

Provides a minimal UI for users to:
- Request password reset
- Submit reset token
- Set a new password securely

---

## 🛠️ Tech Stack

- React (Vite)
- Tailwind CSS
- Axios
- Vercel (Deployment)

---

## 🔄 Flow

1. User enters email
2. Backend sends reset token via email
3. User opens reset link
4. User sets new password
5. Password updated in backend

---

## ⚙️ Setup

### 1. Clone Repo
```bash
git clone https://github.com/your-username/dbsight-forgot-password.git
cd dbsight-forgot-password
npm install
npm run dev
