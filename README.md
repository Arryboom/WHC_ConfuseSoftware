# iOS代码混淆专家   

<div align=center><img src="https://github.com/netyouli/WHC_ConfuseSoftware/blob/master/ConfuseSoftware/logo.png" width = "100" height = "100"/></div></br>

## 最新版本：v1.9.3.6

该软件主要解决机器审核4.3、2.1（使用模拟人工手动混淆模式防止出现2.3.1）

### v1.9.3.6更新内容：
- 1.添加手动加密、解密字符串、生成objc、swift解密函数
- 2.修复混淆项目目录下图片2倍图和3倍图名称不一样的问题
- 3.修复pch文件混淆出现Unicode字符问题
- 4.添加一些关键字过滤


查看更多：[🔍查看更多历史更新记录](https://github.com/netyouli/WHC_ConfuseSoftware/blob/master/history_readme.md)

Introduce
==============
-  ☑ 支持Swift、Objc、u3d项目
-  ☑ 支持swift、objc项目字符串混淆加密(支持中文英文符号表情符号混淆加密)
-  ☑ 支持文件名、类名、方法名、属性名、xib、storyborad关联方法名类名的翻新修改
-  ☑ 支持mp3、wav、png、jpg、jpeg、gif、Assets.xcassets里图片资源文件名自动翻新并同步到代码里
-  ☑ 支持添加混淆方法体、添加混淆属性
-  ☑ 支持自动调用生成的混淆方法体
-  ☑ 支持生成函数、属性名称翻新混淆名称宏映射表(Objc特有功能)
-  ☑ 支持部分混淆(可选插入方法、可选插入属性、可选插入调用生成的方法体)
-  ☑ 支持生成并自动插入混淆函数体
-  ☑ 支持生成并自动插入混淆属性声明
-  ☑ 支持生成详情翻新日志文件(方便排查翻新后产生的编译错误)
-  ☑ 支持加载白名单(过滤不需要翻新的方法名、文件名、目录下子文件)
-  ☑ 支持在加载原路径项目下进行翻新
-  ☑ 支持在加载原路径项目下进行复制备份翻新

Note
==============
- 使用Xcode10加载混淆项目，在混淆之前最好关闭工程，混淆完成了再打开工程，避免Xcode10上面文件名爆红错误

Video
==============
[视频翻新演示：](https://pan.baidu.com/s/1_ji0en1xhPd8s_zIrt2LEQ)https://pan.baidu.com/s/1_ji0en1xhPd8s_zIrt2LEQ

Require
==============
* Mac OS X 10.10+

Install
==============
* 下载该项目然后双击文件./ConfuseSoftware/ConfuseSoftware.dmg 安装文件

Usage
==============
查看翻新效果例子对比工程：./翻新之后App效果工程   ./翻新之前App效果工程

## 动态混淆演示
![](https://github.com/netyouli/WHC_ConfuseSoftware/blob/master/ConfuseSoftware/demo.gif)

## 手动加解密字符串
![image](https://github.com/netyouli/WHC_ConfuseSoftware/blob/master/ConfuseSoftware/字符串加密.png)

## 字符串加密混淆反编译前后对比
![image](https://github.com/netyouli/WHC_ConfuseSoftware/blob/master/ConfuseSoftware/1.png)![image](https://github.com/netyouli/WHC_ConfuseSoftware/blob/master/ConfuseSoftware/2.png)

## 自动翻新iOS项目
![image](https://github.com/netyouli/WHC_ConfuseSoftware/blob/master/ConfuseSoftware/翻新1.png)

## 随机生成Objc方法
![image](https://github.com/netyouli/WHC_ConfuseSoftware/blob/master/ConfuseSoftware/翻新3.png)

## 随机生成Swift方法
![image](https://github.com/netyouli/WHC_ConfuseSoftware/blob/master/ConfuseSoftware/翻新2.png)



## 欢迎下载使用(*￣︶￣)