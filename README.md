# 🚀 Task 4: Version-Controlled DevOps Project with Git

## 📌 Objective
This project demonstrates how to manage a DevOps workflow using Git best practices, including branching strategies, pull requests, tagging, and proper documentation.

---

## 🛠️ Tools Used
- Git
- GitHub
- Markdown

---

## 📁 Project Structure

project-root/
│── README.md
│── .gitignore
│── (your project files here)


---

## 🌿 Git Branching Strategy

This project follows a structured branching model:

- `main` → Production-ready code
- `dev` → Development branch for integration
- `feature/*` → Feature-specific branches (e.g., feature-login, feature-ui)

---

## 🔄 Workflow Followed

### 1️⃣ Initialize Repository
```bash
git init
git remote add origin <your-repo-url>
2️⃣ Create Branches
git checkout -b dev
git checkout -b feature/sample-feature
3️⃣ Work on Features
Develop changes in feature/* branches
Commit changes regularly:
git add .
git commit -m "Added sample feature"
4️⃣ Push to GitHub
git push origin feature/sample-feature
5️⃣ Pull Request (PR) Workflow
Open GitHub
Create Pull Request → feature/* → dev
Review and merge after approval
```

Then merge:

dev → main for final release
🧾 Git Best Practices Followed
Meaningful commit messages
Separate feature branches
Code reviewed via Pull Requests
Clean repository structure
Avoided pushing unnecessary files using .gitignore
🚫 .gitignore Example
node_modules/
.env
__pycache__/
*.log
.DS_Store



🏷️ Tagging Releases

Used tags for version control:

git tag -a v1.0 -m "Initial release"
git push origin v1.0
📖 Learning Outcome

By completing this project, I learned:

Git branching strategies
Collaboration using GitHub Pull Requests
Version control best practices
Managing DevOps workflows efficiently

# 👨‍💻 Author

Harun Yahya Shaik 

DevOps & Cloud Enthusiast

#OUTPUT SCREENSHOT

<img width="1110" height="585" alt="image" src="https://github.com/user-attachments/assets/eb3358dd-57e0-4e4d-b108-106c92da41b8" />

<img width="981" height="588" alt="image" src="https://github.com/user-attachments/assets/ef9d6fe6-f015-4833-a75f-2c6bdef3294a" />

<img width="898" height="590" alt="image" src="https://github.com/user-attachments/assets/0e042605-11bb-48fd-b4aa-14618bb82702" />

<img width="886" height="581" alt="image" src="https://github.com/user-attachments/assets/4d5fdcb6-512a-4b53-8915-36d0a028d124" />

<img width="803" height="547" alt="image" src="https://github.com/user-attachments/assets/d8d4a59d-7914-4174-ad5c-cf7f1f356be8" />




