

## 0628

### 2:00-2:30

java学习

### 2:30-3:00

#### GitHub配置，重新设置ssh

 输出，也不算报错

>  Hi toookah! You've successfully authenticated, but GitHub does not provide shell access.

#### 添加远程的什么什么

```shell
 git remote add origin git@github.com:toookah/java_review.git
```

##### 报错 

> fatal: remote origin already exists.

##### 解决方案

删除

```shell
git remote rm origin
```

#### 可以在这里看到一些配置信息

> /Users/xuyizhou/.git
>
> /Users/xuyizhou/.ssh

### 5:25- 学习git知识[菜鸟教程](https://www.runoob.com/git/git-workspace-index-repo.html)

#### 基本

```
git add 添加到缓存
git commit 添加到仓库
git remote 添加到Github
git push -u origin master
```

#### git 删除服务器文件

