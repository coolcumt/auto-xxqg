auto-xxqg
# 最新版的 自动学习强国 
可以帮你自动刷学习强国
## 仅供我学习autojs使用！切勿用于违法用途，否则开发者不承担任何责任。
### 打包好的apk在build文件夹中，下载后即可安装

# 特别鸣谢：
### 感谢85524365指出的问题，详见：https://github.com/Gingmzmzx/auto-xxqg/issues/6
### 感谢blank-psy指出的问题，详见：https://github.com/Gingmzmzx/auto-xxqg/issues/3

## 下面讲一下函数名执行的方法
自动学习强国从2.4.0以上版本都是采用的函数结构，有很多函数构成，这样可以更方便调试程序以及在其他函数中重复调用一个函数。
在main.js中，有许多函数因为还不完善，并没有添加到主页面上，用函数名执行可以激活这些函数。
先在数据配置页配置要执行的函数名以及参数，再到主页面点击函数名执行，程序会先执行start_app函数，然后再执行选定的函数。

