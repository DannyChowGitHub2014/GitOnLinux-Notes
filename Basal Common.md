#####git setup: 
  sudo apt-get install git-core openssh-server openssh-client  
  sudo apt-get install git-core git-gui git-doc  
  sudo apt-get install libcurl4-gnutls-dev libexpat1-dev gettext libz-dev git-core  
  
#####git fork to local:
  1. cd into your local dir which will store the forked file from git;
  2. type follow common:   
          git clone "your repository ssh link";
          
#####view branch:  
     git branch  
    or  
     git branch -a  
     
#####create branch:  
       git checkout -b branchName  

#####view branch status:  
     git status  
     
#####add the changed file to committed list:  
    git add fileName  

#####commit branch  
       git commit -m "commit description" fileName  
       
#####push branch to remote repository:  
     git push origin branchName
     
#####Install nodejs:
  1.view the command on nodejs website and type in terminal
  2.switch in the folder which is current project and type **npm install**
