# 🚀 Workshop Blueprint: "Git & GitHub: Ground Zero to First PR"
> **A complete, 2-hour hands-on curriculum designed for University of Sahiwal students.**

---

## 🎯 Workshop Goals
By the end of this 2-hour session, every attendee will have:
1. Configured Git locally with their personal credentials.
2. Authenticated securely via SSH or GitHub Personal Access Token (PAT).
3. Cloned a repository, created an isolated branch, committed changes, and pushed to remote.
4. Opened and merged their first Pull Request onto the UOS Tech organization repository.
5. Understood how to apply for the GitHub Student Developer Pack via manual document verification.

---

## ⏱️ Timeline & Session Breakdown

### Module 1: The Why & The Foundation (20 Mins)
- **Why Version Control Matters:** Moving past `final_project_v2_final_FINAL.zip`.
- **How Distributed Teams Work:** The role of GitHub in global engineering and remote hiring.
- **Git vs. GitHub:** Distinguishing the local tool from the cloud collaboration platform.

### Module 2: Environment Setup & Authentication (25 Mins)
- Installing Git on Windows/Linux/macOS.
- Configuring identity:
  ```bash
  git config --global user.name "Your Full Name"
  git config --global user.email "your.email@example.com"
  ```
- Generating SSH keys / VS Code GitHub Integration:
  ```bash
  ssh-keygen -t ed25519 -C "your.email@example.com"
  ```

### Module 3: Hands-on Branching & PR Sandbox (45 Mins)
- **The Sandbox Repo:** `uos-tech/first-contributions`
- Step-by-step student workflow:
  1. Fork the repo to personal account.
  2. Clone locally:
     ```bash
     git clone https://github.com/<username>/first-contributions.git
     cd first-contributions
     ```
  3. Create a unique feature branch:
     ```bash
     git checkout -b add-student-<rollnumber>
     ```
  4. Add student profile card in `students/<rollnumber>.json` or markdown directory.
  5. Commit and push:
     ```bash
     git add .
     git commit -m "feat: add student profile for <name>"
     git push origin add-student-<rollnumber>
     ```
  6. Navigate to GitHub and click **Compare & pull request**.
  7. Automated check runs & student PR is merged live on screen.

### Module 4: Student Perks & Community Roadmap (30 Mins)
- Navigating the **GitHub Student Developer Pack** without an `.edu` email address:
  - How to capture clean photos of your physical student ID and latest official semester fee voucher.
  - Ensuring your billing profile name matches your physical academic identity documents 100%.
  - How to submit the manual verification form.
- Q&A & invitation to join the core organizing committee.
