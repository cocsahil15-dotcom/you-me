# 💕 I Love You Heart — Deploy to Railway

## Deploy in 3 steps

### 1. Push to GitHub
```bash
git init
git add .
git commit -m "love heart app"
git remote add origin https://github.com/YOUR_USERNAME/loveheart.git
git push -u origin main
```

### 2. Deploy on Railway
1. Go to [railway.app](https://railway.app) and sign in
2. Click **New Project** → **Deploy from GitHub repo**
3. Select your repo — Railway auto-detects Python and deploys!
4. Your app goes live at a URL like `https://loveheart-production.up.railway.app`

### 3. Done! 🎉
Share the URL with your love 💌

---

## Local run
```bash
pip install -r requirements.txt
python app.py
```
Open `http://localhost:5001`
