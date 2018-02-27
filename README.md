# Git Newsroom Assignment

### Instructions:
- Form a team of 3-4 people
- Pick one teammate to create a repo on github, and add everyone as collaborators (on the github repo page, click on the 'Settings' tab and click on 'Collaborators' on the left pane
- Everyone should `git clone` the repository to make it available locally

### Task:
Your team has to go through [raw-news.txt](./raw-news.txt) and create directories (1 directory per category) and files (1 file per news tweet).

Rules:
- `git add`, `git commit`, `git push` and `git pull` often.
- Each commit should contain **no more than 1 file** (i.e. commit everytime you add 1 news article) (we'll be watching!)
- Each team member should create roughly the equal amount of news articles.

### Bonus tasks:
1. Ignoring files using `.gitignore`
  - Create a `.gitignore` file in the project directory
  - Create a file named 'not-news.txt' and add 'not-news.txt' to `.gitignore`
  - Verify that it's ignored with `git status`
  - Create a directory named `temp`, create 3 .txt files in it, and add `temp` to `.gitignore`
  - Create a directory named `sandbox`, create 2 .txt files and 1 .doc file in it and ignore only .doc files

2. Fixing merge conflicts
  - Simulate a merge conflict by having 2 people edit the same file on the same line.
  - Fix merge conflict

3. Bonus activity: Pull requests
  - Teammate A: Remove one of your teammates (teammate B) as a collaborator from the repository
  - Teammate B: Because you no longer have access, you won't be able to push to the original repo. You now have to (i) **fork** the repo, (ii) update the remote origin's url in your local machine (hint: use `git remote set-url origin <url>`).
  - Teammate B: make a change, commit, push (to your forked repo) and submit a pull request to the original repo
  - (repeat process for remaining teammates)
