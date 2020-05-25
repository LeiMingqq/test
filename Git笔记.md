# Git-初识Git及应用(上)
> What ls Git?

>> 版本管理工具(VCS)

>>1. 分布式版本控制
>>2. 多个开发人员协调工作
>>3. 有效监听谁做的修改
>>4. 本地及远程操作

# Git 的基础命令行操作

>> Basic Commands

>>1. git init         // 初始化本地git仓库
* 初始化仓库后, 需要配置Git仓库**用户名**和**emali**。
* git config --global user.name 'name'
* git config --global user.emali '1494381296@qq.com'
>>2. git add <file>   // 添加文件
* *.html              // 表示添加所有后缀名一样的
* .                   // 添加目录中的所有文件
>>3. git status       // 查看状态
>>4. git commit       // 提交
* git commit 提交后 需要备注一下,然后按 Esc, 输入 :wq退出
* git commit -m '这样备注直接提交'
>>5. git push         // 推送到仓库
>>6. git pull         // 从远程仓库拉取数据
>>7. git clone        // 从远程仓库拷贝数据
* git clone https://github.com/LeiMingqq/test.git   //**需要添加克隆地址**


+ modified            //文件被修改了

# Git-初识Git及应用(下)

>1. 如何使用git忽略一下不想上传的文件
* 需要**命令行中**创建一个 **.gitignore**, 然后把需要忽略的文件写入到.gitignore的文件中去
* name.后缀            //文件
* /name               //文件夹
>2. 分支的使用
* git branch name     //创建分支
* git checkout name   //切换分支
* git merge name      //合并分支 **注意要在master(主分支)合并**
>3. 主线及分支的合并
>4. 操作远程仓库

* README.md //用来描述/说明网站的内容
* git remote          //查看有没有对应的地址
* git remote add origin https://github.com/leimingqq/testgit.git      //添加地址
* git push -u origin master  //推送到仓库
* //  发送     地址   分支



# Linex命令

1. -version           // 查看版本  
