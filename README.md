# FDS-LEMJ-2022

This repo holds the code for the group LEMJ (Lori, Emanuele, Mattia and Julio) through the different assignments of FDS course at UVA 2022.

## Worflow

Let's follow very simple best practices and code reviewing techniques to make our life easier:

1. If you want to add a feature/some code to the project create a new branch from the master branch. This branch should have a meaningfull name e.g. "julio-data-cleaning". Work on this branch until your code is ready for review.
2. Once you have **tested** your code and have also run black on top (only for python scripts, not notebooks. See black description below) create a pull request (PR) to merge your branch to the master branch. In this PR, add as "reviewers" at least two members of the team that you think should review your code. This workflow allows the coder to have some feedback from collegues and prevent not deseried pushed to production.
3. If you get your PR approved, you can merge your branch to master and your code will be in "production"

NOTES:

- [Black](https://pypi.org/project/black/) is a powerfull code formatter that is very convenient for code standardization. Just download it using `pip install black`. After it is downloaded, you only need to run `python -m black .` on your working directory to format your code.
- I really recommend using GitHub Desktop for an easy and direct integration with GitHub.
