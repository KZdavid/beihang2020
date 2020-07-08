# Here is a BIG title
## Here is a Big title
### Here is a big titile
#### Here is a normal title
##### Here is a SMALL title
###### here is a small title

This is also a BIG title
=
This is also a Big title
-

Hello every one! This is a markdown file. I'll show you how to write a .md file in the following text.
You will surprsingly find that this is not in a newline.

One more 'enter'  
or two spaces after a sentence will help you start a new line.
<br>
sometimes html label works, too

If you want to __emphasize__ something, you can use **both** double * and double _   
or use single * and _ to write *something* in _Italic_

of course, triple * and _ is ***allowed***

&emsp;&emsp;If you want to start with 4 spaces, try the symbols I write in the front of this line.
- '&emsp;' = 2 spaces
- '&ensp;' = 1 space

BTW, now you have seen how to insert an unordered list in a md file.
* \* can also lead an unordered list
+ \+ works in the same way, you can even use \-, \*, \+ in one list like this example. It depends on you.

And an ordered list is defined as below:
1. this is the first
2. this is the second
    - 2.1 of course this is 2.1

Markdown also support block text
> First block
>> second block
>>> third block
>>>> fourth block
>>>>> I don't know how many blocks we can create 

Block can be nested with lists
>Block nest list
1. A
- B

And

- List nest block
    > C

If you want to highlight the code in your text, you can do something like `print()`

As for a code block, you should add a 'tab' before every line of your code

    import numpy as np
    print(np.ones([10, 10]))

In fact, I prefer
```python
import torch as t
print(t.cuda.is_available())
```
Other languages are supported, too
```matlab
A = eye(5);
disp(x' * A * x);
```

Sometimes, If you want to insert a hyperlink, you can do this

[RUNNOOB](https://www.runoob.com/markdown/md-tutorial.html) is a good tutorial website

if some links will be mentioned many times, you can use a label to define a link, like

[link]: https://www.runoob.com/markdown/md-tutorial.html

and then use it [here][link] and [there][link] or [anywhere][link]

When talking about hyperlink, html labels should not be absent, here is an example

<a href = 'https://www.runoob.com/markdown/md-tutorial.html'>link</a>

Another important function is to insert a picture in md file

![DOU](./dou1.jpg)
![DOU](./dou2.jpg "呜呜呜阿斗太可爱了")

In this case html labels are more useful, two examples are shown below

<img src="http://yyxblog.top/images/yuki2.png" width=50%>

<div align=center>
<img src="http://yyxblog.top/images/yuki2.png" width=50%>
</div>

In this section, I'll show you how to type a sheet in markdown. Here is the basic grammar

|  表头   | 表头  |
|  ----  | ----  |
| 单元格  | 单元格 |
| 单元格  | 单元格 |

the second line defines the sheet format
- :- represents left align
- -: represents right align
- :-: represents center align

| 左对齐 | 右对齐 | 居中对齐 |
| :-----| ----: | :----: |
| 1 | 2 | 3 |
| 1 | 2 | 3 |

The most important function is, we can type math formula like in $\LaTeX$

$$ 
x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}
$$

***Note***: Each chracter we mentioned above defines a special text format, if you just want to type the character, use / to tell markdown it's a escape character. e.g, \*, \'

Last but not least, markdown supports html well. If functions I mentioned above cannot meet your demand, please make good use of _Baidu_ .