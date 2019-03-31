## cut 命令  
- ###1.用法简介：
    ```
    用法：cut [选项]... [文件]...
    Print selected parts of lines from each FILE to standard output.
    
    如果没有指定文件，或者文件为&quot;-&quot;，则从标准输入读取。
    
    必选参数对长短选项同时适用。
    -b, --bytes=列表		只选中指定的这些字节
    -c, --characters=列表		只选中指定的这些字符
    -d, --delimiter=分界符	使用指定分界符代替制表符作为区域分界
    -f, --fields=列表		只选中指定的这些域；并打印所有不包含分界符的
    				行，除非-s 选项被指定
    -n				(忽略)
        --complement		补全选中的字节、字符或域
    -s, --only-delimited		不打印没有包含分界符的行
        --output-delimiter=字符串	使用指定的字符串作为输出分界符，默认采用输入
    				的分界符
    -z, --zero-terminated    以 NUL 字符而非换行符作为行尾分隔符
        --help		显示此帮助信息并退出
        --version		显示版本信息并退出
    
    仅使用f -b, -c 或-f 中的一个。每一个列表都是专门为一个类别作出的，或者您可以用逗号隔
    开要同时显示的不同类别。您的输入顺序将作为读取顺序，每个仅能输入一次。
    Each range is one of:
    
    N     N&apos;th byte, character or field, counted from 1
    N-    from N&apos;th byte, character or field, to end of line
    N-M   from N&apos;th to M&apos;th (included) byte, character or field
    -M    from first to M&apos;th (included) byte, character or field

    ```
    



