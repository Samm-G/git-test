# Practical Git Operations:

## Creating a New Repo:
```bash
echo "# git-test" >> README.md

# Create Git Repo
git init

# Add file for Tracking
git add README.md 

# Add to Staging area
git commit -m "first commit" 

# Create a new main branch
git branch -M main

# Add remote repo as 'Origin'
git remote add origin https://github.com/Samm-G/git-test.git

# See the remotes..
git remote -v

# Push to Remote.
git push -u origin main
```

## Add an Existing Repo:
```bash
git remote add origin https://github.com/Samm-G/git-test.git
git branch -M main
git push -u origin main
```

## Git Configurations:
List All Git Configs
```bash
git config -l
```
Set Basic Git Configs:
```bash
git config --global user.name "Samm-G"
git config --global user.email "gsamarth97@gmail.com"
```

## Git Branches:
```bash
# Create branch 
git branch dev1

# Change Branch to main
git checkout main

# This line is on Dev1 Branch
```