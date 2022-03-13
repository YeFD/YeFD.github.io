## HEXO 多设备同步
### 推动到hexo分支
> master分支用于hexo上传静态页面，hexo分支用于上传hexo项目
1. 远程仓库新建hexo分支
2. 本地仓库推送
```
// 初始化
$git init
// 添加远程仓库地址
$git remote add origin git@github.com:YeFD/yefd.github.io.git 
// 新建分支并切换
$git checkout -b hexo
// 推送到远程仓库
$git add .
$git push origin hexo // 第一次可能需要加上--force
```
### hexo项目同步
```
$git clone -b hexo git@github.com:YeFD/yefd.github.io.git
```
