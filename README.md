Git is a distributed version control system (DVCS) used by developers and DevOps engineers to track changes in code, collaborate with teams, and manage software projects efficiently.
It was created by Linus Torvalds in 2005.
Simple Definition
Think of Git as a time machine for your code.

It helps you:

• Save versions of your project

• See what changed

• Go back to older versions if something breaks

• Work with other developers without overwriting each other’s work

￼
What Git Is Used For
1. Tracking Changes
Git records every change made to files in a project.
Example:

• You edit index.html

• Git can show:

• what changed

• who changed it

• when it changed

￼
2. Backup & Recovery
If your code breaks, Git allows you to restore a previous working version.
￼
3. Team Collaboration
Multiple developers can work on the same project at the same time using:

• branches

• merging

• pull requests

Platforms like:

• GitHub

• GitLab

• Bitbucket

use Git to host repositories online.
￼
Important Git Terms

Term

Meaning

Repository (Repo)
A project folder tracked by Git
Commit

A saved snapshot of your project
Branch

A separate workspace for changes
Merge

Combining changes together
Clone

Copying a repo from the internet
Push

Uploading code to GitHub
Pull

Downloading latest changes
Copy table

￼
Basic Git Workflow

Step 1 — Create a project
Bash

Copy
￼

mkdir myproject

cd myproject

Step 2 — Initialize Git

Bash

Copy

￼
git init

This creates a hidden .git folder that Git uses to track everything.

￼
Step 3 — Add files

Bash

Copy

￼
git add .
￼
Step 4 — Save changes
Bash
Copy
￼
git commit -m "Initial commit"
￼
Step 5 — Connect to GitHub
Bash
Copy
￼
git remote add origin https://github.com/username/repo.git
￼
Step 6 — Push code online
Bash
Copy
￼
git push -u origin main
￼
Why Git Is Important in DevOps
In DevOps, Git is used for:
• Infrastructure as Code (IaC)
• CI/CD pipelines
• Configuration management
• Collaboration between developers and operations teams
• Deployment automation
Tools that integrate heavily with Git:
• Jenkins
• Docker
• Kubernetes
• GitHub Actions
￼
Real-Life Example
Imagine you are writing a book:
• Every time you save a chapter → Git creates a version
• If you make a mistake → Git restores the old version
• If 5 people write different chapters → Git combines them safely
That is exactly how Git works with code.
￼
Most Common Git Commands
Bash
Copy
￼
git init
git status
git add .
git commit -m "message"
git push
git pull
git clone <repo-url>
git branch
git checkout
￼
Git vs GitHub
Git
GitHub
Tool installed on your computer
Online platform
Tracks code versions
Hosts Git repositories
Works offline
Requires internet for syncing
Copy table
Git is the engine. GitHub is the cloud storage/collaboration platform.