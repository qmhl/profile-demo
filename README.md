# profile-demo
SpringBoot与Maven多环境整合

参考链接： https://www.cnblogs.com/zhanglw456/p/15035252.html

- 1. 打包的时候，首先现在idea中选择一个环境，如下图所示：

![image](https://user-images.githubusercontent.com/23047031/148911877-fb433845-d332-481d-b90b-44c5c7ab5cf9.png)

- 2 . 启动脚本中 jar -jar  xxx.jar --spring.profiles.active=dev

- 3 . 可以解压jar  然后看下jar包中\BOOT-INF\classes目录

![image](https://user-images.githubusercontent.com/23047031/148912621-49a0d6b6-fe16-492a-b996-5b5b87a98d52.png)

