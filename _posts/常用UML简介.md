常用UML简介

# 什么是UML

统一建模语言(Unified Modeling Language，UML)是一种为面向对象系统的产品进行说明、可视化和编制文档的一种标准语言，是非专利的第三代建模和规约语言。UML是面向对象设计的建模工具，独立于任何具体程序设计语言。

UML作为一种统一的软件建模语言具有广泛的建模能力。

UML立足于对事物的实体、性质、关系、结构、状态和动态变化过程的全程描述和反映。

UML采用一组图形符号来描述软件模型，这些图形符号具有简单、直观和规范的特点，开发人员学习和掌握起来比较简单。所描述的软件模型，可以直观地理解和阅读，由于具有规范性，所以能够保证模型的准确、一致。

# UML的作用

为软件系统建立可视化模型：
UML符号具有良好的语义，不会引起歧义;基于UML的可视化模型，使系统结构直观、易于理解

为软件系统建立构件：UML不是面向对象的编程语言，但它的模型可以直接对应到各种各样的编程语言，包括数据库

为软件系统建立文档：不同的UML模型图可以作为项目不同阶段的软件开发文档

> UML的词汇表包含三个构造块：事物、关系、图

# 四种事物

1. 结构事物

    模型的静态部分，描述概念或物理元素

2. 行为事物

    模型的动态部分，描述了跨越时间和空间的行为

3. 分组事物

    模型的组织部分，是一些由模型分解成的盒子，在所有分组事物中，最主要的是包

4. 注释事物

    模型的解释部分，用于描述说明和标注模型的任何元素

# 四种关系

1. 依赖

    是一种使用关系，独立事物发生变化会影响另一个依赖事物

2. 关联

    是一种拥有关系

    2.1 聚集

3. 泛化

    是一种继承关系，表示一种特殊(子元素)/一般(父元素)关系，表示子元素继承父元素的所有特性和行为

4. 实现

    是一种类与接口的关系，表示类是接口的所有特征和行为的实现

# 九种图