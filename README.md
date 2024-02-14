# A02
**Part 1 Git/GitHub/Webstrom**

1. How To Download Git
    - To download Git on Windows you can this link https://git-scm.com/downloads and get it for free
    - On Mac Git should be installed if not you can download it from Homebrew. First, install Homebrew by pasting             "/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)" into the               terminal. Then, to install Git, paste "brew install git" into the terminal.
    - Type git version into your terminal/command line to check if it's installed.
2. How to Join GitHub
     - You go on your favorite web browser and go to Github https://github.com/ and create an account here
3. Webstrom
    - You can install Webstrom from this link https://www.jetbrains.com/student/
    - Once installed click on it in downloads and continue clicking next until the end
    - Once WebStroms pop up you can do the free trial or click the bottom button if you have a license from JetBrains
4. Connecting Git to Webstrom
    - In Webstorm press (Ctrl+Alt+S) or (CMD + ,) for system preferences.
    - Click on Version Control then Git.
    - Enter the path to your git.exe
    - Click test to make sure it works if yes click OK on the right if not you typed the path wrong
5. Create a Repository on GitHub
    - On the homepage click on the + sign on the upper right
    - Click Create New Repository 
    - Then click Create Repository
6. How to Import a Repository from Gitthub
   - In the repository, click the green "Code" button and copy the HTTPS URL.
   - If you closed Webstorm, open it up again.
   - From the first screen (what you see after launching the app), select "Get from VCS."
   - Paste the HTTPS (GitHub) URL and click "Clone."
7. Push a File to Github
   - To create an HTML file, choose "File," then "HTML file." (CSS is stylesheet)
   - Click "Add" to add the files to Git.
   - At the top of Webstorm, click "Git" and then "commit."
   - Then, a text box should appear; add your commit message (YOU HAVE TO ADD ONE) and click "Commit."
   - Go to VCS -> Git -> Push or Ctrl ->Shift -> K
   - Select the committed file and click "Push."
   - The file should now be on Github

**Part 2 Definitions for Terms**
- **Branch**: A copy of the main **repository**. **Branches** can be a new version of a **repository**, experimental changes, or personal forks of a **repository** for users to alter and test changes.
- **Clone**: A **clone** is an exact copy of a **repository**. When **cloning** a **repository** into another **branch**, the new **branch** becomes a remote-tracking **branch** that can talk upstream to its origin **branch** (via **pushes**, **pulls**, and **fetches**).
- **Commit**: The action of saving changes made to a file or set of files. They should always have a message, such as a brief description of what has changed.
- **Fetch**: You are downloading and copying that **branch's** files to your workstation. Multiple **branches** can be **fetched** at once.
- **GIT**: An open-source software used for tracking and documenting your changes in files via a version control system.
- **Github**: A platform that hosts repositories and helps users store files, track code, and collaborate on projects (with version control).
- **Merge**: Taking the changes from one **branch** and adding them into another (normally main) **branch**. These **commits** are usually first requested via **pull** request before being **merged** by someone.
- **Merge Conflict**: An error when **merging** is usually because two things are merging at the same time.
- **Push**: Updates a **remote** **branch** with the commits made to the current **branch**.
- **Pull**: This is when adding the changes to the main **branch**.
 -**Remote**: A copy of the original **branch**.
- **Repository**: This is a directory that stores all the files, folders, and content needed for your project.

**References**
Ajibola, Segun. “How to Use Git and GitHub – Introduction for Beginners.” freeCodeCamp, 26 Sept. 2022, www.freecodecamp.org/news/introduction-to-git-and-github/#what-are-git-and-github. 
GeeksforGeeks. “Git Merge and Merge Conflict.” GeeksforGeeks, 5 Apr. 2022, www.geeksforgeeks.org/git-merge-and-merge-conflict. 
Git. “A Git Glossary.” Git, git-scm.com/docs/gitglossary#def_chain. 
Hendela, Arthur. “Introduction to Github and Webstorm.” Canvas, 18 Mar. 2019, njit.instructure.com/courses/33677/files/5972199?module_item_id=1281701. 
Krout, Elle. “Git Definitions and Terminology Cheat Sheet.” Pluralsight, 8 June 2023, www.pluralsight.com/resources/blog/cloud/git-terms-explained#merge. 
W3Schools. “Git Commit.” W3Schools, www.w3schools.com/git/git_commit.asp.  
