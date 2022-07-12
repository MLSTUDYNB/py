<<<<<<< HEAD
# python

[TOC]



# 变量

```python
name = 'hello world'
```

这里的name就是变量，这个变量储存的是地址。看下面这个图
![在这里插入图片描述](https://img-blog.csdnimg.cn/ccd4c0f418624d6781cf940d21fa8cdc.png)

>关于变量命名的规则：
>1.变量只能为字符，数字以及下划线，并且不能以数字开头
>2.变量不能为关键字
>3.当变量为内置函数名时，不会报错，但是会覆盖原来函数的功能

# 数据类型

数据类型包括**整型(int)，浮点型(float)，字符串类型(str)，布尔类型(bool)**

```python
a = 'abc'
b = 2
c = 2.3
d = True
print(type(a),type(b),type(c),type(d))
```

输出结果：
![在这里插入图片描述](https://img-blog.csdnimg.cn/e142326119ae476abbd27b8dd2fb86e5.png)

# 运算符

## 算术运算符

	+加	 -减	 *乘	 /除	 //整除	 %取余	 **幂运算


```python
print(4+2)
print(4-2)
print(4*2)
print(5/2)
print(5//2)
print(5%2)
print(2**4)
```

![在这里插入图片描述](https://img-blog.csdnimg.cn/df76026530ab48d6b5c503fc30542ea2.png)

## 赋值运算符

>=

## 比较运算符

	>=,<=,==,!=,>,<

## 布尔运算符

>and,or,not ,in

```python
a=True
b=False
print(a and b)
print(a or b)
c='abcd'
d='abcdef'
print(c in d)
print(c not in d)
```

![在这里插入图片描述](https://img-blog.csdnimg.cn/b82de6abfbc34e9ba01e46a93c5e29e0.png)

## 位运算符

	>>(右移，左边补0) ,<<（左移，右边补0）,|（只要是1运算的结果就为1）,&（只要有0运算的结果就为0）


```python
a=3
b=2
print(a>>1)
print(a<<1)
print(a|b)
print(a&b)
```

3的二进制`11`，右移1位`01`，左移一位`110`
2的二进制`10`,a|b为`11`，a&b为`10`
![在这里插入图片描述](https://img-blog.csdnimg.cn/c6e73f2559f1473d9d75cb9a1d6f9458.png)

# 分支语句

if else,elif

```python
age = int(input('请输入你的年龄'))
if age<18:
    print('未成年')
elif 18<=age<=60:
    print('壮年')
else:
    print('老年')
```

![在这里插入图片描述](https://img-blog.csdnimg.cn/4ac90be00b3a4447bb048dddab0409a1.png)

# 循环语句

while , for 

# 列表
=======
# py
python 学习笔记的记录
>>>>>>> 85a0f187b89689147b8996de83b7b3391bd7a400
