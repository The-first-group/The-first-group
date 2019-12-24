产品  

 

· [主页 ](https://product.hubspot.com/)

 

· [工作](https://www.hubspot.com/jobs/departments/product-and-engineering)

 

· [博客 ](https://product.hubspot.com/blog)



Git和GitHub入门指南（教程）

 

2015年10月1日/[作者MEGHAN NELSON](https://product.hubspot.com/blog/author/meghan-nelson)



 

· 分享

 

 

8月，我们在HubSpot公司举办了[女性工程师聚会](http://www.meetup.com/Women-Who-Code-Boston/events/224072838/)，并为初学者举办了有关使用git和GitHub的研讨会。我首先浏览了有关git的基础知识和背景的[幻灯片演示](https://www.slideshare.net/HubSpot/git-101-git-and-github-for-beginners)，然后我们分成小组来运行我创建的用来模拟大型协作项目的教程。

 

活动结束后我们得到了反馈，反馈者称这是一个实用性的操作介绍。因此，如果您还是git的新手，请按照以下步骤操作，可轻松更改代码库，打开pull request（PR）并将代码合并到master分支中。任何重要的git和GitHub术语均以粗体显示，并带有指向官方git参考资料的链接。

步骤0：安装git并创建一个GitHub帐户

首先您现在需要做的是安装git并创建一个免费的GitHub帐户。

请按照此处的说明安装git（如果尚未安装）。请注意，对于本教程，我们将仅在命令行上使用git。尽管有一些很棒的git GUI（图形用户界面），但我认为先使用git特定的命令学习git，然后在更熟悉该命令后尝试git GUI会更容易。

完成此操作后，在此处创建一个GitHub帐户。 （公共仓库是免费的，但私人仓库是收费的。）

 

步骤1：建立本地git存放区

使用git在本地计算机上创建新项目时，首先要创建一个新的仓库（或简称为“ repo”）。

要使用git，我们将使用终端。如果您对终端和基本命令没有太多经验，请查看本教程（特别是“导航文件系统”和“移动”部分）。

首先，打开一个终端，然后使用cd（更改目录）命令移动到要在本地计算机上放置项目的位置。例如，如果您的桌面上有一个“项目”文件夹，则可以执行以下操作：

 

要在文件夹的根目录中初始化git仓库，请运行git init命令  