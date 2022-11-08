# HelloWorld

Install git for Windows: https://git-scm.com/download/win

Git commands
- How to clone this project from the remote repo to the local computer
<pre>
git clone https://github.com/valerievna2212/HelloWorld.git
</pre>
- How to add new file into repo repo
<pre>

# check status of the repo (to see new files. updated files and so on)
$ git status

On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

# Add file to local repo
$ git add HelloWorld.java

# Commit file (it still will be local only but ready)
$ git commit -m "added new file" HelloWorld.java
[main 765ebd1] added new file
1 file changed, 7 insertions(+)
create mode 100644 HelloWorld.java

# Send updates to the remote repo
$ git push
