# 流程控制
- if else流程：

    - if else
    ```
    if condition
    then
        command1 
        command2
        ...
        commandN
    else
        command
    fi
    ```
    
    - if else-if else
    ```
    if condition1
    then
        command1
    elif condition2 
    then 
        command2
    else
        commandN
    fi
    ```
- for 循环：
```
for var in item1 item2 ... itemN
do
    command1
    command2
    ...
    commandN
done
```

- while 语句
```
while condition
do
    command
done
```

- case 语句：
```
echo '输入 1 到 4 之间的数字:'
echo '你输入的数字为:'
read aNum
case $aNum in
    1)  echo '你选择了 1'
    ;;
    2)  echo '你选择了 2'
    ;;
    3)  echo '你选择了 3'
    ;;
    4)  echo '你选择了 4'
    ;;
    *)  echo '你没有输入 1 到 4 之间的数字'
    ;;
esac
```
