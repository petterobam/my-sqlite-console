[![Build Status](https://travis-ci.org/petterobam/sqlite-console.svg?branch=master)](https://travis-ci.org/petterobam/sqlite-console)
[![MIT Licence](https://badges.frapsoft.com/os/mit/mit.svg?v=103)](https://opensource.org/licenses/mit-license.php)
[![Analytics](https://ga-beacon.appspot.com/UA-85522412-2/welcome-page)](https://github.com/igrigorik/ga-beacon)
[![stable](http://badges.github.io/stability-badges/dist/stable.svg)](http://github.com/badges/stability-badges)

# sqlite-console
用于管理服务器上所有Sqlite数据库的Web应用，实现功能类似于Sqlite控制台。

# 基本功能演示
PS：请放大查看 ~~

![sqlite-console-show](doc/images/sqlite-console-show.gif)

# 基本界面设计
![sqlite-console-design](doc/images/sqlite-console-design.png)

# 登陆界面
![sqlite-console-login](doc/images/sqlite-console-login.gif)
#### PS：开发中可以关闭验证码功能：
```
#是否启用验证码
web.verify-code.enabled=false
```

# 后续功能
0. ~~完善登陆验证（这个很重要）~~
1. 添加更加丰富的Sqlite操作
2. 完善控制台工具

    - 连接
    - 收藏
    - 记录
    - 工具
    - 窗口
    - 帮助

3. 实现多窗口、多连接
4. 添加多级权限（包括对操作系统命令的执行）
5. 添加可视界面编辑操作（建表、修改等）
6. 想起来再做...
