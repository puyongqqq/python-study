# python3基础学习
## 一、标准数据类型 （包含6中基本数据类型）
    其中不可变数据类型有：Number, String, Tuple, 可变数据类型有List, Dictionary, Set。
### （1）Number 数字
支持int, float, bool, complex(复数)
[注]：内置函数type()可以用来查询变量所指向对象的类型, 例如：type(a), 还可以通过ininstance(a, int)。
区别：type()不会认为子类是一种父类类型。
isinstance()会认为子类是一种父类类型。
    
    int：在python3中只有一种整数类型，表示长整型，没有Python2中的Long
    bool：在python2中没有bool类型，用 0 表示 False ，用 1 表示 True 。但是它们的值还是1和0，它们可以和数字相加。
    complex：复数由实数和虚数部分构成，可以用a + bj, 或者complex(a, b)表示，复数的实部和虚部都是浮点型。

### （2）String 字符串
字符串定义单引号 ' 或者双引号 " 括起来，同事使用反斜杠 \ 转义特殊字符。
    
    1. 如果不想反斜杠发生转义，可以在字符串前面添加一个r，表示原始字符串。
    2. 字符串可以使用 + 连接运算符实现字符串拼接，用 * 运算符重复。
    3. python中的字符串有两种索引方式，从左往右以 0 开始， 从右往左以 -1 开始。
    4. python中的字符串不能改变。
    
    字符串截取：str[start:end]
### （3）List 列表
### （4）Tuple 元组
### （5）Set 集合
### （6）Dictionary 字典
