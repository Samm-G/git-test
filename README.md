# Practical Git Operations:

## Creating a New Repo:
```bash
echo "# git-test" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Samm-G/git-test.git
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