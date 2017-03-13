Microsoft Windows [版本 6.1.7601]
版权所有 (c) 2009 Microsoft Corporation。保留所有权利。

E:\git\TechGather>git status
On branch master
Your branch is up-to-date with 'origin/master'.
nothing to commit, working tree clean

E:\git\TechGather>git status
On branch master
Your branch is up-to-date with 'origin/master'.
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

E:\git\TechGather>git add README.md

E:\git\TechGather>git commit -m "M:update new"
[master fa4d776] M:update new
 1 file changed, 4 insertions(+), 1 deletion(-)

E:\git\TechGather>git push
warning: redirecting to https://github.com/yqmcu/TechGather.git/
To https://www.github.com/yqmcu/TechGather.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://www.github.com/yqmcu/TechGather.git'

hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

E:\git\TechGather>git pull README.md
fatal: Invalid gitfile format: README.md
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

E:\git\TechGather>git pull
warning: redirecting to https://github.com/yqmcu/TechGather.git/
remote: Counting objects: 3, done.
remote: Compressing objects: 100% (1/1), done.
remote: Total 3 (delta 2), reused 3 (delta 2), pack-reused 0
Unpacking objects: 100% (3/3), done.
From https://www.github.com/yqmcu/TechGather
   f576365..84e17a1  master     -> origin/master
Auto-merging README.md
CONFLICT (content): Merge conflict in README.md
Automatic merge failed; fix conflicts and then commit the result.

E:\git\TechGather>git status
On branch master
Your branch and 'origin/master' have diverged,
and have 1 and 1 different commits each, respectively.
  (use "git pull" to merge the remote branch into yours)
You have unmerged paths.
  (fix conflicts and run "git commit")
  (use "git merge --abort" to abort the merge)

Unmerged paths:
  (use "git add <file>..." to mark resolution)

        both modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

E:\git\TechGather>git pull
error: Pulling is not possible because you have unmerged files.
hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.
fatal: Exiting because of an unresolved conflict.

E:\git\TechGather>git commit
error: Committing is not possible because you have unmerged files.
hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.
fatal: Exiting because of an unresolved conflict.
U       README.md

E:\git\TechGather>git add README.md

E:\git\TechGather>git commit -m "M:"
[master d5152bb] M:

E:\git\TechGather>git push
warning: redirecting to https://github.com/yqmcu/TechGather.git/
Counting objects: 6, done.
Delta compression using up to 2 threads.
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 611 bytes | 0 bytes/s, done.
Total 6 (delta 4), reused 0 (delta 0)
remote: Resolving deltas: 100% (4/4), completed with 2 local objects.
To https://www.github.com/yqmcu/TechGather.git
   84e17a1..d5152bb  master -> master

E:\git\TechGather>git pull
warning: redirecting to https://github.com/yqmcu/TechGather.git/
remote: Counting objects: 3, done.
remote: Compressing objects: 100% (1/1), done.
remote: Total 3 (delta 2), reused 3 (delta 2), pack-reused 0
Unpacking objects: 100% (3/3), done.
From https://www.github.com/yqmcu/TechGather
   d5152bb..fc011d5  master     -> origin/master
Updating d5152bb..fc011d5
Fast-forward
 README.md | 7 +------
 1 file changed, 1 insertion(+), 6 deletions(-)

E:\git\TechGather>git add README.md

E:\git\TechGather>git commit -m "M:up"
[master 36f90f8] M:up
 1 file changed, 1 insertion(+), 1 deletion(-)

E:\git\TechGather>git push
warning: redirecting to https://github.com/yqmcu/TechGather.git/
Counting objects: 3, done.
Delta compression using up to 2 threads.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 275 bytes | 0 bytes/s, done.
Total 3 (delta 2), reused 0 (delta 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://www.github.com/yqmcu/TechGather.git
   fc011d5..36f90f8  master -> master

E:\git\TechGather>