# howbjackdemo


## This is a repository that is being used to demo gitlab-->github synchronization

We will clean up stuff later 


## Steps to Execute Miroring 

1) Create a  fine-grained personal access token on Github 

2) Go to Settings/Repository on Gitlab and configure Mirroring. 

   You will need: 1)  GitHub repository URL of format: https://USERNAME@github.com/GROUP/PROJECT.git
                  2)  The GitHub personal access token, which will be entered as the password 

3) After selecting **Mirror Repository** the repository pushes shortly thereafter. To force a push, select **Update now** 

## Steps to create a remote gitlab repository

   1. git remote add origin https://gitlab.com/devopstraining1903327/howbjackdemo.git

      Note: Remember to resolve conflict with using "main" or "master" as the protected branch. More to come on this

   2. Create a branch with "git checkout -b <branchname>

   3. Work from the feature branch and push to GitLab. It will be mirrored to GItHub 
   

