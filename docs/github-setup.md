# GitHub Repository Setup Instructions

Follow these steps to create and push your portfolio to GitHub:

## Step 1: Create GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon in the top right → "New repository"
3. Repository name: `<your-id>-<your-name>-assignment1`
   - Example: `202012345-fahad-alqahtani-assignment1`
4. Description: "Personal portfolio website for SWE363 Assignment 1"
5. Select: **Public** (required for submission)
6. Do NOT initialize with README (we already have one)
7. Click "Create repository"

## Step 2: Initialize Git (First Time Setup)

Open PowerShell in your project directory and run:

```powershell
# Navigate to project directory
cd "c:\Users\fahad\Desktop\SWE363 - Assignment 1"

# Initialize git repository
git init

# Configure git (if not done before)
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

## Step 3: Add and Commit Files

```powershell
# Add all files to git
git add .

# Create first commit
git commit -m "Initial commit: Complete portfolio website with all features"
```

## Step 4: Push to GitHub

Replace `<username>` and `<repository-name>` with your actual values:

```powershell
# Link to GitHub repository
git remote add origin https://github.com/<username>/<repository-name>.git

# Push to GitHub
git branch -M main
git push -u origin main
```

Example:
```powershell
git remote add origin https://github.com/johndoe/202012345-john-doe-assignment1.git
git branch -M main
git push -u origin main
```

## Step 5: Deploy to GitHub Pages (Optional)

1. Go to your repository on GitHub
2. Click "Settings" tab
3. Scroll down to "Pages" in left sidebar
4. Under "Source", select "main" branch
5. Click "Save"
6. Wait 1-2 minutes
7. Your site will be live at: `https://<username>.github.io/<repository-name>/`

## Step 6: Update README with Live Link

After deployment, add the live link to your README.md:

```markdown
## 🌐 Live Demo

View the live website: [https://your-username.github.io/repository-name/](https://your-username.github.io/repository-name/)
```

Then commit and push:

```powershell
git add README.md
git commit -m "Add live demo link"
git push
```

## Step 7: Verify Submission

Before submitting on Blackboard, verify:

- ✅ Repository is public
- ✅ All files are uploaded
- ✅ README.md displays correctly
- ✅ Folder structure matches requirements
- ✅ GitHub Pages is deployed (optional)
- ✅ Repository name follows format: `id-name-assignment1`

## Common Git Commands for Updates

```powershell
# Check status
git status

# Add specific file
git add filename.html

# Add all changes
git add .

# Commit changes
git commit -m "Description of changes"

# Push to GitHub
git push

# View commit history
git log --oneline
```

## Troubleshooting

### Issue: Git not recognized
**Solution**: Install Git from [git-scm.com](https://git-scm.com)

### Issue: Authentication error
**Solution**: Use Personal Access Token instead of password
1. Go to GitHub Settings → Developer settings → Personal access tokens
2. Generate new token with "repo" scope
3. Use token as password when pushing

### Issue: Repository already exists
**Solution**: Remove and re-add remote
```powershell
git remote remove origin
git remote add origin https://github.com/username/repo.git
```

## Alternative: GitHub Desktop (GUI)

If you prefer a graphical interface:

1. Download [GitHub Desktop](https://desktop.github.com)
2. Install and sign in to GitHub
3. Click "Add" → "Add Existing Repository"
4. Select your project folder
5. Click "Publish repository"
6. Ensure "Keep this code private" is UNCHECKED
7. Click "Publish Repository"

## Final Checklist

Before submission:

- [ ] Repository created with correct name format
- [ ] All files committed and pushed
- [ ] Repository is public (not private)
- [ ] README.md is complete and displays properly
- [ ] All documentation files are included
- [ ] GitHub Pages deployed (optional but recommended)
- [ ] Repository link copied for Blackboard submission

## Submit on Blackboard

1. Copy your repository URL: `https://github.com/username/repository-name`
2. Go to Blackboard → SWE363 → Assignment 1
3. Paste the repository link
4. Add comment (optional): "Deployed at: <github-pages-url>"
5. Submit

---

**Congratulations!** Your portfolio is now on GitHub and ready for submission! 🎉
