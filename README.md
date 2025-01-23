# @xiechen1201/create-notemd

一个简单的命令行工具，用于快速创建学习笔记的目录结构和Markdown文件。

## 功能特点

- 一键创建标准的学习目录结构
- 自动生成code和note子目录
- 创建指定名称的Markdown文件
- 交互式命令行界面

## 安装

```bash
npm install -g @xiechen1201/create-notemd
```

## 使用方法

1. 在终端中运行命令：
```bash
create-md
```

2. 根据提示输入目录名称和Markdown文件名称

3. 工具将自动创建如下目录结构：
```
你的目录名称/
  ├── code/     # 用于存放代码
  └── note/     # 用于存放笔记
      └── 你的文件名.md
```

## 示例

```bash
$ create-md
请输入目录名称: javascript-learning
请输入 MD 文件的名称: day1-basics

目录已创建: javascript-learning
目录已创建: javascript-learning/code
目录已创建: javascript-learning/note
文件已创建: javascript-learning/note/day1-basics.md
所有操作完成！
```

## 许可证

MIT