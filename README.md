# Odin-recipes
This Website Consists of a Main Index Page and links to a few Pages with Deliciious recipes.
This was a project that i created to asisst me in polishing up my html skills
I also polished my Git Bash knowledge and was able to use Git to Clone repositories from Github remotely.
I also used CSS to center the page layout and also for aesthetics

I also Experienced Issues below as i was trying to Push the project to Git hub. 



  + FullyQualifiedErrorId : PathNotFound,Microsoft.PowerShell.Commands.SetLocationCommand
 
 Tried to get to the Repos Folder and Push the Project to Gibt Hub

PS C:\Users\OnlyM\OneDrive\Desktop\\Repos> % cd repos

and below is the responce from the terminal

% : Es ist nicht möglich, eine Methode für einen Ausdruck aufzurufen, der den NULL hat.
In Zeile:1 Zeichen:1
+ % cd repos
+ ~~~~~~~~~~
    + CategoryInfo          : InvalidArgument: (:PSObject) [ForEach-Object], PSArgumentException
    + FullyQualifiedErrorId : InvokeMethodOnNull,Microsoft.PowerShell.Commands.ForEachObjectCommand
    
    Googled to find a solution. At this point i am running around like a headless chicken.


PS C:\Users\OnlyM\OneDrive\Desktop\\Repos> git repos

        rebase
        reflog
        refs
        remote
        repack
        replay
        
        So lets try to push it again.


PS C:\Users\OnlyM\OneDrive\Desktop\\Repos> git push

and this was the responce from my Git CLi Terminal

fatal: not a git repository (or any of the parent directories): .git
PS C:\Users\OnlyM\OneDrive\Desktop\\Repos> git init
Initialized empty Git repository in C:/Users/OnlyM/OneDrive/Desktop//Repos/.git/

Still running like a headless Chicken. 
PS C:\Users\OnlyM\OneDrive\Desktop\\Repos> git add .
warning: adding embedded git repository: Odin-recipes
hint: You've added another git repository inside your current repository.
hint: Clones of the outer repository will not contain the contents of
hint: the embedded repository and will not know how to obtain it.
hint:
hint:
hint: If you added this path by mistake, you can remove it from the
hint: index with:
hint:








 *  History restored 
~
PS C:\Users\OnlyM\OneDrive\Desktop\\Repos> git add -A
PS C:\Users\OnlyM\OneDrive\Desktop\\Repos> git init                               
Reinitialized existing Git repository in C:/Users/OnlyM/OneDrive/Desktop//Repos/.git/
PS C:\Users\OnlyM\OneDrive\Desktop\\Repos> git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Disable this message with "git config set advice.addEmptyPathspec false"
PS C:\Users\OnlyM\OneDrive\Desktop\\Repos>  git remote add origin https://github.com/Den4cipes.git        
PS C:\Users\OnlyM\OneDrive\Desktop\\Repos> git push origin main
error: src refspec main does not match any                               
error: failed to push some refs to 'https://github.com/username/Odin-recipes.git'
PS C:\Users\OnlyM\OneDrive\Desktop\\Repos> 
 *  History restored 

PS C:\Users\OnlyM\OneDrive\Desktop\\Repos> 
 *  History restored 

