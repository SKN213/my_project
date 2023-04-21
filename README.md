KIIT@DESKTOP-HS2QJ56 MINGW64 ~
$ git config --list --show-origin
file:C:/Program Files/Git/etc/gitconfig diff.astextplain.textconv=astextplain
file:C:/Program Files/Git/etc/gitconfig filter.lfs.clean=git-lfs clean -- %f
file:C:/Program Files/Git/etc/gitconfig filter.lfs.smudge=git-lfs smudge -- %f
file:C:/Program Files/Git/etc/gitconfig filter.lfs.process=git-lfs filter-process
file:C:/Program Files/Git/etc/gitconfig filter.lfs.required=true
file:C:/Program Files/Git/etc/gitconfig http.sslbackend=openssl
file:C:/Program Files/Git/etc/gitconfig http.sslcainfo=C:/Program Files/Git/mingw64/etc/ssl/certs/ca-bundle.crt
file:C:/Program Files/Git/etc/gitconfig core.autocrlf=true
file:C:/Program Files/Git/etc/gitconfig core.fscache=true
file:C:/Program Files/Git/etc/gitconfig core.symlinks=false
file:C:/Program Files/Git/etc/gitconfig pull.rebase=false
file:C:/Program Files/Git/etc/gitconfig credential.helper=manager
file:C:/Program Files/Git/etc/gitconfig credential.https://dev.azure.com.usehttppath=true
file:C:/Program Files/Git/etc/gitconfig init.defaultbranch=master

KIIT@DESKTOP-HS2QJ56 MINGW64 ~
$ git config --global user.name "Sambit Nayak"

KIIT@DESKTOP-HS2QJ56 MINGW64 ~
$ git config --global user.email sambitnayak.tuserate@gmail.com

KIIT@DESKTOP-HS2QJ56 MINGW64 ~
$ git config --global core.editor "code --wait"

KIIT@DESKTOP-HS2QJ56 MINGW64 ~
$ git config --global init.defaultBranch main

KIIT@DESKTOP-HS2QJ56 MINGW64 ~
$ git config --list
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/etc/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.name=Sambit Nayak
user.email=sambitnayak.tuserate@gmail.com
core.editor=code --wait
init.defaultbranch=main

KIIT@DESKTOP-HS2QJ56 MINGW64 ~
$ git config user.name
Sambit Nayak

KIIT@DESKTOP-HS2QJ56 MINGW64 ~
$ git help <verb>
bash: syntax error near unexpected token `newline'

KIIT@DESKTOP-HS2QJ56 MINGW64 ~
$ git help config

KIIT@DESKTOP-HS2QJ56 MINGW64 ~
$ -l
bash: -l: command not found

KIIT@DESKTOP-HS2QJ56 MINGW64 ~
$ git add -h
usage: git add [<options>] [--] <pathspec>...

    -n, --dry-run         dry run
    -v, --verbose         be verbose

    -i, --interactive     interactive picking
    -p, --patch           select hunks interactively
    -e, --edit            edit current diff and apply
    -f, --force           allow adding otherwise ignored files
    -u, --update          update tracked files
    --renormalize         renormalize EOL of tracked files (implies -u)
    -N, --intent-to-add   record only the fact that the path will be added later
    -A, --all             add changes from all tracked and untracked files
    --ignore-removal      ignore paths removed in the working tree (same as --no-all)
    --refresh             don't add, only refresh the index
    --ignore-errors       just skip files which cannot be added because of errors
    --ignore-missing      check if - even missing - files are ignored in dry run
    --sparse              allow updating entries outside of the sparse-checkout cone
    --chmod (+|-)x        override the executable bit of the listed files
    --pathspec-from-file <file>
                          read pathspec from file
    --pathspec-file-nul   with --pathspec-from-file, pathspec elements are separated with NUL character


KIIT@DESKTOP-HS2QJ56 MINGW64 ~
$ cd C:\Users\KIIT\Documents\my_project
bash: cd: C:UsersKIITDocumentsmy_project: No such file or directory

KIIT@DESKTOP-HS2QJ56 MINGW64 ~
$ dir C:\Users\KIIT\Documents\my_project
dir: cannot access 'C:UsersKIITDocumentsmy_project': No such file or directory

KIIT@DESKTOP-HS2QJ56 MINGW64 ~
$ cd

KIIT@DESKTOP-HS2QJ56 MINGW64 ~
$ git init C:\Users\KIIT\Documents\my_project
Initialized empty Git repository in C:/Users/KIIT/UsersKIITDocumentsmy_project/.git/

KIIT@DESKTOP-HS2QJ56 MINGW64 ~
$ cd C:\Users\KIIT\Documents\my_project
bash: cd: C:UsersKIITDocumentsmy_project: No such file or directory

KIIT@DESKTOP-HS2QJ56 MINGW64 ~
$ cd my_project
bash: cd: my_project: No such file or directory

KIIT@DESKTOP-HS2QJ56 MINGW64 ~
$ echo "test content for git tutorial">>CommitTest.txt

KIIT@DESKTOP-HS2QJ56 MINGW64 ~
$ git add CommitTest.txt
fatal: not a git repository (or any of the parent directories): .git

KIIT@DESKTOP-HS2QJ56 MINGW64 ~
$ cd C:/Users/KIIT/Documents/my_project

KIIT@DESKTOP-HS2QJ56 MINGW64 ~/Documents/my_project
$ git add CommitTest.txt
fatal: not a git repository (or any of the parent directories): .git

KIIT@DESKTOP-HS2QJ56 MINGW64 ~/Documents/my_project
$ echo "test content for git tutorial">>CommitTest.txt

KIIT@DESKTOP-HS2QJ56 MINGW64 ~/Documents/my_project
$ git add CommitTest.txt
fatal: not a git repository (or any of the parent directories): .git

KIIT@DESKTOP-HS2QJ56 MINGW64 ~/Documents/my_project
$ cd C:/Users/KIIT/Documents/my_project

KIIT@DESKTOP-HS2QJ56 MINGW64 ~/Documents/my_project
$ git init
Initialized empty Git repository in C:/Users/KIIT/Documents/my_project/.git/

KIIT@DESKTOP-HS2QJ56 MINGW64 ~/Documents/my_project (main)
$ echo "test content for git tutorial">>CommitTest.txt

KIIT@DESKTOP-HS2QJ56 MINGW64 ~/Documents/my_project (main)
$ git add CommitTest.txt
warning: in the working copy of 'CommitTest.txt', LF will be replaced by CRLF the next time Git touches it

KIIT@DESKTOP-HS2QJ56 MINGW64 ~/Documents/my_project (main)
$ git commit -m "added CommitTest.txt to the repo"
[main (root-commit) 25f8e3f] added CommitTest.txt to the repo
 1 file changed, 2 insertions(+)
 create mode 100644 CommitTest.txt

KIIT@DESKTOP-HS2QJ56 MINGW64 ~/Documents/my_project (main)
$
