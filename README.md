"# LCG" 

在命令行上创建一个新的存储库
```
echo "# LCG" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/liuchenggong/LCG.git
git push -u origin master
```

…or push an existing repository from the command line
```
git remote add origin https://github.com/liuchenggong/LCG.git
git push -u origin master
```
…or import code from another repository
```
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.
```