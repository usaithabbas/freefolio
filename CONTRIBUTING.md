# Contributing Guidelines for Freefolio App 👨‍💻

## 👨‍💻 Prerequisite Skills to Contribute

- [Git](https://git-scm.com/)

### Contribute in Documents

- [Markdown](https://www.markdownguide.org/basic-syntax/)

---

## 💥 How to Contribute

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://github.com/OSSPhilippines/freefolio/pulls)
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.png?v=103)](https://github.com/OSSPhilippines/freefolio)

- Take a look at the existing [Issues](https://github.com/OSSPhilippines/freefolio/issues) or [create a new issue](https://github.com/OSSPhilippines/freefolio/issues/new/choose)!
- [Fork the Repo](https://github.com/OSSPhilippines/freefolio/fork). Then, create a branch for any issue that you are working on. Finally, commit your work.
- Create a **[Pull Request](https://github.com/OSSPhilippines/freefolio/compare)** (_PR_), which will be promptly reviewed and given suggestions for improvements by the community.
- Add screenshots or screen captures to your Pull Request to help us understand the effects of the changes proposed in your PR.

---

## ⭐ HOW TO MAKE A PULL REQUEST:

**1.** Start by making a Fork of the [**Freefolio**](https://github.com/OSSPhilippines/freefolio) repository. Click on the <a href="https://github.com/OSSPhilippines/freefolio/fork"><img src="https://i.imgur.com/G4z1kEe.png" height="21" width="21"></a>Fork symbol at the top right corner.

**2.** Clone your new fork of the repository in the terminal/CLI on your computer with the following command:

```bash
git clone https://github.com/<your-github-username>/freefolio
```

**3.** Navigate to the newly created LinkFree project directory:

```bash
cd freefolio
```

**4.** Create a new branch:

```bash
git checkout -b YourBranchName
```

⚠️ **Make sure** not to commit `package.json` or `package-lock.json` file

⚠️ **Make sure** not to run the commands `git add .` or `git add *`. Instead, stage your changes for each file/folder

**4.** Start developement:

All template must conform to the following criteria:

- The template is not a direct copy of an existing template, be creative create your own design ;)
- The template must not contain vulgar words, images, or any other similar content
- The template must not promote people, government, political parties, or any other organization

Technical criteria:

- The `index.html` must have a `title` and `meta description` tag
- The `title` tag should be `<name of template> a Freefolio template by OSSPH`
- You can use any CSS framework like bootstrap, tailwind, etc. As long as they are imported via CDN
- Your template must be static, meaning no dynamic data from outside the code is required for it to work
- Do not use excessively large images, you can compress your assets using https://tinypng.com/ 

And most importantly:

- Have fun! <3

**6.** Add those changes to the branch you just created using the git add command. To let Git track files for a commit, we need to run the following in the terminal:

```bash
git add my_new_file
```
And for adding several files to the staging area in one go. Do this instead, it is more convenient.

```bash
git add .
```

- After git add command see status with git status command:

```bash
git status
```

**7.** Now commit those changes using the git commit command:

```bash
git commit -m "<your_commit_message>"
```

**8.** Push your local commits to the remote repository:

```bash
git push origin YourBranchName
```

**9.** Create a [Pull Request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)!

**10.** **Congratulations!** You've made your first contribution to [**Freefolio**](https://github.com/OSSPhilippines/freefolio)! 🙌🏼

**_:trophy: After this, the maintainers will review the PR and will merge it if it helps move the freefolio project forward. Otherwise, it will be given constructive feedback and suggestions for the changes needed to add the PR to the codebase._**

---

## Style Guide for Git Commit Messages :memo:

**How you can add more value to your contribution logs:**

- Use the present tense. (Example: "Add feature" instead of "Added feature")
- Use the imperative mood. (Example: "Move item to...", instead of "Moves item to...")
- Limit the first line (also called the Subject Line) to _50 characters or less_.
- Capitalize the Subject Line.
- Separate subject from body with a blank line.
- Do not end the subject line with a period.
- Wrap the body at _72 characters_.
- Use the body to explain the _what_, _why_, _vs_, and _how_.
- Reference [Issues](https://github.com/OSSPhilippines/freefolio/issues) and [Pull Requests](https://github.com/OSSPhilippines/freefolio/pulls) liberally after the first line.

---

## 💥 Issues

In order to discuss changes, you are welcome to [open an issue](https://github.com/OSSPhilippines/freefolio/issues/new/choose) about what you would like to contribute. Enhancements are always encouraged and appreciated.

## All the best! 🥇
