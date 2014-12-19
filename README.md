#DataEye渠道打包工具 (windows .net 4.0)

DataEye渠道打包工具开放源码使用 GPL2 许可分发。[**绿色版本下载地址**](https://github.com/wxq491216/dataeye-muti-channel-build-tool/tree/master/Downloads)

打包工具不能完全保证生成的Apk文件的正确性，建议开发者最好做抽样测试。

Google 现在已经发布了最新的[**构建系统**](http://tools.android.com/tech-docs/new-build-system/user-guide)(New Building System) , 在 Android Studio 中已经支持了最新的
构建系统，如果开发者已经迁移，可以使用新的系统方面的生成渠道包，这是取代渠道打包工具的最佳方式。

## 工具说明

[axmleditor.jar](https://github.com/ntop001/AXMLEditor) 一个AXML解析器，拥有很弱的编辑功能，工程中用来编辑二进制格式的 AndroidManifest.xml 文件.

JarSigner.jar 给 Apk 签名， `SignApk.jar`  文件是我们修改过的 `apk ` 签名工具，实现了和 ADT 中一样的签名方式.

这些java工具都是使用java7编译的，如果您还在使用java 1.6 请留下issue。

[DotNetZip](http://dotnetzip.codeplex.com/) 解压缩和压缩文件使用的是DotNetZip(Ionic.Zip.dll), 运行源码需要加入这个库.
## 更新日志

### V1.0

2014-12-19

更新内容

>1. 提交正式版本。

