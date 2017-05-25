<center>烂笔头</center>

    /**
    *                    _ooOoo_
    *                   o8888888o
    *                   88" . "88
    *                   (| -_- |)
    *                    O\ = /O
    *                ____/`---'\____
    *                 .' \\| |// `.
    *               / \\||| : |||// \
    *             / _||||| -:- |||||- \
    *             |   | \\\ - /// |   |
    *             | \_| ''\---/'' |_/ |
    *              \ .-\__ `-` ___/-. /
    *           ___`. .' /--.--\ '. .`__
    *        ."" '< `.___\_<|>_/___.' >' "".
    *        | | : `-\`.;`\ _ /`;.`/-` : | |
    *         \ \ `-. \_ __\ /__ _/ .-` / /
    *       `-.____`-.___\_____/___.-`____.-'
    *                    `=---='
    * ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
    * 佛祖保佑 永无 BUG
    * 佛曰:
    * 写字楼里写字间，写字间里程序员；
    * 程序人员写程序，又拿程序换酒钱。
    * 酒醒只在网上坐，酒醉还来网下眠；
    * 酒醉酒醒日复日，网上网下年复年。
    * 但愿老死电脑间，不愿鞠躬老板前；
    * 奔驰宝马贵者趣，公交自行程序员。
    * 别人笑我忒疯癫，我笑自己命太贱；
    * 不见满街漂亮妹，哪个归得程序员？
    */

===

####  0)        15:46 2017/2/7

>A view template should never perform business logic or interact with a database directly.

>一个视图模板应该永远不会执行业务逻辑或与数据库直接交互。

>一个视图模板应该只和控制器所提供的数据进行交互。

---

####  1)        17:50 2017/2/7

*   Console.Readline 按 enter 结束
*   Console.Readkey  按任意非功能键（字符）结束

---

####  2)        18:20 2017/2/8 字体测试用字

    東 国 三 力 今 書 鷹 酬 鬱 愛 袋 永

---

####  3)        13:14 2017/2/15

>一般推荐的做法是将 JavaScript 引用放到 HTML 文档的结尾，body 结束标签之前，这样脚本就不会妨碍并行下载其他页面资源（图片和 CSS ）。

