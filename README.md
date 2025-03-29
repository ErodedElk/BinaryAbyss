# Binary Abyss / 二进制深渊
![](image/TokGame.jpg)

## 摘要
这是一个二进制安全系列课程。以 **CTF(Capture The Flag)** 为导向，预计将会包括 **Basic(基础知识)**、 **Pwn(二进制漏洞利用)** 与 **Reverse(逆向工程)** 三部分主要内容以及 **Other(其他内容)**。
![](image/top.png)
> 备注：本项目的课程会按照前后铺垫的顺序陆续发布，对于刚入门的同学，建议按照课程更新顺序查看。
## 目录
### 前言
- [项目介绍](https://www.bilibili.com/video/BV1Fc411X7VX):二进制安全系列课程第0节/前言
- 前置技能
	- C 语言
### 基础知识
- [装载与虚拟内存 / 从 C 语言到二进制](https://www.bilibili.com/video/BV1Yu4y1V74t)
	- 什么是内存、什么是地址
	- 什么是虚拟地址
	- 什么是装载动态库
- [汇编基础 / 从 C 语言到汇编](https://www.bilibili.com/video/BV1GC4y1F7wa)
	- 什么是寄存器
	- 处理器与内存如何进行交互
- [Pwn 介绍 / 目标与手段](https://www.bilibili.com/video/BV1J94y1P76i)
	- 一道常规 Pwn 题该有的信息
	- 如何与题目进行交互 / pwntools
- 从做题到出题 / Pwn 容器搭建与部署
- **暂未施工，等待贡献**
### Pwn
- Pwn 环境配置
	- checksec
	- pwndbg
	- one_gadget
	- ROPgadget
	- IDA
	- pwntools
	- [pwn入门之环境搭建 - Haruki](https://hgg-bat.github.io/2021/10/04/pwn%E5%85%A5%E9%97%A8%E4%B9%8B%E7%8E%AF%E5%A2%83%E6%90%AD%E5%BB%BA)
	- [M1/M2 Pwn环境配置 - patrik](https://byesec.com/posts/5aa3009d.html)
	- 这部分内容不做单独讲解，这里引用了两份博客，不完善部分可以自行搜索
- [劫持栈](https://www.bilibili.com/video/BV1ytQaYvETy)
	- ret2text
	- ret2shellcode
	- ret2libc
	- ret2csu
	- 栈迁移 / Stack Pivoting
	- SROP
- [程序保护机制介绍与绕过](https://www.bilibili.com/video/BV1MQofYaEL6)
	- 金丝雀保护 / Canary Protection
	- PIE / 地址无关代码
	- RELRO / 重定向
	- NX / 内存权限限制
- 劫持堆
	- ptmalloc2 堆管理机制
	- 堆溢出 / Heap Overflow
	- UAF 攻击 / Double Free 攻击
	- Tcache Bin Attack
	- Fast Bin Attack
- 沙箱保护 Seccomp 绕过
	- 黑名单 execve
		- 构造 ROP 绕过
		- 堆上劫持利用 magic gadget
- 格式化字符串漏洞利用
	- 栈上的格式化字符串
	- 堆上的格式化字符串
- 整数溢出漏洞利用
- **暂未施工，等待贡献**
### 逆向工程
- 程序逆向分析调试技术
	- 静态分析
	- 动态调试与相关技巧
- 常见程序保护策略
	- 自修改代码 SMC
	- 反调试 / 反编译
- 模拟执行
	- angr 模拟执行原理与实践
- 代码插桩与程序跟踪
	- 白盒代码插桩
		- OLLVM 混淆原理
		- 花指令插桩原理
		- OLLVM 混淆策略定制
	- 二进制插桩
		- 插桩原理
		- 代码插桩跟踪与拦截
- 异构程序分析
	- 跨语言程序分析
		- Python / Golang / Rust / ......
	- 跨架构程序分析
		- Arm / Mips / RISCV / ......
### 其他内容
- 单字节爆破条件与策略
- 面经
- 杂谈：CTF 与实战到底有什么区别
- [杂谈：我们对 Pwn 都有哪些误解](https://tokameine.top/2023/09/21/%E6%88%91%E4%BB%AC%E5%AF%B9%20PWN%20%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B%E8%AF%AF%E4%BC%9A/)
- 行业前景与职业发展杂谈 / 未来我们能做什么?
- **暂未施工，等待贡献**
## 交流群
QQ：**769251521** 
## 赞助
- 暂未施工QWQ
