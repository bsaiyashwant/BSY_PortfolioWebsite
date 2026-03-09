---
description: How to host the portfolio on Vercel
---

Follow these steps to deploy your portfolio to Vercel:

1. **Push to GitHub**:
   - Create a new repository on GitHub.
   - Run these commands in your project folder:
     ```bash
     git init
     git add .
     git commit -m "initial commit"
     git branch -M main
     git remote add origin YOUR_GITHUB_REPO_URL
     git push -u origin main
     ```

2. **Connect to Vercel**:
   - Go to [vercel.com](https://vercel.com) and sign up with your GitHub account.
   - Click "Add New" > "Project".
   - Find your portfolio repository and click "Import".

3. **Configure & Deploy**:
   - Vercel will automatically detect that this is a static project.
   - Click "Deploy".
   - Your site will be live on a `vercel.app` domain in seconds! 🚀

4. **Continuous Deployment**:
   - Every time you push a change to GitHub, Vercel will automatically update your live site.
