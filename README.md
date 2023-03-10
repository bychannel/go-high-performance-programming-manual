# Go 高性能编程手册

### 目录

- 第一章 性能分析
  
  - benchmark 基准测试
  - pprof 性能分析

- 第二章 常用数据结构
  
  - 字符串拼接性能及原理
  - 切片(slice)性能及陷阱
  - for 和 range 的性能比较
  - 反射(reflect)性能
  - 使用空结构体节省内存
  - 内存对齐对性能的影响

- 第三章 并发编程
  
  - 读写锁和互斥锁的性能比较
  - 如何退出协程(超时场景)
  - 如何退出协程(其他场景)
  - 控制协程的并发数量
  - sync.Pool 复用对象
  - sync.Once 如何提升性能
  - sync.Cond 条件变量

- 第四章 编译优化
  
  - 减小编译体积
  - 逃逸分析对性能的影响
  - 死码消除与调试模式
