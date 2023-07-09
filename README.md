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

git remote add origin https://gitlab.com/devopstraining1903327/howbjackdemo.git

4) Remember to resolve conflict with using "main" or "master" as the protected branch. More to come on this

