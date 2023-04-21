## 一、Git是分布式版本控制系统

### 1. 版本控制 [什么是版本控制？ - Azure DevOps | Microsoft Learn](https://learn.microsoft.com/zh-cn/devops/develop/git/what-is-version-control)

版本控制系统是一段时间内帮助跟踪代码中的更改的软件。 当开发人员编辑代码时，版本控制系统会为文件拍摄快照。 然后，它会永久保存该快照，以便以后可以根据需要重新调用它。

如果没有版本控制，开发人员会尝试在其计算机上保留多个代码副本。 这很危险，因为很容易在错误的代码副本中更改或删除文件，可能会丢失工作。 版本控制系统通过管理代码的所有版本来解决此问题，但一次向团队提供单个版本。

###  2. 版本控制软件的基本功能

1. 保存和管理文件
2. 提供客户端工具进行访问
3. 提供不同版本文件的比对功能

### 3. 分布式与集中式版本控制

<img src="C:\Users\qi.h.zhang\AppData\Roaming\Typora\typora-user-images\image-20230421162209563.png" alt="image-20230421162209563" style="zoom: 67%;" />

## 二、Git安装

### 1. [Git官网](https://git-scm.com/)

<img src="C:\Users\qi.h.zhang\AppData\Roaming\Typora\typora-user-images\image-20230421164223647.png" alt="image-20230421164223647" style="zoom:67%;" />

### 2. Git GUI Here和Git Bash Here

<img src="C:\Users\qi.h.zhang\AppData\Roaming\Typora\typora-user-images\image-20230421164410533.png" alt="image-20230421164410533" style="zoom:67%;" />

- **Git GUI Here** : Git的图形化操作入口

- **Git Bash Here** : Git的命令行形式入口

  

## 三、GitHub Desktop

### 1. 主页面

<img src="C:\Users\qi.h.zhang\AppData\Roaming\Typora\typora-user-images\image-20230421172121471.png" alt="image-20230421172121471" style="zoom:67%;" />

### 2. 创建仓库

**2.1 File —> New repository**

<img src="C:\Users\qi.h.zhang\Pictures\gitdesktop\屏幕截图 2023-04-17 175402.png" alt="屏幕截图 2023-04-17 175402" style="zoom:50%;" />

**2.2 填写仓库名称，仓库描述，本地路径**

<img src="C:\Users\qi.h.zhang\Pictures\gitdesktop\屏幕截图 2023-04-17 175811.png" alt="屏幕截图 2023-04-17 175811" style="zoom:50%;" />

**2.3 发布到远程仓库**

<img src="C:\Users\qi.h.zhang\AppData\Roaming\Typora\typora-user-images\image-20230421173225390.png" alt="image-20230421173225390" style="zoom:50%;" />

**2.4 输入远程仓库名称和描述，选择仓库是否为私有**

<img src="C:\Users\qi.h.zhang\AppData\Roaming\Typora\typora-user-images\image-20230421174319522.png" alt="image-20230421174319522" style="zoom:50%;" />

**2.5 成功发布到远程仓库**

![image-20230421173744533](C:\Users\qi.h.zhang\AppData\Roaming\Typora\typora-user-images\image-20230421173744533.png)

### 3. 移除仓库

**3.1 选择仓库 —>右键remove**

<img src="C:\Users\qi.h.zhang\AppData\Roaming\Typora\typora-user-images\image-20230421175311366.png" alt="image-20230421175311366" style="zoom:50%;" />

**3.2 选择是否将仓库从本地删除**

<img src="C:\Users\qi.h.zhang\AppData\Roaming\Typora\typora-user-images\image-20230421180216603.png" alt="image-20230421180216603" style="zoom:50%;" />

## 4. 添加仓库

**4.1 File—> Add local repository **

<img src="C:\Users\qi.h.zhang\AppData\Roaming\Typora\typora-user-images\image-20230421180352089.png" alt="image-20230421180352089" style="zoom:50%;" />

**4.2 选择仓库路径**

<img src="C:\Users\qi.h.zhang\AppData\Roaming\Typora\typora-user-images\image-20230421180523094.png" alt="image-20230421180523094" style="zoom:50%;" />

## <font color="red">**5. 从远程仓库克隆代码</font>

**5.1 File—>Clone repository**

<img src="C:\Users\qi.h.zhang\AppData\Roaming\Typora\typora-user-images\image-20230421181313102.png" alt="image-20230421181313102" style="zoom:50%;" />

**5.2 输入远程仓库地址和本地存放路径**

<img src="C:\Users\qi.h.zhang\AppData\Roaming\Typora\typora-user-images\image-20230421181445363.png" alt="image-20230421181445363" style="zoom:50%;" />

### <font color="red">6. Commit和Push</font>

