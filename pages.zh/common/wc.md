# wc

> 计数行、单词或字节。
> 更多信息：<https://www.gnu.org/software/coreutils/manual/html_node/wc-invocation.html>.

- 计数文件中的行数：

`wc {{[-l|--lines]}} {{文件}}`

- 计数文件中的单词数：

`wc {{[-w|--words]}} {{文件}}`

- 计数文件中的字符（字节）：

`wc {{[-c|--bytes]}} {{文件}}`

- 计数文件中的字符数（考虑所有多字节的字符）：

`wc {{[-m|--chars]}} {{文件}}`

- 使用标准输入，按顺序计数行、单词和字符（字节）：

`{{find .}} | wc`
