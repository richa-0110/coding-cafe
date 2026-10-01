What did --global mean here? What would happen if you left it out?
The --global flag configures Git settings at the user account level, storing the username and email in the global

What appeared in ls -a but not in ls? What is inside it?
The .git directory appears in ls -a but remains hidden in a regular ls command. Inside this folder, Git stores all the vital metadata, tracking data, configuration files, and commit history needed to manage version control for your project

Roughly how many files and folders is Git offering to track? Does anything in that list look like something you did not write?
git is offering to track around 10 files and folders. Yes, the .DS_Store file and the .venv/ folder are automatic system and environment files that were not manually written by me.

Compare this git status with the one from Question 3. What disappeared?
The .venv/ directory and .DS_Store file have disappeared from the untracked files list because they are now being successfully ignored by Git

.gitignore itself shows up as untracked. Should it be committed, or ignored too? Why?
Yes, .gitignore should be committed. This ensures that the file-ignoring rules are tracked by Git and shared across everyone working on the project, keeping the repository clean.

README.md moved from one heading to another in the git status output. Which two? In the three-places model from the session, what just happened to it?
The README.md file moved from the "Untracked files" section to the "Changes to be committed" section. This means the file has been successfully staged and is now ready to be included in the next commit.

What did Git print after the commit? How many files did it say changed?
Git printed the commit confirmation message and tracked a total of 12 files.

What are the first seven characters of your commit called, and what are they for?
They are called the short commit hash (or commit ID), and they serve as a unique identifier to reference that specific commit in Git.

# Coding Café

Lab work for Coding Café, FM102.

**Name:** Richa
**Roll number:** U20260294

## Contents

- `lab1/` — terminal
- `lab2/` — variables, types, operations, I/O
- `lab3/` — conditionals and loops
- `lab4/` — git and github
