# Prework Study Guide Webpage

## A study guide for course prework


- This guide is to help kept track of your learning on how to develope and deploy website
- Why did you build this project? (Note: the answer is not "Because it was a homework assignment.")
It was build to provide a step by step guide 
- What problem does it solve?
It also has the added benifit of providing a place to keep all my notes
- What did you learn?
So far I have learnt how to 

 Module 01
- Create a file
- Write code.
- Create content with HTML, that will appear in a browser. This can be in the form of text, images or parts of a page's layout.
- Style content using CSS to add styling to the content I created with HTML. This includes fonts, colours, spacing and box shadows.
- Create logic with JavaScript to which allows users to interact with the webpage.
- Create a GIT Branch and how to push and pull to the repository

Module 02
- Cultivate a Developer Mindset
- An introduction to an effective developer habits
- Computational thinking
- Agile develpoment
- How to practice a growth mindset as a developer
- How to use pseudocoding to solve basic problems
- We installed the necessary software for the course: 
        - Git Bash, which is an application for Microsoft Windows environments which provides an emulation layer for a Git command line experience. It is used to manage and track source changes, collaborate with other developers and streamline deployment processes using Git commands in a Windows environment 
        - GIThub, which is a Git repository hosting service that provides a web-based graphical interface
        - Visual Studio Code, VS Code for short, which is a source code editor
        - Slack, which is a messaging app for business
- The basics of Markdown syntax. which is a lightweight markup language for creating formatted text using a plain-text editor
- Learnt how to use Git branching and pull requests. Which let you tell others about changes you've pushed to a branch in a repository on GitHub

Module 03 
- Build a Sim Web App
- We Learnt the basic of HTML
- How to analyze and identify HTML elements
- Practiced Git Flow. Which is an alternative Git branching model that involves the use of feature branches and multiple primary branches
- We also built a basic HTML structure for my Prework Study Guide website
- Learnt about JavaScript
        - variables. A “named storage” for data
        - control flow. The order in which statements are executed in a program
        - conditional logic. A control behavior in JavaScript and determine whether or not pieces of code can run.
        - arrays. A type of global object that is used to store data. Arrays consist of an ordered collection or list containing zero or more data types, and use numbered indices starting from 0 to access specific items
        - loops. Which are used in JavaScript to perform repeated tasks based on a condition. Conditions typically return true or false . A loop will continue running until the defined condition returns false.
- How to write and call a JavaScript function while continuing the Git flow
- How to deploy my final project to a public website using GitHub Pages.




## Table of Contents (Optional)

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

Install Git:

Download and install Git from the official website: Git Downloads
During installation, you can choose the default settings for most options.
Sign up for GitHub:

If you don't already have a GitHub account, go to GitHub and sign up for a free account.
Configure Git:

Open Git Bash.
Set your name and email address for Git. Replace Your Name and your.email@example.com with your actual name and email:
bash
Copy code
git config --global user.name "Your Name"
git config --global user.email your.email@example.com
Generate SSH Key (Optional, but recommended):

Generating an SSH key allows you to securely connect to your GitHub account without needing to enter your username and password every time. If you choose not to do this, you'll need to authenticate with your GitHub credentials regularly.
Generate an SSH key by running:
bash
Copy code
ssh-keygen -t ed25519 -C "your.email@example.com"
Follow the prompts to create the SSH key.
Add SSH Key to GitHub (Optional, but recommended):

Copy your public SSH key to the clipboard:
bash
Copy code
cat ~/.ssh/id_ed25519.pub | clip  # On Windows
# OR
cat ~/.ssh/id_ed25519.pub | pbcopy  # On macOS
# OR
cat ~/.ssh/id_ed25519.pub | xclip -selection clipboard  # On Linux
Go to your GitHub account settings, navigate to "SSH and GPG keys," and click "New SSH key." Paste your public key into the field and save it.
Install Visual Studio Code:

Download and install Visual Studio Code from the official website: VS Code
Install Visual Studio Code Extensions (Optional):

Depending on your development needs, you can install extensions for languages, frameworks, and tools you plan to use. You can do this through the Extensions view in VS Code (Ctrl+Shift+X).
Clone a GitHub Repository:

Open Git Bash or your terminal of choice.
Navigate to the directory where you want to store your project.
Clone a GitHub repository using the repository's URL. Replace repository_url with the actual URL of the repository:
bash
Copy code
git clone repository_url
Open the Project in Visual Studio Code:

Open Visual Studio Code.
Use the "File" menu to open the cloned project folder.
Start Developing:

You can now start coding, making changes to the project, committing those changes to Git, and pushing them to GitHub using Visual Studio Code and Git Bash.
Remember to regularly commit your changes to version control and push them to GitHub to keep your codebase up-to-date and collaborate effectively with others. Additionally, ensure that you set up any project-specific dependencies, such as programming languages, libraries, or frameworks, as needed for your development work.



## Usage
The website have been made to help keep track of all the steps needed to show what has been learned at each stage. 
Below is a screenshot of my webpage.


[My Webpage](<images/Screenshot of my webpage.png>)

