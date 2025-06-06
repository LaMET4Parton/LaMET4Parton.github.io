# Contributing to LaMET Webpage

Thank you for your interest in contributing to the LaMET (Large Momentum Effective Theory) webpage! This guide explains how to collaborate via pull requests (PRs) while keeping our master branch clean and our work collaborative.

---

## 🛠️ How to contribute: step-by-step

1. **Clone** the repository to your local machine:
   ```bash
   git clone https://github.com/LaMET4Parton/LaMET4Parton.github.io.git
   cd LaMET4Parton.github.io
   ```
2. **Sync the master branch** to your local machine:
   ```bash
   git checkout master
   git pull origin master
   ```
3. **Create a new branch** for your changes:
   ```bash
   git checkout -b {your-feature-name}
   ```
4. **Make your changes and commit:**
   ```bash
   git add .
   git commit -m "Brief description of your changes"
   git push origin {your-feature-name}
   ```
   You can commit in small steps (e.g., fixing typos, adding sections). These will be squashed after merging.
5. **Open a Pull Request (PR) on GitHub**, click `Contribute` button, then click `Open pull request` button, targeting the `master` branch.

6. **If you encounter a conflict** (e.g., GitHub shows a message like _"This branch has conflicts that must be resolved"_), click **Resolve conflicts**, then:
   - Delete the sections you don’t want to keep,
   - Keep the correct version of the content (usually from your PR branch),
   - Remove the conflict markers (`<<<<<<<`, `=======`, `>>>>>>>`),
   - Then click `Mark as resolved` and `Commit merge`.

7. **Merge your PR:**
   - Use the `Squash and merge` button to keep commit history clean.
   - Edit the commit message to clearly summarize what the PR does.

8. **Delete your branch and update your local repository:**
   - On GitHub, after merging, click `Delete branch` to remove the feature branch from the remote.
   - On your local machine, switch to the `master` branch and pull the latest changes:
     ```bash
     git checkout master
     git pull
     ```
   - Delete your local feature branch:
     ```bash
     git branch -D {your-feature-name}
     ```
   - For next edits, repeat the process from step 2.

9. **Wait for webpage update:**
   - After merging to `master`, GitHub Actions will automatically rebuild and deploy the webpage
   - This process takes about 30 seconds
   - You can monitor the deployment status in the "Actions" tab of the repository
   - Once complete, your changes will be live on the website

---

## 🛡️ Repository Rules

The following rules are enforced to ensure consistency and collaboration:

* **No direct push** to `master` allowed (everyone must use PRs)
* **Squash merge only** (each PR results in a single commit)
* **At least 0 approval** is required to merge a PR, so everyone can self-merge their own PRs
* **All code review comments must be resolved** before merging
* **Force pushes and branch deletions are blocked**

---

## 📘 Tips for Contributors

* [A simple guide to Git](https://rogerdudler.github.io/git-guide/index.html)
* [Cheat sheet for Git](https://www.runoob.com/manual/github-git-cheat-sheet.pdf)
* Remember to sync the master branch to your local machine before making changes
* Use descriptive commit messages like `Add Publications page` or `Fix layout bug in FAQ`
* Keep your PRs focused — small, clear, and reviewable

---

## 🧑‍💼 Maintainers

* Admins may review and request changes
* Everyone with write access can submit PRs and self-merge
* Please be respectful and collaborative when reviewing others' work

---

Happy contributing! 🎉

If you have questions, open an issue or reach out in the collaboration channel. 