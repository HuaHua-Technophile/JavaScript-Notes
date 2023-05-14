getElementsByClassName的实例是使用该方法根据类名获取HTML元素对象的 ***伪数组***，然后对其进行操作。
该方法可以接收一个字符串参数,可以包含一个或多个类名.用空格隔开,不分先后顺序.
返回带有指定类名的所有元素的 ***伪数组*** NodeList

例如，下面的代码可以获取所有具有"test"类名的元素，并改变其颜色为红色¹：

```javascript
var x = document.getElementsByClassName("test");
for (var i = 0; i < x.length; i++) {
  x[i].style.color = "red";
}
```

或者，可以使用该方法从一个特定的父元素开始搜索，获取其所有具有指定类名或类名的后代元素²。例如，下面的代码可以获取id为"parent-id"的元素中具有"test"类名的第一个元素，并打印其内容：

```javascript
var parentDOM = document.getElementById("parent-id");
var test = parentDOM.getElementsByClassName("test")[0];
console.log(test.textContent);
```

源: 与必应的对话， 2023/3/15(1) Document.getElementsByClassName() - Web APIs | MDN - Mozilla. https://developer.mozilla.org/en-US/docs/Web/API/Document/getElementsByClassName 访问时间 2023/3/15.
(2) Element.getElementsByClassName() - Web APIs | MDN - Mozilla. https://developer.mozilla.org/en-US/docs/Web/API/Element/getElementsByClassName 访问时间 2023/3/15.
(3) HTML DOM getElementsByClassName() 方法. https://m.w3schools.cn/jsref/met_element_getelementsbyclassname.asp 访问时间 2023/3/15.
(4) JS用getElementsByClassName获取HTML元素的方法 - web开发 - 亿 .... https://www.yisu.com/zixun/119437.html 访问时间 2023/3/15.
(5) HTML DOM getElementsByClassName() 方法 | 菜鸟教程. https://www.runoob.com/jsref/met-document-getelementsbyclassname.html 访问时间 2023/3/15.