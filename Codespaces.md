---
title: "Getting started with Jupyter on GitHub Codespaces"
image: 'https://github.com/PracticumAI/practicumai.github.io/blob/main/images/icons/practicumai_git.png?raw=true'
image-width: 80px
image-height: 80px
layout: full_page
---

Some of the *Practicum AI* exercises can be completed with the free resources provided by GitHub.com in their Codespaces environment. While this environment does not currently support GPUs, the Python course modules do not use GPUs. Additionally, GPU support is expected at some point. Our hope is that this will provide an easy to use method to run the notebooks for more courses in the future.

To use Codespaces, you will need a GitHub.com account: Sign up at [https://github.com/](https://github.com/).

Codespaces are online coding spaces launched from GitHub repositories. We will learn more about repositories and using `git` in a later exercise, but, essentially, a repository is a collection of files being managed by the `git` version control software. There are a number of ways of creating a repository, but for most *Practicum AI* courses, you can use the GitHub Classroom links. These links will automatically create your own copy of the repository and get you set up to launch a Codespace where you can work on the exercises.

GitHub Classroom is how *Practicum AI* provides individual repositories for each student for each course.

## Accepting a GitHub Classroom Assignment

To start Jupyter in a GitHub Codespace, [click this link to accept the Introduction to Git assignment](https://classroom.github.com/a/l2VposaG).

Once you click the link, you will need to authorize GitHub Classroom to access your account:
![Screenshot of the authorization question when accepting an assignment for the first time](/images/github_authorize.png)

Then you will need to accept the assignment:

![Screenshot of the accept assignment page in GitHub Classroom](/images/github_accept_assignment.png)

GitHub will now setup your personal repository.

> This sometimes takes a minute or two. **Refresh the page** to see if it is finished.

Refresh the page, and there should be a link to your repository.

![Screenshot of the ready to go page showing the link to your repository](/images/github_ready.png)

## Launch your Codespace

Once you have the repository, you can launch the GitHub Codespace.

![Screenshot of the steps to launch a Codespace](/images/github_codespaces_launch.png)

1. Click the green "`<> Code`" button
1. Click the Codespaces tab
1. Click the "Create codespace on main" button

You should see a page similar to this. Some key parts of the page are noted.

![Screenshot of the GitHub Codespace page](/images/Codespaces_overview.png)

## Make a new Python Notebook to explore

The repository and notebooks you have now are part of the `git` exercise we will get to in a bit. But we can create a new Notebook to play with for now.

Use the "Hamburger" menu to select: File > New File...
![Screenshot of New File](/images/codespace_hamburger.png)

Then click on "Jupyter Notebook" (you do not need to enter a name).

The Codespace will ask if you want to install Python, **click the Install** button and wait for the installation to finish.

![Screenshot of install Python](/images/codespace_install_python.png)

Click back on the tab called Untiled-1.ipynb

## Type and run some code

In the box, type: `print("Hello world!")`

You can either click the play button to the left of the cell, or hit the Shift and Enter keys together (Shift-Enter).

> The first time you run a cell in a Codespace, you will need to select a kernel. Click "Python Environments...", and then the Recommended Python environment.

![Screenshot of selecting an environment in a Codespace](/images/codespace_kernel.png)

Codespace Jupyter Notebooks have two main types of cells, or blocks: Code and Markdown. The top bar will allow you to create cells of each type. The lower right hand corner of a cell shows its type and allows you to change the type.

- **Code cells**: are used to type code to run. You can run the code with the play button in the top bar, or using the Shift and Enter keys (Shift-Enter).
- **Markdown cells**: use Markdown syntax to present formatted text. The images, headers, and explanations are made using Markdown and rendered with the same Shift-Enter keys. If you double click on a Markdown cell, you will see the text used to format the text. Hit Shift-Enter to render it again.

![Screenshot of different cell types in Codespaces](/images/codespace_cell_type.png)