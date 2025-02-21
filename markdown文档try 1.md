# <center><font face="楷体" font color=blue>MARKDOWN 入门</font></center>
## <center><font face="宋体" size=5>bhhhyu first try </font></center>
1. **标题**
###  title
//有几个#就是几级标题 且标题和后面的内容需要空格
//最小是6级
2. **引用**
>编辑这类文档很好用
>>还可以用嵌套，非常的好用
3. **列表**
   1. 无序列表
   - 列表1
   + 列表2
   * 列表3
   * 都需要空一格 
   1. 有序列表
   2. 嵌套
>只需要在数字的后面空出tab个空格就可以实现嵌套
   1. Todolist
      - [ ] a
      - [x] b
      - [ ] c
> 可以在这里创建代办事项
4. **表格操作**
  
   |a | b | c |
   |:--- |:---:| --:|
   |a| b | c |
   | 左对齐 | 居中对齐 | 右对齐 |
5. **换行**
- 换行? ---两个以上空格后回车/空一行
- 分割线—————— 三个/多个*
  *** 
- 字体
  |字体|代码|
  |:--:|:--:|
  |*斜体*|* *|
  |==高亮==|== ==|
  |**粗体**|** **|
  |***粗斜体***|*** ***|
  |~~删除~~|~~ ~~|
  |<u>下划线</u>|`<u> </u>`|
-  ` ` 是代码展示键
- 脚注
  写[^2]论文的话比较常用,并且需要在文章末尾进行解释
  原神[^genshin_impact]，我爱玩
6. **代码**
 
   ```
#include<iostream>
using namespace std;
int main()
{
  printf("Hello world!);
  return 0;
}
>整段编程的部分不需要用两组`包围，只用一个就可以了
` printf("Hello 原神");`
>上面的是一大片代码,用三个`括起来
>>下面的是单句的代码写法 左右只用一个`括起来

7. **超链接**
- [使用更多的学习资料可以参考网站]：https://shinnku.com
+ <https://shinnku.com>
- 查看更多功能请[点击链接][教程]
8. **图片**
- 使用图床保存图片并实现插入
[路过图床]:https://imgse.com/ 
<图床可能会崩，慎用
- 使用markdown语法插入
`<a href="https://imgse.com/i/pEQyw26">
<img src="https://s21.ax1x.com/2025/02/20/pEQyw26.webp" 
alt="pEQyw26.webp" border="0" 
/></a>`

<注意两个照片我修改部分的代码


<a href="https://imgse.com/i/pEQyw26"><div align=center>
<img src="https://s21.ax1x.com/2025/02/20/pEQyw26.webp" 
alt="pEQyw26.webp" border="0" 
width="10%" height="10%"/></div></a>

9. **数学公式**
  1. **希腊字母**
    >拼音 且一定要规范
    >latex 语言要用$包裹住
$
    \delta,\lambda\\
    \Delta,\Lambda\\
    \alpha,\Beta\\
    \phi,\varphi\\
    \epsilon,\varepsilon\\
$
  2. **上下标**
 
$ 
   a^2,a_1 \\
   x^{y+z} \\
   p_{ij}\\
   {\rm Ads}afs\\
   {\text Ads}afs\\
   \rm e i j\\
   这三个都是常量，用直立体\\
$ 

>注意,包裹住latex语言的部分不能有空着的行,且句末一定要有两个斜杠/
>英文字母只有在表示变量（或者是单一字符的函数名称，如f(x)）才可以使用斜体，其余情况都应使用罗马体（直立体）
>$x_i$，i表示1，2，……，n，为变量(x为变量，是斜体)
>$x_(\rm i)或x_(\text i)$,i表示“输入”（input）之意，为普通文本
>\text 只对其后的第一个字母生效  \rm 对其后的每个字母都生效

  3. **分式与根式**
    $
    \frac{a+b}{c^2}\\
    \frac 1 2\\
    \frac {\frac{x+y}{3^t}}{z_i}\\
    \dfrac{1}{x+y}\\
    \sqrt{x+y*k^3}\\
    \sqrt 4\\
    \sqrt[3]{y^4}\\
    $
    >fraction 分数 两个大括号，前面是分子，后面是分子
    >dfrac->display-style  放大的意思

  4. **普通运算符**
