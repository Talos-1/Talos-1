# 👋 Hi, I'm Alex

*“I only achieve simplicity with enormous effort”* ― Clarice Lispector

📍Canberra, Australia

🎓B. Software Engineering, M. Cyber Security, & M. Applied AI

## 🧰 Toolbox

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![C#](https://img.shields.io/badge/C%23%20%2F%20.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Go](https://img.shields.io/badge/Go_(learning)-00ADD8?style=flat-square&logo=go&logoColor=white)

**ML / AI**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

**MLOps / DevSecOps**

![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Poetry](https://img.shields.io/badge/Poetry-60A5FA?style=flat-square&logo=poetry&logoColor=white)
![Ruff](https://img.shields.io/badge/Ruff-D7FF64?style=flat-square&logo=ruff&logoColor=black)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![pre-commit](https://img.shields.io/badge/pre--commit-FAB040?style=flat-square&logo=precommit&logoColor=black)

**Security**

![Ghidra](https://img.shields.io/badge/Ghidra-B22222?style=flat-square)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

## What I've built

### [Katabatic](https://github.com/datascience-works/Katabatic): open-source synthetic tabular data

Project lead and Dev/MLOps lead for 40+ contributor framework.

  ![Top contributor: 213 commits](https://img.shields.io/badge/top_contributor-213_commits-2ea44f?style=flat-square&logo=git&logoColor=white)
  ![70% of commits to main since July 2026](https://img.shields.io/badge/main_branch_since_Jul_'26-70%25_of_commits-0969da?style=flat-square)
  ![Merged 22 of 29 PRs on main](https://img.shields.io/badge/PRs_merged-22_of_29-8250df?style=flat-square&logo=githubactions&logoColor=white)

- Built the CI/CD pipeline: GitHub Actions running **Ruff**, **Bandit**, **pip-audit** and **pytest** with a coverage floor, plus a path-filtered **per-model integration matrix** and multi-stage **Docker** builds
- Wrote the **PyPI / TestPyPI release workflows**, Dependabot config and CODEOWNERS
- Migrated packaging to **PEP 621** / Poetry, with pre-commit hooks, Makefile tooling and branch protection
- Designed a **model-promotion contract test harness** that decides which generators (GANBLR, CTGAN, …) are fit to ship
- Acted as maintainer and GitHub admin: review and merge PRs, triage dependency vulnerabilities, report on sprints
