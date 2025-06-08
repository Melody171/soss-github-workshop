# Exercise 01 – Clone and Edit

This exercise helps you practise cloning a repository to your computer and making simple changes.

---

## What you’ll do

- Clone your GitHub repository
- Edit your README file
- Commit and push the changes

---

## Step-by-step

### 1. Open your repository on GitHub

Find the repo you created for your portfolio (or a test one if you're just practising).

Click the green **Code** button and copy the URL shown under “HTTPS”.

Example:
```
https://github.com/your-username/your-repo.git
```

---

### 2. Open GitHub Desktop or your terminal

#### Option A: GitHub Desktop  
- Open GitHub Desktop and select **File > Clone repository**
- Paste the URL you copied
- Choose where to save the folder
- Click **Clone**

#### Option B: Terminal  
Use the command:
```
git clone https://github.com/your-username/your-repo.git
```

---

### 3. Make an edit

Open the folder on your computer. Edit the `README.md` file and add a short line of text — for example, your name or a short description of your project.

Save the file.

---

### 4. Commit your changes

In GitHub Desktop:
- You’ll see your change listed
- Add a commit message (e.g. `Add intro line to README`)
- Click **Commit to main**
- Then click **Push origin**

In the terminal:
```bash
git add README.md
git commit -m "Add intro line to README"
git push origin main
```

---

### 5. Check on GitHub

Go back to your repo on github.com and refresh. You should see your updated file.

---

## Well done

You’ve completed your first local edit and push to GitHub.

Continue to the next exercise: **Creating a branch**
