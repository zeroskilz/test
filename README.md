# test for test branch
## finding it tough to get the info to start being active on github here are some good tutorials 
### Here is a URL that has a great tutorial on how to use git from the terminal
#### I made this change trying to make a subdirectory for test repo

[Great GitHub tutorial link Click me](https://git-scm.com/book/en/v2/Git-Basics-Recording-Changes-to-the-Repository)

   
#### set the Configuration for git 

   *14  git config --global core.editor vim
   *16  git config --global user.name zeroskilz 
   *18  git config --global user.email zeroskilz@mail.com 
   *20  git config color.status auto
   *21  git config --global color.status auto
   *22  git config --global color.branch auto
   *23  git config --global color.interactive auto
   *24  git config --global color.diff auto
   *25  git config --list
   
##### the next command makes a hidden .git folder inside the directory you executed the command in 
   *26  git init
   
##### tells you the current status of the project folder your in for git
   *32  git status

##### this is a quick way to add all files of a specific extension such as c, py, sh, txt, etc...
   *37  git add *.c
   *38  git add *.py

##### clone a repo with git 
   *42  git clone https://github.com/zeroskilz/test

##### create file to be pushed  
   *81  echo "# test for test branch" >> README
##### add the filename
   *82  git add README
##### make a commit or all will fail to push
   *83  git commit -m "Test  commit"

##### create the repo to push files to 
   *85  git remote add origin https://github.com/zeroskilz/

##### Finally Push your work!!! 
   *91  git push -u origin master

![Github Logo](https://github.com/zeroskilz/test/blob/master/images.duckduckgo.com.jpeg "Social Coding")
Format: ![Alt Text](url)

<!-- finito -->

