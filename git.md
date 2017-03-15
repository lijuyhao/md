##GIT的使用方法

- 创建隐藏目录命令：git init

- 自报家门：
 1. 配置用户名：git config user.name 'lifanghao'
 2. 配置邮箱：git config user.email '398422519@qq.com'
 3. 查看配置信息：git config --list
 

- 把代码提交到仓库中：git add 文件路径（git add .）

- 把暂存区文件提交到仓库里：git commit -m '注释'

- 合并add于commit命令：git commit -a -m

- 查看工作区状态：git status

- 添加忽略文件：在项目中有些文件是不需要提交的，我们需要把它忽略掉


 1.需要在 .git文件中所目录中新建一个名为.gitignore的文件
     				
    :/css/index.css 
    :/a.html


- 对比文件差异：git diff

- git diff --cached 比较暂存区和仓库文件的区别  

- 查看日志：git log 可以产看每一次提交的日志

- 简介形式输出提交日志：git lo --oneline

- 版本回退：git rest --hard Head~1

- git rest --hard 版本号

- git reflog   查看之前所有版本版本切换的操作记录

- 创建分支：git branch [分支名] 

- 查看当前所有分支：git branch

- 切换分支：git checkout [分支名] 

- 合并分支：git merge [分支名] 会将指定的分支合并到当前分支

- 删除分支：git branch -d [分知名] 

- 上传代码到git 服务器（push）:git push 远程服务器地址 远程服务器的分支 

- 将远程服务器的地址写成变量的形式：

- git remote add [变量名] [远程服务器的地址]

- 在push时加上-u的参数，就会简历本地当前分支远程服务器指定分支的关联，下一次push的时候就不需要输入分支名了git push [变量名]

- git生成公钥和私钥：ssh-keygen -t rsa 生成的公钥和私钥文件会在当前用户目录下的.ssh目录下

- 从服务器上pull代码到本地：如果本地没有.git目录，需要先初始化一下 git pull [远程服务器的地址] [远程的分支]
 
- gh-pages分支：上传到gh-pages分支 

- 访问url的形式: [github用户名] .github.io/[仓库的名字]/[具体的页面]  
 
 
 
 
  