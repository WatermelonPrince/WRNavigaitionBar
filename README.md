![image](https://github.com/wangrui460/WRNavigationBar/raw/master/screenshots/WRNavigationBar.png)

[For Objective-C：https://github.com/wangrui460/WRNavigationBar](https://github.com/wangrui460/WRNavigationBar)


------------------------------------------------------------

## Requirements
- iOS 8+
- Xcode 8+


## Demo 

![导航栏显示渐变色](https://github.com/wangrui460/WRNavigationBar_swift/raw/master/screenshots/导航栏显示渐变色.gif)

![导航栏显示图片](https://github.com/wangrui460/WRNavigationBar_swift/raw/master/screenshots/导航栏显示图片.gif)

![新浪微博个人中心](https://github.com/wangrui460/WRNavigationBar_swift/raw/master/screenshots/新浪微博个人中心.gif)

![qq空间](https://github.com/wangrui460/WRNavigationBar_swift/raw/master/screenshots/qq空间.gif)

![知乎日报](https://github.com/wangrui460/WRNavigationBar_swift/raw/master/screenshots/知乎日报.gif)

![QQ我的资料页](https://github.com/wangrui460/WRNavigationBar_swift/raw/master/screenshots/QQ我的资料页.gif)

![蚂蚁森林](https://github.com/wangrui460/WRNavigationBar_swift/raw/master/screenshots/蚂蚁森林.gif)

![连续多个界面导航栏透明](https://github.com/wangrui460/WRNavigationBar_swift/raw/master/screenshots/连续多个界面导航栏透明.gif)

![自定义导航栏](https://github.com/wangrui460/WRNavigationBar_swift/raw/master/screenshots/自定义导航栏.gif)

![移动导航栏](https://github.com/wangrui460/WRNavigationBar_swift/raw/master/screenshots/移动导航栏.gif)


## Installation 

> **手动拖入**
> 将 WRNavigationBar 文件夹拽入项目中即可使用

## How To Use

<pre><code>
// 一行代码搞定导航栏显示图片
navBarBackgroundImage = UIImage(named: "imageNav")
// 一行代码搞定导航栏颜色
navBarBarTintColor = .white
// 一行代码搞定导航栏透明度
navBarBackgroundAlpha = alpha
// 一行代码搞定导航栏两边按钮颜色
navBarTintColor = UIColor(red: 0, green: 0.478431, blue: 1, alpha: 1.0)
// 一行代码搞定导航栏上标题颜色
navBarTitleColor = .black
// 一行代码搞定状态栏是 default 还是 lightContent
statusBarStyle = .default
// 一行代码搞定导航栏底部分割线是否隐藏
navBarShadowImageHidden = true;
</code></pre>

<pre><code>
// 设置导航栏默认的背景颜色
UIColor.defaultNavBarBarTintColor = UIColor.init(red: 0/255.0, green: 175/255.0, blue: 240/255.0, alpha: 1)
// 设置导航栏所有按钮的默认颜色
UIColor.defaultNavBarTintColor = .white
// 设置导航栏标题默认颜色
UIColor.defaultNavBarTitleColor = .white
// 统一设置状态栏样式
UIColor.defaultStatusBarStyle = .lightContent
// 如果需要设置导航栏底部分割线隐藏，可以在这里统一设置
UIColor.defaultShadowImageHidden = true
</code></pre>


## See detail
我的简书: [韦德460](http://www.jianshu.com/p/7e92451ab0b2)


## Update
- **2017.07.22**
添加新DEMO：连续多个界面导航栏透明

- **2017.07.09**
解决问题：当一个控制器中包含多个控制器时，导航栏颜色或透明度不正常的问题

- **2017.07.04**
添加新功能：全局设置导航栏显示图片(不建议在非自定义导航栏中使用)

- **2017.07.01**
添加新功能：导航栏可显示图片

- **2017.06.29**
添加新功能：可单独设置每个控制器对应导航栏底部分割线是否隐藏

- **2017.06.29**
解决问题：解决引入WRNavigationBar后，无法设置导航栏标题大小的问题

- **2017.06.19**
解决问题：解决移动导航栏后右滑返回中途取消导致的导航栏错位的问题

- **2017.06.15** 
解决问题：解决scrollView正在滑动的时候，点击返回按钮，导航栏颜色变化突兀的问题

- **2017.05.21** 
解决问题：解决push导航栏没有渐变动画太突兀的问题

- **2017.05.20** 
解决问题：解决侧滑返回导航栏没有渐变动画太突兀的**问题

- **2017.05.16** 
新增Demo：完成自定义导航栏实现透明渐变等效果

- **2017.05.12** 
解决问题：侧滑一点松开透明的导航栏会变不透明

## Features


# Contact me
- Weibo: [@wangrui460](http://weibo.com/wangrui460)
- Email:  wangruidev@gmail.com
- QQ：1204607318

# License

WRNavigationBar is available under the MIT license. See the LICENSE file for more info.

