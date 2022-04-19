[<< previous page|](./03_basic_snapshooting.md) [|main page|](./../README.md) [|next page>>](./05_sharing_and_updating_projects.md)

## Branching and Merging

---

### git branch

+ **Branch management tool** (list, create, delete)
  
  ```
  git branch <name>
  ```

### git checkout

+ **To switch branches and check content out** into a working directory
  
  ```
  git checkout <branch>
  ```

### git merge

+ **Join** two or more development histories together
  
  ```
  git merge <branch>
  ```

### git mergetool

+ **Merge conflict resolution tools** to resolve merge conflicts

    ```
    git mergetool --tool-help
    ```
    [Here](https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging#_basic_merge_conflicts) are some basic merge conflicts 

### git log

+ **Show** commit logs

    ```
    git log
    ```

    For more detail [click here](https://git-scm.com/book/en/v2/Git-Basics-Viewing-the-Commit-History#_viewing_history) or [here](https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshell#_create_new_branch) or even [here](https://git-scm.com/book/en/v2/Git-Tools-Revision-Selection#_commit_ranges)

### git stash

+ Stash the changes in a dirty working directory away

    ```
    git stash
    ```

    [Mo fya](https://git-scm.com/book/en/v2/Git-Tools-Stashing-and-Cleaning#_git_stashing)

### git tag

+ to bookmark a specific point in the code history

    + Lightweight

    ```
    git tag <version>
    ```

    + Annotated
    ```
    git tag -a <version> -m <"message">
    ```
    [Have fun](https://git-scm.com/book/en/v2/Git-Basics-Tagging#_git_tagging)


---

[<< previous page|](./03_basic_snapshooting.md) [|main page|](./../README.md) [|next page>>](./05_sharing_and_updating_projects.md)