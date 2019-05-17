# bean2json
idea插件，把bean对象转json
javaweb开发api接口，经常使用json数据，把bean转json特别费劲，写了个idea插件，完成这个重复性劳动
**项目已开源，代码：[https://github.com/liupeng328/bean2json](https://github.com/liupeng328/bean2json)**

# 开发思路
1. 我肯定不从头写，先google，有最好了，搜到一个pojo2json，安装后发现bean转的json没有格式化，很不好用
2. 拿他的代码改，但是他没公开源码，好吧，找到插件的jar文件，反编译为java代码
idea的插件安装后，默认在这个路径：`用户\.IntelliJIdea2019.1\config\plugins`
`如我的路径：C:\Users\Administrator\.IntelliJIdea2019.1\config\plugins`
![](https://upload-images.jianshu.io/upload_images/2833665-2e2cbe25c9a1a1df.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
反编译为java代码，idea自带功能，打开jar就行了
![](https://upload-images.jianshu.io/upload_images/2833665-d9bafa4d6e912379.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
3. 修改代码，把json格式化然后再复制到系统剪切板

![](https://upload-images.jianshu.io/upload_images/2833665-ea05cf5d04cda390.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

4. 安装插件
本地安装
![](https://upload-images.jianshu.io/upload_images/2833665-00aae906795c00de.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
当然你可以搜索安装
![](https://upload-images.jianshu.io/upload_images/2833665-1c9ffe3390e993ac.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


5. 我已经把这个插件，提交idea 插件库了[https://plugins.jetbrains.com/](https://plugins.jetbrains.com/)
![](https://upload-images.jianshu.io/upload_images/2833665-46cb59fca7ab1863.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

# 扩展
- idea插件库 [https://plugins.jetbrains.com/](https://plugins.jetbrains.com/)
-  创建插件开发环境 [http://www.jetbrains.org/intellij/sdk/docs/basics/getting_started/setting_up_environment.html](http://www.jetbrains.org/intellij/sdk/docs/basics/getting_started/setting_up_environment.html)

- 创建插件项目 [http://www.jetbrains.org/intellij/sdk/docs/basics/getting_started/creating_plugin_project.html](http://www.jetbrains.org/intellij/sdk/docs/basics/getting_started/creating_plugin_project.html)
- 运行和调试插件[http://www.jetbrains.org/intellij/sdk/docs/basics/getting_started/running_and_debugging_a_plugin.html](http://www.jetbrains.org/intellij/sdk/docs/basics/getting_started/running_and_debugging_a_plugin.html)

- 部署插件 [http://www.jetbrains.org/intellij/sdk/docs/basics/getting_started/deploying_plugin.html](http://www.jetbrains.org/intellij/sdk/docs/basics/getting_started/deploying_plugin.html)
- 发布插件 [http://www.jetbrains.org/intellij/sdk/docs/basics/getting_started/publishing_plugin.html](http://www.jetbrains.org/intellij/sdk/docs/basics/getting_started/publishing_plugin.html)

