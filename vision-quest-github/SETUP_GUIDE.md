# 🚀 GitHub Setup Guide

Follow these steps to upload your Vision Quest project to GitHub:

## Method 1: Using GitHub Website (Easiest)

### Step 1: Create a New Repository
1. Go to [GitHub](https://github.com)
2. Click the **+** icon in the top right
3. Select **New repository**
4. Fill in the details:
   - **Repository name**: `vision-quest` (or any name you prefer)
   - **Description**: "Interactive eye health dashboard based on data-driven insights"
   - Choose **Public** or **Private**
   - ✅ Check "Add a README file" (you'll replace it with ours)
   - **License**: MIT License
5. Click **Create repository**

### Step 2: Upload Your Files
1. In your new repository, click **Add file** → **Upload files**
2. Drag and drop these files from the project folder:
   - `index.html`
   - `README.md`
   - `.gitignore`
   - `LICENSE` (if you didn't select it during creation)
3. Write a commit message: "Initial commit - Vision Quest project"
4. Click **Commit changes**

### Step 3: Enable GitHub Pages (Optional - for live demo)
1. Go to **Settings** in your repository
2. Click **Pages** in the left sidebar
3. Under "Source", select **main** branch
4. Click **Save**
5. Your site will be live at: `https://yourusername.github.io/vision-quest/`

## Method 2: Using Git Command Line

### Step 1: Initialize Git
```bash
cd vision-quest-project
git init
```

### Step 2: Create Repository on GitHub
1. Go to [GitHub](https://github.com)
2. Create a new repository (don't initialize with README)
3. Copy the repository URL

### Step 3: Connect and Push
```bash
# Add all files
git add .

# Commit
git commit -m "Initial commit - Vision Quest eye health dashboard"

# Add remote (replace with your URL)
git remote add origin https://github.com/yourusername/vision-quest.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 4: Enable GitHub Pages
```bash
# Your repository is now on GitHub!
# Follow Step 3 from Method 1 to enable GitHub Pages
```

## Method 3: Using GitHub Desktop (User-Friendly)

### Step 1: Install GitHub Desktop
- Download from [desktop.github.com](https://desktop.github.com)

### Step 2: Create Repository
1. Open GitHub Desktop
2. Click **File** → **New Repository**
3. Fill in:
   - **Name**: vision-quest
   - **Local Path**: Choose where to save
   - **Git Ignore**: None
   - **License**: MIT
4. Click **Create Repository**

### Step 3: Add Files
1. Copy your project files to the repository folder
2. GitHub Desktop will detect changes
3. Write commit message: "Initial commit"
4. Click **Commit to main**
5. Click **Publish repository** to push to GitHub

### Step 4: Enable GitHub Pages
- Follow Step 3 from Method 1

## 📝 Your Repository URL Format

After creation, your repository will be accessible at:
- **Repository**: `https://github.com/yourusername/vision-quest`
- **Live Site** (if Pages enabled): `https://yourusername.github.io/vision-quest/`

## 🎯 Quick Checklist

- [ ] Create GitHub repository
- [ ] Upload all project files
- [ ] Enable GitHub Pages (optional)
- [ ] Test the live site
- [ ] Share your repository URL!

## 🔧 Updating Your Project Later

### Using GitHub Website:
1. Go to your repository
2. Click on the file you want to edit
3. Click the pencil icon (Edit)
4. Make changes
5. Commit changes at the bottom

### Using Git Command Line:
```bash
# Make changes to your files
git add .
git commit -m "Description of changes"
git push
```

## 💡 Tips

1. **Make it stand out**: Add a screenshot to your README
2. **Add topics**: In repository settings, add topics like `eye-health`, `data-visualization`, `javascript`
3. **Write good commits**: Describe what you changed, not how
4. **Use branches**: For major changes, create a feature branch

## 🆘 Need Help?

- [GitHub Docs](https://docs.github.com)
- [GitHub Pages Guide](https://pages.github.com)
- [Git Basics](https://git-scm.com/book/en/v2/Getting-Started-Git-Basics)

---

Good luck with your project! 🎉