oder eines ausführbaren Programms erkannt. Überprüfen Sie die Schreibweise des Namens, oder ob der    
In Zeile:1 Zeichen:1
+ touch Honeychicken.html
+ ~~~~~
    + CategoryInfo          : ObjectNotFound: (touch:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\OnlyM\OneDrive\Desktop\\Repos> code honeychicken.html
PS C:\Users\OnlyM\OneDrive\Desktop\\Repos>
 *  History restored 


No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Odin-recipes/

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\OnlyM\OneDrive\Desktop\\Repos> git add .
PS C:\Users\OnlyM\OneDrive\Desktop\\Repos> git status

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   Odin-recipes/README.md
        new file:   Odin-recipes/honeychicken.html
        new file:   Odin-recipes/index.html

 4 files changed, 210 insertions(+)
 create mode 100644 Odin-recipes/README.md
 create mode 100644 Odin-recipes/Recipes/Lasagna.html
 create mode 100644 Odin-recipes/honeychicken.html
 create mode 100644 Odin-recipes/index.html
PS C:\Users\OnlyM\OneDrive\Desktop\\Repos> git push -f origin masterPS C:\Users\OnlyM\OneDrive\Desktop\\Repos> git push -f origin fspec master does not match any
master                                                                            in https://github.co
error: src refspec master does not match any                         mote add orig
error: src refspec master does not match any                         sh -f origin master
error: failed to push some refs to 'origin'
PS C:\Users\OnlyM\OneDrive\Desktop\\Repos> git push -f origin 'sh -f origin master
error: src refspec master does not match any
error: failed to push some refs to 'https://github.com/username/Odin-Recipes.gitn-Recipes.git'
PS C:\Users\OnlyM\OneDrive\Desktop\\Repos> git commit -m "initial commit"
On branch main
nothing to commit, working tree clean
PS C:\Users\OnlyM\OneDrive\Desktop\\Repos> git push origin main
To https://github.com/username/Odin-Recipes.git
n-Recipes.git'
hint: Updates were rejected because the remote contains work that youn-Recipes.git' do not                                                               do not
hint: have locally. This is usually caused by another repository pushing tohint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
PS C:\Users\OnlyM\OneDrive\Desktop\\Repos> git refs
error: need a subcommand
usage: git refs migrate --ref-format=<format> [--dry-run]

PS C:\Users\OnlyM\OneDrive\Desktop\\Repos> git clone git@github.com:username/Odin-recipes.git
fatal: destination path 'Odin-recipes' already exists and is not an empty directory.
PS C:\Users\OnlyM\OneDrive\Desktop\\Repos> git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        renamed:    Odin-recipes/honeychicken.html -> Odin-recipes/Recipes/honeychicken.html

PS C:\Users\OnlyM\OneDrive\Desktop\\Repos> git commit -m "First Commit"
[main 4f92257] First Commit
 rename Odin-recipes/{ => Recipes}/honeychicken.html (100%)
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

error: remote origin already exists.
PS C:\Users\OnlyM\OneDrive\Desktop\\Repos> git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking

 ! [rejected]        main -> main (fetch first)
hint: Updates were rejected because the remote contains work that you do not
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
PS C:\Users\OnlyM\OneDrive\Desktop\\Repos> git init
Initialized empty Git repository in C:/Users/OnlyM/OneDrive/Desktop//Repos/.git/
PS C:\Users\OnlyM\OneDrive\Desktop\\Repos> git add .
PS C:\Users\OnlyM\OneDrive\Desktop\\Repos> git commit -main "first commit"
error: pathspec 'first commit' did not match any file(s) known to git
[main (root-commit) c5fc895] initial commit
 4 files changed, 210 insertions(+)
 create mode 100644 Odin-recipes/README.md
 create mode 100644 Odin-recipes/Recipes/Lasagna.html
 create mode 100644 Odin-recipes/Recipes/honeychicken.html
 create mode 100644 Odin-recipes/index.html
PS C:\Users\OnlyM\OneDrive\Desktop\\Repos> git remote add origin https://github.com/username/Odin-Recipes.git
PS C:\Users\OnlyM\OneDrive\Desktop\\Repos> git remote -v
origin  https://github.com/username/Odin-Recipes.git (push)
PS C:\Users\OnlyM\OneDrive\Desktop\\Repos> git push origin main
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/username/Odin-Recipes.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
PS C:\Users\OnlyM\OneDrive\Desktop\\Repos> git push origin master
error: failed to push some refs to 'https://github.com/username/Odin-Recipes.git'
PS C:\Users\OnlyM\OneDrive\Desktop\\Repos> git push origin main
To https://github.com/username/Odin-Recipes.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/username/Odin-Recipes.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
PS C:\Users\OnlyM\OneDrive\Desktop\\Repos> git pull
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 868 bytes | 28.00 KiB/s, done.
From https://github.com/username/Odin-Recipes
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

PS C:\Users\OnlyM\OneDrive\Desktop\\Repos> git push -u origin main
To https://github.com/username/Odin-Recipes.git
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/username/Odin-Recipes.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. If you want to integrate the remote changes,
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
PS C:\Users\OnlyM\OneDrive\Desktop\\Repos> git config --global push.autoSetupRemote true
PS C:\Users\OnlyM\OneDrive\Desktop\\Repos> git push
To https://github.com/username/Odin-Recipes.git
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/username/Odin-Recipes.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. If you want to integrate the remote changes,
hint: use 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=origin/<branch> main

fatal: the requested upstream branch 'origin/<branch>' does not exist
hint:
hint: If you are planning on basing your work on an upstream
hint: branch that already exists at the remote, you may need to
hint: run "git fetch" to retrieve it.
hint:
hint: If you are planning to push out a new local branch that
hint: "git push -u" to set the upstream config as you push.
hint: Disable this message with "git config set advice.setUpstreamFailure false"
PS C:\Users\OnlyM\OneDrive\Desktop\\Repos> git push -u
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/username/Odin-Recipes.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. If you want to integrate the remote changes,
hint: use 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
PS C:\Users\OnlyM\OneDrive\Desktop\\Repos> git pull --rebase origin main
From https://github.com/username/Odin-Recipes
 * branch            main       -> FETCH_HEAD
PS C:\Users\OnlyM\OneDrive\Desktop\\Repos> git push -u origin main
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 4 threads
Compressing objects: 100% (8/8), done.
Writing objects: 100% (8/8), 5.40 KiB | 425.00 KiB/s, done.
Total 8 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/username/Odin-Recipes.git
   41b21f8..226b4c3  main -> main
branch 'main' set up to track 'origin/main'.
PS C:\Users\OnlyM\OneDrive\Desktop\\Repos> git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
PS C:\Users\OnlyM\OneDrive\Desktop\\Repos> 
