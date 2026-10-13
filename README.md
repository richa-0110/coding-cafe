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

Why does this file get a special name and a special place, rather than being called notes.md like everything else?

Because GitHub automatically finds this file and shows it on the main page of the repository as a welcome guide for visitors.

Refresh the repository page on GitHub. What is showing on the front page, and why that file?

The front page displays all the uploaded project files along with the text content of the README.md file at the bottom. GitHub automatically looks for and renders this specific file because it is designed to act as the main homepage guide and documentation for the repository.

Run git log --oneline again. Did pushing change your local history in any way?

No, pushing did not change the local history in any way. Running git log --oneline shows the exact same commits as before, because pushing only uploads and replicates your existing local history onto the remote GitHub server.

Your repository is private but your TAs can now read it. In your own words, what is the difference between a repository being private and a repository not existing on GitHub at all?

private repository exists securely on GitHub's servers, allowing you and specific invited people (like your TAs) to view and access it. In contrast, a repository that does not exist at all has no data online, meaning no one can find, access, or view it on GitHub.

