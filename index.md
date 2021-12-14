打开百度搜索，在搜索框中输入：github，点击第一条搜索结果。

![image](https://user-images.githubusercontent.com/84163388/142978167-4d0c9280-a555-4c64-864e-e1fd8951bd49.png)


在打开的页面中，分别输入：你喜欢的用户名、你常用的的电子邮箱、以及创建一个安全的密码，然后点击绿色图标（sign up）

![YRBVPEDI3)DNA12T(P1~4LJ](https://user-images.githubusercontent.com/84163388/142978228-93475ea7-7a0a-40cf-bcdd-0c2f4e795fc4.png)

之后，便进入了注册流程的第二步，需要选择一下个人的计划设置，默认的就可以，Unlimited public respositories for free（无限制的免费公共仓库），最后点击绿色图标（Continue）

![20211123141219](https://user-images.githubusercontent.com/84163388/142978353-c7b076a2-163e-42dc-8915-9c3aabf97b43.png)

最后，我们进入了注册的最后一步，是一些关于个人信息的一些东西，如：编程水平，你的职业，你的编程的态度，自我介绍。如果填写了，请点击绿色图标（Submit）,如果不想填写，或者一时不知如何选择，请点击跳过此步骤（Skip this step）

![image](https://user-images.githubusercontent.com/84163388/142978442-abfb5086-d577-444f-a235-405686b54847.png)

登录GitHub

![image](https://user-images.githubusercontent.com/84163388/142979428-e3973313-5e0a-44c2-9b05-81efe63e0712.png)

创建储存库

![20211123144846](https://user-images.githubusercontent.com/84163388/142981472-44b272dd-e88e-4e2c-8b45-afdd9cdef178.png)

![image](https://user-images.githubusercontent.com/84163388/142981757-71b8a85e-5f21-4e92-8ebf-694bd198196e.png)

找到博客地址

![{R$2 }DHM6GZ~@2$()@XDJT](https://user-images.githubusercontent.com/84163388/142983197-da60e920-ac5b-4d7a-89ba-7661557fac47.png)

选择博客主题

![`U0$@QY{_V{4U9{S5H33GHP](https://user-images.githubusercontent.com/84163388/142983251-08dfe3bd-9716-43df-9949-85251702ffa3.png)

![1KK9G6RV3Z9~MZ)7Q2NN2(F](https://user-images.githubusercontent.com/84163388/142983282-79ef4183-04fe-49fb-8b92-e7c6e839da43.png)

创建博客成功

打开储存库选择 gh-pages分支

![Y@DL~6%}M266@Q2 )_6W~{D](https://user-images.githubusercontent.com/84163388/142983735-7393e8d3-25ad-49cb-b819-a524a5df3cf1.png)

选择index.md

![V1S~J6ASD58TG}IV_QR%_(L](https://user-images.githubusercontent.com/84163388/142983798-7d98662f-9533-43b2-842a-a94ceb96f739.png)

编辑博客内容

![{Y I IO}P4{SBVSLK`52 FL](https://user-images.githubusercontent.com/84163388/142983908-388e97fb-f5b9-42d6-8666-90b863c41c88.png)

小组分析仓库的各个功能选项，分工合作由邬宇东同学和李玉峰同学画利用staruml画出仓库代码托管用例图，并由王赢同学进行用例描述与分析及建模过程，再由李玉峰.李天成.宁帆同学写出用例文档，再由李天成，宁帆写出博客内容

接上回

期中作业1.仓库代码托管功能
登录 创建仓库过程如上所示
首先我们需要在本地创建一个项目，作为托管项目。安装好Git之后，我们右键项目文件夹的时候会出现以下提示：

![image](https://user-images.githubusercontent.com/84163388/145961904-86537120-1737-490a-9f25-375df0d9af71.png)

 在弹出的git操作窗口中，使用：git init 初始化一个仓库
 
 ![image](https://user-images.githubusercontent.com/84163388/145962080-f79bb840-3eb9-46a8-9203-7c769244a784.png)
 
 之后会产生一个空的仓库，此时的代码只处于工作区，并未提交到暂存区和版本库。

    接下来我们需要执行以下命令来将代码保存到版本库。

  init之后会产生一个空的仓库，此时的代码只处于工作区，并未提交到暂存区和版本库。

    接下来我们需要执行以下命令来将代码保存到版本库。

    git add 文件名 或者git add  .    ：将文件从工作区提交到暂存区

    git commit -m "备注信息" ：将代码从暂存区提交到版本库master

    git status : 查看当前工作区代码的状态

    git log ：查看git操作的日志
    
![2](https://user-images.githubusercontent.com/84163388/145969372-6eafe6e9-db3c-412c-8428-513ee9b97d57.PNG)

    从这里我们可以看到当前的状态，没有被追踪的文件，那么我们需要将这些代码从工作区提交到暂存区

![3](https://user-images.githubusercontent.com/84163388/145969698-17cfeb91-3fd5-40a9-9773-e5450a7fb1fa.PNG)

 现在代码处于暂存区中，我们需要将暂存区的代码提交到master中
 
 ![4](https://user-images.githubusercontent.com/84163388/145969886-2327d840-4fd9-4eb2-979f-edb516cecb5e.PNG)

   
    配置本地ssh然后将ssh配置在github上
ssh的需要通过git生成公钥，并在GitHub上配置公钥，其他的用户才可以从github上下载代码。这里两种方式都会演示到，我们先使用http来托管项目；

    切到http，并将代码的托管路径copy出来，然后使用git push命令来讲代码传到GitHub上
       
       ![image](https://user-images.githubusercontent.com/84163388/145963790-2026ef11-f396-49c6-a8f4-9b852cfb0da7.png)
       
  刷新就实现了代码上传
2.代码下载首先Pycharm连接github账号配置好ssh公钥登录github搜索Python项目如下图所示

![@U~Z)V (3%C9_D}3}HMYCXN](https://user-images.githubusercontent.com/84163388/145964520-87522319-7eb8-49fd-b0b3-cdd4687fd7c8.png)

找到一个Python项目

![9SZN2MTTMUG16MRO{MSRC2E](https://user-images.githubusercontent.com/84163388/145964600-02340cef-550e-4652-8c2c-ee3ed3b34827.png)

找到其他人的ssh网页地址

![@{6609Q94CW7D}TZ G5MNHK](https://user-images.githubusercontent.com/84163388/145964723-e92dc7c0-15af-4261-a664-9c499984fb63.png)

打开pycharm


![LPZ0}36XY(3Z{WO(~R (8](https://user-images.githubusercontent.com/84163388/145964836-841e1841-7cb1-4f8a-bf26-5440cd7a0ef7.png)

找到Git选项选择clone

![_HL8FG33XX0F$}I@P2LBJ(U](https://user-images.githubusercontent.com/84163388/145965092-2561c113-f2ab-4cb8-997a-6b2d9044ce27.png)

输入刚刚的项目ssh地址

![8EDMYZ6Y_M22993E8E34 ZS](https://user-images.githubusercontent.com/84163388/145965283-1fe042e7-42ae-4fa3-8079-488a9d5a477b.png)



![20211214165403](https://user-images.githubusercontent.com/84163388/145965460-81f9eb94-49df-46b9-8324-92181181245b.png)


下载完成查看代码
    
    ![image](https://user-images.githubusercontent.com/84163388/145965636-cbda7e2e-47a8-4a12-b916-c33394f4ad1d.png)
    
    
    ![image](https://user-images.githubusercontent.com/84163388/145965848-18f19104-c856-4e68-af5c-4578e20c601f.png)



搜索功能就是直接在搜索框里面搜索可以搜索其他人的代码，自己的仓库代码还有自己的仓库

而版本管理也是基于上述的过程不断下载然后更新代码上传至github账号仓库里面进行版本管理
我们先由小组讨论，然后分工进行各自的部分先进行查找相应的资料然后实践上传下载等功能再进行功能里面的对象关系进行画图最后书写过程
小组分工：搜索功能顺序图，通信图由宁帆同学

李天成：仓库代码管理的顺序图和通信图由李天成同学分析进行画图，书写博客内容。
李玉峰：仓库版本功能顺序图和通信图及分析并书写过程
宁帆：搜索功能顺序图，通信图
王赢：分析写出代码托管功能的说明过程
邬宇东：分析写出搜索代码功能的说明过程

