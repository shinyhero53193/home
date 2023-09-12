- CMake
- CMake编译ios下的静态库 .a
- vcpkg
- xcode的构建过程
- xcode链接.a


### Todo
- ~~新建ios项目
- ~~创建Frameworks管理 .a 静态库，在swift/OC 中调用其函数
- 调研swift/OC生命周期，并映射到XR项目中
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
	