# 静态代码分析中规则

## 规则、检查引擎、检查原理

首先，规则是需要结合具体的检查引擎和检查原理来定的。在 Java 语言中，能力处于扛把子地位的，是 Fortify，这里结合 Fortify 介绍一下 Java 静态代码分析中，相关的规则定制。

Fortify 规则定制，可以参考：https://paper.seebug.org/papers/old_sebug_paper/books/Fortify/rules-schema/

### 检查原理和检查引擎
检查引擎，是基于具体的检查原理实现出来的。在面向 Java 语言的静态代码分析中，处于主流地位的静态代码分析技术有三种：模式匹配、污点跟踪 和 状态机检查。

1) 模式匹配


2) 污点跟踪


3) 状态机检查


### 规则和检查引擎

规则，其实就是检查引擎的输入。检查引擎，输入规则和代码信息，输出代码中缺陷的程序。
![image](https://user-images.githubusercontent.com/59104148/119217368-64330900-bb0c-11eb-98c1-c02b0ac28a4a.png)
