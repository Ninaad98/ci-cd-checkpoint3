# CI/CD Checkpoint 3

This repository demonstrates a complete **CI/CD pipeline** using GitHub Actions:
- ✅ Linting & formatting checks
- ✅ Unit tests with coverage
- ✅ Automated build
- ✅ Security audit (scheduled)
- ✅ Deployment to GitHub Pages

---

## 🚀 Live Demo
Once the deployment finishes, the site will be live here:  
👉 [View Website](https://Ninaad98.github.io/ci-cd-checkpoint3/)

---

## 📊 Workflow Status

![CI Pipeline](https://github.com/Ninaad98/ci-cd-checkpoint3/actions/workflows/ci.yml/badge.svg)
![Deploy](https://github.com/Ninaad98/ci-cd-checkpoint3/actions/workflows/pages.yml/badge.svg)
![Dependency Audit](https://github.com/Ninaad98/ci-cd-checkpoint3/actions/workflows/scheduled-audit.yml/badge.svg)

---

## 📦 Workflows
- **CI Pipeline (`ci.yml`)** → Runs on pushes/PRs to `main` & `develop`. Lints, formats, tests, builds.  
- **Deploy (`pages.yml`)** → Publishes the `dist/` folder to GitHub Pages on every push to `main`.  
- **Daily Dependency Audit (`scheduled-audit.yml`)** → Runs nightly to check for vulnerabilities.  
