# Hi！你好啊！我是阿川！欢迎你来到acphp框架！ 

&emsp;说到这个acphp框架，是我在阮一峰老师的博客看"[浅谈MVC模式][1]"的时候，突然心血来潮，想封装一个自己的框架！ 想一想把自己的想法融入到自己的框架中，既锻炼自己的能力又非常的有趣！

&emsp;虽然技术暂时还不咋样，但是我一直在努力，我不甘于此。在谷歌随缘搜索了一遍,有个博主有一篇[MVC框架实例][2]文章，非常感谢他！

## acphp 框架 目录结构
    acphp                WEB部署根目录
    ├─app                应用目录
    │  ├─controllers     控制器目录
    │  ├─view            视图目录
    │  ├─models          模块目录
    │  ├─.htaccess       用于apache的重新写
    │
    ├─config             项目配置
    │  ├─database.php    数据库配置文件
    │
    ├─core               核心目录
    │  ├─base            MVC基类
    │  ├─db              数据库操作类
    │  ├─logs            日志
    │  ├─acphp.php       内核文件
    │
    ├─static             静态文件目录
    │  ├─css
    │  ├─font
    │  ├─images
    │  ├─js
    │
    ├─index.php          入口文件
    ├─README.md          自述

## 代码规范
下述规则是为了程序能更好的相互调用！

   1.Mysql的表明需**小写**。
   2.模块名（Models）需要名[**大驼峰**][3]命名，既首字母**大写**。
   3.控制器（Controller）需要名[**大驼峰**][3]命名，既首字母**大写**。
   4.方法名（Action）需要用[**小驼峰**][3]命名法。
   5.视图（View）部署结构为**控制器名-行为名**，如：paging-paging.php。

## 





[1]: http://www.ruanyifeng.com/blog/2007/11/mvc.html
[2]: https://www.awaimai.com/128.html
[3]: https://www.kancloud.cn/kancloud/lua_style_guide/66327
