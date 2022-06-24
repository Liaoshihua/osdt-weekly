# PLCT实验室招募 Mono 系统开发实习生，将 Mono 移植到 RISC-V 架构

**岗位编号及名称**

BJ64 Mono 系统开发实习生（负责 RISC-V 移植及优化）

**工作内容**

即便微软开源了 dotNet 环境， Mono 系统在 Linux 开源生态中依然占有重要的位置。还有很多事情需要做。具体可以从 [1] 中看到。 PLCT实验室新设置的岗位就是为了让 RISC-V 在不远的未来（2025年之前）成为 Mono 的 Tier-1 支持平台而存在。我们招募看好 RISC-V 发展的同学来一起为开源社区添砖加瓦。

**岗位要求**

目前PLCT实验室没有全职投入在 Mono 系统的 mentor，因此需要第一位实习生有高度的自驱能力，至少要求达到LV4或以上；第二名之后的实习生要求达到 LV3 或更高级别。

远程实习，支持全球实习工资支付（中国学生必须是国内银行卡）。实习随时可以开始随时可以暂停随时可以结束（如果超过一周旷工、或八周没有外部可见产出会被劝退）。

[1] https://github.com/mono/mono/blob/main/docs/riscv.md

## 如何正确的投递简历

在投递简历之前最好对我们有更多一点了解。以下是阅读材料：

PLCT全称是程序语言与编译技术实验室，隶属于中科院软件所智能软件研究中心（ISRC），致力于成为编译技术领域的开源领导者，推进开源工具链及运行时系统等软件基础设施的技术革新，具备主导开发和维护重要基础设施的技术及管理能力。与此同时，努力成为编译领域培养尖端人才的黄埔军校，推动先进编译技术在国内的普及和发展。

- [极简项目管理](https://github.com/lazyparser/minimalist-team-leader) 是目前PLCT实验室的管理方式，实习生也在管理范围内。请先阅读。
- [我们如何进行实习生招聘](https://github.com/lazyparser/weloveinterns/blob/master/how-do-we-interview-interns.md)
- [我们如何对实习生进行能力评定和培养](https://github.com/lazyparser/weloveinterns/blob/master/how-do-we-rank-interns.md)
- [实习生生存手册](https://github.com/lazyparser/survivial-manual-for-interns) 目前还在断断续续的撰写中，欢迎围观和贡献PR (Pull Requests)

阅读之后，接下来就可以发邮件了。以下内容请认真阅读。不符合条件邮件不会收到回复。

有意者请投递简历至：
**吴老师 wuwei2016@iscas.ac.cn**

邮件标题请注明：
**岗位编号 - 姓名 - 手机号码 - 学校**

邮件正文请:
**进行跟应聘职位相关的自我介绍**，不超过300字。

邮件必须附带简历。**没有PDF格式简历的邮件不保证会收到回复**。

## 所有实习生共性要求（技术类）

开放岗位的入职要求（教学助理等非技术类的同学只需要满足前两条）：

1. 良好的沟通理解能力、能够观察和感知他人的态度和观点。能够主动沟通、遇到计划外或坏消息能够大声的说出来。
2. 知道如何陈述bugs/issues以及向其他人求助，如何不浪费同事的时间，将复现bug需要的信息提供完整。
3. 能力值评定一般要求达到LV2级别及以上。参见：[我们如何面试实习生](https://github.com/lazyparser/weloveinterns/blob/master/how-do-we-interview-interns.md)，[我们如何给实习生评级](https://github.com/lazyparser/weloveinterns/blob/master/how-do-we-rank-interns.md)。
4. 热爱编程，经常写代码。C/C++/Java/JavaScript 任何一种常见语言都可以。
5. 熟练使用 Linux 命令行；会一点 Python/Bash 脚本进行自动化。
6. 熟练使用 Google 搜索引擎。
7. 熟练使用 Git，能够自己 rebase 解决 conflicts。
8. （加分）自学了 RISC-V 指令集，包括 RV32GC 和 RV64GC。在自己的电脑上部署运行起来QEMU-RISCV64以及Spike模拟器。
9. （加分）对于网络知识有基本了解并熟练使用，例如SSH任意端口登陆、Port Forwarding、反向链接、ProxyCommand 等配置自行掌握。

点击原文可以调转到公开的实习生仓库：
https://github.com/plctlab/weloveinterns/blob/master/open-internships.md