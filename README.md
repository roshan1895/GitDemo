# GitDemo
This Repo will help to learn github operations and it's commands

<h3>Git Operations & Commands</h3>
These are the following Github Operations:-<br/>
1. Create Repositories<br/>
2. Syncing Repositories<br/>
3. Making Changes<br/>
4. Parallel development<br/>
5. Branching<br/>
6. Merging<br/>
7. Rebasing<br/>
8. Git Flow<br/>

Now,we will cover all the operations with commands use for that operation.

<h3>1.Create Repositories</h3><br/>
Repositories can be created by two way:-<br/>
 i) Create repo on github  and clone it to the system
     
     If i have created a repo "GitDemo" on github so we have to clone it in system by using "clone" command.
     
     command syntax:- git clone "repo_url"
     Example:- git clone "https://github.com/roshan1895/GitDemo.git""
     
     After command run successfully your github repo will be cloned on your sytem Now you can perform operations in it.
     
 ii) Create local repo on your sytem by using git "init" command.    
 
     command syntax:- git init
     Example:- git init
     
     After command run successfully your local repo will be created on your sytem Now you can perform operations in it.
     
     
 <h3>2.Syncing Repositories</h3><br/>
 After creating the github repo or local repo we have to peerform this operationto complete the rep setup process.
  i) If we have created a local repo then we have to sync it with our global repo(github repo) for that we will add the remote.
    
      Command syntax:- git remote add origin "repo_url"
      Example:- git remote add origin "https://github.com/roshan1895/GitDemo.git"
      
  ii) To fetch the latest update of repo we will use "pull" command.
  
      Command syntax:- git pull origin branch_name
      Example:- git pull origin main
      
  iii) To update the repo we will use "push" command.
  
      Command syntax:- git pull origin branch_name
      Example:- git pull origin main   
      
      
 <h3>3.Making Changes</h3><br/>
 In this operation we will  add the file in queue to be commited,commit the code and indexing the file.
  i) If we want to know which files are added to index and are raedy to commmit, we will use "status" command.
    
      Command syntax:- git status
      Example:- git status
      
  ii) If we want to add files to our index of repo, we will use "add" command.
     
     -To add single file  in index. 
      
      Command syntax:- git add file_name
      Example:- git add demo1.txt
      
      -To add Multiple files  in index. 
      
      Command syntax:- git add -A
      Example:- git add -A
      
  iii) To Commit the added file of index,we will use "commit" command.
  
      -To commit single file . 
      
      Command syntax:- git commit -m "commit_message"
      Example:- git commit -m "initial_chnages"
      
      -To commit Multiple files. 
      
      Command syntax:- git commit -a -m "commit_message"
      Example:- git commit -a -m "changes"
          
  iv) To see the commits.
  
      Command syntax:- git log
      Example:- git log
      
      
      
  <h2>Git Commands</h2><br/>
  git config
  git init
  git clone
  git add
  git commit
  git diff
  git reset
  git status
  git rm
  git log
  git show
  git tag
  git branch
  git checkout
  git merge
  git remote
  git push
  git pull
  git stash
  
      
 
      
 
    
   



