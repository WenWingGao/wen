# wen

## 二、Markdown基本语法
### 1、标题
Markdown支持两种标题的语法，类Setext形式和类Atx形式。

类Setext形式是用底线的形式底线包括`=`和`-`，例：
```
一级标题
=====

二级标题
-----
```
**说明: 任意数量的`=`或`-`都可以生效。**

类Atx形式是在标题行的开头加入1到6个`#`，对应1到6级标题，例如：
<pre>
# 一级标题
## 二级标题
### 三级标题
......
###### 六级标题
</pre>
关于Atx形式的标题，可以选择性的使用"闭合"形式的标题，这只是标题的另一种写法，写法是在标题行的行末加入任意数量的`#`(行首决定标题的级别，与行末无关)，例：
<pre>
# 一级标题 #
## 二级标题 ####
### 三级标题 #
</pre>

### 2、段落
一个 Markdown 段落是由一个或多个连续的文本行组成，它的前后要有一个以上的空行（空行的定义是显示上看起来像是空的，便会被视为空行。比方说，若某一行只包含空格和制表符，则该行也会被视为空行）。普通段落不该用空格或制表符来缩进。

##### 强制换行
在文档中如需强制对文本进行换行，可以使用`</br>`标签来进行换行。 例如：`第一行</br>第二行`的结果如下：
>第一行</br>
>第二行

### 3、引用
如果需要在文档中引用一小段段落时，可以用到引用的格式，引用的格式只需要在文本前加入 `>` 即可。例：
>此处是引用

**注意：引用需要以一个空行来标记结束。**
引用可以嵌套使用，即在行首加入不同数量的`>`来标记引用的层级，例如：
> 一级
>> 二级
>>> 三级

### 4、列表
Markdown 支持有序列表和无序列表。
#### 4.1 无序列表
无序列表使用星号、加号或是减号作为列表标记，例如：
<pre>
*   Red
*   Green
*   Blue
</pre>
