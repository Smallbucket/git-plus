## 将本地项目与远程仓库关联    
1.首先将本地项目转换成 git 项目：
 
        git init
        git add .
        git commit -m 'say something...'

2.接着在远程仓库(如 github)创建一个同名项目，创建后获取仓库地址，执行以下命令：
 
        git remote add origin git@github.com:yourname/仓库名.git

3.现在可以提交代码：
 
        git push -u origin master
> Tips: 如果初次提交的代码与服务器有冲突，需要先执行 git pull 同步代码。

[The “fatal: refusing to merge unrelated histories” Git error](https://www.educative.io/edpresso/the-fatal-refusing-to-merge-unrelated-histories-git-error)     


### 修改远程仓库地址
1, 先删除后添加

    git remote remove origin
    git remote add origin git@github.com:yourname/仓库名.git
 
2, 直接修改

    git remote set-url origin git@github.com:yourname/仓库名.git
