# wasm的工具

编译构建,对源码的处理和生成二进制内容,都有相应的工具.
如果偏爱汇编类编程,那么这些工具就会提供帮助.

工具分两套,一套给汇编用,一套给开发者用(这里特指高级语言开发者),

- WABT,WebAssembly Binary Toolkit, 二进制工具套件
- Binaryen, 基础设施,包括编译器和工具链

## WABT

这个套件支持二进制的wasm格式和人类可读的文本格式.
文本格式类似s表达式,这种文本格式可用于分析和调试.

WABT支持的s表达式格式并不是wasm本身.
她只是众多表示wasm文件内容格式的一种.
