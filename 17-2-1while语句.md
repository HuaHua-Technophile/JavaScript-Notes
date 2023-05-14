while语句用于创建一个循环，当一个条件为真时，就执行一个代码块。¹²³

while语句的语法是：

```javascript
while (condition) {
  // code block to be executed
}
```

condition是在每次循环开始前评估的表达式，如果为真，就执行代码块，如果为假，就停止循环。¹²³

下面是一个while语句的例子：

```javascript
let i = 0; // 定义一个变量i
while (i < 5) { // 当i小于5时，执行以下代码块
  console.log(i); // 打印i的值
  i++; // 将i的值加一
}
```

这个例子会在控制台输出0,1,2,3,4，因为当i等于5时，条件不再为真，循环停止。

源: 与必应的对话， 2023/3/11(1) while - JavaScript | MDN - Mozilla. https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/while 访问时间 2023/3/11.
(2) JavaScript while Loop - W3Schools. https://www.w3schools.com/js/js_loop_while.asp 访问时间 2023/3/11.
(3) JavaScript while Statement - W3Schools. https://www.w3schools.com/jsref/jsref_while.asp 访问时间 2023/3/11.