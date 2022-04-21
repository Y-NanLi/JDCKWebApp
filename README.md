# jdckWebApp

#### 介绍
使用内置浏览器登录京东后，获取CK



#### 更新
- 2022-4-21 ~ 2022-4-22：
     -  dev分支已完成 提交CK到青龙，以及青龙的登录、环境变量维护功能，已使用2.11.3版本测试通过。

- 2022-4-20：
     -  捣鼓了下QQ授权登录，比较鸡肋，需要把APP设置成默认浏览器，具体看下面的使用说明。

- 2022-4-19：
     -  **青龙脚本兼容版**  [giteeCK.py](https://gitee.com/maxinDev/jdck-web-app/blob/master/temp/giteeCK.py) ,已测试 2.8.0 、2.11.2

- 2022-4-18：
    - 解决android12安装出现-22问题
    - 脚本添加推送

    
#### 后续的一些想法：

- 2022-4-22：
    - ✗ 区分管理员、普通用户APP，管理员可登录、维护青龙数据， 普通用户只能使用浏览器抓CK，以及提交到GitEE或青龙服务器。
- 2022-4-19：
    - ✔ APP添加青龙IP的配置页面，有公网的可以直接提交CK到服务器，免得嫖Gitee服务器；
    - ✔ APP接入青龙的一些简单功能，暂时接入（登录、环境变量维护）；
    

#### 

#### 安装教程


#### 使用说明


- QQ授权登录


    > 偶然发现浏览器在JD登录页有个QQ授权登录，可以拉起手机QQ授权，于是捣鼓了一下，发现如果在【JdWeb】APP中使用QQ授权登录，QQ授权后，会跳转到手机的默认浏览器；
    > 额。。？这样我没办法拿到CK了啊。。 最后妥协了，直接在手机 设置 -> 应用管理 -> 默认应用管理 -> 浏览器  ，把【JdWeb】APP设置成了默认浏览器，再测试了一次，发现成功了。
    > 总的看起来，非常鸡肋。聊胜于无吧，先记录下。


#### 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request

