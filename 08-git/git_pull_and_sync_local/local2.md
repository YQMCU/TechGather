Microsoft Windows [版本 6.1.7601]
版权所有 (c) 2009 Microsoft Corporation。保留所有权利。

E:\git - 副本>git clone https://www.github.com/yqmcu/TechGather.git
Cloning into 'TechGather'...
warning: redirecting to https://github.com/yqmcu/TechGather.git/
remote: Counting objects: 147, done.
remote: Compressing objects: 100% (111/111), done.
remote: Total 147 (delta 39), reused 132 (delta 28), pack-reused 0R
Receiving objects:  48%00 KiB | 8.00 KiB/s
Receiving objects: 100% (147/147), 65.50 KiB | 8.00 KiB/s, done.
Resolving deltas: 100% (39/39), done.

E:\git - 副本>git status
fatal: Not a git repository (or any of the parent directories): .git

E:\git - 副本>git status
fatal: Not a git repository (or any of the parent directories): .git

E:\git - 副本>cd ../git

E:\git>git status
fatal: Not a git repository (or any of the parent directories): .git

E:\git>cd ../git - 副本

E:\git - 副本>cd TechGather

E:\git - 副本\TechGather>git status
On branch master
Your branch is up-to-date with 'origin/master'.
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

E:\git - 副本\TechGather>git add README.md

E:\git - 副本\TechGather>git commit -m "M:update"
[master 84e17a1] M:update
 1 file changed, 4 insertions(+), 1 deletion(-)

