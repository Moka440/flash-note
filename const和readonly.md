## const和readonly <span class="tag">C#1.0</span>

- 相同点
  - 二者都用来声明常量
  - 初始化后都无法再(直接)修改值
- 不同点
  - readonly可以在构造函数中初始化，而const则必须在声明时初始化
  - readonly只能用于声明类的字段，const还可以用于声明局部变量
  - readonly是语法特性，const则本质上是字面常量
  - readonly的初始化不必是编译时常量，const则必须是字面常量
 <link rel="stylesheet" href="markdown.css">