do...while语句用于创建一个循环，它会先执行一次代码块，然后再检查条件是否为真，如果为真，就重复执行代码块，如果为假，就停止循环。³⁵

do...while语句的语法是：

```javascript
do {
  // code block to be executed
}
while (condition);
```

condition是在每次循环结束后评估的表达式，如果为真，就继续执行代码块，如果为假，就停止循环。³⁵

下面是一个do...while语句的例子：

```javascript
let i = 0; // 定义一个变量i
do {
  console.log(i); // 打印i的值
  i++; // 将i的值加一
}
while (i < 5); // 当i小于5时，继续循环
```

这个例子会在控制台输出0,1,2,3,4，因为即使第一次执行时i的值是0不满足条件，也会执行一次代码块，并且在后面的循环中满足了条件。

源: 与必应的对话， 2023/3/11(1) JavaScript do/while Statement - W3Schools. https://www.w3schools.com/jsref/jsref_dowhile.asp 访问时间 2023/3/11.
(2) do...while - JavaScript | MDN - Mozilla. https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/do...while 访问时间 2023/3/11.
(3) JavaScript while Loop By Examples - JavaScript Tutorial. https://www.javascripttutorial.net/javascript-while-loop/ 访问时间 2023/3/11.
(4) JavaScript while Loop By Examples - JavaScript Tutorial. https://www.javascripttutorial.net/javascript-while-loop/ 访问时间 2023/3/11.
(5) JavaScript while and do...while Loop (with Examples) - Programiz. https://www.programiz.com/javascript/while-loop 访问时间 2023/3/11.