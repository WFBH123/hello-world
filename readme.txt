Hello!
#Waleed Albeladi 2235739
# git-it-assignment
1 Get Git 
git --version
git config --global user.name "Waleed Albeladi"
git config --global user.email "gbp1061@gmail.com"

2 Repository
mkdir hello-world
cd hello-world
git init 

3 Commit To It 
create file readme.txt
git status
git add readme.txt
git commit -m "Created message"
git diff

4 GitHubbin 
git config --global user.username WFBH123

5 Remote Control 
git remote add origin https://github.com/WFBH123/hello-world.git
git push origin main

6 Forks And Clones 
git clone https://github.com/WFBH123/patchwork.git
cd .\Patchwork\
git remote add upstream https://github.com/jlord/patchwork.git
git remote -v

7 Branches Aren't Just For Birds
git branch add-WFBH123
git checkout add-WFBH123
git status
git add .
git commit -m "commit message"
git push origin add-WFBH123

8 It's a Small World
add 'reporobot' as a collaborator

9 Pull Never Out Of Date
git pull origin add-WFBH123

![](./screenshot.png)
