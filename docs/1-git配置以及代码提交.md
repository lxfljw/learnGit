# 一、配置

## 提交用户名和邮箱
这个配置会用于 `commit` 的用户名和邮箱，用于找到提交此 `commit` 的人。

```shell
git config --global user.name "yourname"
git config --global user.email youremail
```

## 输出颜色

```shell
git config --global color.ui true
```

## 初始化文件夹为 git 仓库

进入你的文件目录，执行以下代码：

```shell
git init <dirname>
```
如果你没有目录，可以添加文件名自动创建文件；执行完成后，会在文件生成一个隐藏目录 `.git` 文件，这就是git的版本库。而被初始化的这个目录就叫做工作区。


# 二、 提交代码
假设我们有一个名为 demo 的目录，先来初始化 demo 目录：

```shell
cd demo
git init
```

创建名为 A.txt 的文件，文件内容只有 A 字母。

```shell
echo A > A.txt
```



