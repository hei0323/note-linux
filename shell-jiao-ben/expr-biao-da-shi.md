原生bash不支持简单的数学运算，但是可以通过其他命令来实现，例如 awk 和 expr，expr 最常用。

语法格式：
```php
#反引号``包围+expr+运算符（+ - * / %）+变量
value1=3
value2=4
echo `expr $value1 + $vlaue2`
```
