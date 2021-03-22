[TOC]



# MarkDown基本语法

正式开始语法部分～
## 插入目录
```markdown
[TOC]
```
## 标题

```
# 标题名字（井号的个数代表标题的级数）
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
####### 最多支持六级标题
```

## 段落

段落没有特殊的格式，直接用一个空行来表示重新开始一个段落。

## 文字

### 斜体

```markdown
这是用来 *斜体* 的 _文本_
```

这是用来 *斜体* 的 *文本*

### 加粗

```markdown
这是用来 **加粗** 的 __文本__
```

这是用来 **加粗** 的 **文本**

### 斜体+加粗

```markdown
这是用来 ***斜体+加粗*** 的 ___文本___
```

这是用来 ***斜体+加粗*** 的 ***文本***

### 删除线

```markdown
这就是 ~~删除线~~ (使用波浪号)
```

这就是 ~~删除线~~ (使用波浪号)

### 下划线

下划线是HTML语法

`下划线` 下划线

## 分隔线

可以在一行中使用三个或更多的 `*`、`-` 或 `_` 来添加分隔线

```markdown
***
------
___
```

------

------

------

## 扩展语法的说明

部分渲染器可能不支持该效果，若不在意跨软件性可以使用（意思就是换了个别的支持markdown语法的地方敲字，某些样式可能识别不出来）

## 高亮（需勾选扩展语法）

```markdown
这是用来 ==高亮== 的文本
```

这是用来 ==高亮== 的文本

## 下标（需勾选扩展语法）

```markdown
水 H~2~O 
双氧水 H~2~O~2~ 
```

水 H~~2~~O

双氧水 H~~2~~O~~2~~

## 上标（需勾选扩展语法）

```markdown
面积 m^2^ 
体积 m^3^
```

面积 m^2^
体积 m^3^

## 表情符号

Emoji 支持表情符号，你可以用系统默认的 Emoji 符号。

输入方式

