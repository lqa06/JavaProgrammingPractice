# Lab1：Java 变量与运算符基础练习

## 实验背景

本次实验涵盖 Java 编程的基础语法，包括输出语句、变量声明、基本数据类型、字符串操作以及各类运算符的使用（算术运算符、赋值运算符、比较运算符、逻辑运算符、三元运算符）。

---

## 提交要求

```
学号姓名/
└── Lab1/
    └── java_basics.md    # 将答案填入本文件各题代码块后提交
```

截止时间：**2026-3-23**，届时不再接受任何Lab1的pr请求。

---

## 题目 1：输出个人信息

编写 Java 程序，输出以下三行消息（**请替换为你自己的真实信息**）：

```
My name is 张三
My student ID is 20231001
I'm learning Java!
```

**预期输出：**

```
My name is 张三
My student ID is 20231001
I'm learning Java!
```

**你的答案：**

```java

```

---

## 题目 2：修正编译错误

以下每段代码都存在错误，请找出并修正。

### 练习 2.1

```java
public class Hello {
    public static void main(String[] args) {
        System.out.println("Hello World"
    }
}
```

**预期输出：**

```
Hello World
```

**你的答案：**

```java

```

### 练习 2.2

```java
public class Test {
    public static void main(String[] args) {
        system.out.println("Hello Java");
    }
}
```

**预期输出：**

```
Hello Java
```

**你的答案：**

```java

```

### 练习 2.3

```java
public class Info {
    public static void main(String[] args) {
        System.out.println("Line 1") System.out.println("Line 2")
    }
}
```

**预期输出：**

```
Line 1
Line 2
```

**你的答案：**

```java

```

### 练习 2.4

```java
public class Test {
    public static void Main(String[] args) {
        System.out.println("Test");
    }
}
```

**预期输出：**

```
Test
```

**你的答案：**

```java

```

---

## 题目 3：变量定义与数据类型

定义以下变量并输出：
- `name`: 你的姓名（String）
- `age`: 你的年龄（int）
- `score`: 85.5（float）
- `isPass`: true（boolean）

**预期输出：**

```
Name: 张三
Age: 20
Score: 85.5
Pass: true
```

**你的答案：**

```java

```

---

## 题目 4：字符串拼接

定义变量 `String name = "张三"` 和 `int id = 20231001`，通过字符串拼接输出：

**预期输出：**

```
学生张三的学号是20231001
```

**你的答案：**

```java

```

---

## 题目 5：算术运算符

声明 `int a = 20` 和 `int b = 3`，输出加减乘除取模运算结果。

**预期输出：**

```
a + b = 23
a - b = 17
a * b = 60
a / b = 6
a % b = 2
```

**你的答案：**

```java

```

---

## 题目 6：自增自减运算符

声明 `int x = 5`，分别输出 `++x` 的值和 `x` 的值，再输出 `x--` 的值和 `x` 的值。

**预期输出：**

```
++x = 6
x = 6
x-- = 6
x = 5
```

**你的答案：**

```java

```

---

## 题目 7：赋值运算符

声明 `int num = 10`，使用赋值运算符（+=、-=、*=、/=、%=）依次运算并输出结果。

**预期输出：**

```
num += 5: 15
num -= 3: 12
num *= 2: 24
num /= 4: 6
num %= 4: 2
```

**你的答案：**

```java

```

---

## 题目 8：比较运算符

声明 `int m = 15` 和 `int n = 20`，输出 6 种比较运算结果（==、!=、>、<、>=、<=）。

**预期输出：**

```
m == n: false
m != n: true
m > n: false
m < n: true
m >= n: false
m <= n: true
```

**你的答案：**

```java

```

---

## 题目 9：逻辑运算符

声明 `boolean a = true, b = false`，输出以下运算结果：
- a && b
- a || b
- !a
- a ^ b

**预期输出：**

```
a && b: false
a || b: true
!a: false
a ^ b: true
```

**你的答案：**

```java

```

---

## 题目 10：三元运算符

声明 `int score = 75`，使用三元运算符判断是否及格（>=60），输出 "及格" 或 "不及格"。

再声明 `int x = 10, y = 20`，使用三元运算符输出较大值。

**预期输出：**

```
成绩: 及格
较大值: 20
```

**你的答案：**

```java

```

---

## 题目 11：综合练习

编写程序，定义变量：
- 语文成绩：80
- 数学成绩：90
- 英语成绩：85

计算并输出总分、平均分（保留1位小数）、是否全部及格（>=60）、是否有优秀（>=90）。

**预期输出：**

```
总分: 255
平均分: 85.0
全部及格: true
有优秀: true
```

**你的答案：**

```java

```
