# Joe-Cocoa-Touch-Class.xctemplate
Joe Cocoa Touch Class.xctemplate


TMUI_iOS_Templates

当我们在 Xcode 里新建文件时，Xcode 默认提供了多种文件模板，并且不同的 class，模板里默认提供的内容也不一样。

这个项目主要是配合 iOS 使用，为 iOS 里常用的几个基类提供模板，另外系统的 UIKit 里的一些常用类也有相应的模板提供，具体请查看项目文件。

使用方式

进入 Xcode 模板存放路径：

`cd /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/Library/Xcode/Templates/File\ Templates/iOS/Source`
将项目拉取下来，并命名为 Joe Class.xctemplate（文件夹名自由定义，后缀名不可变），注意这个目录是系统目录，需要 root 权限才能修改，所以所有 git 命令都需要加 sudo。

`sudo git clone https://github.com/chengzongxin/Joe-Cocoa-Touch-Class.xctemplate.git Joe\ Cocoa\ Touch\ Class.xctemplate`
无需重启 Xcode，直接新建文件，即可看到“Joe Class”的模板可供选择。
