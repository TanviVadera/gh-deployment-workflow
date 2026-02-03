 GitHub Pages Deployment using GitHub Actions 🚀

This project demonstrates how to automatically deploy a static website (`index.html`) to **GitHub Pages** using **GitHub Actions**.

The deployment workflow is configured to run **only when `index.html` is changed** on the `main` branch.

---

## 📌 Project Overview

- Repository Name: `gh-deployment-workflow`
- Website Type: Static HTML
- Deployment Tool: GitHub Actions
- Hosting Platform: GitHub Pages

---


## ⚙️ How the Workflow Works

1. A change is made to `index.html`
2. Code is pushed to the `main` branch
3. GitHub Actions workflow is triggered
4. The workflow:
   - Checks out the repository
   - Configures GitHub Pages
   - Uploads website files
   - Deploys the site to GitHub Pages
5. The website goes live automatically

---

## 🔄 Workflow Trigger Condition

The workflow runs **only when**:

- A push is made to the `main` branch  
- The `index.html` file is modified  

This is controlled using the `paths` filter in the workflow.

---

## 🔐 Required Permissions

The workflow uses the following permissions:

- `contents: read` → Read repository files
- `pages: write` → Deploy to GitHub Pages
- `id-token: write` → Secure authentication for deployment

---

## 🌍 Live Website

The website is available at:

https://tanvivadera.github.io/gh-deployment-workflow/


GitHub Pages URLs follow this format:

https://<username>.github.io/<repository-name>/


---

## 🧪 How to Test Deployment

1. Edit `index.html`
2. Commit and push changes to `main`
3. Go to the **Actions** tab and verify the workflow runs successfully
4. Refresh the GitHub Pages URL to see updates

---

## 🛠 Technologies Used

- HTML
- GitHub Actions
- GitHub Pages
- Git

---

## ✅ Learning Outcomes

- Understand GitHub Actions workflows
- Learn conditional workflow triggers
- Deploy a static website automatically
- Gain hands-on CI/CD experience

---

## 📄 License

This project is for learning and practice purposes.
