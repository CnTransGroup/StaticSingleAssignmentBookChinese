# 《Static Single Assignment Book》翻译

<img src="public/cover.png?raw=true" align="right" weight="300" height="400"/>

> + [英文版PDF，仅供翻译参考](public/ssabook.pf)

# 目录
+ 第一部分 基础SSA
    + [第一章 介绍](src/chapter1.md)
        + 1.1 SSA定义 
        + 1.2 SSA的非形式化语义
        + 1.3 与传统数据流分析的比较
        + 1.4 此情此景此SSA
        + 1.5 本书余章说明
    + [第二章 性质和变体](src/chapter2.md) **翻译中**
        + 2.1 Def-use和use-def链
        + 2.2 最简性
        + 2.3 严格SSA形式和支配属性
    + 第三章 SSA构造和解构算法
    + 第四章 SSA高级构造算法
    + 第五章 再谈SSA解构
    + 第六章 SSA的函数式表示
+ 第二部分 分析
    + 第七章 简介
    + 第八章 基于SSA传播信息
    + 第九章 存活性
    + 第十章 Loop tree和归纳变量
    + 第十一章 冗余消除
+ 第三部分 扩展
    + 第十二章 简介
    + 第十三章 静态单赋值信息
    + 第十四章 图和Gating函数
    + 第十五章 Psi-SSA形式
    + 第十六章 哈希化SSA形式：HSSA
    + 第十七章 数组SSA形式
+ 第四部分
    + 第十八章 SSA形式和代码生成
    + 第十九章 指令选择
    + 第二十章 If转换
    + 第二十一章 机器代码生成期的SSA解构
    + 第二十二章 寄存器分配
    + 第二十三章 基于SSA的硬件编译
    + 第二十四章 为PHP开发基于SSA的编译器 


## 免责声明
译者纯粹出于学习目的与个人兴趣翻译本书，不追求任何经济利益。译者保留对此版本译文的署名权，其他权利以原作者和出版社的主张为准。本译文只供学习研究参考之用，不得公开传播发行或用于商业用途。有能力阅读英文书籍者请购买正版支持。