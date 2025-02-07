# Get Git Go

### *🚀 Complete Process: Forking a Repo, Updating It, and Pushing Changes to the Original Repo*

When you *fork* a repository, you create a copy of the original repo in your GitHub account. You can then make changes in your fork and *send a Pull Request (PR)* to the original repository to contribute your changes.

---

## *🔹 Step 1: Fork the Repository on GitHub*

1️⃣ Go to the original repository on GitHub.

2️⃣ Click the *"Fork"* button (top-right corner).

3️⃣ This creates a copy of the repository in your GitHub account.

✅ *Your fork is now available at:*

[https://github.com/YOUR-USERNAME/REPO-NAME](https://github.com/YOUR-USERNAME/REPO-NAME)

---

## *🔹 Step 2: Clone Your Fork Locally*

To work on the project, you need to clone your fork to your local machine.

```bash
git clone [https://github.com/YOUR-USERNAME/gitws.git](https://github.com/YOUR-USERNAME/gitws.git)
cd gitws
```

---

## *🔹 Step 3: Create a New Branch for Your Changes*

Always create a *new branch* before making changes to keep main clean.

```bash
git checkout -b YOUR-NAME
```

Replace YOUR-NAME with a meaningful name related to your update.

---

## *🔹 Step 4: Make Changes and Commit*

Edit the necessary files and save them. Then, stage and commit your changes:

```bash
git add .
git commit -m "Added a new feature"
```

---

## *🔹 Step 5: Push Changes to Your Fork*

Push your branch to your fork on GitHub:

```bash
git push origin [feature-branch]
```

---

## *🔹 Step 6: Create a Pull Request (PR)*

1️⃣ Go to your fork on GitHub.

2️⃣ You'll see a *"Compare & pull request"* button. Click it.

3️⃣ Make sure the base repository is the *original repo* and the base branch is main.

4️⃣ Add a title and description for your PR.

5️⃣ Click *"Create Pull Request"*.

✅ Now, the maintainers of the original repo can review and merge your changes.

---

### *🎉 Congratulations! You Have Successfully Contributed to an Open-Source Project! 🚀*