[来源-Best Practices for Speeding Up Your Web Site - Yahoo Developer Network](http://developer.yahoo.com/performance/rules.html#js_bottom.)

---

####  4)        10:23 2017/2/20

*   `IServiseLocator` 开头的「I」代表的是 interface （接口）。
*   `Task<TResult>` 第二个「T」代表的是 task （任务）。

---

####  5)        13:39 2017/2/20

>源代码的阅读次数要远超过编写次数。

---

####  6)        17:29 2017/2/20

>请仅仅把标题标签用于标题文本，不要仅仅为了产生粗体文本而使用它们，请使用其它标签或 CSS 代替。

---

####  7)        14:07 2017/2/21 jQuery toggle()

通过 jQuery，可以使用 `toggle()` 方法来切换 `hide()` 和 `show()` 方法显示被隐藏的元素，并隐藏已显示的元素。

---

####  8)        14:03 2017/3/2

*   `<ul\>` : unordered lists  无序列表
*   `<ol\>` : ordered lists    有序列表
*   `<li\>` : list item        列表项

---

####  9)        10:07 2017/3/3

*   CTRL+INSERT == CRTL+C == 复制
*   SHIFT+INSERT == CRTL+V == 粘贴

前者这组快捷键方便左手使用鼠标的用户

---

####  10)       11:21 2017/3/3

>年轻人，你要做到平时不出拳，可一旦出拳就要直中要害。

[来源-一个女程序猿的成长之路（4）—— 初入职场篇(b) - 简书](http://www.jianshu.com/p/379f67d43cb2)

---

####  11)       13:48 2017/3/3 显示节点的层次结构

显示节点的层次结构。（块状，颜色）

    * {background-color: rgba(255, 0, 0, .2);}
    * * {background-color: rgba(0, 255, 0, .2);}
    * * * {background-color: rgba(0, 0, 255, .2);}
    * * * * {background-color: rgba(255, 0, 255, .2);}
    * * * * * {background-color: rgba(0, 255, 255, .2);}
    * * * * * * {background-color: rgba(255, 255, 0, .2);}

[代码来源-Quora](https://www.quora.com/What-are-the-most-interesting-HTML-JS-DOM-CSS-hacks-that-most-web-developers-dont-know-about/answer/Gajus-Kuizinas)

显示节点的层次结构。（外部框）

    [].forEach.call($$("*"), function(a) {
        a.style.outline = "1px solid #" + (~~(Math.random() * (1 << 24))).toString(16)
    })

[代码来源-知乎](https://www.zhihu.com/question/27432017/answer/40621923)

---

####  12)       14:43 2017/3/3 JS的 map(),filter(),reduce() 方法

JS的 `map()`,`filter()`,`reduce()` 方法

![JS的 map(), filter(), reduce() 方法](https://ooo.0o0.ooo/2017/03/03/58b9114a36fd1.jpg)

*   [map()](http://www.cnblogs.com/rocky-fang/p/5756733.html)方法返回一个由原数组中的每个元素调用一个指定方法后的返回值组成的新数
*   [filter()](http://www.cnblogs.com/rocky-fang/p/5757140.html)用于把 Array 的某些元素过滤掉，然后返回剩下的元素组成的数组。
*   [reduce()](http://www.cnblogs.com/rocky-fang/p/5755755.html)把一个函数作用在这个 Array 的`[x1, x2, x3……]`上，这个函数必须接收两个参数，`reduce()` 把结果继续和序列的下一个元素做累积计算其效果就是：

        [x1, x2, x3, x4].reduce(f) = f(f(f(x1, x2), x3), x4)

---

####  13)       14:07 2017/3/6 CRUD

*   增加(Create)
*   读取查询(Retrieve)
*   更新(Update)
*   删除(Delete)

---

####  14)       9:45 2017/3/7 当你在浏览器中输入 google.com 并且按下回车之后发生了什么？

[当你在浏览器中输入 google.com 并且按下回车之后发生了什么？](https://github.com/skyline75489/what-happens-when-zh_CN/blob/master/README.rst#g)

---

####  15)       10:11 2017/3/7 排序算法图片总结

![排序算法图片总结](https://ooo.0o0.ooo/2017/03/07/58be16a16381b.png)

    n:          数据规模
    k:          「桶」的个数
    In-place:   占用常数内存，不占用额外内存
    Out-place:  占用额外内存

[图片来源](http://www.jianshu.com/p/7fd6d41d43b0)

---

####  16)       14:23 2017/3/7 3 种排序（JavaScript 实现）

冒泡排序

    //冒泡排序
    function bubble_sort(arr) {
        var times = 0;
        var temp;
        console.time("冒泡排序");
        for (var i = 0; i < arr.length; i++) {
            for (var j = 0; j < arr.length - 1 - i; j++) {
                if (arr[j] > arr[j + 1]) {
                    temp = arr[j];
                    arr[j] = arr[j + 1];
                    arr[j + 1] = temp;
                    times++;
                }
            }
        }
        console.timeEnd("冒泡排序");
        console.log(times);
        return arr;
    }

![冒泡排序](https://ooo.0o0.ooo/2017/03/07/58be52a13cb2b.gif)

选择排序

    //选择排序
    function selection_sort(arr) {
        var times = 0;
        var minindex, temp
        console.time("选择排序");
        for (var i = 0; i < arr.length - 1; i++) {
            minindex = i;
            for (var j = i; j < arr.length; j++) {
                if (arr[j] < arr[minindex])
                    minindex = j;
                times++;
            }
            temp = arr[i];
            arr[i] = arr[minindex];
            arr[minindex] = temp;
        }
        console.timeEnd("选择排序");
        console.log(times);
        return arr;
    }

![选择排序](https://ooo.0o0.ooo/2017/03/07/58be53278ee42.gif)

插入排序

    //插入排序
    function insertion_sort(arr) {
        var times = 0;
        console.time("插入排序");
        for (var i = 1; i < arr.length; i++) {
            var key = arr[i];
            var j = i - 1;
            while (j >= 0 && arr[j] > key) {
                arr[j + 1] = arr[j];
                j--;
                times++;
            }
            arr[j + 1] = key;
        }
        console.timeEnd("插入排序");
        console.log(times);
        return arr;
    }

![插入排序](https://ooo.0o0.ooo/2017/03/07/58be539594903.gif)

---

####  17)       11:21 2017/3/8 JavaScript 的 console.log() 使用方法

1.  输出字符

    input:

        console.log('%');

    output:

        %

2.  输出字符串

    input:

        console.log("字符串abc123!@#");

    output:

        字符串abc123!@#

3.  输出整数

    input:

        console.log(1);

    output:

        1

4.  输出小数

    input:

        console.log(3.1415926);

    output:

        3.1415926

5.  输出变量

    input:

        var a = 1;
        console.log(a);

    output:

        1

6.  输出数组

    input:

        var arr=[0,1,2,3,4,5];
        console.log(arr);

    output:

        [0, 1, 2, 3, 4, 5]

7.  输出对象

    input:

        var _object = {};
        _object.name = "obj";
        _object.age = 19;
        console.log(_object);

    output:

        Object {name: "obj", age: 19}

8.  通过占位符来输出

    input:

        var i = 1;
        var f = 3.1415926
        var str = "abc123!@#"
        var arr = [0,1,2,3,4,5];
        var obj = {};
        obj.name = "obj";
        obj.age = 19;
        console.log("整数i:%d\n小数f:%f\n字符串str:%s\n数组arr:%o\n对象obj:%o\n",i,f,str,arr,obj);

    output:

        整数i:1
        小数f:3.1415926
        字符串str:abc123!@#
        数组arr:[0, 1, 2, 3, 4, 5]0: 01: 12: 23: 34: 45: 5length: 6__proto__: Array[0]
        对象obj:Objectage: 19name: "obj"__proto__: Object

`console.log` 支持的格式标志

![console.log 支持的格式标志](https://ooo.0o0.ooo/2017/03/08/58bf8c8495318.jpg)

---

####  18)       13:13 2017/3/10 C# 接口的作用

[C# 接口的作用](http://www.cnblogs.com/zxx193/p/4910529.html)

---

####  19)       13:35 2017/3/14 Vue 实例生命周期

![Vue 实例生命周期](https://ooo.0o0.ooo/2017/03/14/58c7814a08b47.png)

---

####  20)       17:00 2017/3/16 Char.IsDigit 方法

指示指定的 Unicode 字符是否属于十进制数字类别。

---

####  21)       10:49 2017/3/20 常用缩写全称

（按缩写的首字母升序排列）

ab.     | Full Name                                        | 中文意思
--------|--------------------------------------------------|------------------------------
AJAX    | Asynchronous Javascript And XML                  | 异步 JavaScript 和 XML
args    | Arguments                                        | -
arr     | Array                                            | 数组
BASIC   | Beginners' All-purpose Symbolic Instruction Code | 初学者通用符号指令代码（培基）
char    | Character                                        | 字符
CSS     | Cascading Style Sheets                           | 层叠样式表
db      | Database                                         | 数据库
DIV     | Division                                         | 划分
DOM     | Document Object Model                            | 文档对象模型
DTD     | Document Type Definition                         | 文档类型定义
enum    | Enumerate                                        | 枚举
err     | Error(s)                                         | 错误
FCL     | Framework Class Library                          | 框架类库
GNU     | GNU's Not Unix                                   | 革奴计划
HTML    | HyperText Markup Language                        | 超级文本标记语言
ID      | Identity                                         | 身份标识方式
JS      | JavaScript                                       | -
JSON    | JavaScript Object Notation                       | JavaScript 对象标记
IBM     | International Business Machines Corporation      | 国际商业机器公司
init    | Initialize                                       | 初始化
int     | Intager                                          | 整数
LINQ    | Language Integrated Query                        | 语言集成查询
MAX     | Maximum                                          | 最大值
md      | Markdown                                         | -
MIN     | Minimum                                          | 最小值
MS      | Microsoft                                        | 微软
MSDN    | Microsoft Developer Network                      | 微软开发者网络
MVC     | Model View Controller                            | 视图、模型、控制器
N/A(NA) | Not Applicable                                   | 不可用
num     | Number Of                                        | 数量
OO      | Object Oriented                                  | 面向对象
OOP     | Object Oriented Programming                      | 面向对象编程
OS      | Operating System                                 | 操作系统
PHP     | Hypertext Preprocessor                           | 超文本预处理器
pwd(1)  | PassWord                                         | 密码、口令
pwd(2)  | Print Working Directory                          | 打印当前工作目录（Unix 命令）
ref     | Reference                                        | 参考
Rime    | Rime Input Method Engine                         | 中州韵输入法引擎
SGML    | Standard Generalized Markup language             | 标准通用置标语言
src     | Source                                           | 源文件
str     | String                                           | 字符串
var     | Variable                                         | 变量
W3C     | World Wide Web Consortium                        | 万维网联盟
WYSIWYG | What You See Is What You Get                     | 所见即所得
XML     | Extensible Markup Language                       | 可扩展标记语言
……      | ……                                               | ……
TBC     | To Be Continued                                  | 待续

---

####  22)       15:30 2017/3/21

*   [once and only once（一次且仅一次，简称 OAOO）](https://zh.wikipedia.org/wiki/%E4%B8%80%E6%AC%A1%E4%B8%94%E4%BB%85%E4%B8%80%E6%AC%A1)
*   [Don't repeat yourself（不要重复你自己，简称 DRY）](https://zh.wikipedia.org/wiki/%E4%B8%80%E6%AC%A1%E4%B8%94%E4%BB%85%E4%B8%80%E6%AC%A1)

---

####  23)       10:46 2017/3/22 没有消息就是好消息。

>没有消息就是好消息。

[来源-创建版本库 - 廖雪峰的官方网站](http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000/0013743256916071d599b3aed534aaab22a0db6c4e07fd0000)

---

####  24)       13:04 2017/3/24 二进制兼容

所谓「二进制兼容性」指的就是在升级（也可能是 bug fix）库文件的时候，不必重新编译使用这个库的可执行文件或使用这个库的其他库文件，程序的功能不被破坏。

[来源-二进制兼容 - 简书](http://www.jianshu.com/p/87febb375969)

---

####  25)       9:54 2017/3/27 C# get 访问器

最好不用使用 `get` 访问器更改对象的状态。例如，以下访问器在每次访问 number 字段时都会产生更改对象状态的副作用。

    private int number;
    public int Number
    {
        get
        {
            return number++;   // Don't do this
        }
    }

但是可以用于放回字段值，或用于计算并返回字段值。例如：

    class Employee
    {
        private string name;
        public string Name
        {
            get
            {
                return name != null ? name : "NA";
            }
        }
    }

在上一个代码段中，如果不对 Name 属性赋值，它将返回值 NA。

[来源-使用属性（C# 编程指南）](https://msdn.microsoft.com/zh-cn/library/w86s7x04.aspx)

---

####  26)       9:23 2017/3/29

*   [Let Me Baidu That For You](https://lmbtfy.cn/)
*   [Let Me Google That For You](http://lmgtfy.com/)

---

####  27)       10:16 2017/3/29 C# ref 和 out

两个参数的不同在于：

1.  `ref` 传进去的参数必须在调用前初始化，`out` 不必，即：

        int i;
        SomeMethod(ref i);  //语法错误
        SomeMethod(out i);  //通过

2.  `ref` 传进去的参数在函数内部可以直接使用，而 `out` 不可，即：

        public void SomeMethod(ref int i)
        {
            int j=i;    //通过
            //...
        }

        public void SomeMethod(out int i)
        {
            int j=i;    //语法错误
        }

3.  `ref` 传进去的参数在函数内部可以不被修改，但 `out` 必须在离开函数体前进行赋值。

---

####  28)       16:09 2017/3/29 默认值表

下表显示了由默认构造函数返回的值类型的默认值。 默认构造函数是通过 `new` 运算符来调用的，如下所示：

    int myInt = new int();

以上语句同下列语句效果相同：

    int myInt = 0;

请记住：在 C# 中不允许使用未初始化的变量。

值类型  | 默认值
--------|-----------------------------------------------------------------------------
bool    | false
byte    | 0
char    | '\0'
decimal | 0.0M
double  | 0.0D
enum    | 表达式 (E)0 产生的值，其中 E 为 enum 标识符。
float   | 0.0F
int     | 0
long    | 0L
sbyte   | 0
short   | 0
struct  | 将所有的值类型字段设置为默认值并将所有的引用类型字段设置为 null 时产生的值。
uint    | 0
ulong   | 0
ushort  | 0

[来源-默认值表（C# 参考）](https://msdn.microsoft.com/zh-cn/library/83fhsxwc.aspx)

---

####  29)       11:27 2017/3/31 小马

>但是小马，你怎么能听松鼠的话呢？只有用你自己的脚试试才知道这条河有多深！

[来源-TeX 与 LaTeX](http://www.ctex.org/documents/shredder/tex_frame.html)

---

####  30)       13:49 2017/3/31 C# 委托和事件

[C# 委托和事件](http://www.tracefact.net/CSharp-Programming/Delegates-and-Events-in-CSharp.aspx)

---

####  31)       16:35 2017/3/31

当

    if (BoilEvent != null)
        BoilEvent(temperatuerl);

时，可以用

    BoilEvent?.Invoke(temperatuerl);

来简化委托调用。

---

####  32)       18:10 2017/3/31 Visual Studio 滚动条上的颜色所表示的意思

颜色     | 意思
---------|--------------------
白色横线 | 光标位置
亮绿色   | 已经保存的内容
黄色     | 修改了没保存的内容
亮红色   | 语法错误
暗红色   | 断点
淡绿色   | 警告
褐色     | ctrl+f 的项

---

####  33)       11:29 2017/4/7 鸭子类型

>" When I see a bird that walks like a duck and swims like a duck and quacks like a duck,I call that bird a duck."

>“当看到一只鸟走起来像鸭子、游泳起来像鸭子、叫起来也像鸭子，那么这只鸟就可以被称为鸭子。”

我们并不关心对象是什么类型，到底是不是鸭子，只关心行为。

![" When I see a bird that walks like a duck and swims like a duck and quacks like a duck, I call that bird a duck."](https://ooo.0o0.ooo/2017/04/07/58e70843f10c5.jpg)

[来源-什么是鸭子类型(duck typing) - mattkang - 博客频道 - CSDN.NET](http://t.cn/R7GkIU1)

[来源-鸭子类型_百度百科](http://t.cn/R6r6wmL)

---

####  34)       16:12 2017/4/7 交换两个变量的值，不使用第三个变量

    int a, b;
    a = 10;
    b = 12;

    a = b - a; // a = 2; b = 12
    b = b - a; // a = 2; b = 10
    a = b + a; // a = 12; b = 10

---

####  35)       17:16 2017/4/7 用有趣的办法输出 42

JavaScript：

    var ________ = 0.023809523809523808, ____ = 1, ___ = 0, __ = 0, _ = 1;
           __ -           ___
         /_  |0        //     \\
        /_/   0     //          \\
       /_/_  |0                //
      /_/_   |0              //
     /_/____ |_           //
    /________|0        //
             |0     //______________

---

####  36)       14:26 2017/4/12 Yoda Notation（Yoda 表示法）

在 C/C++ 里面使用这样的表达式顺序：

    if ("blue" == theSky)

这是为了避免意外的写成：

    if (theSky = "blue")

“Yoda 表示法”的名字来源于《星球大战》的 Yoda 大师。他说话的单词顺序相当奇特，比如：“Backwards it is, yes!”

[来源-几个超炫的专业词汇](http://www.yinwang.org/blog-cn/2013/04/14/terminology)
[来源-Yoda 表示法错在哪里](http://www.yinwang.org/blog-cn/2013/04/14/yoda-notation)

---

####  37)       15:00 2017/4/12

很早以前，人工智能专家们就发现一个很有趣的现象，是这样：

>对于人来说很难，很烦的事情（复杂的计算，下棋，推理……），对于计算机来说，其实算是相对容易的事情。</br>
>对于人来说很容易的事情（认人，走路，开车，打球……），对于计算机来说，却非常困难。</br>
>计算机不能应付复杂的环境，只能在相对完美的环境下工作，需要精确的，离散的输入。</br>
>人对环境的适应能力很高，擅长于处理模糊的，连续的，不完美的数据。

[来源-AlphaGo与人工智能](http://www.yinwang.org/blog-cn/2016/03/09/alpha-go)

---

####  38)       10:32 2017/4/14 泛型——类型参数的约束

Constraint                    | Description
------------------------------|----------------------------------------------------------------------------------------------------------
`where T: struct`             | 类型参数必须是值类型。可以指定除 `Nullable` 以外的任何值类型。有关更多信息，请参见使用可以为 `null` 的类型。
`where T : class`             | 类型参数必须是引用类型；这一点也适用于任何类、接口、委托或数组类型。
`where T : new()`             | 类型参数必须具有无参数的公共构造函数。当与其他约束一起使用时，`new()` 约束必须最后指定。
`where T : <base class name>` | 类型参数必须是指定的基类或派生自指定的基类
`where T : <interface name>`  | 类型参数必须是指定的接口或实现指定的接口。可以指定多个接口约束。约束接口也可以是泛型的。
`where T : U`                 | 为 `T` 提供的类型参数必须是为 `U` 提供的参数或派生自为 `U` 提供的参数。

---

####  39）       12:47 2017/4/14 bool类型的与（&）或（|）运算

x       | y       | x&y     | x\|y
--------|---------|---------|---------
`true`  | `true`  | `true`  | `true`
`true`  | `false` | `false` | `true`
`true`  | `null`  | `null`  | `null`
`false` | `true`  | `false` | `true`
`false` | `false` | `false` | `false`
`false` | `null`  | `false` | `null`
`null`  | `true`  | `null`  | `true`
`null`  | `false` | `false` | `null`
`null`  | `null`  | `null`  | `null`

---

####  40）       13:56 2017/4/14 Vim 模式与模式转换

Vim一共有4个模式：

*   正常模式 (Normal-mode)
*   插入模式 (Insert-mode)
*   命令模式 (Command-mode)
*   可视模式 (Visual-mode)

1.  正常模式

    正常模式一般用于浏览文件，也包括一些复制、粘贴、删除等操作。这时击键时，
    一般的键/键组合会被当成功能键，而不会键入对应的字符。

    在这个模式下，我们可能通过键盘在文本中跳来跳去，跳动的范围从小到大是字符、
    单词、行、句子、段落和屏幕。

    启动 Vim 后默认位于正常模式。不论位于什么模式，按下 `Esc` 键(有时需要按两下）
    都会进入正常模式。

2.  插入模式

    在正常模式中按下 `i`, `I`, `a`, `A` 等键（后面系列文章会详细介绍），会进入插入模式。

    现在只用记住按 `i` 键会进行插入模式。*插入模式中，击键时会写入相应的字符。*

3.  命令模式

    在正常模式中，按下 `：`（冒号）键，会进入命令模式。在命令模式中可以执行
    一些输入并执行一些 Vim 或插件提供的指令，就像在 shell 里一样。这些指令包括
    设置环境、文件操作、调用某个功能等等。

4.  可视模式

    在正常模式按下 `v`, `V`, `Ctrl+v`，可以进入可视模式。可视模式中的
    操作有点像拿鼠标进行操作，选择文本的时候有一种鼠标选择的即视感，有时候
    会很方便。

不论在其他什么模式下，按一次或两次 `Esc` 键都可以回到正常模式。

[来源-【vim】模式与模式切换 - 赵子清 - 博客园](http://www.cnblogs.com/zzqcn/p/4619012.html)

---

####  41）       10:48 2017/4/19 CSS 黑科技

1.  实时编辑 CSS

    在 HTML 5 中新增了一个新的全局属性，`contenteditable` 属性。

    >`contenteditable` 属性规定是否可编辑元素的内容。

    我们可以通过设置这个属性，来对之前的一些文本进行编辑。

    该属性的取值：

    |值|描述|
    |-|-|
    |true|规定可以编辑元素的内容。|
    |false|规定无法编辑元素的内容。|
    |classname|继承父元素的 contenteditable 属性。|

    我们可以利用当前内容可编辑的这个特性，来去实现一个小的效果，例如这样。

    ![contenteditable](https://ooo.0o0.ooo/2017/04/19/58f6d17a5fbaa.gif)

        <!DOCTYPE html>
        <html lang="en">
        <head>
            <meta charset="UTF-8">
            <title>MR_LP</title>
        </head>
        <body>
            <style style="display:block" contentEditable>
                body { color: blue }
            </style>
        </body>
        </html>

2.  calc()

    `calc()` 从字面我们可以把他理解为一个函数function。

    其实 calc 是英文单词 calculate (计算)的缩写，是 CSS3 的一个新增的功能，用来指定元素的长度。

    比如说，你可以使用 `calc()` 给元素的 `border`、`margin`、`pading`、`font-size` 和 `width` 等属性设置动态值。

    为何说是动态值呢？因为我们使用的表达式来得到的值。

    不过 `calc()` 最大的好处就是用在流体布局上，可以通过 `calc()` 计算得到元素的宽度。

        .box{
            width: calc(100% - (10px + 5px) * 2);
        }

    `calc()` 语法非常简单，就像我们小时候学加（+）、减（-）、乘（*）、除（/）一样，使用数学表达式来表示。

    而且我们在使用的过程中，需要注意下面几条使用规则：

    *   使用“+”、“-”、“*” 和 “/”四则运算；
    *   可以使用百分比、px、em、rem等单位；
    *   可以混合使用各种单位进行计算；
    *   表达式中有“+”和“-”时，其前后必须要有空格，如“`widht: calc(12%+5em)`”这种没有空格的写法是错误的；
    *   表达式中有“*”和“/”时，其前后可以没有空格，但建议留有空格。

3.  大白

<html>
    <head>
        <meta charset="utf-8">
        <title>Baymax</title>
        <link rel=stylesheet href="demo2.css"/>
    </head>
    <style>
        /*body {
            background: #595959;
        }*/
        #baymax{
         /*设置为 居中*/
            margin: 0 auto;
            /*高度*/
            height: 600px;
            /*隐藏溢出*/
            overflow: hidden;
        }
        #head{
            height: 64px;
            width: 100px;
            /*以百分比定义圆角的形状*/
            border-radius: 50%;
            /*背景*/
            background: #fff;
            margin: 0 auto;
            margin-bottom: -20px;
            /*设置下边框的样式*/
            border-bottom: 5px solid #e0e0e0;
            /*属性设置元素的堆叠顺序；    拥有更高堆叠顺序的元素总是会处于堆叠顺序较低的元素的前面*/
            z-index: 100;
            /*生成相对定位的元素*/
            position: relative;
        }
        #eye,
        #eye2{
            width: 11px;
            height: 13px;
            background: #282828;
            border-radius: 50%;
            position: relative;
            top: 30px;
            left: 27px;
            /*旋转该元素*/
            transform: rotate(8deg);
        }
        #eye2{
            /*使其旋转对称*/
            transform: rotate(-8deg);
            left: 69px;    top: 17px;
        }
        #mouth{
            width: 38px;
            height: 1.5px;
            background: #282828;
            position: relative;
            left: 34px;
            top: 10px;
        }
        /*躯干和腹部*/
        #torso,
        #belly{
            margin: 0 auto;
            height: 200px;
            width: 180px;
            background: #fff;
            border-radius: 47%;
            /*设置边框*/
            border: 5px solid #e0e0e0;
            border-top: none;
            z-index: 1;
        }
        #belly{
            height: 300px;
            width: 245px;
            margin-top: -140px;
            z-index: 5;
        }
        #cover{
            width: 190px;
            background: #fff;
            height: 150px;
            margin: 0 auto;
            position: relative;
            top: -20px;
            border-radius: 50%;
        }
        /*心脏*/
        #heart{
          width:25px;
          height:25px;
          border-radius:50%;
          position:relative;
          /*向边框四周添加阴影效果*/
          box-shadow:2px 5px 2px #ccc inset;
          right:-115px;
          top:40px;
          z-index:111;
          border:1px solid #ccc;
        }
        /*手臂*/
        #left-arm,
        #right-arm{
            height: 270px;
            width: 120px;
            border-radius: 50%;
            background: #fff;
            margin: 0 auto;
            position: relative;
            top: -350px;
            left: -100px;
            transform: rotate(20deg);
            z-index: -1;
        }
        #right-arm{
            transform: rotate(-20deg);
            left: 100px;
            top: -620px;
        }
        /*手指头*/
        #l-bigfinger,
        #r-bigfinger{
            height: 50px;
            width: 20px;
            border-radius: 50%;
            background: #fff;
            position: relative;
            top: 250px;
            left: 50px;
            transform: rotate(-50deg);
        }
        #r-bigfinger{
            left: 50px;
            transform: rotate(50deg);
        }
        #l-smallfinger,
        #r-smallfinger{
            height: 35px;
            width: 15px;
            border-radius: 50%;
            background: #fff;
            position: relative;
            top: 195px;
            left: 66px;
            transform: rotate(-40deg);
        }
        #r-smallfinger{
            background: #fff;
            transform: rotate(40deg);
            top: 195px;
            left: 37px;
        }
        /*大腿*/
        #left-leg,
        #right-leg{
            height: 170px;
            width: 90px;
            border-radius: 40% 30% 10px 45%;
            background: #fff;
            position: relative;
            top: -640px;
            left: -45px;
            transform: rotate(-1deg);
            z-index: -2;
            margin: 0 auto;
        }
        #right-leg{
            background: #fff;
            border-radius:30% 40% 45% 10px;
            margin: 0 auto;
            top: -810px;
            left: 50px;
            transform: rotate(1deg);
        }
    </style>
<body>
     <div id="baymax">
        <!-- 定义头部，包括两个眼睛、嘴 -->
        <div id="head">
            <div id="eye"></div>
            <div id="eye2"></div>
            <div id="mouth"></div>
        </div>
        <!-- 定义躯干，包括心脏 -->
        <div id="torso">
            <div id="heart"></div>
        </div>
        <!-- 定义肚子腹部，包括 cover（和躯干的连接处） -->
        <div id="belly">
            <div id="cover"></div>
        </div>
        <!-- 定义左臂，包括一大一小两个手指 -->
        <div id="left-arm">
            <div id="l-bigfinger"></div>
            <div id="l-smallfinger"></div>
        </div>
        <!-- 定义右臂，同样包括一大一小两个手指 -->
        <div id="right-arm">
            <div id="r-bigfinger"></div>
            <div id="r-smallfinger"></div>
        </div>
        <!-- 定义左腿 -->
        <div id="left-leg"></div>
        <!-- 定义右腿 -->
        <div id="right-leg"></div>
    </div>
</body>
<html>

[来源-细数前端中的一些黑科技 - MR_LP的博客 - 博客频道 - CSDN.NET](http://blog.csdn.net/mr_lp/article/details/53539218)

---

####  42)       14:10 2017/4/19 GitHub中"watch" "star" "fork"三个按钮干什么用的

1.  想拷贝别人项目到自己帐号下就 `fork` 一下。
2.  持续关注别人项目更新就 `star` 一下
3.  `watch` 是设置接收邮件提醒的。

[来源-GitHub中"watch" "star" "fork"三个按钮干什么用的_百度知道](https://zhidao.baidu.com/question/2053288558473167507.html)

---

####  43)       16:21 2017/4/19 编码规范

>不管有多少人共同参与同一项目，一定要确保每一行代码都像是同一个人编写的。

[来源-编码规范 by @mdo](http://codeguide.bootcss.com/)

---

####  44)       11:37 2017/5/3 为什么文件名要小写？

>文件名建议只使用小写字母，不使用大写字母。

>为了醒目，某些说明文件的文件名，可以使用大写字母，比如 `README`、`LICENSE`。

1.  可移植性

    Linux 系统是大小写敏感的，而 Windows 系统和 Mac 系统正好相反，大小写不敏感。一般来说，这不是大问题。

    但是，如果两个文件名只有大小写不同，其他都相同，跨平台就会出问题。

    *   foobar
    *   Foobar
    *   FOOBAR
    *   fOObAr

    上面四个文件名，Windows 系统会把它们都当作 `foobar` 。如果它们同时存在，你可能没办法打开后面三个文件。

    另一方面，在 Mac 系统上开发时，有时会疏忽，写错大小写。

        // 正确文件名是 MyModule.js
        const module = require('./myModule');

    上面的代码在 Mac 上面可以运行，因为 Mac 认为 `MyModule.js` 和 `myModule.js` 是同一个文件。但是，一旦代码到服务器运行就会报错，因为 Linux 系统找不到 `myModule.js`。

    如果所有的文件名都采用小写，就不会出现上面的问题，可以保证项目有良好的可移植性。

2.  易读性

    小写文件名通常比大写文件名更易读，比如 `accessibility.txt` 就比 `ACCESSIBILITY.TXT` 易读。

    有人习惯使用驼峰命名法，单词的第一个字母大写，其他字母小写。这种方法的问题是，如果遇到全部是大写的缩略词，就会不适用。

    比如，一个姓李的纽约特警，无论写成 `NYPoliceSWATLee` 还是 `NyPoliceSwatlee`，都怪怪的，还是写成 `ny-police-swat-lee` 比较容易接受。

3.  易用性

    某些系统会生成一些预置的用户目录，采用首字母大写的目录名。比如，Ubuntu 在用户主目录会默认生成 `Downloads`、 `Pictures`、`Documents` 等目录。

    Mac 系统更过分，一部分系统目录也是大写的，比如 `/Library/Audio/Apple Loops/`。

    另外，某些常见的配置文件或说明文件，也采用大写的文件名，比如 `Makefile`、`INSTALL`、`CHANGELOG`、`.Xclients` 和 `.Xauthority` 等等。

    所以，用户的文件都采用小写文件名，就很方便与上面这些目录或文件相区分。

    如果你打破砂锅问到底，为什么操作系统会采用这样的大写文件名？原因也很简单，因为早期 Unix 系统上，`ls` 命令先列出大写字母，再列出小写字母，大写的路径会排在前面。因此，如果目录名或文件名是大写的，就比较容易被用户首先看到。

    ![排序](https://ooo.0o0.ooo/2017/05/03/59095dbbdf08d.png)

4.  便捷性

    文件名全部小写，还有利于命令行操作。比如，某些命令可以不使用 `-i` 参数了。

        # 大小写敏感的搜索
        $ find . -name abc
        $ locate "*.htmL"

        # 大小写不敏感的搜索
        $ find . -iname abc
        $ locate -i "*.HtmL"

    ![大写shift键](https://ooo.0o0.ooo/2017/05/03/59095e3a64148.png)

    另外，大写字母需要按下 `Shift` 键，多多少少有些麻烦。如果文件名小写，就不用碰这个键了，不仅省事，还可以提高打字速度。

    程序员长时间使用键盘，每分钟少按几次 `Shift`，一天下来就可以省掉很多手指动作。长年累月，也是对自己身体的一种保护。

    综上所述，文件名全部使用小写字母和连词线（all-lowercase-with-dashes），是一种值得推广的正确做法。

[来源-为什么文件名要小写？ - 阮一峰的网络日志](http://www.ruanyifeng.com/blog/2017/02/filename-should-be-lowercase.html)

---

####  45)   18:11 2017/5/3 各个系统的换行符转义

Windows 下的文本文件换行符：`\r\n`。

Linux/Unix 下的文本文件换行符：`\r`。

Mac 下的文本文件换行符：`\n`。

[来源-Java写到.txt文件，如何实现换行 - liangoo7的专栏 - 博客频道 - CSDN.NET](http://blog.csdn.net/liangoo7/article/details/7882773)

---

####  46)   17:26 2017/5/17 Lorem ipsum

>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Wikipedia 上的解释是，这只是一段用来测试排版效果的占位文字，没有实际的含义。

据说，16世纪的时候就有人开始用了。

当时的某个印刷工人，从古罗马政治家西塞罗的文章中，选了一段拉丁文，

>"Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit "

进行了混排，就把它创造出来了。这句拉丁文的英译是

>"Neither is there anyone who loves grief itself since it is grief and thus wants to obtain it"

译成中文就是

>"无人爱苦，亦无人寻之欲之，乃因其苦......"

[来源-关于Lorem ipsum - 阮一峰的网络日志](http://www.ruanyifeng.com/blog/2009/04/lorem_ipsum.html)

[相关-Lorem Ipsum - All the facts - Lipsum generator](http://www.lipsum.com/)

---

####  47)   10:39 2017/5/23 使图片变黑白的 CSS。

    .grayscale{
        -webkit-filter: grayscale(100%);
        -moz-filter: grayscale(100%);
        -ms-filter: grayscale(100%);
        -o-filter: grayscale(100%);
        filter: grayscale(100%);
        filter: gray;
    }

---
