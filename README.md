＃项目功能简介
- 该项目用于对文件的加密/解密
- 项目己经给出了Makefile
- 运行流程：
>1.解析 <mode〉 是加/解密，如果mode的值不是1或者2’反馈错误信息
>2. 对文件进行加/解密（简单的异或加/解密）
>3.如果文件、<input_file>、<output_file> 有问题，先输出文件错误信息，加解密函数退出函数返-1
>4.如果文件没有问题，加密完成打印文件加/解密成功信息
# 使用说明
一共有4项输入分别为<mode> <input_file> <output_file> <key>
>
>
a.“〈mode〉 值为1或者2 ，1表示
b.<input_file>为输入文件，<output_file> 为输出文件
c.<key> 为加密密钥
#作者信息
- 姓名：欧阳宇轩
- 邮箱：3130414147@qq.com
- GitHub：Yuu

