# 如何在自己的电脑上搭建一个属于自己的WebApp
 1. 先阐述一下环境吧:
 * 手机app开发需要的ide以及开发环境
     * android部分
         * android-studio 官方
         * idea 收费较高的java集成开发环境
         * eclipse 社区免费版 插件丰富
2. 推荐一款插件给大家当然这个插件是在你做应用的环境搭建好了以后，，这款插件瞬间提升逼格
3. cordova 自我感觉还是mac 使用这款插件的话还挺简单的。当然你得有个npm 顺带也装一个nodejs吧
4. 简单阐述一下mac 下如何使用cordova [1] :http://cordova.apache.org/官网看一下无脑操作吧。
  * npm install -g cordova 因为权限问题在你的终端输入的时候 ： sudo npm install -g cordova(把自己开发的web程序打包成app安装包)
  * cordova 现在支持主流的手机操作系统, android iOS wp
  * cordova 提供很多的插件, 通过插件可以调用设备的硬件
  * 安装好了后 cordova create app（这里的app是你应用的名称到时候会创建一个文件夹出来）    //创建应用
  * cd app 进入应用文件夹
  * cordova platform add ios //为app添加一个平台
  * cordova build ios//编译项目
  * cordova run ios //在指定平台上运行程序 xx为平台名字
  * 
  
多注意看报错的地方，这个插件很无脑的。如果你电脑有Xcode。你又是一个web 前段想看看他们app是怎么构建的。你下个这插件。可以稍微有点成就感。
很高端的

 
