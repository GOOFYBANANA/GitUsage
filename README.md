## Git 使用命令 & Github简易blog的制作

---

#### 任政宇blog

 - ***邮箱*** : ren352601884@163.com
 - ***qq*** : 352601884

---

### Git 文件上传库

- **Git初始化**：`git init`
- **初始化用户名**：`git config --global user.name '用户名'`
- **初始化用户邮箱**：`git config --global user.name '邮箱'`
- **克隆远程库到本地**：`git clone 远程库地址`

![远程库地址](pic\5.png)

![使用命令](pic\6.png)

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

- **新建仓库：仓库名格式**：`用户名.github.io`   当然也可以用自己想要的名字：访问blog链接格式为:`用户名.github.io.库名`
- ***创建***  `README.md ` ***文件***
- 点击***settings***

![步骤图片](pic\7.png)

- 点击 `choose theme` 选择模板

![步骤图片](pic\8.png)

- 随便选择一个就行了

![步骤图片](pic\9.png)

- 模版选择完毕后会发现库里面的  `README.md ` 被填充了许多的内容  想要显示自己的内容直接把这些改掉就行了

![步骤图片](pic\10.png)

- `https://用户名.github.io/库名 `  访问以下看看

![步骤图片](pic\12.png)

- 这里有些需要注意的地方

![步骤图片](pic\11.png)

