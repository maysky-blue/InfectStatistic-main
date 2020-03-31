#### 缩进
使用Tab进行缩进(一般默认为四个空格)

#### 命名规范
一般使用简单的英文单词来进行命名变量，如果有时对于同一区域变量较多则采用英文单字+数字的方式（例如a1,a2,a3）<br/>
函数的命名符合驼峰命名法，举例来说若有一个函数执行命令，则组合其英文单词命名为ExcuteCommand<br/>
常量名一般用全大写字母进行命名<br/>
数组命名中括号跟在类型之后 形如String[] s;但有时因为长时间coding可能会不小心写在变量名之后，发现后会及时改正<br/>

#### 运算符
运算符与变量之间必定有至少一个空格

#### 循环
尽量不使用while,尽可能使用for循环保证可读性

#### 杂项
每行代码不超过100个字符（包括中文）
但如果对于一个完整复制语句为了保证整体性则不进行换行
对于注释尽可能不复杂化（灿辉老师标准）
保证注释仅提供思路不解释完整方法
函数的大括号在左括号后进行换行，右括号单独一行
当保证函数只占一行时则形如public void AddNum(int a){//省略代码}