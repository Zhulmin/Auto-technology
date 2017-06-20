# Auto-technology



### 自动打包

### 使用sh脚本打包
* [iOS-AutoPackage](https://github.com/913868456/iOS-AutoPackage) 使用shell脚本打包
  
#### 该方法Xcode 8.3版本过期, Xcode更新以后缺少[PackageApplication](https://pan.baidu.com/s/1i4BErJ3)文件

报错:
```shell
xcrun: error: unable to find utility “PackageApplication”, not a developer tool or in PATH
```
  
解决办法：从老版本拷贝该文件到这个路径 
```shell
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin 
```
  
执行命令:
```shell
sudo xcode-select -switch /Applications/Xcode.app/Contents/Developer/
```
```shell
chmod +x /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin/PackageApplication
```
  
  
    
