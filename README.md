# Gitlab Test

Gitlab测试
李浩宇

杜豪     阿巴阿巴阿巴阿巴阿巴阿巴阿巴阿巴阿巴阿巴阿巴阿 李星悦 刘淇文

#### 教程补充

**克隆仓库后**

git clone git@118.195.201.140:root/gitlab-test.git

**切换到仓库的文件夹**

cd gitlab-test

**因为木有直接推送主分支的权限所以要进行如下操作**

**创建自己的分支**

git branch [分支的名称 如：dh]

(别与远程仓库的已有分支重名)

git branch (查看所有本地分支)

git branch -a (查看所有远程分支)

**切换到自己的分支**

git checkout [分支的名称]

**然后对文件进行一定的修改**

**将文件添加到暂存区**

git add [文件名]    (也可以使用 . 或 * 添加所有文件)

git status (查看文件变更状态)

**提交这次修改到仓库区**

git commit -m [“提交时附带的说明文字”]

**将分支推送到远程仓库**

git push --set-upstream origin [分支的名字]   (第一次推送，远程仓库无对应的分支，推送并创建)

git push   (之后再在当前分支修改提交后，就这样子推送)

**然后就等管理员查看合并分支了**

### 最后附上我查询用的git命令地址：https://gitee.com/all-about-git

韩聪聪 熊健东 侯雨欣 李沂
