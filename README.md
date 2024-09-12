# git常用命令


#创建文件夹后初始化仓库
git init

#从git仓库拷贝项目
git clone <url>

#添加文件到缓存区
git add <file>

#将缓存区内容添加到仓库，-m添加注释
git commit -m <"...">

#推送新分支到远程仓库
git push origin <branch>

#查看文件状态
git status

#比较的是工作目录中当前文件和暂存区域快照之间的差异
git diff

#取消工作区的文件修改
git checkout <file>

#取消缓存区的文件修改
git reset HEAD <file>

#删除文件
git rm <file>

#查看提交日志信息
git log

#列出当前库中所有本地分支
git branch

#创建一个分支，基于当前分支创建的
git branch <branch>

#从一个分支切换到另一个分支
git checkout <branch>
