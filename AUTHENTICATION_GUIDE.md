# 🔐 GitHub Authentication Guide

GitHub requires a **Personal Access Token** (PAT) instead of a password for pushing code.

## Quick Steps to Create a Token:

### Step 1: Create Personal Access Token

1. Go to GitHub.com and **sign in**
2. Click your **profile picture** (top right)
3. Click **"Settings"**
4. Scroll down and click **"Developer settings"** (left sidebar, at the bottom)
5. Click **"Personal access tokens"** → **"Tokens (classic)"**
6. Click **"Generate new token"** → **"Generate new token (classic)"**
7. Fill in:
   - **Note**: "Portfolio Website" (or anything you want)
   - **Expiration**: Choose "90 days" or "No expiration" (your choice)
   - **Scopes**: Check **`repo`** (this gives full repository access)
8. Click **"Generate token"** at the bottom
9. **⚠️ IMPORTANT**: Copy the token immediately! It looks like: `ghp_xxxxxxxxxxxxxxxxxxxx`
   - You won't be able to see it again!

### Step 2: Use the Token to Push

When you run `git push`, it will ask for:
- **Username**: `AmineLaz10` (your GitHub username)
- **Password**: Paste your **Personal Access Token** (not your GitHub password!)

---

## Alternative: Use GitHub CLI (Easier!)

If you prefer, you can install GitHub CLI which handles authentication automatically:

```bash
# Install GitHub CLI (if not installed)
brew install gh

# Authenticate
gh auth login

# Then push normally
git push -u origin main
```

---

## Ready to Push?

Once you have your token, I'll help you push the code!

