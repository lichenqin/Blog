## 编译器编写----Scanner

`计算机科学类`

Scanner是第一步，假设这个程序是scan，那么命令行输入:

```
>> scan filename
output: filename.o
scanner work correctly
```

filename.o 里面应该是所有的token信息，实际上运用了getToken() 这个函数，每次返回一个Token信息。

用到的算法与方法: `regular expression` `tompson algorithm` `subset construction algorithm`