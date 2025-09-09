# <center><font face='微软雅黑' color=orange size=7>Markdown使用</font></center>

****
## 字体形态
*title* 一个星号 斜体
**title** 两个星号 加粗
***title*** 三个星号 加粗+斜体

| 字体 | 代码 |
| :---: | :---: |
| *斜体* | * * |
| ==高亮== | == == |
| **粗体** | ** ** |
| ***斜+粗*** | *** *** |
| ~~划掉~~ | ~~ ~~ |
| <u> 下划线 </u> |html `<u> </u>` |



***
## 标题
# 一级标题：一个#
## 二级标题：两个#
一次类推，最多6级
***
## 引用
> 引用：一个>
>666
>789
>>**嵌套**引用：二级 >>
***
## 列表 
1. 无序： + - *
- 有序
- 有序
* 列表
+ 都可以
+ 好像 加减乘 段间距不一样
1. 有序
   1. 嵌套
   2. 嵌套！
2. TodoList：- [ ] ？
     - [ ] 学
     - [x] 玩
     - [x] 睡
  *****
## 表格： | : --- 
| 左对齐 | 居中对齐 | 右对齐 |
| :--- | :---: | ---: |
| 1    | 2 |   3 | 
*****
## 段落
- 换行
- 分割线：三个及以上 *
***
## 脚注/注释 
他说wwsgclh[^1]是真的
****
## 代码块 ` or  ``` 
```
a=1
b=2
if a=b:
    print(df)
else:
    print(clh)
```

` print('helloworld')`
***
## 超链接
- 直接上链接 www.google.com
- 详情可以[点击这里](https://www.bilibili.com)
- <www.youtube.com>
  
```
[链接名称](地址)
或者
<链接地址>
```
>注释法 [链接名称][注释]
>点击这里进入B站 [Bilibili][b] ~~为什么成功不了？~~ *注释之间要有空行！！*
******
## 图片
1. 直接拖图片过来
        问题：存储在本地路径，只能由本地看见
2. 使用[图床](https://imgse.com/)
   
[![pVR3F0I.png](https://s21.ax1x.com/2025/09/09/pVR3F0I.png)](https://imgse.com/i/pVR3F0I)

## 插入数学公式：$
### <u>latex</u>公式

- 行内 用一个$
  
  $f(x)=3x^4+3$
- 段落 用2个$
  
$$
\begin{Bmatrix}
a & b \\
c & d
\end{Bmatrix}
$$
****
## HTML语言
  1. **font** 
   以标题为例：
```<center><font face='微软雅黑' color=orange size=7>Markdown使用</font></center>```
   2. **图片**：调整大小、位置
      1. 大小：width height
      2. 位置：div align=...
同样以图床为例：
<div align=center><a href="https://imgse.com/i/pVR3F0I"><img src="https://s21.ax1x.com/2025/09/09/pVR3F0I.png" alt="pVR3F0I.png" border="50" width='150%' height='90%' /></a></div>
 

****
## CSS语言
- 实现同种标题全部居中
    1. ctrl+shift+p 搜索：
    ``` Markdown Preview Enhanced:Customize CSS```
    2. 在```style.less```中使用css语法调整标题格式等内容
****
## 个性化设置
* 见 File----Preferences----Settings(or ctrl+,)
******
## 导出为PDF
- 右键在浏览器中另存为PDF







[^1]: lol

[b]: https://www.bilibili.com
