getElementsByTagName的实例是使用该方法根据标签名获取HTML元素对象的 ***伪数组***，然后对其进行操作。例如，下面的代码可以获取所有的<p>元素，并改变其颜色为红色²：

```javascript
var x = document.getElementsByTagName("p");
for (var i = 0; i < x.length; i++) {
  x[i].style.color = "red";
}
```

或者，可以使用该方法从一个特定的父元素开始搜索，获取其所有匹配标签名的后代元素¹。例如，下面的代码可以获取id为"div1"的元素中的所有<p>元素，并弹出其数量：

```javascript
var div1 = document.getElementById("div1");
var div1Paras = div1.getElementsByTagName("p");
var num = div1Paras.length;
alert(`There are ${num} paragraphs in #div1`);
```

源: 与必应的对话， 2023/3/15(1) Document.getElementsByTagName() - Web APIs | MDN - Mozilla. https://developer.mozilla.org/en-US/docs/Web/API/document/getElementsByTagName 访问时间 2023/3/15.
(2) Document.getElementsByTagName() - Web APIs | MDN - Mozilla. https://developer.mozilla.org/en-US/docs/Web/API/document/getElementsByTagName 访问时间 2023/3/15.
(3) HTML DOM Document getElementsByTagName() Method - W3Schools. https://www.w3schools.com/jsref/met_document_getelementsbytagname.asp 访问时间 2023/3/15.
(4) Element.getElementsByTagName() - Web APIs | MDN - Mozilla. https://developer.mozilla.org/en-US/docs/Web/API/Element/getElementsByTagName 访问时间 2023/3/15.