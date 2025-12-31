# Push README to GitHub - Quick Guide

## ✅ What's Done
- Created local folder: `C:\Users\user\Downloads\Github\nishika25-ta`
- Copied README file
- Initialized Git repository
- Committed the README

## 🚀 Next Steps

### Step 1: Create Repository on GitHub

1. Open your browser and go to: **https://github.com/login**
2. Sign in to your GitHub account (`nishika25-ta`)
3. Click the **"+"** icon in the top right corner
4. Click **"New repository"**

### Step 2: Repository Settings

Fill in these details:
- **Repository name**: `nishika25-ta` ⚠️ Must match your username exactly!
- **Description**: "Config files for my GitHub Profile"  
- **Visibility**: ✅ **Public** (very important!)
- **Initialize repository**: ❌ Leave ALL checkboxes UNCHECKED
  - Don't add README
  - Don't add .gitignore
  - Don't choose a license

Click **"Create repository"**

### Step 3: Push Your Code

After creating the repository, GitHub will show you commands. **OR** just run these commands:

```powershell
cd C:\Users\user\Downloads\Github\nishika25-ta

git remote add origin https://github.com/nishika25-ta/nishika25-ta.git

git push -u origin main
```

### Step 4: Verify

1. Go to: `https://github.com/nishika25-ta/nishika25-ta`  
2. You should see your README in the repository

3. Go to: `https://github.com/nishika25-ta`  
4. Your profile README should now be visible! 🎉

---

## 🔐 Authentication Notes

If Git asks for credentials:
- **Username**: `nishika25-ta`
- **Password**: You'll need a **Personal Access Token** (not your regular password)

### To create a Personal Access Token:
1. GitHub → Settings → Developer settings → Personal access tokens → Tokens (classic)
2. Generate new token
3. Select scope: `repo` (full control)
4. Copy the token and use it as your password

---

## 🆘 Need Help?

Let me know when you've created the repository and I'll help you push it!
