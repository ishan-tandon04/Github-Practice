# Github-Practice
1. Clone sets origin to a reference to the remote repo
2. git branch --set-upstream origin main sets the default remote branch to main for the current local branch; remote tracking branches are references to the state of remote branches
3. In the commit tree, it pulls from origin and master and then merges them together in the local branch
4.  Unless you force pull, it will not overwrite the commit
5.  Merge
6.  No, it is still behind the remote master
7.  Yes it was delted, now only contains the main branch
8.
```
    commit 3056d2341b7b9716ceff5e1c6b7f1ac85b595275 (HEAD -> main, origin/main, origin/HEAD)
|\  Merge: eeb4628 3e597d3
| | Author: Kevin Lou <58053969+klou23@users.noreply.github.com>
| | Date:   Wed Oct 20 13:59:57 2021 -0600
| | 
| |     Merge pull request #2 from ishan-tandon04/Feature2
| |     
| |     Just added a new edit
| |   
| *   commit 3e597d3e0b538338bd1aea4ec70b5dab90236a30
| |\  Merge: a54de53 eeb4628
| |/  Author: Kevin Lou <58053969+klou23@users.noreply.github.com>
|/|   Date:   Wed Oct 20 13:59:39 2021 -0600
| |   
| |       Merge branch 'main' into Feature2
| |   
* |   commit eeb462889e9ae1c32d0f7aa555545e40d98f7d32
|\ \  Merge: 2b7e7b8 3729f14
| | | Author: Kevin Lou <58053969+klou23@users.noreply.github.com>
| | | Date:   Wed Oct 20 13:53:33 2021 -0600
| | | 
| | |     Merge branch 'main' of https://github.com/ishan-tandon04/Github-Practi:
```
