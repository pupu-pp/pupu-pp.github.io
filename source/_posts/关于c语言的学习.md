---
title: 关于c语言的学习
date: 2026-10-08 14:17:52
tags:
---
    关于c语言的学习：
    #include <stdio.h> 表示所应用的库： 
           <stdio.h> 即 std = standard；
                         i  = input;
                         0  = output; 即基础输入与输出
    int main()  即为主函数 作为程序的入口 有且只有一个（需要特别注意的是 如果一个项目内有多个.c文件 也只能有一个main函数）：
            int表示返回类型 main则为函数名  
    size of 计算字符长度：
            打印计算结果时 ... printf("%zu\n" , size of char) ...
    占位符：
            %d 打印整数（十进制）
            %c 打印字符
            %f 打印小数                            
