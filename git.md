## git init: 新建初始git项目   出现.git目录  不想用删之
## config:
git config --global user.name 

git config --global user.email


## git 配置文件   一下顺序验证
/etc/gitconfig  (可以配置git账号)
cat ~/.gitconfig (可以配置公司账户)
./.git/config 



## git配置:
https://github.com/LKI/myconf/blob/master/.gitconfig


## Git文件状态
untracked 

----   git add 

staged

----   git commit 

committed

git commit

git branch 

## 查看目标文件大小
du -sh <file path>|<不加代表当前文件大小>


## git save
某些改动不想commit 

git save 暂存至镜像

git load 拿出暂存的文件或改动
