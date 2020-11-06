### Tips for using git:

#### Cloning
git clone (URL for repo) (directory to clone in)

#### Starting from Scratch
git init
$ git add *.c
$ git add LICENSE
$ git commit -m “any message here”

#### Change Cycle
think "A + C + P"
add + commit + push

options for push include 'origin master'

git pull
git status
git add (filename)
git commit -m "message"
git push origin master

### Setup Tips:

#### Identity
git config --global user.name "Jane Smith"
git config --global user.email "example@email.com"
check with:
git config --global user.name (should return Jane Smith)
git config --global user.email (should return example@email.com)

#### Default Editor
git config --global core.editor emacs

#### Settings Check
git config --list

#### Help
git help command
git command --help
man git-command

[<<< Back](README.md)
