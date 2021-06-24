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
      
      
 
    
   



