# 🔢 Simple Calculator Web App with CI/CD (GitHub Actions + Pages)

A lightweight **calculator web app** built using **HTML** with inline CSS and JavaScript.
The project is integrated with **GitHub Actions** to enable automatic deployment to **GitHub Pages** whenever changes are pushed to the repository.

---

## 🚀 Features
- Perform **basic arithmetic operations**: Addition, Subtraction, Multiplication, Division
- **Calculate button** → enter numbers, choose operation, then calculate
- **Clear button** → reset inputs and results
- Minimal UI with a clean design
- Fully automated **CI/CD pipeline** using GitHub Actions

---

## 🛠️ Tech Stack
- **Frontend**: HTML (with inline CSS & JavaScript)
- **CI/CD**: GitHub Actions
- **Hosting**: GitHub Pages

---

## ⚙️ CI/CD Workflow
The project uses GitHub Actions to automatically deploy on every push to the `main` branch.

Workflow steps:
1. Checkout repository
2. Configure GitHub Pages
3. Upload project files
4. Deploy to GitHub Pages

Workflow file: [`.github/workflows/deploy.yml`](https://github.com/harsh-ydv8/calculator-ci-cd/blob/main/.github/workflows/deploy.yml)

---

## 🌐 Live Demo
👉 [Calculator App Live Here](https://harsh-ydv8.github.io/calculator-ci-cd/)

---

## 📸 Demo Preview
<img width="2559" height="1599" alt="image" src="https://github.com/user-attachments/assets/95d620dd-d4cb-428e-abba-73d01460ee30" />

---

## 📂 Project Structure
---
```
calculator-ci-cd/
├── index.html
├── .github/
│   └── workflows/
│       └── deploy.yml
└── README.md
```
---

## 📝 How to Run Locally
1. Clone this repo:
   ```bash
   git clone [https://github.com/harsh-ydv8/calculator-ci-cd.git](https://github.com/harsh-ydv8/calculator-ci-cd.git)
   cd calculator-ci-cd
2. Open index.html in any browser.
