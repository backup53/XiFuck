
# XiFuck

一门参考了 [Brainfuck](https://zh.wikipedia.org/wiki/Brainfuck) 的乳包语言

可以在正常的 C 编译器中编译通过

释放[权平](https://zh.wikipedia.org/wiki/权平)！

|XiFuck|Brainfuck|C|
|---|---|---|
|习近平|+|++*ptr;|
|大撒币|-|--*ptr;|
|||
|修宪|>|++ptr;|
|连任|<|--ptr;|
|||
|登基|.|putchar(*ptr);|
|包皇|,|*ptr = getchar();|
|||
|习特勒|[|while (*ptr) {|
|宽衣|]|}|

## 使用 C 编译器编译

```c
#include "./xifuck.h"

敬祝伟大的领袖伟大的导师伟大的统帅伟大的舵手我们心中最红最红的红太阳习主席万寿无疆万寿无疆万寿无疆
    (...在这里写下 XiFuck 语句)
敬祝习主席的亲密战友我们的王副主席身体健康永远健康永远健康
```

## Hello World

[hello-world.xifuck.c](hello-world.xifuck.c)

```c
#include "./xifuck.h"

敬祝伟大的领袖伟大的导师伟大的统帅伟大的舵手我们心中最红最红的红太阳习主席万寿无疆万寿无疆万寿无疆
    习近平 习近平 习近平 习近平 习近平  习近平 习近平 习近平 习近平 习近平              // initialize counter (cell #0) to 10
    习特勒                                                                         // use loop to set 70/100/30/10
        修宪 习近平 习近平 习近平 习近平 习近平  习近平 习近平                            // add  7 to cell #1
        修宪 习近平 习近平 习近平 习近平 习近平  习近平 习近平 习近平 习近平 习近平          // add 10 to cell #2
        修宪 习近平 习近平 习近平                                                     // add  3 to cell #3
        修宪 习近平                                                                 // add  1 to cell #4
        连任 连任 连任 连任  大撒币                                                   // decrement counter (cell #0)
    宽衣
    修宪 习近平 习近平  登基                                                      // print 'H'
    修宪 习近平  登基                                                            // print 'e'
    习近平 习近平 习近平 习近平 习近平  习近平 习近平  登基                           // print 'l'
    登基                                                                       // print 'l'
    习近平 习近平 习近平  登基                                                    // print 'o'
    修宪 习近平 习近平  登基                                                      // print ' '
    连任 连任  习近平 习近平 习近平 习近平 习近平  习近平 习近平 习近平 习近平 习近平  习近平 习近平 习近平 习近平 习近平  登基  // print 'W'
    修宪 登基                                                                   // print 'o'
    习近平 习近平 习近平  登基                                                    // print 'r'
    大撒币 大撒币 大撒币 大撒币 大撒币  大撒币  登基                                 // print 'l'
    大撒币 大撒币 大撒币 大撒币 大撒币  大撒币 大撒币 大撒币  登基                     // print 'd'
    修宪 习近平  登基                                                            // print '!'
    修宪 登基                                                                   // print '\n'
敬祝习主席的亲密战友我们的王副主席身体健康永远健康永远健康
```

## Copyright

Copyright (c) 2016 Li Qiang
