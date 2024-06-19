# Enviornment-Setup

## Abstract

Our course will be developed throughout the theory of computational finance with relevant coding experiments. The classical setup for this computing is to install anaconda with python 3.X and GitHub desktop on your computer. To ease of our installation, we will use cloud computing platform with GitHub. In this part, we will learn the followings:

- Setup GitHub account and a class repo.
- Create a Jupyter notebook with Colab and update GitHub

## First touch with GitHub


GitHub is exactly how people build software. GitHub. is a web-based hosting service for version control using Git. As of 2018, GitHub becomes the largest host of source code in the world, and Microsoft completed GitHub acquisition by the end of 2018. To learn GitHub, you may start with [GitHub help](https://help.github.com/). 

Let's start with the following steps:

- Visit [GitHub](https://github.com/) and register for your own account.
- create a repo with course-name. please tick public/initialize readme/mit license.
- Modify README.md.

## Jupyter notebook with Colab

The Jupyter Notebook App is a server-client application that allows editing and running notebook documents (ex. python, latex) via a web browser. The Jupyter Notebook App can be executed on a local desktop requiring no internet access or can be installed on a remote server and accessed through the internet.

For instance, we can write math symbols using latex enclosed by double dollar sign:
$$\phi(x) = \frac{1}{\sqrt{2\pi}} e^{-1/x^2}$$

jupyter nbconvert --execute --to markdown README.ipynb

