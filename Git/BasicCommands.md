- Add : git init .
- Remove : sudo rm -rf .git
- Global Config List: git config --list --global
- Set Username: git config --global user.name "akshaya-kumar-biswal"
- Set Email: git config --global user.email "mail.akshayabiswal@gmail.com"

#### create a new repository on the command line

```txt
echo "# DevDocs" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:akshaya-kumar-biswal/DevDocs.git
git push -u origin main
```

#### push an existing repository from the command line

```txt
git remote add origin git@github.com:akshaya-kumar-biswal/DevDocs.git
git branch -M main
git push -u origin main
```
