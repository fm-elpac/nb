欢迎阅读 《歧语言之书》 !

本书是歧语言的主要文档, 包含入门教程, 参考手册等。

**草稿**: 注意目前施工中, 部分内容不完整。


## 简介

无歧义中文编程语言, 简称 **歧语言** (nb_lang)。

No amBiguous Chinese programming language, short as NB.


## 主要特点

+ 基于中文的语法设计, 无空格语法。

  现代汉语, 简体中文 (`zh_CN`)

+ 语言设计参考:
  - [python](https://www.python.org/)
  - [月兔 (moonbit)](https://www.moonbitlang.cn/)
  - [rust](https://www.rust-lang.org/)
  - js

+ 使用的底层技术:
  - [WebAssembly (wasm)](https://webassembly.org/)
  - [月兔 (moonbit)](https://www.moonbitlang.cn/)


## 栗子

+ `第一个程序.歧`

  ```
  输出 666。
  ```

+ `循环.歧`

  ```
  # 这是注释

  循环 3 次:
    写 6。

  换行。
  ```

+ `吃货.歧`

  ```
  定义类型吃货:
    名字(文本)。

  定义吃, 参数自己(吃货)、东西(文本):
    输出 "\(自己的名字)吃了\(东西)"。

  # 测试
  定义变量窝, 吃货。  # 窝是吃货 ^_^
  窝的名字是 "喵喵"。

  定义变量饭, "汤面条"。

  窝吃饭。  # 喵喵吃了汤面条
  ```


## 相关链接

+ 歧语言设计文档: <https://github.com/fm-elpac/nb>

+ 《歧语言之书》 <https://fm-elpac.github.io/nb>

+ 歧语言编译器: <https://github.com/fm-elpac/nbc>


## LICENSE

[`CC-BY-SA 4.0+`](https://creativecommons.org/licenses/by-sa/4.0/)

本书使用 CC-BY-SA 4.0 许可发布。
This book is released under CC-BY-SA 4.0 LICENSE.
