## Java CPG 资料
基于 CPG（Code Property Graph）的静态代码分析

### 仓库

1. Plume

基于 Soot 生成的 Jimple，在过程间分析的基础上，将数据插入 图数据库，包括 AST，CFG，PDG 等，和 Joern 非常类似。

官网：https://plume-oss.github.io/plume-docs/

Github： https://github.com/plume-oss/plume

2. Tabby

也是使用静态分析框架 Soot 作为语义提取工具，将 class 文件转化为代码属性图。 并使用 Neo4j 图数据库来存储生成的代码属性图CPG

Github： https://github.com/wh1t3p1g/tabby
