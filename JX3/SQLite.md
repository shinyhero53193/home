### 工作项
- 构建
	 PC
	 Android
	 Ios
- 读文件改为读SQLite
- 内存/性能测试

### 现有项
- SQLite 是存储position的，由lua调用
- 较大的表格
	 player_animation_m* 
	 player_animation_f*
- 数据结构： m_setNpcNoMap
- 函数：KTableList::IsNpcNoMap()

### 备注
- SQL支持内存数据库
- 线程安全