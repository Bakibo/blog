---
title: "Password Protector"
date: 2022-07-03T08:01:03+03:00
draft: true
---

Sometimes you want to make your code public and when you code
sometimes you will have to use information that you would not like to expose to others.
Like passwords, andress, email and more.. And with python is not different..
Using a combination of python-dotenv and a .gitignore file, you'll be good to go!

python-dotenv is a Python module that allows you to specify environment variables
in “.env” (dot-env) file within your Python project directory.
Environment variables is the set of key-value pairs for the current user environment.
They are generally set by the operating system and the current user-specific configurations.
Python-dotenv helps us work with SECRETS and KEYS without exposing them to the outside world,
and keep them safe during development too!!

The .gitignore file tells Git which files to ignore when committing your project to the GitHub repository.
gitignore is located in the root directory of your repo.
Combining the two we can store our sensitive information in ".env" file and add them to the gitignore 
when committing our project.

