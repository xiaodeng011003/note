## 常用命令
cat：可以理解为concatenate的缩写，功能是连接多个文件并且打印输出到屏幕，或者重定向到指定文件
此命令常用于显示单个文件内容，或者将几个文件内容连接起来一起显示，还可以从标准输入中读取内容并显示，生产环境中，他常与重定向或追加符号配合使用。

1.查看文件内容： cat file.txt
2.把多个文件合并成一个文件： cat file1.txt file2.txt > newfile.txt
3.创建编辑新文件： 输入cat >file.txt ,后面接要编辑的内容，使用快捷键ctrl+d或ctrl+c结束编辑
4.非交互式的编辑或追加内容到文件尾：cat>>file.txt<< EOF
									  hello
EOF
EOF必须顶格
5.清空文件内容：使用cat /dev/null >file.txt就可以将文件内容清空，但文件还是存在。

