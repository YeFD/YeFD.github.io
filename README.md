## HEXO 多设备同步
###  push远程仓库其它分支
```
// 初始化
$git init
// 添加远程仓库地址
$git remote add origin git@github.com:YeFD/yefd.github.io.git 
// 新建分支并切换
$git checkout -b hexo
// 推送到远程仓库
$git add .
$git push origin hexo --force
```
### clone
```
$git clone -b hexo git@github.com:YeFD/yefd.github.io.git
```
