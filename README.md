# proj145-ebpf-impl-by-rust
用Rust重新实现ebpf


### 项目描述

eBPF是Linux操作系统中监控和调试内核活动的方便工具，将eBPF以及其相关的kprobes内核监控程序使用Rust进行重新实现，并支持对Rust异步函数的监控。

### 所属赛道

2022全国大学生操作系统比赛的“OS功能设计”赛道

### 参赛要求

* 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生（2022年春季学期或之后本科毕业的大一~大四的学生）
* 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
* 请遵循“2022全国大学生操作系统比赛”的章程和技术方案要求

### 项目导师

向勇

* github [https://github.com/xyongcn](https://github.com/xyongcn)
* email [xyong@tsinghua.edu.cn](mailto:xyong@tsinghua.edu.cn)

### 难度

高

### 特征

* 熟悉kprobes和eBPF的流程
* 熟悉Rust异步函数流程
* 熟悉 elf 文件格式，elf 加载，elf 链接

### License

* GPL3

### 预期目标

* 把kprobe和eBPF写成独立的库，以支持对基于Rust语言的OS使用
* 扩展对Rust的异步函数的跟踪能力，力争达到类似于同步函数的跟踪能力和方便程度；能够对Rust异步函数里的单独状态进行跟踪
* 动态获取同步和异步函数的参数和返回值信息；

