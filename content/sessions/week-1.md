---
section_id: Workshop Sessions
nav_order: 3
title: Week 1
topics: Version Control; Repositories; Cloning 
---

## Learning Objectives

- Discuss the advantages of a static website.
- Create a GitHub account.
- Create a GitHub repository.
- Learn the basic commands and functionality of Git and GitHub.
- Link your GitHub remote repository to your local machine via GitHub Desktop.

## GitHub Basics

This module will walk you through setting up your GitHub account, and will introduce you to some common tasks that can be completed through the GitHub interface. It has been adapted from [Learn Static's Introduction to GitHub](https://github.com/learn-static/foundations-0-github) and [Evan Will's go-go gh-pages](https://evanwill.github.io/go-go-ghpages-b/).

Before we get started, let's clarify some terms:

[Git](https://git-scm.com/) is a popular free, distributed version control system–i.e. a piece of software used to track the history of changes in a folder of files. Git can be used on your personal computer, or by online services to track the development of a project, such as…

[GitHub](https://github.com/), a popular web platform for hosting Git repositories–i.e. a place to store and sync your project files online. Think of it as Google Drive for code with super robust "track changes" baked in. Built around the powerful version control of Git, it provides a handy web interface for managing, editing, and collaborating on repositories.

The steps below will familiarize you with the GitHub platform, and with how it tracks the changes you make to your files.

### Step 1. Create a GitHub account

1. Open <https://github.com> in a new tab
2. Click the "Sign up" button
3. Enter your email and create a username and password to complete the sign up process

### Step 2. Create a GitHub Repository

Follow these steps to copy code from another repository into your own and start editing it:

1. Make sure you're logged into your account on [GitHub](https://github.com)
2. On GitHub, click the “+” plus icon in the upper right of the nav bar.
3. Select “New repository”
4. This brings you to a "Create a new repository" form. Follow these steps:
    1. In the **Repository name** text box, give your repository the name `dsf-github-basics`. If you'd like to create your own name for the repository, be sure to use a lowercase name without spaces or odd characters. Dashes (`-`) or underscores (`_`) are okay.
    2. In the **Description** text box, add `A place to learn GitHub basics`.
    3. Select the option for "**Public**" repository.
    4. Leave the "Include all branches" option **Unchecked**!
    5. Click on the green button "**Create repository from template**". This will take you to your new repository.

### Step 3. Explore the interface and repository

1. Explore your repository:
    - gray bar: most recent activity; commit history
    - repo list: files and folders, looks like directory
    - readme preview
    - about: click and describe this repository

2. Explore navigation bar:
    - code: brings us back to main repo page
    - issues/pull requests/etc.: more advanced
    - settings: modify repo, lets go initiate github pages


### Step 4. Edit README file

1. Click on the `README.md` link. This will open your README file.

    The README file is a place to describe your repository.
    By default, GitHub displays the README on the repository home page, so it is often the first place visitors will look for information about your project.

2. In the top right corner of the README file, locate and click on the pencil icon.

    You are now in GitHub's editing mode.

3. Delete this line of text and instead type `# My Project`.
4. Add text below your title to describe your project. For example, you can add `A place to learn GitHub basics`

### Step 5. Make a Commit

When you make a commit, Git takes a snapshot of the changes you made and permanently stores it in your repository's history.
Your "commit message" is a short description of what the changes do or why you made them--this is a required note to your future self and your collaborators to help everyone understand the code and history.

1. To commit the changes you just made to your README file, scroll to the bottom of the page where you made your README edits. You'll see a box titled "Commit changes."
2. In the text box directly underneath "Commit changes," type `update project title`, or a brief message of your choosing that indicates what changes you made to this file.
3. Skip the option to add an extended description to the commit, and keep the box checked next to "Commit directly to the main branch". (Note that you can add an extended description of your changes if you need to, but usually a brief commit message will work just fine).
4. Click on the green "Commit changes" button. This will save your changes and take you back to your repository's home page.
5. Scroll down to the bottom of your repository to view the new title you added to the README file.

You can view recent commits on your repository's home page.
Commit messages and their timestamps are located to the right of the repository files.

### Step 6. View the Changes

Let's take a closer look at the changes you've made to the README file:

1. On your repository's home page, scroll back up and locate the README.md file link. To the right of the link, you should see the commit message you just created (it should say `update project title`).
2. Click on this commit message (*not* on the filename).

    When you click the commit message, GitHub will show you the changes made and the files edited during that commit. 
    Deletions will display in red while additions to a file will display in green. 

3. Click your repository's name (located in the top left of the window) to return to the repository's home page.

### Step 7. Add a New File to the Repository

Now it's time to add a new file to your project.

1. On your repository's home page, locate and click the "Add file" button, situated to the right above your repository's files. When this button is clicked, a drop-down menu will appear. Select the option "Create new file".
2. An option to name your file will appear toward the top of your screen. Give your file the name: `new-file.txt`
3. Add the following sentence to the body of your text file: `This is a new file in my GitHub repository.`
4. Commit your new file to your repository by adding the commit message `add new file` (just as you did in the "Make a Commit" section above), and pressing the green "Commit new file" button.

### Step 8. Check Out the Repository's History

As you continue to add files and make commits to your repository, there may come a time in which you need to view all of the edits you've made to your files.
Let's view all the changes we've made to the repository so far.

1. On your repository's home page, locate the commit count for your repository, situated underneath the green "Code" button and to the right of the clock icon. It should display a number followed by the word "commits" (example: "3 commits"): 
2. Click on this commit count link.

    You are now viewing your repository's history (all the commits that have ever been made to your repository).

3. Click on the commit message `update project title` to view the changes that were made as part of that commit.
4. Click your repository's name (located in the top left of the window) to return to the repository's home page.

## Remote to Local

While GitHub's interface allows for editing, developing, and launching a website, working locally will help you work effectively and efficiently. This section will introduce you to the concept of remote and local repositories through the use of GitHub Desktop.

### Step 1. Install GitHub Desktop

1. Navigate to [GitHub Desktop](https://github.com/apps/desktop) and download the appropriate version of GitHub Desktop for your operating system. 
2. Follow the prompts to complete the installation. For more information, see [Installing GitHub Desktop](https://docs.github.com/en/desktop/installing-and-authenticating-to-github-desktop/setting-up-github-desktop).
    1. Sign in to your Github.com account via the GitHub Desktop prompt.
    2. Select `authorize` after reviewing access prompt.
    3. When viewing `configure git` prompt, select `use my GitHub account name and email address`.
    4. Click `finish`
3. Arrive at `Let's get started.` prompt.

### Step 2. Clone Your Repository Using GitHub Desktop

1. Select `clone repository`.
2. Select repository we created in previous module. If you followed along, it will be titled `dsf-github-basics`.
3. Click `clone`. 

### Step 3. Explore GitHub Desktop and its Functionality

1. Explore navigation bar:
    - Current repository dropdown menu
    - Current branch dropdown menu
    - Suggested action:
        - Fetch
        - Pull
        - Push
2. Explore commit viewer:
    - Changes
    - History
    - Commit message
3. Explore main viewer:
    - Open the repository in your external editor
    - View the files of your repository in Finder/Windows Explorer
    - Open the repository page on GitHub in your browser