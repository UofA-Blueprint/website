# 🏗️ Blueprint Internal Tools Website

Welcome to the **Blueprint Internal Tools Website** repository!

## 📄 Description

The **Blueprint Internal Tools Website** serves as a consolidated source of information for all things Blueprint. The site contants multiple static pages built using the [Hugo](https://gohugo.io/) static site generator.

## 🚀 Steps to Start Contributing

Follow these steps to set up and contribute to the project:

### 1. Install Hugo

To build and run the website locally, you'll need to install Hugo. Visit the [official Hugo installation guide](https://gohugo.io/getting-started/installing/) for platform-specific instructions.

### 2. Clone the Repository

```bash
git clone <repository-url>
cd <repository-folder>
```

### 3. Branch from `developer`

```bash
# from main
git switch -c 123-your-branch
```

_NOTE: Make sure to append the ticket number from notion to the **start** of the branch name._

### 4. Develop locally

Run the following command to start a local server to see changes during development:

```bash
hugo server
```

### 5. Commit changes

Save completed work by creating organized commits, this is done via the following command:

```bash
git add <file-path>
git commit -m "summary message"
```

TIP: Use the commit message emoji guide, [Gitmoji](https://gitmoji.dev/), to provide reviewers with visual context in commit messages (for example, ":recycle: refactored navbar").

### 6. Push changes to GitHub

Run:

```bash
git push
```

... to sync your branch to GitHub. If this is your first push on a fresh branch you will need to run the command that git suggests after running the previous command, it should look something like this:

```bash
git push --set-upstream origin 123-your-branch
```

### 6. Request a review

Once your changes are committed and pushed to GitHub, request a **Code Review** from two authorized team members. This is done by navigating to GitHub directly after pushing the branch and clicking **Compare & pull request** at the top of the page.

Once a pull request is created, add a detailed description of the changes made, click _assign yourself_ under Assignees, and select two reviewers from the team under Reviewers. If you are unsure of who to assign, please post a question in the Discord channel.

NOTE: A pull request may be denied if there is a missing/unacceptable description. Please provide the reviewer with some context.
