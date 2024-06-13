#Assignment | Git & GitHub
TASKS 
1. Fork the repository ( https://github.com/engineerbaz/docker-file.git ) by clicking on the Fork button on the upper right corner.

2. Clone your forked repository with git clone

3. Create some files in the default branch.

4. Make a branch in it as prod (git branch prod) and a few files

5. Push changes in in prod branch to Github only

6. Create a file of your Task in Markdown language and upload.



5. Push changes in in prod branch to Github only


root@osama-Virtual-Machine:/home/osama/GitLocal/testrepo1# git branch
* main
root@osama-Virtual-Machine:/home/osama/GitLocal/testrepo1# git checkout -b PROD1
Switched to a new branch 'PROD1'
root@osama-Virtual-Machine:/home/osama/GitLocal/testrepo1# git branch
* PROD1
  main
root@osama-Virtual-Machine:/home/osama/GitLocal/testrepo1# git checkout PROD1
Already on 'PROD1'
root@osama-Virtual-Machine:/home/osama/GitLocal/testrepo1# git remote -v
origin  https://osamamansoor1986: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@github.com/osamamansoor1986/testrepo1.git (fetch)
origin  https://osamamansoor1986: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@github.com/osamamansoor1986/testrepo1.git (push)
root@osama-Virtual-Machine:/home/osama/GitLocal/testrepo1# git remote add Prod https://github.com/osamamansoor1986/testrepo1.git
root@osama-Virtual-Machine:/home/osama/GitLocal/testrepo1# git remote -v
Prod    https://github.com/osamamansoor1986/testrepo1.git (fetch)
Prod    https://github.com/osamamansoor1986/testrepo1.git (push)
origin  https://osamamansoor1986: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@github.com/osamamansoor1986/testrepo1.git (fetch)
origin  https://osamamansoor1986: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@github.com/osamamansoor1986/testrepo1.git (push)
root@osama-Virtual-Machine:/home/osama/GitLocal/testrepo1# git remote set-url Prod https://osamamansoor1986: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@github.com/osamamansoor1986/testrepo1.git
root@osama-Virtual-Machine:/home/osama/GitLocal/testrepo1# git push -u Prod PROD
error: src refspec PROD does not match any
error: failed to push some refs to 'https://github.com/osamamansoor1986/testrepo1.git'
root@osama-Virtual-Machine:/home/osama/GitLocal/testrepo1# git push -u Prod PROD1
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 258 bytes | 258.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'PROD1' on GitHub by visiting:
remote:      https://github.com/osamamansoor1986/testrepo1/pull/new/PROD1
remote:
To https://github.com/osamamansoor1986/testrepo1.git
 * [new branch]      PROD1 -> PROD1
branch 'PROD1' set up to track 'Prod/PROD1'.
root@osama-Virtual-Machine:/home/osama/GitLocal/testrepo1# git branch
* PROD1
  main
root@osama-Virtual-Machine:/home/osama/GitLocal/testrepo1# touch "pakistan" > Pakistan.txt
root@osama-Virtual-Machine:/home/osama/GitLocal/testrepo1# git add .
root@osama-Virtual-Machine:/home/osama/GitLocal/testrepo1# git commit -m "pakistan file addition"
[PROD1 e81d9e9] pakistan file addition
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Pakistan.txt
 create mode 100644 pakistan
root@osama-Virtual-Machine:/home/osama/GitLocal/testrepo1# git push -u Prod PROD1
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 262 bytes | 262.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/osamamansoor1986/testrepo1.git
   aaa3c32..e81d9e9  PROD1 -> PROD1
branch 'PROD1' set up to track 'Prod/PROD1'.
root@osama-Virtual-Machine:/home/osama/GitLocal/testrepo1#

