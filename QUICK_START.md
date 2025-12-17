# 🚀 Quick Start: Get Your Portfolio Online in 5 Steps

Your files are ready! Follow these simple steps:

---

## ✅ Step 1: Create GitHub Account (if needed)

1. Go to **https://github.com**
2. Click **"Sign up"**
3. Create your account

---

## ✅ Step 2: Create New Repository

1. After logging in, click the **"+"** icon (top right)
2. Click **"New repository"**
3. Fill in:
   - **Name**: `aminelazrak.github.io` (use YOUR username!)
   - **Visibility**: Select **Public** ✅
   - **DO NOT** check any boxes (README, .gitignore, license)
4. Click **"Create repository"**

---

## ✅ Step 3: Copy Your Repository URL

After creating, GitHub will show you a page. Look for a URL like:
```
https://github.com/aminelazrak/aminelazrak.github.io.git
```

**Copy this URL** - you'll need it in the next step!

---

## ✅ Step 4: Connect and Push Your Code

Open Terminal (or this terminal) and run these commands:

**Replace `YOUR_USERNAME` with your actual GitHub username!**

```bash
cd /Users/aminelazrak/Desktop/Portfolio
git remote add origin https://github.com/YOUR_USERNAME/YOUR_USERNAME.github.io.git
git push -u origin main
```

**Example** (if your username is `aminelazrak`):
```bash
git remote add origin https://github.com/aminelazrak/aminelazrak.github.io.git
git push -u origin main
```

You'll be asked for your GitHub username and password (or token).

---

## ✅ Step 5: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **"Settings"** (top menu)
3. Click **"Pages"** (left sidebar)
4. Under **"Source"**:
   - Select **Branch**: `main`
   - Select **Folder**: `/ (root)`
5. Click **"Save"**

---

## 🎉 Done! Your Site is Live!

Wait 1-2 minutes, then visit:
**https://YOUR_USERNAME.github.io**

Example: `https://aminelazrak.github.io`

---

## 💡 Need Help?

- **Authentication issues?** GitHub might ask for a Personal Access Token instead of password
- **Site not showing?** Wait 2-3 minutes, GitHub needs time to build
- **Want to update?** Just edit files, then run:
  ```bash
  git add .
  git commit -m "Update portfolio"
  git push
  ```

---

## 📝 What I've Already Done For You:

✅ Initialized Git repository
✅ Added all your files
✅ Created initial commit
✅ Set branch to "main"
✅ Created this guide

**You just need to:**
1. Create GitHub account (if needed)
2. Create repository
3. Run the `git remote` and `git push` commands
4. Enable GitHub Pages

Good luck! 🚀

