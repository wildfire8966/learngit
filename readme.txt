this is a readme file.
this is a add content.
add a new line. do something change.
first change.
second change.

Go学习记录

引用名人豪森布鲁兹老爷在China的一句名言

好吧，没事儿就多看书、多学习

所以，我就开始了我的学习之旅。 ![new1](/Users/yuanye8/Downloads/new1.jpg

 首先，聊聊Go有什么优点：

1. 编译型语言，速度快，估计没C和java快，绝对比python快
2. 开发效率高，绝对比C/C++效率高
3. 简单容易上手，属于C-Family的语言，有C基础就可以快速上手

废话不多说，HelloWorld来一个

    package main
    
    import "fmt"
    
    func main() {
        fmt.Println("Hello, world!")
    }

之后，使用命令go run hello.go运行，大功告成。

接下来，要持续学习，列个目标先：

- [ ] hello,world

- [ ] 基本语法、变量与常量
- [ ] 数组、指针与语言结构
- [ ] 高级语法特性

当然，目标是要有的，玩不完成就看心情了

来个数学公式练练手


z_i^2 = x_i^2 + y_i^2


数学公式的编写，先放一下，用到了再查看

http://mlworks.cn/posts/introduction-to-mathjax-and-latex-expression/

可以编写出像下面这么漂亮的公式也是蛮好的


\mathbf{V}_1 \times \mathbf{V}_2 =  \begin{vmatrix} 
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
\frac{\partial X}{\partial u} &  \frac{\partial Y}{\partial u} & 0 \\
\frac{\partial X}{\partial v} &  \frac{\partial Y}{\partial v} & 0 \\
\end{vmatrix}


当然，表格也是必须的，比如，下面这样

  Left-Aligned 	Center Aligned 	Right Aligned
  col 3 is     	some wordy text	        $1600
  col 2 is     	   centered    	          $12
  zebra stripes	   are neat    	           $1

[footnote]: Here is the text of the footnote.

---

华丽的分割线，上图，呵呵呵，最高的是我



很帅吧！:happy:

很帅吧！:smile:

很帅吧！:happy:




