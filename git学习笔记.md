## git 本地操作

* cd 到指定的路径
* 执行初始化命令

```
git init
```

* 管理目录下的文件状态

```
git status
// 红色为新增文件或修改过文件
```

* 管理指定文件

```
git add Filename //管理指定新增文件 

git add .  // 管理所有新增文件
```

* 配置个人信息（仅初次）

```
git config --global user.email 'i@dewei.me'
git config --global user.name 'dewei'
```

* 提交版本

```
git commit -m '备注信息'
```

* 查看版本记录 

```
git log
```



## 提交到github

```
git remote add origin https://github.com/dewei233/mysite.git
git branch -M main
git push -u origin main
```

