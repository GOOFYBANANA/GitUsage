## 任政宇blog
## Git 使用命令

### Git 文件上传库

- **Git初始化**：`git init`

- **初始化用户名**：`git config --global user.name '用户名'`

- **初始化用户邮箱**：`git config --global user.name '邮箱'`

- **克隆远程库到本地**：`git clone 远程库地址`

- **文件上传到本地库**：
  - 先上传到暂存区：`git add 文件名`
  - 查看文件是否提交到暂存区:`git status`

  - 从暂存区上传到本地库：`git commit -m '提交信息'`

![指令图片](pic\2.png)

![指令图片](pic\4.png)

- **本地库文件上传到远程库**：`git push`

![指令图片](pic\3.png)

- **本地库文件删除**：
  - 删除本地库中文件：`rm -rf 文件名`

  - 删除暂存区文件：`git rm 文件名`
  - 确定删除：`git commit -m '删除信息'`

- **修改本地库文件**：

  - 修改文件：`vim 文件名`
  - 提交到暂存区：`git add 文件名`
  - 更新到本地库：`git commit -m '提交信息'`

### Git 搭建个人主页 

- **新建仓库：仓库名格式**：`用户名.github.io`
- ***创建***  `README.md ` ***文件***
- 点击***settings***

![步骤图片](pic\1.png)

