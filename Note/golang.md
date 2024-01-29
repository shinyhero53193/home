## 1、并发编程

### goroutine
- 用channel控制goroutine的退出
- 优雅退出，做完遗留工作

### 内存模型
- 异步下可能出现编译器/内存重排的情况
- 多个goroutine访问数据，必须先序列化
- 使用显示的同步
- 机器字
- 信号量：
- 互斥锁、条件变量：

### data race 
- 临时变量：引用，共享
- 全局/成员变量：加锁，原子
- CPU 缓存操作， 导致数据竞争

### Mutex
- CAS 比较并替换
- state 锁定、唤醒
- 正常模式和饥饿模式  饥饿：新的goroutine正在CPU上运行，有优势，使得旧goroutinre长时间取不到锁
- 互斥、自旋 自动进行模式的切换
- 读写锁 readwait: 阻塞的goroutine数量，readCount: 当前在读的goroutine数量
- 遵循FIFO原则

### Channel
- 多个goroutine中共享数据优先使用channel，少量共享资源或缓存的保护通常使用Mutex。

### Atomic
- COW 写时复制

### delve
- 当coredump产生时，会在core_pattern中写入堆栈，用dlv查看错误堆栈文件

### interface
- 非侵入式 ： 不需要用户代码引入框架代码的信息
- 一组method的集合
-  用于实现多态
- 依赖反转， 进行功能解耦
- 便于单元测试

### 内存逃逸


### Map