$
  a+b^2-k_i\\
  \times 乘\\
  \cdot 点乘\\
  \div 除\\
  \pm 正负号\\
  \mp 负正号\\
  \ > <正常\\
  \ge 大于等于 greater or euqal\\
  \le 小于等于 less or equal\\
  \gg 远大于\\
  \ll 远小于\\\
  \ne 不等于\\
  \approx 约等于apporximate\\
  \equiv 恒等于 equivalent\\
  \cap ，\cup 交并集\\
  \in 属于\\
  \notin 不属于\\
  \subseteq 子集\\
  \subsetneqq真子集\\
  \varnothing空集\\
  \forall,\exists任意，存在\\
  \nexists 不存在\\
  \because 因为\\
  \therefore 所以\\
  \mathbb R,\R,实数集\\
  \mathbb Q\\
  \mathbb N\\
  \mathbb Z\\
  \mathbb Z_+\\
  \mathbb Z_-\\
  \mathcal F,傅里叶变换的F\\
  \mathscr F\\
  \cdots\\
  \cdot横向\\
  \vdots竖向\\
  \ddots斜向\\
  \infty 无穷 infinity\\
  \partial 偏微分的微分符号\\
  \nabla,nabla算子\\
  \propto 正比于 proportional\\
  \degree 度\\
  \sin x\\
  \cos x\\
  \tan x\\
  \cot x\\
  \arcsin x\\
  \arcsin (tan {cos(x*y))}\\
  \log_2 x\\
  \ln e\\
  \lg x\\
  \lim_{x\to 0} \frac{ x}{\sin x}\\
  \lim_{x\to \infty}\frac{y}{\sqrt x}\\
  \lim\limits_{x \to 0}\frac{2^x}{y}\\
  \max x\\
  \rm MSE(x)\\
$
>运算符名称超过一个字母是应使用直体

   5.**大型运算符**
   $
   \sum 总和\\
   \prod 总积product\\
   \sum_i\\
   \sum_{i=0}^N\\
   \prod\limits_{i=0}^N\\
   \frac{\sum\limits_{i=0}^n x_i}{\prod\limits_{i=1}^n x_i}\\
   \int 积分 integral\\
   \iint 双重积分\\
   \iiint 多重积分\\
   \oint,回路积分\\
   \oiint\\
   \int_{-\infty}^0 f(x)\,\text dx\\
   a\,a\\
   a\ a\\
   a\quad a\\
   a\qquad a\\
   观察上面的几种空格方式\\
   $  
   6. **标注符号**
  $
  \vec x 向量 vector\\
  \overrightarrow {axh}大箭头\\
  \bar x,平均值\\
  \overline {AB},大横线\\
  $
  7. **箭头**
  $
  \leftarrow\\
  \rightarrow\\
  \Rightarrow\\
  \Leftrightarrow等价于\\
  \longleftarrow\\
  $
  8. **括号与定界符**
  $
  (),[]正常\\
  \{\}\\
  \lceil,\rceil\\
  \lfloor,\rfloor\\
  | |\\
  \left(0,\frac  1 a \right]\\
  (0,\frac  1 a ]\\
  \frac {\partial f}{\partial x}|_{x=0}\\
 \left.\frac {\partial f}{\partial x}\right|_{x=0}\\
  $
  9. **多行公式**
  $
  \begin{aligned}
  a=b+c+d\\
  =e+f\\
  a&=b+c+d\\
   &=e+f
  \end{aligned}
  $
  10. **大括号**
  $
  f(x)=
  \begin{cases}
  \sin x,& -\pi\le x \le \pi\\
  0,& \text{其他}
  \end{cases}
  $
  11. **矩阵**
  >矩阵一共有四种环境 matrix  bmatrix  pmatrix  vmatrix
  >first
  $
  \begin{matrix}
  a & b & \cdots & c\\
  \vdots &\vdots &\ddots & \vdots\\
  e &f &\cdots &g\\
  \end{matrix}
  $
  >second
  $
  \begin{bmatrix}
  a & b & \cdots & c\\
  \vdots &\vdots &\ddots & \vdots\\
  e &f &\cdots &g\\
  \end{bmatrix}
  $
  >third
  $
  \begin{pmatrix}
  a & b & \cdots & c\\
  \vdots &\vdots &\ddots & \vdots\\
  e &f &\cdots &g\\
  \end{pmatrix}
  $
 >forth
  $
  \begin{vmatrix}
  a & b & \cdots & c\\
  \vdots &\vdots &\ddots & \vdots\\
  e &f &\cdots &g\\
  \end{vmatrix}
  $
  >$\bf{A} 粗体bold faec $用粗体的字母来表示矩阵名 
  >$\bf B^{\rm T}转置符号 $
>实战演练 
$
f(x)=\frac{1}{\sqrt {2\pi}\sigma}{\rm e}^{-\frac{(x-\mu)^2}{2\sigma^2}}\\
$






















<a href="https://imgse.com/i/pEQyw26"><div align=center>
<img src="https://s21.ax1x.com/2025/02/20/pEQyw26.webp" 
alt="pEQyw26.webp" border="0" 
width="10%" height="10%"/></div></a>








  ***
[教程]:https://shinnku.com
[^2]:这里写脚注的具体内容，注意没有空格，脚注后直接加冒号之后直接加句子
[^genshin_impact]:是一款非常出名的游戏，二次元开放世界rpg游戏
- 由文章末尾可知，不论我们在脚注内写的内容是什么，最终呈现出来的都是由顺序决定的正整数
- 注意链接的解释要放在脚注之前，不然无法响应


















