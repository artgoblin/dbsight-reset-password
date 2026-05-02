# DBSight Forgot Password 🔐

Standalone frontend page for handling password reset flow in DBSight.  
Deployed independently on Vercel for simplicity and scalability.

---
#Demo


https://github.com/user-attachments/assets/b64fb8d0-c6c7-4751-824c-32069ea1fff8

[screen-capture (1).webm](https://github.com/user-attachments/assets/ff78da88-b28d-4477-94a4-c97282eec494)

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
