CocoaPodsDemo
=============

这是一个测试
写这东西完全是为了测试

ruby -v 查看ruby版本信心





pod search 第三方类库名
进入工程文件夹, 创建一个叫Podfile的文件
vim Podfile
输入如下信息
........乱写的
pod AFNetworking
pod SDWebimage

终端输入
pod install
耐心等待,片刻即好

当添加新的第三方类库的时候
只需要进入到Podfile添加如下代码
pod 类库名

终端输入(进入工程所在的文件夹中)
pod update
