# GitHub Setup 

This guide will help you upload your assignment to GitHub step by step.

---

## Step 1: Check Your Git Branch

Run this in Git Bash:

```bash
git branch
```

- If it shows `main`, use:
  ```bash
  git push -u origin main
  ```
- If it shows `master`, use:
  ```bash
  git push -u origin master
  ```

---

## Step 2: Navigate to Your Project Folder

Example: If your folder is on the Desktop and named `Assignment-1`, use:

```bash
cd ~/Desktop/Assignment-1
```

---

##  Step 3: Initialize Git & Push to GitHub

In Git Bash, run the following **one at a time**:

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YourUsername/YourRepo.git
git push -u origin main
```

>  Replace `https://github.com/YourUsername/YourRepo.git` with your actual GitHub repository link.

---

##  How to Find Your GitHub Repository URL

1. Go to [https://github.com](https://github.com) and log in.
2. Click on your repository.
3. Click the green **"Code"** button.
4. Under **HTTPS**, copy the link (e.g., `https://github.com/YourUsername/Assignment-1.git`)
5. Use this in the `git remote add origin` command above.

---


