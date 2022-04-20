[<< previous page|](./07_debugging.md) [|main page|](./../README.md) [|next page>>](./09_email.md)

## Patching

---

### git cherry-pick

+ Takes the patch that was introduced in a commit and tries to reapply it on the current branch
  
  ```
  git cherry-pick <keyid>
  ```

### git rebase

+ Reapply a series of commits one by one in the same order somewhere else
  
  ```
  git rebase [description]
  ```

  Check [Rebasing](https://git-scm.com/book/en/v2/Git-Branching-Rebasing#_rebasing)

### git revert

+ Revert some existing commits
  
  ```
  git revert [description]
  ```
  
  Check [Reverse the commit](https://git-scm.com/book/en/v2/Git-Tools-Advanced-Merging#_reverse_commit)
---

[<< previous page|](./07_debugging.md) [|main page|](./../README.md) [|next page>>](./09_email.md)