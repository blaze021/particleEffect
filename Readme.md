### Terminal Logs

IT33520+locadm@IT33520 MINGW64 /e/projects/particle_effect
$ git init
Initialized empty Git repository in E:/projects/particle_effect/.git/

IT33520+locadm@IT33520 MINGW64 /e/projects/particle_effect (master)
$ git add README.md
fatal: pathspec 'README.md' did not match any files

IT33520+locadm@IT33520 MINGW64 /e/projects/particle_effect (master)
$ git add .

IT33520+locadm@IT33520 MINGW64 /e/projects/particle_effect (master)
$ git commit -m "Boilerplate code for particle effect"
[master (root-commit) 2b2574a] Boilerplate code 
for particle effect
 Committer: unknown <locadm@IT33520.vecvnet.com>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used 
for this commit with:

    git commit --amend --reset-author

 3 files changed, 114 insertions(+)
 create mode 100644 index.html
 create mode 100644 script.js
 create mode 100644 style.css

IT33520+locadm@IT33520 MINGW64 /e/projects/particle_effect (master)
$ git branch -M main

IT33520+locadm@IT33520 MINGW64 /e/projects/particle_effect (main)
$ git remote add origin https://github.com/blaze021/particleEffect.git

IT33520+locadm@IT33520 MINGW64 /e/projects/particle_effect (main)
$ git push -u origin main
info: please complete authentication in your browser...
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 1.36 KiB | 277.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/blaze021/particleEffect.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.

IT33520+locadm@IT33520 MINGW64 /e/projects/particle_effect (main)
$ git config --global user.name "blaze021"

IT33520+locadm@IT33520 MINGW64 /e/projects/particle_effect (main)
$ git config --global user.email "tarunblaze@gmail.com"