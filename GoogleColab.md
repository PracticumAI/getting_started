---
title: "Getting started with Jupyter on Google Colaboratory"
image: 'https://github.com/PracticumAI/practicumai.github.io/blob/main/images/icons/practicumai_git.png?raw=true'
image-width: 80px
image-height: 80px
layout: full_page
---

[Google Colaboratory](https://colab.research.google.com/) (or Colab) is another option. It offers an environment that is similar to Jupyter, and can read files from GitHib.com. Colab also offers runtimes with GPUs, which becomes more important for the *Practicum AI* courses after the Python course.

One of the drawbacks of Colab is that it is more challenging to setup full integration with GitHub. While the Colab can read you notebook from GitHub, it can not read data files or other things that are located in your repository, which can cause issues.

To enable that, you would need to clone the repository into a folder in your Google Drive and then mount your drive. Full `git` integration is not part of Colab as with other options covered.

Google Colab does offer some other benefits with collaboration and the free tier of GPU use.

## Get started in Colab

To get started, you will need a Google account.

> Note: University of Florida Google accounts cannot use Google Colab. You will need to use a personal Google account.

Navigate to [https://colab.research.google.com/](https://colab.research.google.com/)

![Screenshot of Google Colab Launch screen](/images/Colab_launch.png)

Google's *Welcome to Colaboratory* is a great introduction. Click Cancel to work through that.

Alternatively, click New notebook.

## Type and run some code

In the box, type: `print("Hello world!")`

You can either click the play button to the left of the cell, or hit the Shift and Enter keys together (Shift-Enter).

Colab Notebooks have two main types of cells, or blocks: Code and Text (Markdown and other formatting is supported). The top bar will allow you to create cells of each type. 

- **Code cells**: are used to type code to run. You can run the code with the play button in the top bar, or using the Shift and Enter keys (Shift-Enter).
- **Text cells**: use Markdown syntax or formatting options to present formatted text. The images, headers, and explanations are made using Markdown and rendered with the same Shift-Enter keys. If you double click on a Markdown cell, you will see the text used to format the text. Hit Shift-Enter to render it again.

![Screenshot of different cell types in Colab](/images/Colab_cell_type.png)