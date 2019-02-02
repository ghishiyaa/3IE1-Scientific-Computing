
VOPublic@LT-10109-L MINGW64 ~
$ pwd
/c/Users/VOPublic

VOPublic@LT-10109-L MINGW64 ~
$ cd Downloads/

VOPublic@LT-10109-L MINGW64 ~/Downloads
$ git config --global user.name "Ghishiyaani Thangavel"

VOPublic@LT-10109-L MINGW64 ~/Downloads
$ git config --global user.email "thangavg@mcmaster.ca"

VOPublic@LT-10109-L MINGW64 ~/Downloads
$ git config --list
core.symlinks=false
core.autocrlf=true
core.fscache=true
color.diff=auto
color.status=auto
color.branch=auto
color.interactive=true
help.format=html
rebase.autosquash=true
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
http.sslbackend=openssl
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
credential.helper=manager
user.name=Ghishiyaani Thangavel
user.email=thangavg@mcmaster.ca

VOPublic@LT-10109-L MINGW64 ~/Downloads
$ git clone https://github.com/ghishiyaa/3IE1-Scientific-Computing.git
Cloning into '3IE1-Scientific-Computing'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (6/6), done.

VOPublic@LT-10109-L MINGW64 ~/Downloads
$ git status
fatal: not a git repository (or any of the parent directories): .git

VOPublic@LT-10109-L MINGW64 ~/Downloads
$ cd 3IE1-Scientific-Computing/

VOPublic@LT-10109-L MINGW64 ~/Downloads/3IE1-Scientific-Computing (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        new_text_doc.txt

no changes added to commit (use "git add" and/or "git commit -a")

VOPublic@LT-10109-L MINGW64 ~/Downloads/3IE1-Scientific-Computing (master)
$ git add new_text_doc.txt

VOPublic@LT-10109-L MINGW64 ~/Downloads/3IE1-Scientific-Computing (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        new file:   new_text_doc.txt

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   README.md


VOPublic@LT-10109-L MINGW64 ~/Downloads/3IE1-Scientific-Computing (master)
$ git add --all

VOPublic@LT-10109-L MINGW64 ~/Downloads/3IE1-Scientific-Computing (master)
$ gir status
bash: gir: command not found

VOPublic@LT-10109-L MINGW64 ~/Downloads/3IE1-Scientific-Computing (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        modified:   README.md
        new file:   new_text_doc.txt


VOPublic@LT-10109-L MINGW64 ~/Downloads/3IE1-Scientific-Computing (master)
$ git commit -m 'added new text file;changed on local PC'
[master ac2ddbd] added new text file;changed on local PC
 2 files changed, 3 insertions(+)
 create mode 100644 new_text_doc.txt

VOPublic@LT-10109-L MINGW64 ~/Downloads/3IE1-Scientific-Computing (master)
$ git push
$ git push origin master
$ git status
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 438 bytes | 48.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/ghishiyaa/3IE1-Scientific-Computing.git
   ace2ed7..ac2ddbd  master -> master

VOPublic@LT-10109-L MINGW64 ~/Downloads/3IE1-Scientific-Computing (master)
$ $ git push origin master
bash: $: command not found

VOPublic@LT-10109-L MINGW64 ~/Downloads/3IE1-Scientific-Computing (master)
$ $ git status
bash: $: command not found

VOPublic@LT-10109-L MINGW64 ~/Downloads/3IE1-Scientific-Computing (master)
$ git pull origin master
remote: Enumerating objects: 8, done.
remote: Counting objects: 100% (8/8), done.
remote: Compressing objects: 100% (5/5), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (6/6), done.
From https://github.com/ghishiyaa/3IE1-Scientific-Computing
 * branch            master     -> FETCH_HEAD
   ac2ddbd..a396f1a  master     -> origin/master
Updating ac2ddbd..a396f1a
Fast-forward
 new_text_doc.txt | 4 +++-
 1 file changed, 3 insertions(+), 1 deletion(-)

VOPublic@LT-10109-L MINGW64 ~/Downloads/3IE1-Scientific-Computing (master)
$ cd ..

VOPublic@LT-10109-L MINGW64 ~/Downloads
$ git clone https://github.com/jasonbrodeur/EC_Wx_tools.git
Cloning into 'EC_Wx_tools'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 104 (delta 0), reused 0 (delta 0), pack-reused 101
Receiving objects: 100% (104/104), 1.92 MiB | 6.86 MiB/s, done.
Resolving deltas: 100% (56/56), done.

VOPublic@LT-10109-L MINGW64 ~/Downloads
$ cd 3IE1-Scientific-Computing/

VOPublic@LT-10109-L MINGW64 ~/Downloads/3IE1-Scientific-Computing (master)
$ git pull
remote: Enumerating objects: 45, done.
remote: Counting objects: 100% (45/45), done.
remote: Compressing objects: 100% (44/44), done.
remote: Total 44 (delta 17), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (44/44), done.
From https://github.com/ghishiyaa/3IE1-Scientific-Computing
   a396f1a..9a82bf6  master     -> origin/master
Updating a396f1a..9a82bf6
Fast-forward
 Getting to Know Markdown.md |  66 ++++++++++++++++++++++++++++++++++++++++++++
 download.png                | Bin 0 -> 6399 bytes
 2 files changed, 66 insertions(+)
 create mode 100644 Getting to Know Markdown.md
 create mode 100644 download.png

VOPublic@LT-10109-L MINGW64 ~/Downloads/3IE1-Scientific-Computing (master)
