- CMake
- CMake编译ios下的静态库 .a
- vcpkg
- xcode的构建过程
- xcode链接.a


### Todo
- 新建ios项目
- 创建Frameworks管理 .a 静态库，在swift/OC 中调用其函数
- 调研swift生命周期，并映射到XR项目中
- 在test中添加生命周期的管理，事件注册等
- 调用XR的main, baseLogic等
- 各个逻辑功能接入、验证
- 宏开关，使安卓，ios可用
- 重构～～～～


### 进度 --->
- 10%

### Note
- 生成framework的指令：
	 -xcodebuild -create-xcframework \
	 -library build/libSH.a \
	 -output SH.xcframework

游戏引擎的多平台性能、内存优化；手游热更新方案。主要负责了读配置表内存的优化，具体是指用数据库的手段，去除掉配置表数据占的部分内存；以及/C++热更新方案的研讨制定。由于工程比较宏大，以学习了解为主。

