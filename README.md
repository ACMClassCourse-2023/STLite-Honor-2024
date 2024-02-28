# STLite-Honor-2024
Toy Implementation of the C++ Standard Template Library (STL). Course project of Data Structure Honor (2024 Spring), SEIEE, SJTU

## 内容概要

本学期大作业要求同学们完成下面五个任务：

1. vector (5 pts)
2. list (5 pts)
2. priority queue (7 pts)
2. linked hash map (8 pts)
3. map / B+ tree (15/16 pts)

实现代码的接口框架与头文件已经给出，同学们需要补充完整的实现。

同学们需要在每个任务的截止日期前，完成相应任务的实现，并提交到 OJ 上。助教会在截止日期后一段时间内安排 Code Review。

**注意：在本作业中，除非下发代码含有，只允许使用 `cstdio`、`cstring`、`iostream`、`cmath`、`string` 五个 C++ 标准库，如需使用其他功能请自行实现。**

**注意：对于每个任务，在 OJ 上通过测试数据可获得 80% 的分数，Code Review 占 20% 的分数。**

### 关于 map / B+ tree 的评分说明

作业发布后添加

## 发布时间 & 截止时间

1. vector：发布时间 第二周周日（2024.3.3），截止时间 第五周周日（2024.3.24）；
2. list：
3. priority_queue：
4. linked_hashmap：
5. map/bpt：

请大家严格把握好时间！建议尽早开工尽早完成！

## 文件说明

以 vector 为例，在 vector 文件夹下分别有数据和接口文件。

* **其中 `vector.hpp` 是你仅需实现的文件，也是 OJ 上提交的代码。**

* `exceptions.hpp` 与 `utility.hpp` 是两个辅助文件(**不可修改**)，提供了异常处理类与 pair 类，你可以在你的代码中自由使用。
* data 文件夹中有多组测试数据，分别位于各个文件夹中。

## 如何测试你的代码？

以 vector 为例，若要在本地测试，请将你的代码 `vector.hpp`、相应测试点下的 cpp 文件 `code.cpp`  和 `class-bint.hpp`, `class-integer.hpp`, `class-matrix.hpp`, `utility.hpp`, `exceptions.hpp` 放在同一个目录下编译运行。

### 内存泄漏？

如果你想在本地测试自己的代码是否存在内存泄漏，请点击[如何检测内存泄漏？](./tutorials/detect-memory-leak/detect-memory-leak.md)

当然，**你不一定非要在自己电脑上测试**。如果你提交的代码中存在内存泄漏，OJ 会告诉你的。

## 评测及提交方式

* 以 vector 为例，你只需要将你 `vector.hpp` 中的代码粘贴到 OJ 上提交即可
* 评测**开 O2 优化**
* 由于 Valgrind 内存检测会导致程序运行时间增长，**OJ 上的 Memory Check 会相应扩大时限**。
