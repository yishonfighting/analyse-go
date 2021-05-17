### Go 源码解读归档

Go语言从2009诞生之初已有十余年的历史，但是不同于其他语言，这么长的时间里，GO本身的语言并没有太大的变化。
从语言设计的角度看，作为一门从诞生之初就考虑低成本、高并发、简洁等原则的语言，包涵其简洁设计背后的各项实现机制以及具体工作原理。

#### 为什么源码？

技术、架构一直在变化，就算是设计也总在演进、源码也总是在不断的变化，但是源码可以帮助我们更加深的对语言本身的理解，以及理解某个设计背后所使用的根本原理。

我很喜欢一句话，代码总是可以推到重来，但是原理却可以"永生"。

那么，希望后续的一些说明也能带给你些许的启发。·    