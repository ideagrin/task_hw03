[<< previous page|](./01_setup_and_config.md) [|main page|](./../README.md) [|next page>>](./03_basic_snapshooting.md)

## Getting and Creating Projects

---

### git init

+ To create **_a new Git repository_**

  + Go to the project's directory (i.e. HW03_git_manual)
  
  ```bash=
  cd C:/Users/user/HW03_git_manual
  ```
  + Run the command to take a directory and turn it into a new Git repository with version control
  ```bash=
  git init
  ```

For more information about branch name change [use this](https://git-scm.com/book/en/v2/Git-Branching-Remote-Branches#_remote_branches).


---
### git clone

+ To get **_a copy of an existing Git repository_**
  
  + Clone a repository with
  
  ```
  git clone <url>
  ```
  + A new directory name can be specified by an additional argument
  
  ```bash=
  git clone <url> new_name
  ```

The `git clone` command is sort of container:
1. It creates a new directory; 
2. Runs `git init` to make it an empty Git repository; 
3. Adds a remote (`git remote add`) to the URL by default name _origin_; 
4. Runs a `git fetch`;  
5. Checks out the latest commit with `git checkout`.

To unbundle a bundled Git repository go [here](https://git-scm.com/book/en/v2/Git-Tools-Bundling#_bundling).



---

[<< previous page|](./01_setup_and_config.md) [|main page|](./../README.md) [|next page>>](./03_basic_snapshooting.md)