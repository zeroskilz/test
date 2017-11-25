# First Github Repository
### Sources for terminal commands
![Github Logo](https://github.com/zeroskilz/test/blob/master/images/gitscm.png)

[Github Tutorial](https://git-scm.com/book/en/v2/Git-Basics-Recording-Changes-to-the-Repository)



### 
<!--!"*"[RESERVED FOR MD ATTRIBUTES"*"] -->
<!--![Github $main{Rulz}]( " ")
![Github Logo]("lorem")
###### headers 1-6
-->
 
##### clone a repo with git 
    * git clone https://github.com/zeroskilz/test

##### create the .git directory
    * git init

### configure git so it knows you
###### global for all repos
    * git configure --global user.email zeroskilz@mail.com
    * git configure --global user.name zeroskilz

##### only for the current repo
    * git configure user.name zeroskilz
    * git configure user.email zeroskilz@mail.com

##### create readme as markdown file
   *  echo "# test for test :" >> README.md
##### add the filename
   * git add README.md
##### we must commit to the change
###### commit information 
[Commit info](https://git-scm.com/docs/git-commit)
   * git commit -m "Test  commit"
##### Info pertaining to modifications, removal, tracking uncommitted files  
   * git status

##### "Add all files with extension .c and .py
   * git add *.c
   * git add *.py
   * git add filename


##### Create the alias of the git repo 
   * git remote add origin https://github.com/zeroskilz/test.git
##### Finally Push your work to the server!!! 
   * git push -u origin master
  
## Create a Worker Branch off from test
   * git branch tester
##### To switch to the branch use the below code!
   * git checkout tester
##### then to switch back to the master
   * git checkout master




![Github Logo](https://github.com/zeroskilz/test/blob/master/images/images.duckduckgo.com.jpeg "Social Coding")

<!-- finito -->

