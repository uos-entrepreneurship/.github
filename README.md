# 🏛️ University of Sahiwal — GitHub Campus Community Hub

Welcome to the central repository and staging ground for establishing the **University of Sahiwal Tech & Entrepreneurship Society** and pursuing accreditation as the campus's first **GitHub Campus Expert**.

---

## 📂 Repository Structure

- [`.github/profile/README.md`](file:///c:/Uni/.github/profile/README.md) — The flagship organization profile page designed to display on your GitHub Organization profile (`github.com/orgs/<your-org>`).
- [`CAMPUS_EXPERT_PORTFOLIO.md`](file:///c:/Uni/CAMPUS_EXPERT_PORTFOLIO.md) — Comprehensive narrative framework, institutional analysis, metric targets, and essay answers prepared for the official GitHub Campus Expert application.
- [`WORKSHOP_SERIES_GIT_ZERO_TO_HERO.md`](file:///c:/Uni/WORKSHOP_SERIES_GIT_ZERO_TO_HERO.md) — Ready-to-deliver 2-hour interactive workshop curriculum for student onboarding and first pull request execution.

---

## ⚡ Quick Start: Deploying to GitHub

To publish this hub to your newly created GitHub organization:

```bash
# 1. Initialize Git in this directory (if not already done)
git init
git branch -M main

# 2. Stage and commit all society files
git add .
git commit -m "feat: initial commit for UoS Tech Society assets"

# 3. Create a public repository named '.github' inside your GitHub Organization
# Example: https://github.com/uos-tech/.github

# 4. Link and push to your organization's .github repo
git remote add origin https://github.com/<your-org-slug>/.github.git
git push -u origin main
```

*(Note: Creating a repository named `.github` in your organization and putting `profile/README.md` inside it activates GitHub's special Organization Profile display feature!)*