GitHub repositories are versatile and can be used for various purposes, both for individuals and teams. Here are some common uses for a GitHub repository:

Version Control for Code:

GitHub is primarily known for hosting code repositories. Developers use it to store, manage, and collaborate on software projects. Each commit represents a version of the codebase, allowing you to track changes and collaborate with others.
Open Source Projects:

GitHub is a popular platform for hosting open-source projects. Developers from around the world can contribute to the project by forking the repository, making changes, and submitting pull requests.
Collaborative Software Development:

Teams of developers use GitHub to work on software projects collaboratively. It offers tools for code reviews, issue tracking, and project management, making it easier to coordinate efforts.
Portfolio Showcase:

Individuals can use GitHub to showcase their coding skills by creating repositories that display personal projects, code samples, and contributions to open source. This serves as a portfolio for potential employers.
Documentation:

GitHub can host documentation repositories, making it easy to create, edit, and version documentation for software projects. Markdown and other markup languages are commonly used for this purpose.
Static Website Hosting:

GitHub Pages allows you to host static websites directly from a GitHub repository. You can create a website by adding HTML, CSS, and JavaScript files to a dedicated branch or directory.
Continuous Integration and Deployment (CI/CD):

GitHub integrates with CI/CD tools like GitHub Actions and Jenkins, allowing you to automate the testing and deployment of your code.
Data Analysis and Visualization:

GitHub is not limited to code. Data scientists and analysts use it to share Jupyter notebooks, R scripts, and other data-related projects.
Project Management:

GitHub's issue tracking system and project boards can be used for project management. You can create tasks, assign them to team members, and track progress.

 Below are instructions and examples for some common use cases of GitHub repositories.

1. Creating a New Repository:

To create a new repository on GitHub, follow these steps:

Log in to your GitHub account.
Click the "+" icon in the top right corner of the GitHub website.
Select "New repository."
Fill in the repository name, description, and other settings.
Choose whether the repository should be public or private.
Click the "Create repository" button.
2. Cloning a Repository:

To clone an existing GitHub repository to your local machine, use the git clone command:
bash
Copy code
git clone repository_url
Example:

bash
Copy code
git clone https://github.com/username/my-project.git
3. Adding and Committing Changes:

Make changes to your code or project files locally.
Use the following Git commands to add and commit changes:
bash
Copy code
git add .               # Stage all changes
git commit -m "Message" # Commit changes with a descriptive message
4. Pushing Changes to GitHub:

To push your local commits to the GitHub repository, use the git push command:
bash
Copy code
git push origin branch_name
Example:

bash
Copy code
git push origin main
5. Pulling Changes from GitHub:

To fetch and merge changes from the GitHub repository into your local copy, use the git pull command:
bash
Copy code
git pull origin branch_name
Example:

bash
Copy code
git pull origin main
6. Branching and Merging:

Create a new branch for a new feature or bug fix:
bash
Copy code
git checkout -b new_feature
Switch between branches:
bash
Copy code
git checkout branch_name
Merge branches:
bash
Copy code
# While on the target branch (e.g., 'main')
git merge source_branch
7. Collaborating on a Repository:

Fork a repository:

Click the "Fork" button on the GitHub repository page to create your copy of the repository.
Create a pull request (PR):

After making changes in your forked repository, create a pull request to suggest changes to the original repository.
Review and merge PRs:

Repository maintainers can review pull requests, provide feedback, and merge changes.
8. Managing Issues:

GitHub provides an issue tracker for bug tracking and feature requests.
Create issues, assign them to team members, and track progress.
9. GitHub Pages (Hosting a Website):

To host a static website using GitHub Pages, create a gh-pages branch or use a docs/ directory in your repository.
Your website will be accessible at https://username.github.io/repository.
10. Collaboration with Teams:

csharp
Copy code
- You can add collaborators to your repository, manage access permissions, and work on projects as a team.
11. Repository Settings:

diff
Copy code
- Customize repository settings, including branch protection rules, webhooks, and integrations.
These instructions and examples cover the basics of using GitHub repositories for version control, collaboration, and project management. GitHub offers more advanced features and integrations that you can explore as your projects become more complex.

## Credits


Developed by Claire Fraser
Image bowtie-cat.jpg was provided by edX Bootcamp
Trainning material including links to resources provided by edX Bootcamp



## License

MIT License

Copyright (c) 2023 Claire

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


---

🏆 The previous sections are the bare minimum, and your project will ultimately determine the content of this document. You might also want to consider adding the following sections.

## Badges

![badmath](https://img.shields.io/github/languages/top/nielsenjared/badmath)

Badges aren't necessary, but they demonstrate street cred. Badges let other developers know that you know what you're doing. Check out the badges hosted by [shields.io](https://shields.io/). You may not understand what they all represent now, but you will in time.

## Features

If your project has a lot of features, list them here.

## How to Contribute

If you created an application or package and would like other developers to contribute to it, you can include guidelines for how to do so. The [Contributor Covenant](https://www.contributor-covenant.org/) is an industry standard, but you can always write your own if you'd prefer.

## Tests

Go the extra mile and write tests for your application. Then provide examples on how to run them here.

