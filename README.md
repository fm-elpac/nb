# 歧语言 (文档)
<https://github.com/fm-elpac/nb>

镜像:
TODO

无歧义中文编程语言, 简称 **歧语言** (nb_lang)。

No amBiguous Chinese programming language, short as NB.

正式名称: `紫腹巨蚊` (Toxorhynchites gravelyi) 系列 `花盘茶渍` (Lecanora flowersiana) 语言

![CI](https://github.com/fm-elpac/nb/actions/workflows/ci.yml/badge.svg)

《歧语言之书》: <https://fm-elpac.github.io/nb>

**警告: 歧语言项目目前还处于很早期的阶段, 各方面很不完善, 潜藏着大量的 BUG 和错误, 没有进行完善的安全评估, 所以请勿用于处理敏感数据。**
**歧语言目前被设计仅用于学习编程, 请勿用于重要的关键任务。**


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


## 栗子 (example)

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


## 常见问题 (FAQ)

+ 为什么选择中文编程 ?

  希望可以提高代码的可读性, 降低编程的学习难度, 让更多的中国人能够编程。

更多问题请见: <https://fm-elpac.github.io/nb/1_简介/1_常见问题.html>


## 主要组件

+ 歧编 (nbc): 歧语言编译器

+ 歧格 (nbf): 代码格式化工具

+ 标准库 (libnb): 歧语言标准库

+ 歧服 (nbs): 歧语言 LSP 服务器

+ 歧测 (ntr): 歧语言测试框架 (Nb Test fRamework)


## LICENSE

[`CC-BY-SA 4.0+`](https://creativecommons.org/licenses/by-sa/4.0/)

本仓库的内容使用 创意共享-署名-相同方式共享 (CC-BY-SA 4.0) 许可证 (LICENSE).
This repository is released under Creative Common (CC-BY-SA 4.0) license.
