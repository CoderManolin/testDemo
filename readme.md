## 当前项目的说明书

#### git操作的具体步骤

1. cd 路径 进入当前目录
2. 配置git基本操作<br/>
git config --global user.name "github账号"
<br/>
git config --global user.email "github注册邮箱"
<br/>
  【注】没有消息就是好消息
3. git init 在本地进行初始化(简历暂存区)  
    >.git 文件存储当前项目的所有版本信息

4.工作区=>暂存区  
   git add 文件  
git add * 提交所有文件   

git commit -m "这一次提交的描述"

5.查看当前工作区的状态  
git status  

6.从暂存区恢复文件到工作区  
git checkout  

7.查看工作区和暂存区版本区别  
git diff  

8.clear 清屏操作  

9.git log  
  查看已经提交到暂存区的历史版本


10.恢复文件到指定的某一个版本
git reset --hard 版本号



11.生成SSH密钥
    ssh-keygen -t rsa -C "你github邮箱账号"  

12.windows电脑查找文件:  


我的电脑=>用户=>用户名文件夹=>.ssh(隐藏文件)=>xxx.pub(存有密钥)



13.github账户配置密匙  
git remote add origin https://github.com/Ming-Coder/testDemo.git  

git push -u origin master  
【注】提交过程，可能需要你输入用户名和密码




