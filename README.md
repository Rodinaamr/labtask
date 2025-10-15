🧩 Repository Setup & Workflow Guide
📁 Repository Setup

Create a New GitHub Repository

Go to GitHub
 and click New Repository.

Name your repository and add a short description.

Do not initialize it with a README yet (we’ll do it locally).

Initialize Locally

git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/<your-username>/<repository-name>.git
git push -u origin main

🌿 Branching & Commit History

Create a Feature Branch

git checkout -b feature/update-readme


Make Multiple Meaningful Commits

git add README.md
git commit -m "Add initial README structure"

git add .
git commit -m "Update README with setup and workflow instructions"


Push Branch to GitHub

git push -u origin feature/update-readme


Open a Pull Request (PR)

Go to your repository on GitHub.

Click Compare & pull request.

Add a clear PR title and detailed description (e.g., “Updated README with repository setup guide”).

Request a review (optional) and merge into main once approved.

🧩 Issues & Labels

Create and manage issues for tracking bugs and feature enhancements.

🐛 Bug Report

Title: Login button not responding on mobile
Label: bug
Assignee: @your-username

Description:
The login button fails to respond on mobile browsers.

✨ Feature Request

Title: Add real-time location sharing
Label: enhancement
Assignee: @your-username

Description:
Allow users to share live GPS location with friends/family for a set time period.

📋 Project Board

Create a Project Board named “Development Progress”.

Add three columns:

📝 To Do

🚧 In Progress

✅ Done

Convert your Issues into cards and place them in the To Do column.

As you work, move them to In Progress → Done when completed.

🧠 Best Practices

Write clear and descriptive commit messages (e.g., “Fix login button event listener on mobile”).

Use feature branches for each new update or bug fix.

Keep your main branch clean by merging only tested and reviewed code.

Use labels to organize issues and track development status.

Regularly update your Project Board to reflect current progress.
