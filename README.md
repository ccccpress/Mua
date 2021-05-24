# MuaScript
MuaScript is a script language inspired by Lua


自动类型推断 + 变量遮盖
```
let a = 1                   // 无符号整数
let b = - 1.0               // 双精度浮点数
let c = "string"            // 字符串
let d = { "hello" "word" }  // 数组
let e = { foo = "ball" }    // 表
```

强类型 + 前缀函数
```
let a = 1.0
let b = [int] a

let c = "-123"
let b = [int] [double] c
```

半自动内存管理
```
let a = {}
a = nil / free a
return a
```
