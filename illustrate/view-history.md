
## 查看提交历史纪录

查看最近几个提交的文件列表

    git log -number --stat
number 为数字，代表最近的几次

查看指定提交的文件列表

    git log <commit hash> --stat
<commit hash> 为提交的hash值

查看某个文件的历史

    git log filename

查看文件每次提交的不同

    git log -p filename

列出文件的所有改动历史

    git log --pretty=oneline filename

只查看某次提交的文件变化

    git show <commit hash> filename
