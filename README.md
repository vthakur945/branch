This is just a test repository to learn git commands and branch
1. Initialize git and create a main branch 
   Created a new directory using mkdir command
    - git init - to initialize the repo
    - git add filename - to add this file to the staging area, it prepares it to be committed
    - git commit -m "first commit" - commit the file
    - git branch -M main Create the main branch and switch to it. This is the main line of development 

2. Creating a local branch
    - git checkout -b my-new-branch # create a new branch and switch to it
    - make some changes to this new branch like create a file
    - Add and commit new file
        - git add features.txt
        - git commit -m "added new features" 

3. Push to a remote repository
    Connecting local repository to a remote one
     - created an empty repository on the Github UI and added it 
        - git remote add origin https://github.com/vthakur945/branch.git
    - Push your local main branch to the remote repository. The -u flag sets the upstream, so future pushes are simpler
        - git push -u origin main
