# 基于SpringBoot+Mybatis+MySQL5.7的轻语音乐网 

## 主要用到的技术：

 * 使用maven进行项目构建
 * 使用Springboot+Mybatis搭建整个系统
 * 使用ajax连接前后端
 * 使用框架Bootstrap、JQuery开发前端界面 
 * 使用MySQL存储歌曲链接和图片链接
 * 使用cookies存储用户id等
 
 ## 主要分为六个模块
 
 * **用户管理模块**：用户登录、用户注册、修改密码
 * **榜单列表模块**：动态地从数据库中获取歌曲的链接和数据在榜单中显示
 * **歌曲搜索模块**：在首页的搜索框中可以输入关键字进行歌曲的模糊搜索
 * **歌曲收藏模块**：在榜单列表中或搜索页面中可以点击歌曲进行收藏
 * **我的音乐模块**：收藏的歌曲会被添加到我的音乐列表中，在我的音乐列表中也可以对歌曲进行删除操作
 * **音乐播放器模块**：在榜单、搜索页面和我的音乐列表等地方点击歌曲可以跳转到播放页面进行播放。播放页面显示播放进度条，删除歌曲，暂停等操作。播放页面背景为模糊背景，根据歌手的专辑图片自动变化。
 ## 问题：如何启动本系统？ 
 
 1. 将sql文件在MySQL运行生成表和数据
 2. 最后直接启动SsApplication类后访问http://localhost:8080/test/mainpage.html 就可以进入本系统！
 
 ## 功能展示
 
 * 主页
 
 ![image](https://github.com/Linliquan/springboot-music/images/主页.jpg)
 
 ![image](https://github.com/Linliquan/springboot-music/blob/master/images/%E4%B8%BB%E9%A1%B5.jpg?raw=true)
