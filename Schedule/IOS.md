- CMake
- CMake编译ios下的静态库 .a
- vcpkg
- xcode的构建过程
- xcode链接.a


### Todo
- ~~新建ios项目
- ~~创建Frameworks管理 .a 静态库，在swift/OC 中调用其函数
- ~~调研swift/OC生命周期，并映射到XR项目中
- 在test中添加生命周期的管理，事件注册等
- 调用XR的main, baseLogic等
- 各个逻辑功能接入、验证
- 宏开关，使安卓，ios可用
- 重构～～～～

### Note
- 生成framework的指令：
	 -xcodebuild -create-xcframework \
	 -library build/libSH.a \
	 -output SH.xcframework
- macos 可以运行，ios 编译出错

- view controller的生命周期


### Q
- cmake构建xcode工程不能运行
- 构建的工程目录没有.h

ZHAOBOQIANG1 [赵博强] <ZHAOBOQIANG1@kingsoft.com>、 YangLin [杨林] <yanglin@kingsoft.com>、 ZouHao [邹浩] <ZouHao@kingsoft.com>、 XIEXIAOLAN [谢晓岚] <XIEXIAOLAN@kingsoft.com>、 罗茜 <luoxi@kingsoft.com>、 xsj_3DEngine_All [引擎平台全员] <xsj_3DEngine_All@kingsoft.com>