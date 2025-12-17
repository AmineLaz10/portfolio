# Complete Guide: Hosting Your Portfolio on GitHub Pages

This guide will walk you through hosting your portfolio website on GitHub Pages (github.io) from scratch.

## Prerequisites

✅ Git is installed (we checked - you have it!)
✅ A GitHub account (we'll help you create one if needed)

---

## Step 1: Create a GitHub Account (if you don't have one)

1. Go to [github.com](https://github.com)
2. Click **"Sign up"** in the top right
3. Enter your email, create a password, and choose a username
4. Verify your email address when prompted

---

## Step 2: Initialize Git in Your Project

I'll help you do this automatically, but here's what happens:

```bash
git init                    # Initialize git repository
git add .                   # Add all files
git commit -m "Initial commit"  # Save your files
```

---

## Step 3: Create a New Repository on GitHub

1. **Log in to GitHub** at [github.com](https://github.com)

2. **Click the "+" icon** in the top right corner
   - Select **"New repository"**

3. **Fill in the repository details:**
   - **Repository name**: `portfolio` (or `yourname.github.io` - see note below)
   - **Description**: "My data science portfolio website" (optional)
   - **Visibility**: Choose **Public** (required for free GitHub Pages)
   - **DO NOT** check "Initialize with README" (we already have files)
   - **DO NOT** add .gitignore or license (we already have them)

4. **Click "Create repository"**

### ⚠️ Important Note About Repository Name:

- **Option 1**: Name it `yourusername.github.io` (replace `yourusername` with your GitHub username)
  - Your site will be at: `https://yourusername.github.io`
  - This is the simplest option!

- **Option 2**: Name it `portfolio` (or anything else)
  - Your site will be at: `https://yourusername.github.io/portfolio`
  - You'll need to configure the base path

**I recommend Option 1** for the cleanest URL!

---

## Step 4: Connect Your Local Project to GitHub

After creating the repository, GitHub will show you commands. But I'll prepare everything for you!

You'll need to run these commands (I'll help you):

```bash
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git branch -M main
git push -u origin main
```

Replace `YOUR_USERNAME` and `YOUR_REPO_NAME` with your actual values.

---

## Step 5: Enable GitHub Pages

1. **Go to your repository** on GitHub
2. Click on **"Settings"** (top menu bar)
3. Scroll down to **"Pages"** in the left sidebar
4. Under **"Source"**, select:
   - **Branch**: `main`
   - **Folder**: `/ (root)`
5. Click **"Save"**

---

## Step 6: Access Your Live Website

After a few minutes (usually 1-2 minutes), your site will be live at:

- If you named it `yourusername.github.io`: `https://yourusername.github.io`
- If you named it something else: `https://yourusername.github.io/repository-name`

You'll see a green checkmark when it's ready!

---

## Step 7: Making Updates

Whenever you want to update your website:

1. Make changes to your files
2. Run these commands:

```bash
git add .
git commit -m "Update portfolio"
git push
```

Your changes will appear on your live site in 1-2 minutes!

---

## Troubleshooting

### Site not showing up?
- Wait 2-3 minutes (GitHub needs time to build)
- Check Settings → Pages to ensure it's enabled
- Make sure your repository is Public

### Getting authentication errors?
- You might need to use a Personal Access Token instead of password
- Or use GitHub Desktop (easier for beginners)

### Want to use a custom domain?
- Go to Settings → Pages
- Add your custom domain in the "Custom domain" section

---

## Next Steps

1. ✅ I'll initialize git for you
2. ✅ You create the GitHub repository
3. ✅ I'll help you push your code
4. ✅ You enable GitHub Pages
5. 🎉 Your site goes live!

Let me know when you've created your GitHub account and repository, and I'll help you push the code!

