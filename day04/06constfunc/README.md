# 常函数与常对象

* 在类成员函数的形参表后，函数体之前加上`const`关键字，该成员函数的this指针即具有长属性，这样的成员函数被称为常函数

```
class 类名{
    返回类型 函数名(形参表) const {
        函数体;
    }
};
```

* 在常函数内部无法修改成员变量的值，除非该成员变量被`mutable`关键字修饰





