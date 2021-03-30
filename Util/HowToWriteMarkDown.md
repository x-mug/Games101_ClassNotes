<!--
 * @Author: xmug
 * @Date: 2021-03-30 23:11:24
 * @LastEditors: x-mug
 * @LastEditTime: 2021-03-31 00:59:29
 * @FilePath: \Games101\HowToWriteMarkDown.md
-->
# Markdown的部分语法
这一节全部用Gif来给大家展示——（做gif图很麻烦啊，推荐一个开源免费的软件ScreenToGif，可惜不能通过支付宝给他们捐赠……）

## 2.1. 标题编辑

![Title](https://pic4.zhimg.com/v2-f7caa56b9a160cf3149f5f9c75e52c67_b.webp)

# 标题
## 次级标题
### XXXX

## 2.2. 正文

![Content](https://pic3.zhimg.com/v2-a0610e72785ea32706fe259fd59f0faa_b.webp)

正文直接输入就可以了

但是换行要注意，换行需要真正的空一行
直接输入不会换行

## 2.3. 代码块
干IT的少不了和各种代码，命令行接触；Markdown的代码块功能就非常有用了——

代码块通过两行 ``` 符号框出，如果你写的代码是某种语言，那么可以在第一行末尾加上这个语言的名字，代码块内的代码就会执行对应的高亮语法，例如python

![Code](https://pic2.zhimg.com/v2-7880bcfe5527b500f5fbdaa1d9349f59_b.webp)

```python
import pygame

pygame.init()
```

## 2.4. 行内代码
正文中的代码，则通过输入`` 框出

![Code inside](https://pic4.zhimg.com/v2-bb63b917c2a506bb23f7c4977bd1f553_b.webp)

那么如何进入子文件夹呢？``cd subfolder``即可

## 2.5. 列表
有序列表，输入数字，加一个句点，然后空格即可；可以缩进空置多级列表；

![Order list](https://pic2.zhimg.com/v2-d1b1d7b123b2e0210f1313246b3190dd_b.webp)

1. Node 1
2. Node 2
3. Node 3

无序列表，输入 - ,然后空格

![Unorder list](https://pic2.zhimg.com/v2-f9dec5e2fe26147b0a59b34bce285e91_b.webp)

- Node 1
- Node 2
- Node 3


## 2.6. 加粗和倾斜

上面是常用的一些用法，还有一些我没列出来的用法，比如插入表格，各位可以自行“度娘”或者“谷哥”一下。

![](https://pic3.zhimg.com/v2-ebb24a16981ec67cacd311b56feb57ee_b.webp)

**加粗**
*倾斜*

# 3. 小结
相信聪明的同学已经知道我为什么建议一开始用vscode写markdown了——原因很简单，分栏输入和预览，你可以直观的看到自己输入的代码渲染后的效果，当然，这其实是大部分markdown编辑器都支持的行为——typora有些不太一样，它不是这种分栏模式。

如果你是印象笔记或者有道云笔记的用户，其实这两个笔记现在也都支持markdown了，但是说实话，使用体验我个人认为并不好，而且最重要的是，抹杀了markdown的自由性，既然都用笔记了，好像用不用markdown也无所谓了。

markdown的语法并不多，也没有很复杂的格式，样式完全基于软件所支持的CSS样式渲染，如我上一篇文章所说，很多时候，简单的就是最好的。你不太可能拿markdown来写一篇正式的论文，但是作为日常的笔记来说，markdown再好不过——够用、可迁移、专注写作。

下篇会介绍一下windows上的markdown编辑神器——typora。用熟了markdown的语法后，你可以立即抛弃vscode，投身typora的怀抱。