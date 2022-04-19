[<< previous page|](./00_shortlist.md) [|main page|](./../README.md) [|next page>>](./02_getting_and_creating_projects.md)

## Setup and Config

---

### git config 

+ **_First-Time Git Setup_** 
  
  + User *settings*
   
  ```bash=
  git config --list --show-origin
  ``` 

  + User *identity*
  
  ```bash=
  git config --global user.name "user name"
  git config --global user.email "email@domain.com"
  ```

  + User *editor* (_VS Code_ configuration)

  ```bash=
  git config --global core.editor "code --wait"
  ```

  + User *default branch name* (i.e. main)
  
  ```bash=
  git config --global init.defaultBranch main
  ```

To experience the entirety of **Git Configuraton** the hard way [click here](https://git-scm.com/book/en/v2/Customizing-Git-Git-Configuration#_git_config). 

For **Git Aliases** i.e. shorthand commands that expand to long option sequences please refer via the [link](https://git-scm.com/book/en/v2/Git-Basics-Git-Aliases#_git_aliases).

To get acquainted with the **Rebasing** (one of the  two main ways to integrate changes from one branch into another) please follow the [link](https://git-scm.com/book/en/v2/Git-Branching-Rebasing#_rebasing).

Another useful tool called **Credential Storage** which is used to set up a default store for user HTTP passwords can be found [here](https://git-scm.com/book/en/v2/Git-Tools-Credential-Storage#_credential_caching).

---

### git help

+ To view all _the documentation_ about any command with all of the possible options and flags please run

  ```bash=
  git help <command>
  ```



---

[<< previous page|](./00_shortlist.md) [|main page|](./../README.md) [|next page>>](./02_getting_and_creating_projects.md)