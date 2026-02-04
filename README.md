[![CI Pipeline](https://github.com/charithareddymule/devops-ci-miniwhat/actions/workflows/ci.yml/badge.svg)](https://github.com/charithareddymule/devops-ci-miniwhat/actions/workflows/ci.yml)

🚀 **Live Deployment**  
https://charithareddymule.github.io/devops-ci-miniwhat/

# DevOps CI/CD Mini Project

This project demonstrates an end-to-end **CI/CD pipeline** implemented using **GitHub Actions**.  
It automates testing, enforces code quality through linting, and deploys the application automatically to **GitHub Pages** after successful checks.

---

## What this project does

- Runs automated tests on every code push (Continuous Integration)
- Enforces Python code quality using **flake8** linting
- Blocks deployment if tests or linting fail
- Automatically deploys the project to **GitHub Pages** after all checks pass
- Displays real-time pipeline status using a GitHub Actions badge

---

## CI/CD Workflow

1. Code is pushed to the repository
2. GitHub Actions triggers the CI pipeline
3. Automated tests are executed using **pytest**
4. Code quality is checked using **flake8** (linting)
5. If all checks pass, a deployment artifact is created
6. The project is automatically deployed to **GitHub Pages**
7. If any step fails, deployment is blocked

This ensures that only clean and tested code reaches production.

---

## Tech Stack Used

- **GitHub** – Source code management  
- **GitHub Actions** – CI/CD automation  
- **Python** – Application logic  
- **Pytest** – Automated testing  
- **Flake8** – Linting and quality gate  
- **GitHub Pages** – Static site deployment  

---

## Why this project matters

This project reflects a real-world DevOps workflow where:
- Automation reduces manual effort
- Quality gates prevent faulty or unclean code
- Deployment happens only after successful validation

It demonstrates how modern development teams use CI/CD pipelines to ensure reliability and consistency in production deployments.

---

## Outcome

- Fully automated CI/CD pipeline
- Enforced testing and code quality standards
- Safe and conditional deployment
- Live deployed application with zero manual intervention

---

## How to run locally (optional)

```bash
pip install pytest flake8
pytest
flake8 .
