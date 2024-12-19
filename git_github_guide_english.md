# A Simple Guide to Git and GitHub for Beginners

## 1. What is Git and How Does It Work?
### Simple Definition:
- **Git** is a **Version Control System (VCS)**.
- Its main purpose is to record any changes you make to your project's files so you can easily return to any previous version.
- Everything works **locally** (on your computer), so you don’t need an internet connection.

![Git Local Workflow](https://git-scm.com/images/about/git.png)

### How Does Git Work Behind the Scenes?
1. **Local Folder**: Git works inside your project folder.
2. **Snapshots**: Every time you make a "commit," Git takes a snapshot of your changes.
3. **History**: It keeps a history of all the versions so you can return to any one of them when needed.
4. **Difference Between Versions**: Git uses differences (diff) between files to save space.

![Git Commit History](https://www.atlassian.com/dam/jcr:efc6126f-6e1c-409c-b631-f97d823e13a1/hero_git_commit_history.png)

---

## 2. What is GitHub and How Does It Work?
### Simple Definition:
- **GitHub** is a website that allows you to upload your project (the files stored locally) and share it with your team.
- It acts as an online storage for your code.
- It allows other people to collaborate and make changes to the same project.

![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

### How Does GitHub Work Behind the Scenes?
1. **Repository**: The code repository gets uploaded from your computer to GitHub.
2. **Push & Pull**:
   - **Push**: Upload the changes you made locally to GitHub.
   - **Pull**: Download the changes from GitHub to your computer.
3. **Collaboration**: Everyone can create their own branch to make changes and then merge it into the main code.

![Push & Pull Diagram](https://miro.medium.com/v2/resize:fit:1400/1*tnSWUP_G5PjK7hFbCm03Hw.png)

---

## 3. The Difference Between Git and GitHub
| **Aspect**          | **Git**                                | **GitHub**                            |
|---------------------|--------------------------------------|--------------------------------------|
| **Definition**      | A version control system on your computer | An online platform to store and share code |
| **Usage**           | Tracks changes locally                | Collaborates with a team and uploads code |
| **Internet**        | Does not require internet             | Requires internet to push/pull changes |
| **Storage**         | Saves code locally on your computer   | Saves code on the internet            |

---

## 4. Why Do We Use Git and GitHub?
### Why Use **Git**?
1. **Track Changes**: Follow every edit made to your code.
2. **Rollback**: If something goes wrong, you can easily return to a previous version.
3. **Organize Work**: Test new changes in separate branches without breaking the main code.

### Why Use **GitHub**?
1. **Store Code**: Keep your project safe online so it doesn’t get lost.
2. **Collaboration**: Easily share and work on code with teammates.
3. **Backup**: Even if your computer crashes, your code is safe on GitHub.
4. **Code Review**: Review teammates’ suggestions before merging their changes.

![GitHub Collaboration](https://docs.github.com/assets/images/help/pull_requests/pull-request-review-comments.png)

---

## Quick Summary
- **Git**: A local version control system.
- **GitHub**: An online platform to store and share code.
- We use them to organize our work, track changes, and collaborate with our team.
