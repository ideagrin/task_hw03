[<< previous page|](./05_sharing_and_updating_projects.md) [|main page|](./../README.md) [|next page>>](./07_debugging.md)

## Inspection and Comparison

---

### git show

+ Shows various types of objects (blobs, trees, tags and commits)
  
  ```
  git show [<options>] [<object>…​]
  ```
### git shortlog

+ `git log` output summary
  
  ```
  git shortlog [<options>] [<revision-range>] [[--] <path>…​]
  ```

### git describe

+ Gives an object a readable name based on an available ref (requires annotated tags (`-a` or `-s` flag), or non-annotated tags, add the `--tags` option to the command)
  ```
  git describe [--all] [--tags] [--contains] [--abbrev=<n>] [<commit-ish>…​]
  ```



---

[<< previous page|](./05_sharing_and_updating_projects.md) [|main page|](./../README.md) [|next page>>](./07_debugging.md)