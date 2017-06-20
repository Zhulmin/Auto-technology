# Auto-technology



### 自动打包

使用sh脚本打包
* [iOS-AutoPackage](https://github.com/913868456/iOS-AutoPackage) 使用shell脚本打包

该方法Xcode 8.3版本过期, Xcode更新以后缺少[PackageApplication](http://blog.csdn.net/itiapp_home/article/details/70241011)文件

xcrun: error: unable to find utility “PackageApplication”, not a developer tool or in PATH

解决办法：找到这个路径 
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin 
然后拷贝一份原来的PackageApplication文件到里面即可。

PackageApplication文件[下载](https://pan.baidu.com/s/1i4BErJ3)


