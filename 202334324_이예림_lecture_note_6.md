# Lecture Note 6
### 202334324 이예림
---

### Git
Version Control System and Source Code Management.

### Git Configuration

Git configurations are stored in three levels.

  System: --system option. Affects all uses and repositories on the system(administrative).  
    file: /etc/gitconfig
   Global: --global option. Affects all repositories of a current user.  
    file: ~/.config/git/config
   Local: --local option. Specific to the current repository.  
    file: .git/config

Each level over rides values in the previous level: system -> global -> local

---

 $ git init: Initializing a Repository in an Existing Directory.

 $ git status: Checking Repository Status.

 $ git add[filename]: Adding a new file to be staged.

 $ git rm--cached[filename]: Unstaging a file.

 $ git commit -m "message": Committing a file.

 $ git branch: Changing the branch.

.gitignore: Ignoring files.
