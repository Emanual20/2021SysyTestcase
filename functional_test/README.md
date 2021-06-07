# 2021SysyTestcase



- bbbblockkkk.* 

  >检查block的语法，里面可以没有任何语句

- big_returnval.*

  >检查返回值，返回值应该模256

- hidden_var.*

  > 检查不同作用域的同名变量使用情况

- long_func.*

  > 对于较长的函数，arm的语言特性可能有某些标号由于立即数位宽限制无法跳转

- long_name.*

  > 较长的标识符。

- many_params\*.*

  > 很多的参数，对于较长的函数，arm的语言特性可能有某些标号由于立即数位宽限制无法跳转。检测常量池。

- printf.*

  > 检查putf函数是否支持。

- same_name*.\*

  > 对于sysy文法规定，支持函数和变量名的标识符同名。

- test_array.*

  > 用于测试函数调用嵌套函数调用，代码生成的顺序，以及数组的基本运算。
