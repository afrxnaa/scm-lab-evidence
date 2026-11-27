Session 1 Reflection



Q1. Why is a commit history useful when maintaining software?



A commit history is useful because it allows developers to see what changes were made and when they happened. For example, if a bug appears in a program, developers can check previous commits to find out which change might have caused it. In my repository, I made commits such as "Add README for SCM evidence repository" and "Add teammate file". These commits help me understand the changes made to my project and make it easier to track the development process.



Q2. Explain the difference between Git and GitHub, using your two repositories as examples.



Git is a version control system that tracks changes to files and manages commits on my computer. GitHub is an online platform where I can store and share my Git repositories with other people. For example, I used Git to manage my SCM lab evidence repository and the GitHub Skills exercise repository, while GitHub allowed me to upload and access these repositories online.



Q3. What risk does using a branch and pull request reduce?



Using a branch and pull request reduces the risk of making mistakes directly in the main branch. Developers can make changes and test their work on a separate branch before asking for it to be reviewed. This helps identify errors before merging the changes into the main project and prevents unfinished or incorrect changes from affecting other developers.



Q4. Which commands changed only your computer and which changed GitHub?



Commands such as git add, git commit, git status, git log and git pull worked with my local repository or updated files on my computer. Creating files using commands such as echo also changed only my computer. The git push command uploaded my commits and changes to GitHub. The git clone command downloaded a copy of the repository from GitHub to my computer without changing the online repository.



Concept Table (Part 1) --corrected compare with Appendix A

|Term|My definition in on one sentence|Corrected (Appendix A)|
|-|-|-|
|Repository|A storage location where Git keeps all project files, their history, and changes made over time.|Project folder plus its full history.|
|Working Tree (working directory)|The folder containing the project files where you can create, edit, or delete files.|The files you see and edit.|
|Staging Area (index)|A place where you select and prepare changes that you want to include in your next commit.|List of changes chosen for the next commit.|
|Commit|A saved snapshot of the changes made to your project, along with a message describing those changes.|Saved snapshot with message, author and date.|
|Branch|A separate line of development that allows you to work on new features or changes without affecting the main project.|Movable pointer to a line of commits, for parallel work. |
|Merge|The process of combining changes from one branch into another branch.|Combine the work of two branches.|
|Remote|A version of your repository stored on another location, usually an online platform such as GitHub, that allows collaboration.|A copy of the repository on another server, for example origin on GitHub.|
|Push/Pull/Clone|Push - Uploads your local commits to a remote repository, Pull - Downloads and combines the latest changes from a remote repository into your local repository, Clone - Creates a local copy of an existing remote repository on your computer.|Upload commits / download and integrate commits / copy a remote repository for the first time.|



