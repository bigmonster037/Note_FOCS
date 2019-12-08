# 第十二章复习题

#### 1. 什么是抽象数据类型？在抽象数据类型中，什么是已知的？什么是隐藏的？

抽象数据类型即为将数据和操作的定义封装为一个可供使用的数据类型。

在抽象数据类型中，数据和操作的定义是已知的，操作的实现是隐藏的。

#### 2. 什么是栈？本章定义的4种栈的基本操作是什么？

栈是一种只能够后进先出的限制线性表。

其四种操作为：建栈，入栈，出栈，查看栈是否为空

#### 3. 什么是队列？本章定义的4种队列的基本操作是什么？

队列是一种只能够先进先出的限制线性表。

其四种操作为：建队列，入队，出队，查看队列是否为空

#### 4. 什么是广义线性表？本章定义的6种广义线性表的基本操作是什么？

广义线性表相对于限制线性表而言，其不限制对线性表的操作。

其六种操作为：建表，插入，删除，查找，遍历，查看表是否为空

#### 5. 定义一棵树，区分树和二叉树，区分二叉树和二叉搜索树

树是一个只有一个点的入度为零的有向连通图。

二叉树限定了每个节点的子树数量至多为2。

二叉搜索树限定了其左子树的值均小于根，且右子树的值均大于根，并且左右子树也均为二叉搜索树。

#### 6. 二叉树的深度优先遍历和广度优先遍历有何不同？

深度优先遍历为递归搜索，其会优先将当前遍历分支遍历完成再遍历下一个分支。

广度优先遍历为按层次遍历，其不会优先深入遍历分支。

#### 7. 什么是图？有向图和无向图的区别是什么？

图即为点集和边集。有向图的边具有指向性，而无向图的边不具有指向性（可以将无向图的每条边看作是两条相反的有向边）。

#### 8. 列出栈和队列的一些应用

栈：倒转数据，括号匹配，步骤回溯。

队列：缓存队列。

#### 9. 列出广义线性表的一些应用

数据存储和访问

#### 10. 列出二叉树和二叉搜索树的一些应用

有序数据的存储和快速搜索