1. 输入 `:` 将会出现智能提示`:smile:`😄![img](https://github.githubassets.com/images/icons/emoji/unicode/1f604.png?v8)
2. 直接输入法选入
3. 快捷键后点选：
   - Mac: control+command+space点选
   - Window:使用 Win键+. 或者Win键+. 点选

不同方式输入的emoji可能最后渲染的会不一样😄，影响不大

```markdown
:smile: :laughing: :dizzy_face: :sob: :cold_sweat: :sweat_smile:  :cry: :triumph: :heart_eyes: :relaxed: :sunglasses: :weary: :100: :clap: :bell: :gift: :question: :bomb: :heart: :coffee: :cyclone: :bow: :kiss: :pray: :sweat_drops: :hankey: :exclamation: :anger:
```

😄![img](https://github.githubassets.com/images/icons/emoji/unicode/1f604.png?v8) 😆![img](https://github.githubassets.com/images/icons/emoji/unicode/1f606.png?v8) 😵![img](https://github.githubassets.com/images/icons/emoji/unicode/1f635.png?v8) 😭![img](https://github.githubassets.com/images/icons/emoji/unicode/1f62d.png?v8) 😰![img](https://github.githubassets.com/images/icons/emoji/unicode/1f630.png?v8) 😅![img](https://github.githubassets.com/images/icons/emoji/unicode/1f605.png?v8) 😢![img](https://github.githubassets.com/images/icons/emoji/unicode/1f622.png?v8) 😤![img](https://github.githubassets.com/images/icons/emoji/unicode/1f624.png?v8) 😍![img](https://github.githubassets.com/images/icons/emoji/unicode/1f60d.png?v8) ☺![img](https://github.githubassets.com/images/icons/emoji/unicode/263a.png?v8) 😎![img](https://github.githubassets.com/images/icons/emoji/unicode/1f60e.png?v8) 😩![img](https://github.githubassets.com/images/icons/emoji/unicode/1f629.png?v8) 💯![img](https://github.githubassets.com/images/icons/emoji/unicode/1f4af.png?v8) 👏![img](https://github.githubassets.com/images/icons/emoji/unicode/1f44f.png?v8) 🔔![img](https://github.githubassets.com/images/icons/emoji/unicode/1f514.png?v8) 🎁![img](https://github.githubassets.com/images/icons/emoji/unicode/1f381.png?v8) ❓![img](https://github.githubassets.com/images/icons/emoji/unicode/2753.png?v8) 💣![img](https://github.githubassets.com/images/icons/emoji/unicode/1f4a3.png?v8) ❤![img](https://github.githubassets.com/images/icons/emoji/unicode/2764.png?v8) ☕![img](https://github.githubassets.com/images/icons/emoji/unicode/2615.png?v8) 🌀![img](https://github.githubassets.com/images/icons/emoji/unicode/1f300.png?v8) 🙇![img](https://github.githubassets.com/images/icons/emoji/unicode/1f647.png?v8) 💋![img](https://github.githubassets.com/images/icons/emoji/unicode/1f48b.png?v8) 🙏![img](https://github.githubassets.com/images/icons/emoji/unicode/1f64f.png?v8) 💦![img](https://github.githubassets.com/images/icons/emoji/unicode/1f4a6.png?v8) 💩![img](https://github.githubassets.com/images/icons/emoji/unicode/1f4a9.png?v8) ❗![img](https://github.githubassets.com/images/icons/emoji/unicode/2757.png?v8) 💢![img](https://github.githubassets.com/images/icons/emoji/unicode/1f4a2.png?v8)

## 列表

### 无序列表

符号 空格

```markdown
* 可以使用 `*` 作为标记
+ 也可以使用 `+`
- 或者 `-`
```

- 可以使用 `*` 作为标记

- 也可以使用 `+`

- 或者 `-`

### 有序列表

数字 `.` 空格

```markdown
1. 有序列表以数字和 `.` 开始；
3. 数字的序列并不会影响生成的列表序列；
4. 但仍然推荐按照自然顺序（1.2.3...）编写。
```

1. 有序列表以数字和 `.` 开始；
2. 数字的序列并不会影响生成的列表序列；
3. 但仍然推荐按照自然顺序（1.2.3…）编写

```markdown
可以使用：数字\. 来取消显示为列表（用反斜杠进行转义）
```

## 表格

使用 `|` 来分隔不同的单元格，使用 `-` 来分隔表头和其他行：

```markdown
name | price
--- | ---
fried chicken | 19
cola|5
```

> 为了使 Markdown 更清晰，`|` 和 `-` 两侧需要至少有一个空格（最左侧和最右侧的 `|` 外就不需要了）。

| name          | price |
| ------------- | ----- |
| fried chicken | 19    |
| cola          | 5     |

为了美观，可以使用空格对齐不同行的单元格，并在左右两侧都使用 `|` 来标记单元格边界，在表头下方的分隔线标记中加入 `:`，即可标记下方单元格内容的对齐方式：

```markdown
|    name       | price |
| :------------ | :---: |
| fried chicken | 19    |
| cola          |  32   |
```

| name          | price |
| ------------- | ----- |
| fried chicken | 19    |
| cola          | 32    |

==使用快捷键`command`+`opt`+`T`更方便(段落→表格→插入表格，即可查看快捷键)==

## 引用

开头使用 **>** 符号 ，然后后面紧跟一个**空格**符号

```markdown
> “后悔创业”
```

> “后悔创业”

```markdown
> 也可以在引用中
>> 使用嵌套的引用
```

> 也可以在引用中
>
> > 使用嵌套的引用

## 代码

### 代码块

代码块中的文本（包括 Markdown 语法）都会显示为原始内容

~~~markdown
```语言名称（也可以不指定）
public static void main(String[] args) {
   }
~~~

### 行内代码

也可以通过反引号（``），插入行内代码

![image-20210306171044147](https://jojo-995.gitee.io/2021/03/06/markdown-tutorial/image-20210306171044147.png)

```markdown
例如 `Markdown`
```

例如 `Markdown`



## 跳转

### 外部跳转–超链接

格式为 `[link text](link)`。

```markdown
[帮助文档](https://support.typora.io/Links/#faq)
```

[帮助文档](https://support.typora.io/Links/#faq)

### 内部跳转–本文件内跳-Typora支持

格式为 `[link text](#要去的目的地-标题名称）`。

不管标题有几个#，设置链接时*只有一个#\*，标题里的\*空格*可以用’-‘代替，开头结尾的空格无所谓。

```markdown
[我想跳转](#完结)
```

> Open Links in Typora
>
> You can use `command+click` (macOS), or `ctrl+click` (Linux/Windows) on links in Typora to jump to target headings, or open them in Typora, or open in related apps.

[我想跳转](https://jojo-995.gitee.io/2021/03/06/markdown-tutorial/#完结)

如果不想跳到标题，则可以自定义锚点

```html
<a href="#anchor">不，你不想跳，你要回去</a>
<a name="anchor">锚点</a> 
```

### 自动链接

使用 `<>` 包括的 URL 或邮箱地址会被自动转换为超链接：

```markdown
<https://www.baidu.com>

<123@email.com>
```

[https://www.baidu.com](https://www.baidu.com/)

[123@email.com](mailto:123@email.com)

### 重复链接

当在一个文章==重复使用同一个链接（对下面的图片也是一样的适用）==时，我们可以通过变量来设置一个链接，相当于给这个链接起了个名字，方便统一修改，变量赋值在文档引用的下面进行：

```markdown
这个链接用 1 作为网址变量名字 [百度][1]
这个链接用 jojo 作为网址变量名字 [JoJo的博客][jojo]
然后在文档的结尾为变量赋值（网址）

  [1]: http://www.baidu.com/
  [jojo]: http://jojo-995.gitee.io/
```

这个链接用 1 作为网址变量名字 [百度](http://www.baidu.com/)
这个链接用 jojo 作为网址变量名字 [JoJo的博客](http://jojo-995.gitee.io/)
然后在文档的结尾为变量赋值（网址）

## 图片

```markdown
![自己起的图片名字](图片地址或者图片本地存储的路径)
```

### 网上的图片

```markdown
![我爱的🍗](https://ss0.bdstatic.com/94oJfD_bAAcT8t7mm9GUKT-xh_/timg?image&quality=100&size=b4000_4000&sec=1580814517&di=2630beac440e5dab0e44c7286a3b2b61&src=http://imgsrc.baidu.com/forum/w=580/sign=12c730c4ff03738dde4a0c2a831ab073/9497794f9258d1091818e6d6d858ccbf6d814d1b.jpg)
```

![炸鸡](https://jojo-995.gitee.io/2021/03/06/markdown-tutorial/9497794f9258d1091818e6d6d858ccbf6d814d1b.jpg)

### 本地图片

在同一个文件夹里（用相对路径）或者直接拷贝（配合snipaste截屏工具使用效果一级棒）[点击下载sinapste](https://zh.snipaste.com/)

```markdown
![我爱的🍗](markdown-tutorial/image-20210306172630754.png)
```

![我爱的🍗](https://jojo-995.gitee.io/2021/03/06/markdown-tutorial/image-20210306172630754.png)

# 利用Markdown画图（需勾选扩展语法）

==~~我觉得这玩意不如直接用[processon](https://www.processon.com/)或[Draw.io](https://app.diagrams.net/)在线画了然后截截图~~==（draw.io还有客户端，**强烈安利** 下面有关的资料除了饼图都可以不用看了，怪我当初太年轻🐶