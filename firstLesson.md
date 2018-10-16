##第一天笔记

###确定当前位置

![pwd.png](https://upload-images.jianshu.io/upload_images/14467497-c0b545ff3a9c5541.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

###进入根目录 （cd+路径：进入某文件） 显示当前文件夹内所有文件

![cd,ls.png](https://upload-images.jianshu.io/upload_images/14467497-80352a7636bbd0c0.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

###进入Desktop 文件  新建一个Lckgit文件

![mkdir.png](https://upload-images.jianshu.io/upload_images/14467497-4512f9af0395d372.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


###从储存库中复制（克隆）文件 （会在当前文件中默认新建文件储存文件） 选择SSH模式

![kelong.png](https://upload-images.jianshu.io/upload_images/14467497-9b6b28619dc6bd60.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

###生成ssh密匙，输入命令后，连按三个回车生成SSH 密钥

![5.png](https://upload-images.jianshu.io/upload_images/14467497-4df023fbdf7e90e5.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

###检测状态 （是否有新建删除等操作）

![6.png](https://upload-images.jianshu.io/upload_images/14467497-adbe29609e87a15e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


###创建lpl.md

![7.png](https://upload-images.jianshu.io/upload_images/14467497-fca3ddb3d8f04fba.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

###将文件添加到本地缓存

![8.png](https://upload-images.jianshu.io/upload_images/14467497-f28970095ada7405.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)



###将文件添加到本地仓库

![9.png](https://upload-images.jianshu.io/upload_images/14467497-70f0fe76e0399126.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


####第一次将文件添加到本地库需要验证

![10.png](https://upload-images.jianshu.io/upload_images/14467497-678ab23329db6344.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)



####输入自己的邮箱和用户名

![11.png](https://upload-images.jianshu.io/upload_images/14467497-18cc9e4ef303a3bd.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

###将文件上传到博客

![a.png](https://upload-images.jianshu.io/upload_images/14467497-e4e4c0021bb11dfe.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

###SVN的优点：

1、采用集中式，易于管理，保证安全性；
2、管理方便，逻辑明确，理念符合常规思维；
3、代码的一致性高；
4、适合人数不多的项目开发；
5、允许一个文件有任意多的可命名属性，会关注所有的文件类型；
6、支持二进制文件，更容易处理大文件；
7、支持空目录。

SVN的缺点：
1、服务器压力太大，数据库容量暴增；
2、必须连接在服务器上，否则基本不能工作、提交、对比、还原等；
3、不适合开源开发。

===========================

Git的优点：
1、适合分布式开发，强调个体；
2、公共的服务器压力和数量都不会太大；
3、速度快， 成熟的架构，开发灵活；
4、任意两个开发者之间可以很容易的解决冲突；
5、离线工作，管理代码成本低，不需要依赖服务器；
6、部署方便。基本上下个命令就可以用；
7、良好的分支机制，可以让主干代码保持干净。

Git的缺点：
1、资料少，学习成本比较大，学习周期比较长，要求人员素质比较高；
2、不符合常规思维；
3、代码保密性差，一旦开发者把整个库克隆下来就可以完全公开所有代码和版本信息。
--------------------- 
作者：星空-点点 
来源：CSDN 
原文：https://blog.csdn.net/bmicnj/article/details/78413058?utm_source=copy 
版权声明：本文为博主原创文章，转载请附上博文链接！
