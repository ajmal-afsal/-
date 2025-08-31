# 📂 File Store Bot (Clone)

A Telegram File Store Bot built with **Pyrogram**.

## 🚀 Deployment

### Railway
1. Fork this repo.
2. Go to [Railway](https://railway.app) → Create New Project → Deploy from GitHub.
3. Add these environment variables:
   - API_ID
   - API_HASH
   - BOT_TOKEN
   - ARCHIVE_CHANNEL
   - OWNER_ID
4. Deploy → Done ✅

### Heroku
1. Fork this repo.
2. Go to [Heroku](https://dashboard.heroku.com) → New App → Connect GitHub.
3. Add Config Vars in Settings:
   - API_ID
   - API_HASH
   - BOT_TOKEN
   - ARCHIVE_CHANNEL
   - OWNER_ID
4. Deploy branch → Done ✅

## 🛠 Run Locally
```bash
pip install -r requirements.txt
python infileStore_bot_full_code.py

---

## 3. Deploy Anywhere

### 🚀 On **Railway**
- Best option (free tier, persistent storage).
- After linking repo, just add variables and deploy.

### 🚀 On **Heroku**
- Easy, but storage resets on redeploy (your DB is wiped).
- Use only for testing unless you connect an external DB (like MongoDB).

### 🚀 On **VPS / Local**
```bash
git clone https://github.com/YOUR_USERNAME/FileStoreBot.git
cd FileStoreBot
pip install -r requirements.txt
python infileStore_bot_full_code.py
