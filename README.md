# how-tomcat-works

这是书本《How tomcat works》的源码

虽然该书是以tomcat4.1.1原型的，但其循序渐进的方式依旧是理解web服务器工作的好途径

关于源码的出处，以及该书的网址：http://www.brainysoftware.com/9780975212806

需要说明的，直接下载上述网址的源码如果导入到IDE中，会报缺少依赖包的错误，因为源码里的lib包确实是不够的

所以我下载了tomcat4.1.12，使用它的lib包，外加一个commons-daemon-1.1.0.jar，进行了补充

所以现在从这个git上下载的源码是可以直接跑起来的。

注意：这不是一个maven项目，因为早期的很多lib包在中央仓库都是没有的。

你可以在下载此项目以后，把lib目录下的依赖包放到你的nexus私服上去，这样把项目做成maven项目也是可以的


