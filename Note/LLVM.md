### 流程
- 将原代码转化为内存中的抽象语法树AST
- 前端生成中间代码（IR）
	 内存中的LLVM IR
	 比特码形式的
	 可读形式的
- 后端优化IR
- 后端生成汇编代码

### 步骤
- 编写LLVM Pass 可以对IR进行分析和修改
