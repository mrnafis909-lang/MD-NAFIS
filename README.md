# 🧵 MD-NAFIS Textile Color Agent

A simple, web-based AI agent to create multiple **color tone variations** of your textile design instantly.

---

## 🚀 Deploy on Render (Recommended)

### Step-by-Step Setup

1. Go to 👉 [Render.com](https://render.com)
2. Create a **free account** or log in.
3. Click **New + → Web Service**
4. Choose **“Deploy from GitHub”**
5. Connect your GitHub account and select this repo.
6. Set the following options:

   - **Build Command:** `pip install -r backend/requirements.txt`
   - **Start Command:** `uvicorn backend.app:app --host=0.0.0.0 --port=$PORT`

7. Click **Deploy** 🎉

After 1–2 minutes, your Textile Color Agent will be live!

---

## 💻 Local Test (Optional)

1. Open terminal:
   ```bash
   pip install -r backend/requirements.txt
   uvicorn backend.app:app --reload
   ```
2. Open `frontend/index.html` in your browser.

---

## 📂 How to Use

- Upload your textile design (.jpg / .png).
- It automatically creates 6 random color tone variations.
- You can download or preview them instantly.

---

## ✨ Example Workflow

| Step | Action | Result |
|------|---------|---------|
| 1 | Upload design | Preview loads |
| 2 | Click “Generate Variations” | 6 tone versions appear |
| 3 | Save the best for client | Done ✅ |

---

**Author:** MD NAFIS  
**Purpose:** For textile digital print designers to generate fast color variations without Photoshop or GPU.
