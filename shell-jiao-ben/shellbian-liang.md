# Shell变量

- 命名规则：  

   1.命名规则和其他编程语言基本相同。
   2.注意变量名和=号之间不能有空格！！！！
   
- 定义普通变量：
   `var_temp="我是一个变量"`
- 定义只读变量：
   ```
   var_temp="我是一个变量"
   readonly var_temp
   ```
- 变量使用：
```
#使用美元符号+变量名 即可引用 大括号定义变量的边界
var_temp="我是一个变量"
echo $var_temp
echo ${var_temp}
```
- 变量删除:

 ```unset var_temp ```
- 变量种类：
   - 1.局部变量
   - 2.环境变量
   - 3.Shell变量
- 拼接字符串：和PHP一样，但去掉连接符.号  
- 获取字符串长度：
`echo ${#var_temp}`
- 截取字符串：
`echo ${var_temp:1:4}`#获取2到4之间的字符

- 定义数组变量：
   ```markdown
   #只支持一维数组
   temp_arr=(value1 value2 value3)
   temp_arr[3]=value4
   #获取数组长度
   echo ${#temp_arr[@]}
   ```
   
 