E:\git - 副本\TechGather>git push
warning: redirecting to https://github.com/yqmcu/TechGather.git/
Counting objects: 3, done.
Delta compression using up to 2 threads.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 281 bytes | 0 bytes/s, done.
Total 3 (delta 2), reused 0 (delta 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://www.github.com/yqmcu/TechGather.git
   f576365..84e17a1  master -> master

E:\git - 副本\TechGather>git pull -m
error: unknown switch `m'
usage: git pull [<options>] [<repository> [<refspec>...]]

    -v, --verbose         be more verbose
    -q, --quiet           be more quiet
    --progress            force progress reporting

Options related to merging
    -r, --rebase[=<false|true|preserve|interactive>]
                          incorporate changes by rebasing rather than merging
    -n                    do not show a diffstat at the end of the merge
    --stat                show a diffstat at the end of the merge
    --log[=<n>]           add (at most <n>) entries from shortlog to merge commi
t message
    --squash              create a single commit instead of doing a merge
    --commit              perform a commit if the merge succeeds (default)
    --edit                edit message before committing
    --ff                  allow fast-forward
    --ff-only             abort if fast-forward is not possible
    --verify-signatures   verify that the named commit has a valid GPG signature

    --autostash           automatically stash/stash pop before and after rebase
    -s, --strategy <strategy>
                          merge strategy to use
    -X, --strategy-option <option=value>
                          option for selected merge strategy
    -S, --gpg-sign[=<key-id>]
                          GPG sign commit
    --allow-unrelated-histories
                          allow merging unrelated histories

Options related to fetching
    --all                 fetch from all remotes
    -a, --append          append to .git/FETCH_HEAD instead of overwriting
    --upload-pack <path>  path to upload pack on remote end
    -f, --force           force overwrite of local branch
    -t, --tags            fetch all tags and associated objects
    -p, --prune           prune remote-tracking branches no longer on remote
    --recurse-submodules[=<on-demand>]
                          control recursive fetching of submodules
    -j, --jobs[=<n>]      number of submodules pulled in parallel
    --dry-run             dry run
    -k, --keep            keep downloaded pack
    --depth <depth>       deepen history of shallow clone
    --unshallow           convert to a complete repository
    --update-shallow      accept refs that update .git/shallow
    --refmap <refmap>     specify fetch refmap


E:\git - 副本\TechGather>git fetch
warning: redirecting to https://github.com/yqmcu/TechGather.git/
remote: Counting objects: 6, done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 6 (delta 4), reused 6 (delta 4), pack-reused 0
Unpacking objects: 100% (6/6), done.
From https://www.github.com/yqmcu/TechGather
   84e17a1..d5152bb  master     -> origin/master

E:\git - 副本\TechGather>start .

E:\git - 副本\TechGather>git pull
warning: redirecting to https://github.com/yqmcu/TechGather.git/
Updating 84e17a1..d5152bb
Fast-forward
 README.md | 4 ++++
 1 file changed, 4 insertions(+)

E:\git - 副本\TechGather>git add README.md

E:\git - 副本\TechGather>git commit -m "M:update"
[master fc011d5] M:update
 1 file changed, 1 insertion(+), 6 deletions(-)

E:\git - 副本\TechGather>git push
warning: redirecting to https://github.com/yqmcu/TechGather.git/
Counting objects: 3, done.
Delta compression using up to 2 threads.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 279 bytes | 0 bytes/s, done.
Total 3 (delta 2), reused 0 (delta 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://www.github.com/yqmcu/TechGather.git
   d5152bb..fc011d5  master -> master

E:\git - 副本\TechGather>git add README.md

E:\git - 副本\TechGather>git commit -m "M:"
On branch master
Your branch is up-to-date with 'origin/master'.
nothing to commit, working tree clean

E:\git - 副本\TechGather>git add README.md

E:\git - 副本\TechGather>git commit -m "M:"
[master e99054b] M:
 1 file changed, 1 insertion(+), 1 deletion(-)

E:\git - 副本\TechGather>git push
warning: redirecting to https://github.com/yqmcu/TechGather.git/
To https://www.github.com/yqmcu/TechGather.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://www.github.com/yqmcu/TechGather.git'

hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

E:\git - 副本\TechGather>git push
warning: redirecting to https://github.com/yqmcu/TechGather.git/
To https://www.github.com/yqmcu/TechGather.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://www.github.com/yqmcu/TechGather.git'

hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

E:\git - 副本\TechGather>git reset -h
usage: git reset [--mixed | --soft | --hard | --merge | --keep] [-q] [<commit>]
   or: git reset [-q] [<tree-ish>] [--] <paths>...
   or: EXPERIMENTAL: git reset [-q] [--stdin [-z]] [<tree-ish>]
   or: git reset --patch [<tree-ish>] [--] [<paths>...]

    -q, --quiet           be quiet, only report errors
    --mixed               reset HEAD and index
    --soft                reset only HEAD
    --hard                reset HEAD, index and working tree
    --merge               reset HEAD, index and working tree
    --keep                reset HEAD but keep local changes
    -p, --patch           select hunks interactively
    -N, --intent-to-add   record only the fact that removed paths will be added
later
    -z                    EXPERIMENTAL: paths are separated with NUL character
    --stdin               EXPERIMENTAL: read paths from <stdin>


E:\git - 副本\TechGather>git reset HEAD^
More?
More?
fatal: ambiguous argument 'HEAD
': unknown revision or path not in the working tree.
Use '--' to separate paths from revisions, like this:
'git <command> [<revision>...] -- [<file>...]'

E:\git - 副本\TechGather>
E:\git - 副本\TechGather>git checkout README.md

E:\git - 副本\TechGather>git pull
warning: redirecting to https://github.com/yqmcu/TechGather.git/
remote: Counting objects: 3, done.
remote: Compressing objects: 100% (1/1), done.
remote: Total 3 (delta 2), reused 3 (delta 2), pack-reused 0
Unpacking objects: 100% (3/3), done.
From https://www.github.com/yqmcu/TechGather
   fc011d5..36f90f8  master     -> origin/master
Auto-merging README.md
CONFLICT (content): Merge conflict in README.md
Automatic merge failed; fix conflicts and then commit the result.

E:\git - 副本\TechGather>git reset --hard 36f90f8b926e4db941fb14b1123d39c49ff113
74
HEAD is now at 36f90f8 M:up

E:\git - 副本\TechGather>git reset --hard 36f90f8b926e4db941fb14b1123d39c49ff113
74
HEAD is now at 36f90f8 M:up

E:\git - 副本\TechGather>git pull
warning: redirecting to https://github.com/yqmcu/TechGather.git/
Already up-to-date.

E:\git - 副本\TechGather>