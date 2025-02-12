# 🚀 My DevOps Lab Website

Welcome to **Saad's DevOps Lab Website!** This project is a simple website hosted using **GitHub Pages**. It's a part of my DevOps learning journey where I explore GitHub, automation, and deployment.

## 🌟 What’s Inside?
This repository contains:
- A **basic HTML website**
- Steps to **host a site on GitHub Pages**
- **Automated deployment** using GitHub Actions (coming soon! 🚀)

---

## 📜 Steps I Followed (A Fun Journey!)

### **1️⃣ Setting Up the Repo on My EC2 Instance**
First, I started fresh by creating a new GitHub repository:
1. Went to [GitHub](https://github.com/) and created a **new repository** named `my-website`.
2. Cloned the repo onto my EC2 Ubuntu instance:
   ```bash
   cd ~/dnetflix-task
   git clone https://github.com/saadniftaj/my-website.git
   cd my-website
   ```

### **2️⃣ Creating My Website Files**
I built a simple HTML page to get things rolling:
```bash
nano index.html
```
Then, I added this cool content:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Saad's Website</title>
</head>
<body>
    <h1>Welcome to My DevOps Lab Website!</h1>
    <p>This is a simple website hosted using GitHub Pages.</p>
</body>
</html>
```
Saved and exited (`CTRL + X`, then `Y`, then `ENTER`).

### **3️⃣ Pushing the Code to GitHub**
After setting up my website, I pushed it to my GitHub repository:
```bash
git init
git add .
git commit -m "Initial commit with website files"
git branch -M main
git remote add origin https://github.com/saadniftaj/my-website.git
git push -u origin main
```
Boom! My code was now on GitHub. 🎉

### **4️⃣ Enabling GitHub Pages**
To make the website live:
1. Went to **GitHub repo → Settings → Pages**.
2. Selected the **`main`** branch and clicked **Save**.
3. Waited a few minutes, and voilà! 🚀

### **🔗 Live Website**
You can check out my live website here:  
👉 **[https://saadniftaj.github.io/my-website/](https://saadhaniftaj.github.io/my-website/)**

---

## 🔥 Next Steps: Automating Deployment!
Now, let's take this further by setting up **GitHub Actions** to automate deployment. Stay tuned! 🛠️

📌 More updates coming soon!

