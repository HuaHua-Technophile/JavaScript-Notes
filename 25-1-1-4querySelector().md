document.querySelector的实例是使用该方法根据CSS选择器获取HTML元素 ***对象***，然后对其进行操作。例如，下面的代码可以获取第一个<p>元素，并改变其颜色为红色²：

```javascript
var x = document.querySelector("p");
x.style.color = "red";
```

或者，可以使用该方法获取具有复杂选择器的元素¹。例如，下面的代码可以获取id为"main"的元素中的第一个<input>元素，并打印其值：

```javascript
var x = document.querySelector("#main input");
console.log(x.value);
```

源: 与必应的对话， 2023/3/15(1) Document.querySelector() - Web APIs | MDN - Mozilla. https://developer.mozilla.org/en-US/docs/Web/API/Document/querySelector 访问时间 2023/3/15.
(2) Document.querySelector() - Web APIs | MDN - Mozilla. https://developer.mozilla.org/en-US/docs/Web/API/Document/querySelector 访问时间 2023/3/15.
(3) HTML DOM Document querySelector() Method - W3Schools. https://www.w3schools.com/jsref/met_document_queryselector.asp 访问时间 2023/3/15.
(4) JavaScript querySelector: Selecting Elements By CSS Selectors. https://www.javascripttutorial.net/javascript-dom/javascript-queryselector/ 访问时间 2023/3/15.