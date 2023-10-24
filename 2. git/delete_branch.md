# Delete Local Branch
```console
git branch -d <branch_name>
git branch -D <branch_name>
```
> -d alias for --delete, which only deletes if it has already been fully merged in its upstream branch
> 
> -D alias for --delete --force, which deletes the branch "irrespective of its merged status."

# Delete Remote Branch
```console
git push <remote_name> --delete <branch_name>
# eg:
git push origin --delete duc.dinh.ng
```
