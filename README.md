# https-work-in-git
This repository to understand git https
Commands for remote and example as mentioned below
**git remote -v**
**git remote set-url origin https://<token>@github.com/amit-burnwal/https-work-in-git.git
**
ubuntu@git-learn:~/https-work-in-git$ **git remote -v**
origin  https://github.com/amit-burnwal/https-work-in-git.git (fetch)
origin  https://github.com/amit-burnwal/https-work-in-git.git (push)

ubuntu@git-learn:~/https-work-in-git$ git remote set-url origin https://<token>@github.com/amit-burnwal/https-work-in-git.git

ubuntu@git-learn:~/https-work-in-git$ git remote -v
origin  https://<token>@github.com/amit-burnwal/https-work-in-git.git (fetch)
origin  https://<token>@github.com/amit-burnwal/https-work-in-git.git (push)

ubuntu@git-learn:~/https-work-in-git$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
ubuntu@git-learn:~/https-work-in-git$ git push origin main
