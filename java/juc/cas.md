# 介绍

compare and swap

# 缺点

当获取不到资源时,会长期占有资源

cas在写回数据时是先将原数据进行比较是否发生改变,如果不变则写回新数据,但是有的时候**数据不变不代表没有发生修改**

 