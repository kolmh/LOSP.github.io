---
layout: nodate
title: 更新历史
subtitle: 点点滴滴，记录成长的每一步
---
该页面中更新历史，除首个版本是相对于Slim Bean的修改日志外，其余均为相对于上一个公开版本的更新日志。

*__2013.8.28 版本:RELEASE1.3__*  
新增 升级HALO版本至2.0  
新增 侧边栏  
新增 滑动返回手势  
优化 T9拨号结果高亮  
新增 HALO支持调整大小  
修复 部分情况下系统热重启的问题  
优化 更新汉化  
修复 部分情况下锁屏出错  
优化 更换窗口动画  
修复 发彩信FC  
优化 更新米2内核到最新版本  
删除 状态栏透明模式中的“全部”，因为部分APP不支持该模式  
优化 改善滚动流畅度  
优化 合并至Slim Bean 2013-8-28源码  
__本次新增的功能均可以在 设置——导航 中打开、关闭、自定义__  
更多更新请见<https://github.com/LOSP>中对应的commit

*__2013.8.23 版本:RELEASE1.2__*  
新增 重启菜单添加快速重启  
新增 支持T9拼音拨号  
修复 相机快门音禁用设置无效  
优化 合并秋叶随风米2最新源码  
修复 米2 WIFI MAC地址改变  
修复 米1 GPS无效\[尝试性修复\]  
优化 检测到电信卡后自动固定置网络制式为CDMA  
优化 对一些底层函数进行优化  
修复 减少启动器FC  
优化 更新汉化  
优化 合并至Android 4.3 JSS15Q(android-4.3_r2.2)源代码  
更多更新请见<https://github.com/LOSP>中对应的commit

*__2013.8.19 版本:RELEASE1.1__*  
修复 每次开机都需要更新应用  
修复 闹铃不响  
新增 状态栏显示运营商  
优化 拨号盘底部按钮布局调整  
新增 小米手机系列支持重启菜单中双系统切换  
新增 设置界面中新增权限管理选项  
优化 调整移动网络设置到设置首页  
修复 横屏时无法安装应用  
优化 减少启动器FC的情况  
修复 插入耳机时状态栏无图标  
优化 取消内置Google服务  
优化 设置浏览器首页为LOSP官网  
优化 更新汉化  
优化 合并米2部分源码至mitwo-dev最新版本  
更多更新请见<https://github.com/LOSP>中对应的commit

*__2013.8.16 MIUI Recovery 2.10__*  
此版本为MIUI Recovery更新  
修复 备份时Recovery闪退  
新增 支持adb sideload刷机  
优化 合并至Android4.3源码  
修复 不能刷Google服务包的问题  

*__2013.8.15 版本:BETA1.05__*  
__1.05有部分代码重构，所以，从1.0及以下版本刷至1.05及以上的，如果出现无限FC，请清空cache__  
新增 支持米2/2s  
修复 部分情况下，信号强度显示为2147483647的问题  
优化 全部采用gcc4.7编译，可能解决部分不稳定现象  
优化 默认开启ROOT权限  
新增 支持连接到Ad-Hoc虚拟热点,仅支持WEP或无加密  
新增 手指快速划过底部触摸按键可以锁屏  
修复 桌面FC  
修复 部分情况下，HALO通知内容残留在屏幕上的问题  
优化 合并至SlimBean 8-15最新源码  
优化 合并米2内核至秋叶随风最新版本  
更多更新请见<https://github.com/LOSP>中对应的commit

*__2013.8.13 版本:BETA1.0__*  
从此版本开始，LOSP全面升级至Android 4.3  
此版本仅限米1/1s  
修复 HALO按钮导致的通知栏错位  
修复 电信3G  
优化 流畅度  
新增 LOSP开机动画  
优化 调整设置界面  
优化 更改状态栏网速显示逻辑  
更多更新请见<https://github.com/LOSP>中对应的commit

*__2013.8.9 版本:BETA0.2__*  
修复 打开HALO时无法安装应用  
优化 更改应用安装界面风格  
新增 应用安装支持选择安装到SD卡或内置存储  
新增 通话记录页面未知来电显示归属地  
修复 屏幕突然变亮  
修复 状态栏网速显示不正确  
新增 LOSP定制版列表动画  
修复 HALO部分FC及浮动导致的问题  
优化 更新米2内核和适配代码至秋叶随风提交的最新版本  
优化 拨号键盘删除键调整至拨号键右侧  
新增 内置Google服务套件  
新增 应用安装界面提供按钮来开启安装未知来源应用  
优化 修正汉化  
更多更新请见<https://github.com/LOSP>中对应的commit

*__2013.8.5 版本:BETA0.1__*  
新增 支持中文运营商显示  
新增 合并Paranoid的HALO源代码  
新增 日历支持农历/节假日/二十四节气显示（仅中文语言环境有效）  
新增 来去电归属地显示  
优化 强制固定CDMA订阅模式为RUIM/SIM，这样电信版首次开机就有信号  
优化 关机时自动关闭移动数据，以防丢失数据网络  
优化 移植高通frameworks/opt/telephony的部分代码，以更好地支持电信卡  
新增 支持状态栏网速显示  
新增 可在设置——界面——HALO中打开或关闭通知栏中的HALO按钮  
修复 通知栏快速设置面板中“移动网络”瓷块现在可以开关移动数据  
优化 修正部分汉化  
新增 有触摸按键灯的机型，比如米1,可以在设置——界面——显示中设置键盘灯延迟或关闭键盘灯  
新增 LightLauncher启动器支持抽屉界面透明，默认透明度和状态栏透明度一样  
优化 默认状态栏和通知栏透明度50%  
新增 内置输入法为谷歌拼音输入法  
优化 在长按Home键出现的“最近任务”面板中，仅显示正在运行的应用，如果应用的进程已经结束，比如手动按下了“退出”按钮，则不再显示该应用  
修复 部分地区电信卡无法上网  
优化 代码兼容性，可兼容新设备接口和老设备接口，便于适配  
更多更新请见<https://github.com/LOSP>中对应的commit
