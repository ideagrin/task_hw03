[<< previous page|](02_getting_and_creating_projects.md) [|main page|](./../README.md) [|next page>>](./04_branching_and_merging.md)

## Basic Snapshooting

---

### git add

+ Used to **add content from** the working directory **into** the staging area (or “index”) **for** the next commit
  
  + To begin tracking a new file
  
  ```
  git add <file> 
  ```

  +  If it’s a directory, the command adds all the files in that directory
  
  ```
  git add *
  ```

Can be utilized to solve [basic merge conflicts](https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging#_basic_merge_conflicts)

---

### git status

+ Working directory and staging area file **status report** (modified and unstaged, staged and not yet committed, basic hints how to solve issues)
  
  ```
  git status
  ```

Pretty much all the info is covered [here](https://git-scm.com/book/en/v2/Git-Basics-Recording-Changes-to-the-Repository#_checking_status)

---

### git diff

+ _Differences_ between two trees
  + Working environment vs. staging area
  
  ```
  git diff
  ```
  
  + Staging area vs. last commit
  
  ```
  git diff --staged
  ```
  
  + Commit vs. commit
  
  ```
  git diff master branchB
  ```

  + [Staged vs. Unstages changes](https://git-scm.com/book/en/v2/Git-Basics-Recording-Changes-to-the-Repository#_git_diff_staged)
  + [Possible whitespace issues](https://git-scm.com/book/en/v2/Distributed-Git-Contributing-to-a-Project#_commit_guidelines)
  + [A/B branch comparison](https://git-scm.com/book/en/v2/Distributed-Git-Maintaining-a-Project#_what_is_introduced)
  
---

### git difftool

+ _External tool_ to show the difference between two trees
  
  ``` 
  git difftool
  ```

---

### git commit

+ **Record changes to the repository**, takes all the _staged file contents_ and records a new permanent snapshot in the database
  
  ```
  git commit
  ``` 

Options / additional flags
+ `-m <msg>` - Use the given message as the commit message;
+ `-a` - a simple shortcut to _skip the staging area_;
+ `--amend` - redo the most recent commit
+ `-S` - to sign an individual commit

---

### git reset

+ To **undo** things (e.g. unstaging a staged file)
  
  ```
  git reset HEAD <file>
  ```
  + *HEAD* - Last commit snapshot, the last commit on a branch.
  + *Index* - Proposed next commit
  + *The Working Directory* - Sandbox

Options / additional flags
+  The command returns the HEAD pointer and optionally changes the index or staging area and can also optionally change the working directory if `--hard` flag is used.

---

### git rm

+ **To remove files** from the staging area and working directory
  ```
  git rm <file>
  ```
Options / additional flags
+ `-f` - force removal, when the file was modified and already staged;
+ `--cached` - to keep the file in the working tree but remove it from staging area;
+ `git rm \*~` - removes all files whose names end with a ~ 

---

### git mv

+ To move a file and then run `git add` on the new file and `git rm` on the old file, thus **to rename a file**
  
  ```
  git mv <file_from> <file_to>
  ```

---

### git clean

+ **To remove** not tracked files from your working directory
  
  ```
  git clean -f -d
  ```


---



[<< previous page|](02_getting_and_creating_projects.md) [|main page|](./../README.md) [|next page>>](./04_branching_and_merging.md)