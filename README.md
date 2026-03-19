# Portfolio Website

This repository contains my **personal portfolio website** built with HTML, CSS, and modern UI techniques like **glassmorphism** and hover animations. It also serves as a hands-on project to practice **GitHub Actions** and **GitOps-based CI/CD deployment**.

---

## 🚀 Features

- Modern single-page portfolio website
- Glassmorphic UI with interactive hover effects
- Fully responsive design for mobile and desktop
- Automated deployment with **GitHub Actions**
- Continuous updates via **GitOps workflow**

---

## 🛠 Tech Stack

- HTML, CSS
- GitHub Pages (for hosting)
- GitHub Actions (CI/CD workflow)

---

## 📂 GitHub Actions Workflow

The site is automatically deployed via the following GitHub Actions workflow (`.github/workflows/deploy.yml`):

- **Trigger:** Manual trigger via `workflow_dispatch`  
- **Permissions:**  
  - `pages: write` → deploys to GitHub Pages  
  - `id-token: write` → authentication with cloud provider (if needed)  
  - `contents: read` → reads repository contents  
- **Steps:**  
  1. **Checkout Code** – Uses `actions/checkout@v4` to pull the repository code.  
  2. **Setup GitHub Pages** – Configures GitHub Pages deployment using `actions/configure-pages@v4`.  
  3. **Upload Artifact** – Uploads the static website files using `actions/upload-pages-artifact@v4`.  
  4. **Deploy** – Deploys to GitHub Pages with `actions/deploy-pages@v4`.  

This setup follows a **GitOps approach**, meaning every update to the repository automatically triggers a new deployment of the site.

---

## 🌐 Live Demo

You can view the live website here: https://portfolio.techabhi.xyz/  

---

## ⚡ How to Contribute / Test

1. Fork the repository  
2. Make changes to your local branch  
3. Commit and push the changes  
4. Trigger the workflow manually via **Actions → deploy**  
5. Check deployment logs and live preview  

---

## 💡 Learning Outcomes

- Practiced **GitHub Actions CI/CD workflows**  
- Learned **automated deployment to GitHub Pages**  
- Reinforced **GitOps principles**  
- Tested **modern front-end UI design techniques**  

---

## 📧 Contact

- Email: abhibandal33@gmail.com  
- LinkedIn: [linkedin.com/in/abhiraj-bandal-a53014194](https://www.linkedin.com/in/abhiraj-bandal-a53014194)

---

**#GitHubActions #CI_CD #GitOps #DevOps #WebDevelopment #PortfolioWebsite #Automation #FrontendDevelopment #LearningByDoing**
