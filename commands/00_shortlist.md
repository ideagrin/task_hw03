[|main page|](./../README.md) [|next page>>](./01_setup_and_config.md)

## SHORTLIST

---

### Configuration
    git config user.name "username"
    git config user.email "email@domain.com"

### Initialize a git repository
    git init

### Add all files to be commited
    git add .

### Add one file to be commited
    git add -- file_name.ext

### Add all files inside one folder to be commited
    git add -- folder_name

### Commit
    git commit -m 'description'

### Update local repository from a remote (origin = remote name, master = branch name)
    git pull origin master

### Send commit to a remote repository
    git push origin master

### Clone a remote repository
    git clone <url>

### Show origin details (origin = remote name)
    git remote show origin

### Create a branch
    git checkout branch_name
    git checkout -b branch_name

### Merge branches
    git checkout branch_to_receive_merge
    git merge branch_to_be_merged

### Undo all changes
    git checkout .

### Undo changes in specific file
    git checkout -- file_name.ext

### Undo commit definetelly
    git reset --hard hash_to_commit_or_branch

### Finding the guilty
    git blame filename.ext

### Checking steps
    git reflog

### Checking commits
    git log


---

[|main page|](./../README.md) [|next page>>](./01_setup_and_config.md)