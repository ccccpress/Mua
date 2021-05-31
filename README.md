# MuaScript
MuaScript is a script language inspired by Lua

注释
```
# 单行注释
###
多行注释
###
```

自动类型推断 + 变量遮盖
```
a := 1
b := - 1.0
c := "string"
d := { "hello" "word" }
e := { "foo" = "ball" }
```

半自动内存管理
```
a := {}
a = nil / return a
```

条件控制语句
```
if a == 1
{ 
    [println "a = 1"]
}
```
也提供一种快捷写法
```
a := 1 if not a
```

强类型函数
```
foo := [int a double b] double
{
    return [double a] + b
}

c := [foo 1 1.1]
```