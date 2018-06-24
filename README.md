# c
## c的一些要点
1. 数组做函数参数的退回问题 退回为一个指针
结论： 把数组的内存首地址和数组的有效长度传给被调用参数
实参的a和形参的a得数据类型本质不一样，形参中的数组，编译器会把它当成指针处理
形参写在函数上，和写在函数内是一样的，只不过是具有对外的属性而已。

2. 指针指向谁 就把谁的地址赋给指针
指针变量 和 它所指向的内存空间变量是两个不同的概念
理解指针的关键，是在内存。 没有内存，哪来的指针。
