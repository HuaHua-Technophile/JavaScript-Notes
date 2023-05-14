**switch** 语句用于根据一个表达式的值匹配多个情况，每个情况对应一个代码块，如果有匹配的情况，就执行相应的代码块，如果没有匹配的情况，就执行默认的 **default** 代码块。

下面是一个switch语句的例子：

```javascript
let fruit = "apple"; // 定义一个变量fruit
switch (fruit) { // 根据fruit的值匹配不同的情况
  case "banana": // 如果fruit是"banana"
    console.log("香蕉"); // 打印"香蕉"
    break; // 跳出switch语句
  case "apple": // 如果fruit是"apple"
    console.log("苹果"); // 打印"苹果"
    break; // 跳出switch语句
  case "orange": // 如果fruit是"orange"
    console.log("橘子"); // 打印"橘子"
    break; // 跳出switch语句
  default: // 如果没有匹配的情况
    console.log("我不知道这是什么水果"); // 打印"我不知道这是什么水果"
}
```

这个例子会在控制台输出"苹果"，因为fruit的值是"apple",满足了case "apple" 的情况。