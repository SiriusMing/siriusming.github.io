

[TOC]

​	![image-20240531173611654](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240531173611654.png)



### Day 1

1.因特网怎么工作

**The ==internet== is a global network of computers (or local networks)** 

**connected via a network of routers**

<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240520192034394.png" alt="image-20240520192034394" style="zoom:67%;" />

2.互联网协议 ==这一页重要 留意== 

![image-20240520193307200](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240520193307200.png)

#### **==重点：application layer 协议 以及是什么==**

​	The Application Layer is topmost layer in the Open System Interconnection (OSI) model. This layer provides several ways for manipulating the data (information) which actually enables any type of user to access network with ease. This layer also makes a request to its bottom layer, which is presentation layer for receiving various types of information from it. **==The Application Layer interface directly interacts with application and provides common web application services.==** This layer is basically highest level of open system, **which provides services directly for application process.**

​	应用层是开放系统互连(OSI)模型的顶层。该层提供了多种操作数据(信息)的方法，使任何类型的用户都可以轻松访问网络。该层还向底层(表示层)发出请求，从底层接收各种类型的信息。应用层接口直接与应用程序交互，**提供通用的web应用服务**。这一层基本上是开放系统的最高层，直接为应用程序流程提供服务。

![image-20240520193910492](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240520193910492.png)

![image-20240530190436691](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240530190436691.png)

![image-20240530190452102](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240530190452102.png)

#### 	 dns 定义 为什么用它 是用来做什么的

​	Domain Name System (DNS) is a **hostname** for ==IP address translation service==. DNS is a [distributed database](https://www.geeksforgeeks.org/distributed-database-system/) implemented in a hierarchy of name servers. It is an application layer protocol for message exchange between clients and servers. It is required for the functioning of the [Internet](https://www.geeksforgeeks.org/what-is-internet-definition-uses-working-advantages-and-disadvantages/).

​	**DNS (Domain Name System)是IP地址转换服务的主机名。**DNS是在名称服务器层次结构中实现的分布式数据库。它是用于客户端和服务器之间消息交换的应用层协议。这是互联网运作所必需的。

​	为什么用：

​	Every host is identified by the IP address but remembering numbers is very difficult for people also the IP addresses are not static therefore a mapping is required to change the domain name to the IP address. So DNS is used to convert the domain name of the websites to their numerical IP address.

​	每个主机都由IP地址标识，但记住数字对人们来说非常困难，IP地址也不是静态的，因此需要映射将域名更改为IP地址。因此，DNS用于将网站的域名转换为其数字IP地址。 Devices can use DNS servers (*“phonebook of the internet”*) to **convert  hierarchical DNS addresses to IP addresses.**

1. Readability 可读性

2. Flexibility 灵活性
3. Stability 稳定性
4. Hierarchical tree structure 分层树结构

![image-20240530190637780](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240530190637780.png)

![image-20240530194605403](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240530194605403.png)

![image-20240530195548326](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240530195548326.png)

![image-20240530195637545](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240530195637545.png)





### Day 2 

#### html基本语法规则之类

​	**HTML（HyperText Markup Language）是一种标记语言，用于创建网页结构和内容**。它由一系列标签（tags）组成，每个标签描述了页面上的不同元素，例如文本、图像、链接等。HTML 提供了一种结构化的方式来描述网页，使得浏览器能够正确地解析和显示网页内容。

![image-20240530202639151](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240530202639151.png)

HTML 的用途

- **网页内容的结构化**：使用 HTML 标签来组织和格式化网页内容。

- **嵌入媒体**：可以嵌入图像、音频、视频等多媒体内容。

- **超文本链接**：创建链接，允许用户在网页之间导航。

- **表单**：使用表单元素（如 `<form>`、`<input>`、`<textarea>`）来收集用户输入。

  

HTML 头部是 `<head>`元素的内容。与`<body>`元素的内容（在浏览器中加载时显示在页面上）不同，head 的内容不会显示在页面上。

```html
<!DOCTYPE html>
<html lang="en-US">
  <head>
    <meta charset="utf-8" />
    <title>My test page</title>
  </head>
  <body>
    <p>This is my page</p>
  </body>
</html>

```

/

![image-20240531202858541](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240531202858541.png)

![image-20240531211433800](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240531211433800.png)

在第二个标题的结束标签中有个小错误，将 `<h1>` 替换为 `<h2>` 以匹配开始标签。

- `<h2>Ordered list</h2>`: 标题，表示接下来的内容是一个有序列表。
- `<ol>`: 有序列表的开始标签。
- `<li>First in list</li>`: 列表的第一个项目。
- `<li>Second in list</li>`: 列表的第二个项目。
- `<li>Third in list</li>`: 列表的第三个项目。
- `</ol>`: 有序列表的结束标签。



- `<h2>Unordered list</h2>`: 标题，表示接下来的内容是一个无序列表。
- `<ul>`: 无序列表的开始标签。
- `<li>First in list</li>`: 列表的第一个项目。
- `<li>Second in list</li>`: 列表的第二个项目。
- `<li>Third in list</li>`: 列表的第三个项目。
- `</ul>`: 无序列表的结束标签。

![image-20240531211500961](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240531211500961.png)

​	**Emphasis:**

Tags `<em>` and `<strong> `can be used for emphasizing text
Note that tags `<i> `and `<b> `are often used for italics and bold, but their actual formatting can be redefined!

```html
...
<body>
<h2>Emphasis</h2>
<em>I wish to emphasize this
text.</em>
<br>
<strong>A strongly emphasized
text.</strong>
</body>
...
```

quote:

```html
<body>
<h2>Quotes</h2>
Hamlet:<blockquote>
"To be or not to be?" </blockquote>
</body>
```

​	Table:

​	<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240601143630300.png" alt="image-20240601143630300" style="zoom:80%;" />

​	<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240601143917426.png" alt="image-20240601143917426" style="zoom:80%;" />

​	<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240601145816449.png" alt="image-20240601145816449" style="zoom:80%;" />

​	添加 `controls` 属性后，浏览器会在视频或音频元素上显示播放控件。例如：

- 对于 `<video>` 元素，控件包括播放/暂停按钮、音量控制、进度条、全屏按钮等。
- 对于 `<audio>` 元素，控件包括播放/暂停按钮、音量控制、进度条等

​	<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240601151800552.png" alt="image-20240601151800552" style="zoom:80%;" />

​	注释comments： Any text between `<!--  -->` is considered as a comment and will not be displayed in the browser

- **`<link>` 标签**

`<link>` 标签主要用于将 HTML 文档与外部资源相关联。最常见的用法是将文档与样式表（CSS）相关联。`<link>` 标签通常放在 `<head>` 部分，用于指定文档的外部资源，比如样式表、网站图标等。

```html
<link rel="stylesheet" href="styles.css">
```

- `	rel`：表示与外部资源的关系。常用的值包括 `stylesheet`（表示样式表）和 `icon`（表示网站图标）。
- `href`：指定外部资源的 URL



- **`<a>` 标签**

  `<a> `标签（锚点标签）用于创建超链接，它可以将用户导航到另一个网页、文件、电子邮件地址或其他 URL。==href 属性在 <a> 标签中使用，用于指定链接目标的 URL。==

  ```html
  <a href="https://www.example.com">Visit Example.com</a>
  ```

  - `href`：指定链接目标的 URL。
  - `target`：指定链接打开的方式，常用值包括 `_self`（在同一窗口或标签中打开，默认值）、`_blank`（在新窗口或新标签中打开）。

- 

​	**在 HTML 中，通常我们使用自闭合标签来表示不需要包含任何内容的元素。这些元素通常在标记语言中被称为“空元素”或“空标签”。以下是一些常见的自闭合标签：**

1. `<br>`：表示换行。

2. `<img>`：表示图像。

   ```html
   <img src="example.jpg" alt="Example Image">
   ```

3. `<input>`：表示输入框。

   ```html
   <input type="text" name="username" placeholder="Enter your username">
   ```

   `placeholder` 属性是 HTML 表单元素中的一个可选属性，用于在输入框中提供一个提示性的文本，以便用户了解该输入框应该输入什么内容

4. `<hr>`：表示水平分隔线。

5. `<meta>`：表示元数据。

6. `<link>`：表示文档与外部资源的关系。

7. `<base>`：指定页面中所有相对 URL 的基本路径。

8. `<col>`：定义表格列。

9. `<area>`：定义图像映射中的区域。

10. `<embed>`：定义外部的可交互内容或插件。

    

    #### HTML 表单（HTML Form）是网页中用于收集用户输入数据的元素集合。表单通常用于收集用户输入的信息，例如用户名、密码、电子邮件地址等，并将这些信息发送到服务器进行处理。

    一个 HTML 表单通常由 `<form>` 元素和多个输入控件（如文本框、复选框、单选按钮、下拉列表等）组成。

    <img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240601153148233.png" alt="image-20240601153148233" style="zoom:80%;" />

    <img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240601153518227.png" alt="image-20240601153518227" style="zoom:80%;" />

    #### `type` 属性

    - `type` 属性用于指定 `<input>` 元素的输入类型。例如，`type="text"` 表示一个单行文本输入框。
    - 不同的 `type` 值可以生成不同类型的输入字段，如文本框、密码框、复选框、单选按钮等。

    #### `name` 属性

    - `name` 属性用于指定输入字段的名称。在表单提交时，浏览器会将此名称与用户输入的值一起发送到服务器。
    - `name` 属性的值可以在服务器端脚本（如 PHP、Python 等）中用来引用特定的输入字段。

    <img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240601155333870.png" alt="image-20240601155333870" style="zoom:80%;" />

    - `<label for="username">Username:</label>`
      - `for="username"`：`<label>` 标签的 `for` 属性值为 `username`。
      - `<input type="text" id="username" name="username">`：与 `for` 属性值匹配的 `<input>` 元素具有 `id="username"`。
      - 当用户点击“Username”标签时，焦点将自动移到 `id` 为 `username` 的输入框。
    - `<label for="password">Password:</label>`
      - `for="password"`：`<label>` 标签的 `for` 属性值为 `password`。
      - `<input type="password" id="password" name="password">`：与 `for` 属性值匹配的 `<input>` 元素具有 `id="password"`。
      - 当用户点击“Password”标签时，焦点将自动移到 `id` 为 `password` 的输入框。

    <img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240601160404418.png" alt="image-20240601160404418" style="zoom:80%;" />

    #### `<option>` 元素

    - `<option>` 元素用于定义一个下拉列表中的选项。
    - 它通常与 `<select>` 元素一起使用。

    #### `value` 属性

    - `value` 属性为每个选项指定一个值。

    - 这个值通常在表单提交时被发送到服务器。

    - `value` 属性用于指定每个 `<option>` 元素的值。当用户从下拉列表中选择某个选项并提交表单时，这个 `value` 属性的值将作为表单数据的一部分发送到服务器。

      - ```html
        <form action="/submit" method="post">
          <label for="fruits">Choose a fruit:</label>
          <select id="fruits" name="fruits">
            <option value="apple">Apple</option>
            <option value="banana">Banana</option>
            <option value="cherry" selected>Cherry</option>
            <option value="date">Date</option>
          </select>
          <br><br>
          <input type="submit" value="Submit">
        </form>
        
        ```

        - `<option value="apple">Apple</option>`：用户看到的选项文本是“Apple”，如果用户选择这个选项并提交表单，发送到服务器的值是 `apple`。

        - `<option value="banana">Banana</option>`：用户看到的选项文本是“Banana”，如果用户选择这个选项并提交表单，发送到服务器的值是 `banana`。

        - `<option value="cherry" selected>Cherry</option>`：用户看到的选项文本是“Cherry”，如果用户选择这个选项并提交表单，发送到服务器的值是 `cherry`。这个选项被默认选中。

        - `<option value="date">Date</option>`：用户看到的选项文本是“Date”，如果用户选择这个选项并提交表单，发送到服务器的值是 `date`。

        - ### 表单提交时的行为

          如果用户选择了“Banana”，然后提交表单，发送到服务器的数据将包含 `fruits=banana` 这一对键值对。这表示用户选择的水果是香蕉。

          ### 在客户端获取选中的值

          在客户端，你可以使用 JavaScript 获取选中选项的 `value` 值进行处理

          ```javascript
          <script>
          document.getElementById('fruits').addEventListener('change', function() {
            var selectedValue = this.value;
            console.log('Selected value:', selectedValue);
          });
          </script>
          ```

          

    #### `selected` 属性

    - `selected` 属性用于指定默认选中的选项。
    - 在页面加载时，带有 `selected` 属性的选项会被默认选中。

    #### 选项文本

    - 每个选项的文本内容写在 `<option>` 元素的开始和结束标签之间。
    - 这个文本会显示在下拉列表中供用户选择。

    <img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240601160652580.png" alt="image-20240601160652580" style="zoom:80%;" />

    复选框（checkbox）是一种允许用户从多个选项中选择一个或多个选项的表单控件。每个复选框都有一个唯一的 `id` 和 `value` 属性，`label` 元素用于为复选框提供可点击的文本标签。

    ​	<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240601161637071.png" alt="image-20240601161637071" style="zoom:80%;" />

    当用户在表单中选择一个或多个复选框并提交表单时，所有被选中的复选框的 `name` 和 `value` 属性将作为表单数据发送到服务器。例如，如果用户选择了 “Flight” 和 “Bus”，提交的数据将包含 `flight=Flight` 和 `bus=Bus`。

    <img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240601162607282.png" alt="image-20240601162607282" style="zoom:80%;" />

    <img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240601163426601.png" alt="image-20240601163426601" style="zoom:80%;" />

    HTML 结构：

    <img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240601163759096.png" alt="image-20240601163759096" style="zoom:80%;" />

    - **描述意义而非表现**：语义元素主要用于描述页面元素的意义，而不是它们的展示方式。
    - **`<header>`**：定义页面的头部区域，通常包含导航、标题等内容。
    - **`<nav>`**：定义导航栏，用于放置页面导航链接。
    - **`<section>`**：定义文档中的一个区域或节，用于分隔内容。
    - **`<article>`**：定义页面中的独立内容单元，如一篇文章或博客帖子。
    - **`<aside>`**：定义侧栏内容，通常用于放置与主要内容相关的辅助信息。
    - **`<footer>`**：定义页面的底部区域，通常包含版权信息、联系信息等。

#### 	**==Block and inline elements==**

​	![image-20240530202103893](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240530202103893.png)

​	![image-20240601170847331](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240601170847331.png)

### Day 3 

#### 	CSS定义以及基本语法结构

​		![image-20240601173736782](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240601173736782.png)

​	<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240601174511906.png" alt="image-20240601174511906" style="zoom:80%;" />

​	三种不同方式：![image-20240601174638271](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240601174638271.png)

​	![image-20240601175011207](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240601175011207.png)

​	![image-20240601175612661](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240601175612661.png)

​	![image-20240601180320283](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240601180320283.png)

​	![image-20240601180714433](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240601180714433.png)

​	![image-20240601181537492](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240601181537492.png)

- Property color is used to set the colour of the text
- Property background-color is used to set the background color of an element
- Property font-family can be used to set the font of the text
- Property font-size can be used to set the size of the font
  - <img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240601183455882.png" alt="image-20240601183455882" style="zoom:50%;" />

​	<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240601184226140.png" alt="image-20240601184226140" style="zoom:80%;" />

#### 	CSS箱结构：

​	<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240601184837990.png" alt="image-20240601184837990" style="zoom:80%;" />

​	![image-20240601185017046](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240601185017046.png)

​	![image-20240601195113058](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240601195113058.png)

​	![image-20240601195420778](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240601195420778.png)

​	![image-20240601195545111](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240601195545111.png)

​	![image-20240601200649145](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240601200649145.png)

​	CSS position property:

​	![image-20240601201010875](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240601201010875.png)

​	a

​	a

​	a

​	a

​	a

​	a

​	a

### Day 4 

​	sd

#### 	bootstrap 的定义:

​	![image-20240530203948652](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240530203948652.png)

- ​	It provides a simple and unified solution for developers to create interfaces.

- ​	It contains powerful built-in components and is easy to customize.

- ​	It also provides Web-based customization.

- ​	It's open source.

  使用了预定义的CSS风格和脚本![image-20240530210256943](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240530210256943.png)

  ![image-20240530210926613](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240530210926613.png)

  ![image-20240530211719689](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240530211719689.png)

  mm

  

  

### Day 5 

#### 	js的定义 怎么写code

​	JS区分大小写

​	**JavaScript 是一种高级编程语言，通常用于在网页上创建交互效果和动态功能。**它是一种客户端脚本语言，*意味着它在客户端或用户设备上执行*，而不是在服务器上执行。JavaScript 的一些常见用途包括表单验证、创建动画和效果、操作 **DOM（文档对象模型）**以及向服务器发起异步请求。它经常与 HTML 和 CSS 一起使用，用于创建完整功能的 Web 应用程序。

​	![image-20240531173431241](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240531173431241.png)

​	JS可以做什么：

1. **处理用户输入**：

   - JavaScript 可以处理来自表单、按钮和其他 HTML 元素的用户输入。它能够根据这些输入更新页面、触发动画或执行其他操作。

2. **响应用户事件**：

   - JavaScript 可以响应用户的各种事件，如点击、悬停和滚动。这使得网页更加动态和互动。

3. **表单验证**：

   - JavaScript 可以在用户提交表单之前验证输入，确保数据符合特定要求。例如，确保电子邮件地址的格式正确，或密码满足复杂性要求。

4. **修改文档对象模型 (DOM)**：

   - JavaScript 可以修改网页的 DOM，从而动态地改变网页的内容和结构。可以添加、删除或更改 HTML 元素和样式。

   ```js
   <!DOCTYPE html>
   <html>
   <head>
       <title>JavaScript Example</title>
       <style>
           .hidden {
               display: none;
           }
       </style>
   </head>
   <body>
       <h1 id="title">Welcome to My Web Page</h1>
       <button id="changeTitleBtn">Change Title</button>
       <p id="content">This is a paragraph.</p>
   
       <form id="myForm">
           Name: <input type="text" id="nameInput"><br>
           Email: <input type="text" id="emailInput"><br>
           <input type="submit" value="Submit">
       </form>
   
       <script>
           // 修改 DOM 内容
           document.getElementById("changeTitleBtn").addEventListener("click", function() {
               document.getElementById("title").innerHTML = "Title Changed!";
           });
   
           // 表单验证
           document.getElementById("myForm").addEventListener("submit", function(event) {
               let name = document.getElementById("nameInput").value;
               let email = document.getElementById("emailInput").value;
   
               if (name === "") {
                   alert("Name must be filled out");
                   event.preventDefault(); // 阻止表单提交
               } else if (!validateEmail(email)) {
                   alert("Invalid email address");
                   event.preventDefault(); // 阻止表单提交
               }
           });
   
           function validateEmail(email) {
               const re = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
               return re.test(String(email).toLowerCase());
           }
   
           // 响应用户事件
           document.getElementById("content").addEventListener("mouseover", function() {
               this.style.color = "red";
           });
   
           document.getElementById("content").addEventListener("mouseout", function() {
               this.style.color = "black";
           });
       </script>
   </body>
   </html>
   ```

​	<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240603101206373.png" alt="image-20240603101206373" style="zoom:80%;" />

​	放置的方式:

![image-20240531173713219](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240531173713219.png)

​	head:<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240603101645014.png" alt="image-20240603101645014" style="zoom:80%;" />

​	`document` 对象是 DOM 的根节点，表示整个 HTML 文档。通过 `document` 对象，JavaScript 可以访问和操作文档的所有元素、属性和内容。

​	body: <img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240603102434908.png" alt="image-20240603102434908" style="zoom:80%;" />

​	external: <img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240603102507973.png" alt="image-20240603102507973" style="zoom:80%;" />

​	`getElementById` 是 JavaScript 提供的一个方法，用于在 DOM（Document Object Model，文档对象模型）中获取具有指定 ID 的元素。这个方法是 `document` 对象的一部分。

​	**JavaScript 与 DOM 交互:**

JavaScript 通过 DOM 进行网页内容的访问和操作，`getElementById` 只是其中一个方法。以下是一些常用的 DOM 方法和属性：

- **`getElementsByClassName`**：返回包含所有具有指定类名的元素的集合。
- **`getElementsByTagName`**：返回包含所有具有指定标签名的元素的集合。
- **`querySelector`**：返回匹配指定 CSS 选择器的第一个元素。
- **`querySelectorAll`**：返回匹配指定 CSS 选择器的所有元素的集合。

**修改 DOM 内容:**

通过获取 DOM 元素的引用，JavaScript 可以修改其内容和属性，例如：

- **`innerHTML`**：设置或获取元素的 HTML 内容。
- **`textContent`**：设置或获取元素的文本内容（不包含 HTML 标签）。
- **`style`**：设置或获取元素的内联样式。



##### 	JS关键字

​	关键字是 JavaScript 语言中的保留字，它们用于控制代码的结构、逻辑和行为。使用这些关键字可以实现变量声明、条件判断、循环、函数定义等功能。

```js
// 变量声明
var x = 10;
let y = 20;
const z = 30;

// 控制结构
if (x < y) {
    console.log('x is less than y');
} else {
    console.log('x is not less than y');
}

switch (z) {
    case 10:
        console.log('z is 10');
        break;
    case 20:
        console.log('z is 20');
        break;
    default:
        console.log('z is something else');
}

// 循环
for (let i = 0; i < 5; i++) {
    console.log(i);
}

while (x < 15) {
    x++;
}

do {
    y--;
} while (y > 15);

// 函数和类
function greet(name) {
    return `Hello, ${name}`;
}

class Person {
    constructor(name) {
        this.name = name;
    }

    greet() {
        return `Hello, my name is ${this.name}`;
    }
}

const person = new Person('John');
console.log(person.greet());

// 异常处理
try {
    throw new Error('Something went wrong');
} catch (error) {
    console.error(error.message);
} finally {
    console.log('This will always run');
}

```

##### 	statements

​	在 JavaScript 中，语句（Statements）是执行特定操作的代码片段。**语句是 JavaScript 程序的基本构建块，按它们在程序中出现的顺序逐一执行。**JavaScript 语句可以执行各种任务，例如赋值、函数声明、循环、条件判断以及异常处理。

​	<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240603104414702.png" alt="image-20240603104414702" style="zoom:80%;" />

​	<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240603104454817.png" alt="image-20240603104454817" style="zoom:80%;" />

赋值语句

赋值语句用于将值分配给变量。

```javascript
let x = 5;
const y = 10;
var z = x + y;
```

声明函数

函数声明语句用于定义一个函数，该函数可以重复调用。

```javascript
function greet(name) {
    return `Hello, ${name}!`;
}

const greeting = greet("Alice");
console.log(greeting); // 输出: Hello, Alice!
```

循环语句

循环语句用于反复执行一段代码，直到满足特定条件。

```javascript
for (let i = 0; i < 5; i++) {
    console.log(i); // 输出: 0 1 2 3 4
}

let j = 0;
while (j < 5) {
    console.log(j); // 输出: 0 1 2 3 4
    j++;
}
```

条件语句

条件语句用于根据条件执行不同的代码块。

```javascript
let age = 18;

if (age >= 18) {
    console.log("You are an adult.");
} else {
    console.log("You are a minor.");
}

let day = "Monday";

switch (day) {
    case "Monday":
        console.log("It's Monday!");
        break;
    case "Friday":
        console.log("It's Friday!");
        break;
    default:
        console.log("It's some other day.");
}
```

异常处理

异常处理语句用于捕获和处理运行时错误，以防止程序崩溃。

```javascript
try {
    let result = someFunction(); // someFunction 未定义，将抛出错误
} catch (error) {
    console.error("An error occurred:", error.message);
} finally {
    console.log("This will always run.");
}
```

​	JavaScript 语句是编写程序的基本单位，它们按顺序执行，完成各种操作任务。通过组合和嵌套这些语句，可以编写出复杂的逻辑和功能，从而实现强大的应用程序。

##### 	变量

​	![image-20240603104827359](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240603104827359.png)

​	<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240603103808916.png" alt="image-20240603103808916" style="zoom:80%;" />

- `const` 声明的变量是常量，一旦被赋值就不能再被修改。

- `var` 声明的变量是可变的，可以随时重新赋值。

  <img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240603105538970.png" alt="image-20240603105538970" style="zoom:80%;" />

  JavaScript 中的块语句和作用域是理解变量可访问性和生命周期的重要概念。以下是对块语句、全局作用域和局部作用域的详细解释：

  ### 块语句（Block Statements）

  块语句是将一组语句放在一起，并用花括号 `{}` 包围。块语句常用于控制流语句（如 `if`、`for`、`while`）中，以定义一个作用域。

  

  ```javascript
  if (true) {
      let x = 10;
      console.log(x); // 输出: 10
  }
  // console.log(x); // 错误: x is not defined
  ```

  在上面的示例中，`let x = 10;` 被定义在一个 `if` 语句的块中，因此 `x` 只能在该块中访问，块外访问会报错。

  ### 全局作用域（Global Scope）

  全局作用域是指在代码的任何地方都可以访问的变量。这些变量在函数和块语句外部声明。

  

  - 在全局作用域中声明的变量在整个程序的任何地方都可以访问。
  - 在浏览器环境中，全局变量成为 `window` 对象的属性。

  ```javascript
  var globalVar = "I am global";
  
  function exampleFunction() {
      console.log(globalVar); // 输出: I am global
  }
  
  exampleFunction();
  console.log(globalVar); // 输出: I am global
  ```

  ### 局部作用域（Local Scope）

  局部作用域是指变量只能在函数内部或块内部访问，这些变量在函数或块语句内部声明。

  

  - 函数作用域：在函数内部声明的变量只能在函数内部访问。
  - 块级作用域：在块语句（如 `if`、`for` 等）内部使用 `let` 或 `const` 声明的变量只能在该块内部访问。

  ```javascript
  function exampleFunction() {
      let localVar = "I am local";
      console.log(localVar); // 输出: I am local
  }
  
  exampleFunction();
  // console.log(localVar); // 错误: localVar is not defined
  ```

  在上面的示例中，`localVar` 是一个局部变量，它只能在 `exampleFunction` 函数内部访问，在函数外部访问会报错。

  ```javascript
  if (true) {
      let blockVar = "I am block-scoped";
      console.log(blockVar); // 输出: I am block-scoped
  }
  // console.log(blockVar); // 错误: blockVar is not defined
  ```

  在这个示例中，`blockVar` 只能在 `if` 块内部访问，块外访问会报错。

  变量重声明:

  - **可以在函数外部重新声明与函数内部同名的变量，它们不会相互影响，因为它们存在于不同的作用域。**

  ```javascript
  let varName = "outside";
  
  function exampleFunction() {
      let varName = "inside";
      console.log(varName); // 输出: inside
  }
  
  exampleFunction();
  console.log(varName); // 输出: outside
  ```

  在上面的示例中，函数内部的 `varName` 和函数外部的 `varName` 是不同的变量，因为它们位于不同的作用域。

  

  - **块语句**：使用 `{}` 包围的语句组。
  - **全局作用域**：在函数和块语句外部声明的变量，可在整个程序中访问。
  - **局部作用域**：在函数内部或块语句内部声明的变量，只能在该函数或块语句中访问。
  - **变量重声明**：同名变量可以在不同作用域中声明，不会相互影响。

  注释：

  <img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240603111355609.png" alt="image-20240603111355609" style="zoom:80%;" />

  运算：

  <img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240603111705257.png" alt="image-20240603111705257" style="zoom:80%;" />

  <img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240603112056738.png" alt="image-20240603112056738" style="zoom:80%;" />

  <img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240603112630792.png" alt="image-20240603112630792" style="zoom:80%;" />

  <img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240603112755908.png" alt="image-20240603112755908" style="zoom:80%;" />

  <img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240603113038390.png" alt="image-20240603113038390" style="zoom:80%;" />

  <img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240603114023896.png" alt="image-20240603114023896" style="zoom:80%;" />

  <img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240603114907432.png" alt="image-20240603114907432" style="zoom:80%;" />

  ##### 数据类型

  <img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240603115134886.png" alt="image-20240603115134886" style="zoom:80%;" />

  <img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240603115510227.png" alt="image-20240603115510227" style="zoom:80%;" />

  ![image-20240603115625877](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240603115625877.png)

  <img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240603115830022.png" alt="image-20240603115830022" style="zoom:80%;" />

  - `courseName` 是一个变量，它包含字符串 `"JavaScript"`。
  - 在模板字符串中，`${}` 语法用于插入变量或表达式的值。
  - 在这个模板字符串中，`${courseName}` 将被替换为变量 `courseName` 的值，即 `"JavaScript"`。
  - 因此，`text` 变量将被赋值为 `"Welcome to JavaScript!"`。

  模板字符串是一种更灵活和方便的字符串表示方法，特别是在需要拼接多个字符串或嵌入变量时。它们提供了更清晰、更易读的代码，并且可以减少使用字符串连接符（+）的需要。

##### Array

​	![image-20240603120844299](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240603120844299.png)

​	<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240603152523541.png" alt="image-20240603152523541" style="zoom:80%;" />

​	

```js
const array_name = ["item1", "item2", "item3"];
array_name[1] = "newItem"; // 修改数组中的元素值
console.log(array_name); // 输出: ["item1", "newItem", "item3"]
```

在这个例子中，尽管使用了 `const` 关键字声明了 `array_name`，但我们仍然可以修改数组中的元素值。这是因为 `array_name` 常量持有的是数组的引用，而不是数组本身。因此，我们可以修改数组中的内容，但不能将一个新的数组赋给 `array_name`。

对const而言：如果我们尝试重新分配一个新的值给 `array_name`，就会得到一个错误：

```js
array_name = ["newItem1", "newItem2"]; // TypeError: Assignment to constant variable.
```

这是因为我们试图重新分配一个新的数组给常量 `array_name`，这是不允许的。 `const` 声明确保了变量的引用不会被改变，但不会阻止我们修改其引用所指向的对象的内容

​	**数组 `toString()` 方法**

当 `toString()` 方法应用于数组时，它会将数组的每个元素转换为字符串，并用逗号分隔这些元素，然后返回整个字符串。

```js
array.toString()
```

```javascript
let fruits = ["apple", "banana", "orange"];
let fruitsString = fruits.toString();
console.log(fruitsString); // 输出: "apple,banana,orange"
```

​	**`push()`**

- 在数组末尾添加一个或多个元素，并返回新的长度。

  ```javascript
  let fruits = ["apple", "banana"];
  fruits.push("orange"); //这里会返回新的长度
  console.log(fruits); // ["apple", "banana", "orange"]
  ```

​	**`pop()`**

- 移除数组末尾的一个元素，并返回该元素。

  ```js
  let fruits = ["apple", "banana", "orange"];
  let last = fruits.pop(); //如果直接fruits.pop()的话会返回被pop的元素
  console.log(fruits); // ["apple", "banana"]
  console.log(last);   // "orange"
  ```

​	**`concat()`**

- 合并两个或多个数组，并返回一个新的数组。

  ```javascript
  let fruits = ["apple", "banana"];
  let moreFruits = ["orange", "mango"];
  let allFruits = fruits.concat(moreFruits);
  console.log(allFruits); // ["apple", "banana", "orange", "mango"] 
  ```

  ​	**`sort()`**

- 对数组的元素**按照字母的顺序**进行排序并返回此数组。

  ```js
  let fruits = ["orange", "apple", "banana"];
  fruits.sort(); //这样会在控制台直接返回了
  console.log(fruits); // ["apple", "banana", "orange"]
  ```

##### 	IF-else and switch:

​	<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240603155300895.png" alt="image-20240603155300895" style="zoom:67%;" />

​	`if...else if...else` 语句结构是按照顺序逐一检查条件的，一旦某个条件为 `true` 并执行了对应的代码块，后续的条件将不再被检查和执行。这个特性确保了在一个条件链中，只有一个代码块会被执行。

​	swith:

​	<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240603155528254.png" alt="image-20240603155528254" style="zoom:67%;" />

- **`expression`**：要评估的表达式。它的值将与每个 `case` 的值进行比较。
- **`case x`**：如果 `expression` 的值严格等于 `x`(只有在值和类型都相等的情况下，才会认为它们匹配，并执行对应的代码块。)，则执行该代码块。
- **`break`**：用于在执行完一个 `case` 的代码块后，退出 `switch` 语句。如果没有 `break`，程序会继续执行下一个 `case` 代码块。
- **`default`**：如果 `expression` 的值与所有 `case` 的值都不匹配，则执行 `default` 代码块。`default` 是可选的，但通常会包括在内以处理未预见的情况。

`switch` 语句在找到匹配的 `case` 后并不会自动停止，而是继续执行后续的 `case` 代码块，直到遇到 `break` 语句或 `switch` 语句结束。这种行为称为“fall-through”。如果希望在匹配到一个 `case` 后停止执行，必须在代码块末尾使用 `break` 语句。

#### 	==loops 十分重要 怎么用for loop写代码==

​	<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240531174612646.png" alt="image-20240531174612646" style="zoom:80%;" />

##### 	for 循环：

​	

```js
for (initialization; condition; increment/decrement) {
    // code block to be executed
}
```

1. **`initialization`**：`let i = 0;` 初始化循环变量 `i`，并将其设置为 `0`。这部分代码在循环开始前只执行一次。
2. **`condition`**：`i < 5;` 在每次循环迭代之前检查 `i` 是否小于 `5`。如果条件为真，执行循环体内的代码；如果条件为假，退出循环。
3. **`increment/decrement`**：`i++;` 每次循环迭代结束后，将 `i` 的值增加 `1`。
4. **`code block`**：`console.log(i);` 打印当前的 `i` 值。

​	<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240603160204195.png" alt="image-20240603160204195" style="zoom:80%;" />

​	ep:

```js
for (let i = 0; i < 5; i++) {
    console.log(i);
}
```

​	<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240603161134376.png" alt="image-20240603161134376" style="zoom:80%;" />

##### 	WHILE:

​	`while` 循环是一种常用的控制结构，用于在满足特定条件时重复执行代码块。

```javascript
while (condition) {
    // code block to be executed
}
```

1. **`condition`**：条件表达式，在每次循环迭代之前检查该条件。如果条件为真，则继续执行循环体内的代码；如果条件为假，则退出循环。
2. **`code block`**：代码块，这是循环每次迭代时要执行的代码。

ep: 

```js
let i = 1;

while (i <= 5) {
    console.log(i);
    i++;
}
```

**使用场景:**

- 当循环的次数未知，但循环应在满足特定条件时继续执行时，使用 `while` 循环。
- `while` 循环特别适用于需要在每次迭代中动态更新条件的情况。

**注意事项:**

- 确保在循环体内更新条件，以避免无限循环。
- 如果条件始终为真，循环将变为无限循环。在开发时要小心这种情况，以免造成程序崩溃或死锁。

​	<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240603162426274.png" alt="image-20240603162426274" style="zoom:80%;" />

##### Do while:

​	`do...while` 循环是一种与 `while` 循环类似的控制结构，但与 `while` 循环不同的是，`do...while` 循环会先执行一次代码块，然后再检查条件。==这意味着即使条件一开始就为假，代码块也会至少执行一次。==

```js
do {
    // code block to be executed
} while (condition);
```

1. **`code block`**：代码块，这是循环每次迭代时要执行的代码。
2. **`condition`**：条件表达式，在每次循环迭代之后检查该条件。如果条件为真，则继续执行循环体内的代码；如果条件为假，则退出循环。

​	ep:

```js
let i = 1;

do {
    console.log(i);
    i++;
} while (i <= 5);
```

​	<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240603162356810.png" alt="image-20240603162356810" style="zoom:80%;" />

​	`do...while` 循环是一种与 `while` 循环类似的控制结构，但与 `while` 循环不同的是，它会先执行一次循环体内的代码，然后再检查条件。这种特性使其适用于需要至少执行一次循环体内代码的场景。

##### 	For-in loop:

​	s

![image-20240602212724394](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240602212724394.png)

​	`while` 循环在检查条件之前就可能跳过执行代码块，而 `do...while` 循环则保证至少执行一次代码块，然后再检查条件。

1. **for 循环**：
   - **作用**：通过指定初始条件、循环条件和每次迭代之后的操作来迭代一个范围内的值。

   - **语法**：

     ```js
     for (initialization; condition; increment/decrement) {
         // code block
     }
     
     ```

   - **示例**：

     ```javascript
     for (let i = 0; i < 5; i++) {
         console.log(i);
     }
     ```

2. **while 循环**：

   - **作用**：在条件为真时重复执行一个代码块。

   - **语法**：	

     ```javascript
     while (condition) {
         // code block
     }
     
     ```

   - **示例**：

     ```javascript
     let i = 0;
     while (i < 5) {
         console.log(i);
         i++;
     }
     
     ```

3. **do...while 循环**：
   - **作用**：类似于 while 循环，但是无论条件是否为真，它至少执行一次代码块。
   
   - **语法**：

     ```js
     do {
         // code block
     } while (condition);
     ```
   
     
   
   - **示例**：
   
     ```js
     let i = 0;
     do {
         console.log(i);
         i++;
     } while (i < 5);
     ```
   
4. **for...in 循环**：
   - **作用**：用于遍历对象的==可枚举属性==。
   
   - **语法**：

     ```js
     for (variable in object){ 
     	// code block 
     }
     ```
   
   - **示例**：
   
     ```js
     const person = { name: 'John', age: 30 };
     for (let key in person) {
         console.log(key + ': ' + person[key]);
     }
     ```
   
     
   
5. **for...of 循环**：
   
   - **作用**：用于遍历==可迭代对象的值==，如数组、字符串等。
   
   - **语法**：
   
     ```js
     for (variable of iterable) { 
     	// code block
     }
     ```
   
   - **示例**：
   
     ```js
     const arr = ['a', 'b', 'c'];
     for (let value of arr) {
         console.log(value);
     }
     ```
   
     

### Day 6 

#### function

​	<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240603100335478.png" alt="image-20240603100335478" style="zoom:80%;" />

​	s

​	s

#### 	==global scope/local scope十分重要（至少2个问题） 定义==

​	

#### 	对于code知道什么是global/local 变量

​	在 JavaScript 中，变量的作用域可以是全局作用域（global scope）或局部作用域（local scope）。**全局作用域中的变量在整个程序中都是可见和可访问的，而局部作用域中的变量只在定义它们的代码块（通常是函数）内部可见和可访问。**

​	创建全局变量：

全局变量是在全局作用域内声明的变量。可以在任何地方声明全局变量，通常在代码的顶层（在任何函数之外）进行声明。使用以下方法创建全局变量：

​	1:**使用 var 关键字**：

```js
var globalVariable = 'This is a global variable';
```

​	2.**在 window 对象上添加属性**（在浏览器环境中）：

```js
window.globalVariable = 'This is a global variable';
```

创建局部变量：

局部变量是在局部作用域内声明的变量。局部变量只在定义它们的函数内部或块级作用域内部可见。使用以下方法创建局部变量：

​	1.**使用 let 或 const 关键字**：

```js
function exampleFunction() {
    let localVariable = 'This is a local variable';
}
```

​	2.**在函数内部声明变量**：

```js
function exampleFunction() {
    var localVariable = 'This is a local variable';
}
```



#### 	js 知道怎么写function（以及里面的所有方法） 以及定义 (如果用别的方法展示知道也是一个function)

#### 	知道js的objects （定义 目的等）

#### 	知道class和object的不同 （重要）

### ==Day 7== 

#### 	==callback是最重要的（至少3）== 

#### 	识别function里面哪些是callback function 什么时候可以用/怎么用

#### 	json 的定义/目的

### Day 8 

#### 	dom 定义/目的

#### 	

​	

### Day 9 

#### 	node.js 的异步怎么用 异步方式是什么（可能又要回归callback)p6开始

### Day 10 

#### 	socket.io 定义目的 知道是干什么用的

​	<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240602211257257.png" alt="image-20240602211257257" style="zoom:80%;" />

​	<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240602211608299.png" alt="image-20240602211608299" style="zoom:80%;" />

​	<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240602211853896.png" alt="image-20240602211853896" style="zoom:80%;" />

​	<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240602211926503.png" alt="image-20240602211926503" style="zoom:80%;" />

​	*Socket.IO 是一个用于实时 web 应用程序的 JavaScript 库，*它实现了 WebSocket 协议并提供了许多高级功能，如自动重连、心跳检测、事件机制等。Socket.IO 使得在客户端（通常是浏览器）和服务器之间实现低延迟、双向和基于事件的通信变得简单而高效。

​	目的和用途：

**Socket.IO 的主要目的是简化实时、双向通信的实现，使得客户端和服务器之间可以高效地传输数据。**它提供了一套易于使用的 API，帮助开发者快速构建实时功能强大的 Web 应用程序。以下是 Socket.IO 的主要用途和目的：

1. **实时通讯**：
   - **聊天应用**：如即时消息应用、客户支持聊天系统等。Socket.IO 可以实现实时的消息传递，确保用户之间的对话是即时的。
   - **通知系统**：如实时通知和警报系统。Socket.IO 可以用来实时推送通知给用户，例如新邮件提醒、系统更新等。
2. **协作工具**：
   - **实时协作编辑**：如多人同时编辑文档或代码的应用。Socket.IO 可以确保所有参与者看到的内容是同步的。
   - **白板应用**：支持多个用户同时在一个画布上绘图和注释。
3. **实时数据流**：
   - **仪表板和监控系统**：如实时更新的业务数据仪表板、股票行情图等。Socket.IO 可以确保数据实时刷新，用户无需手动刷新页面。
   - **物联网（IoT）**：实时收集和展示传感器数据，监控设备状态等。
4. **在线游戏**：
   - **多人游戏**：如需要实时同步玩家动作和状态的在线多人游戏。Socket.IO 可以用来实现低延迟的玩家互动和数据同步。
   - **游戏房间和匹配系统**：创建和管理游戏房间，匹配玩家等。
5. **直播和互动**：
   - **视频和音频直播**：实现低延迟的视频和音频直播，以及观众的实时互动。
   - **实时问答和投票**：在直播或会议中进行实时问答和投票互动。
6. **其他实时应用**：
   - **地理位置共享**：实时共享用户的地理位置，例如打车应用中的司机和乘客位置更新。
   - **在线教育**：实时课堂互动，教师和学生之间的即时交流。

### Day 11 

#### 	automated test 重要 定义目的 用处（好处是什么）

​	

#### 	==jest的scenarios很重要（至少2个要） 要知道jest的output （对于错误的output是什么）p39（这一页非常重要 比如选择题）==

### Day 12 

#### 	知道关系/non关系数据库的定义 

#### 	知道所有关于database的概念的定义 （结合了很多知识点）

### Day 13 

#### 	概念简述

<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240602190434800.png" alt="image-20240602190434800" style="zoom:80%;" />![image-20240602203238190](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240602203238190.png)

![image-20240602203238190](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240602203238190.png)

**文档数据库**:

*MongoDB中的记录是一个文档，它是由数据结构组成的 字段和值对。*MongoDB文档类似于JSON 对象。字段的值可以包括其他文档、数组、 和文档数组。

​	![MongoDB 文档。](https://www.mongodb.com/docs/manual/images/crud-annotated-document.bakedsvg.svg)

使用文档的优点是：

- 在许多编程中，文档对应于本机数据类型 语言。
- 嵌入式文档和数组减少了对昂贵连接的需求。
- 动态架构支持流畅的多态性。



​	不同的模式适用于不同的应用类型

多态模式

示例：

在一个产品目录系统中，不同类型的产品具有一些共同的属性（如名称、价格、描述等），但也有一些特定于每种产品类型的属性（如尺寸、颜色、重量等）。通过多态模式，可以将这些共同的属性和特定的属性进行灵活管理，从而更好地组织和查询产品数据。

​	**多态模式是一种适用于集合中文档具有相似但不完全相同结构的情况的数据建模模式。**通过将文档的共同字段和特定子文档进行合理划分和管理，多态模式提高了数据建模的灵活性、查询效率和可扩展性，使得数据处理更加方便和高效。

​	ep: 对于职业运动员的记录既有相似之处也有不同之处。使用多态模式，我们可以很容易地适应这些差异。如果不使用多态模式，我们可能会有一个保龄球运动员的集合和一个网球运动员的集合。当我们想询问所有运动员时，我们需要进行耗时且复杂的连接操作（join）。相反，由于我们使用了多态模式，*我们所有的数据都存储在一个运动员集合中，通过一个简单的语句就可以完成对所有运动员的查询。*

当文档具有更多的相似性而不是差异性时，就会使用多态模式。这种模式设计的典型用例是：

- 单一视图应用程序
- 内容管理
- 移动应用程序
- 产品目录

​	<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240602190644145.png" alt="image-20240602190644145" style="zoom:80%;" />

​	<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240602191007203.png" alt="image-20240602191007203" style="zoom:80%;" />

#### attribute pattern

​	**属性模式（Attribute Pattern）适用于具有大量相似字段的大型文档，其中一部分字段具有共同特征**。这种模式特别适合处理那些只有在文档的一个小子集中需要进行排序的字段。

适用条件：

- 我们有一些大文档，它们有很多相似的字段，而这些字段的一个子集具有共同的特征，我们希望对该子集字段进行排序或查询；
- 我们需要排序的字段只能在一小部分文档中找到；

​	示例：

在一个电子商务网站中，产品信息存储在大型文档中。每个产品都有一组共同的属性，如名称、价格、描述等。此外，一部分产品可能具有特殊属性，如尺寸、颜色等，这些特殊属性只在少数产品中出现，并且需要进行排序。*通过属性模式，可以将共同属性和特殊属性分开管理，提高数据管理的效率。*

属性模式是一种有效管理大型文档中相似字段的数据建模模式。通过将具有共同特征的字段归类和管理，可以提高数据组织的效率，降低排序操作的开销，并提升数据管理的灵活性和可维护性。

​	<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240602191454665.png" alt="image-20240602191454665" style="zoom:80%;" />

​	原本的样子需要查询很多次（SELECT)才可以查完 <img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240602191647373.png" alt="image-20240602191647373" style="zoom:50%;" />

​	改成这样就可以减少。使用属性模式，我们可以将此信息移至数组中并减少对索引需求。我们将这些信息转换成一个包含键值对的数组：<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240602191720014.png" alt="image-20240602191720014" style="zoom:50%;" />

属性模式针对每个文档中许多类似字段提供了更简单的文档索引。**通过将这个数据子集移动到一个键值子文档中，我们可以使用不确定的字段名，为信息添加额外的限定符，并更清楚地说明原始字段和值的关系。**当我们使用属性模式时，由于需要的索引更少，查询变得更简单更快。

#### 	bucket schema design十分重要 用处是什么

​	**桶模式（Bucket Pattern）是一种用于实时分析的数据建模模式，适用于一段时间内流动的数据，**通常指时间序列数据。在桶模式中，数据被分成不同的时间段，并存储在相应的文档中，以便进行实时分析、预测、发现历史趋势以及优化数据存储

​	通过将数据按时间划分存储在不同的桶中，可以清晰地组织数据、减少文档数量、优化数据存储结构，帮助用户进行实时分析、预测未来趋势和优化数据存储。

​		![image-20240602192401539](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240602192401539.png)

​	<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240602192738246.png" alt="image-20240602192738246" style="zoom:80%;" />

​	<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240602192752931.png" alt="image-20240602192752931" style="zoom:80%;" />

​	**使用桶模式，我们将数据“封装”到一个小时的桶中。**这个特定的数据流仍然在增长，因为它目前只有42个测量值；这个小时还有更多的测量值要添加到“桶”中。当它们添加到**measurements**数组中时，**transaction_count**将增加，并且**sum_temperature**也将更新。

有了预先聚合的**sum_temperature**值，就可以很容易拉出一个特定的存储桶并确定该桶的平均温度（**sum_temperature** / **transaction_count**）。在处理时间序列数据时，知道2018年7月13日加利福尼亚州康宁市下午2:00至3:00的平均温度通常比知道下午2:03那一时刻的温度更有意义也更重要。**通过用桶组织数据并进行预聚合，我们可以更轻松地提供这些信息。**

ep:	有一个Bosch的物联网实现可以成为时间序列数据在现实世界中体现价值的一个例子。他们将MongoDB和时间序列数据应用于一个汽车业的数据程序中。该应用程序从整个车辆的各种传感器中获取数据，从而提高车辆本身的诊断能力和部件性能。

#### 	13.2

​	<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240602203457239.png" alt="image-20240602203457239" style="zoom:80%;" />

​	<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240602203519906.png" alt="image-20240602203519906" style="zoom:80%;" />

​	<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240602203549905.png" alt="image-20240602203549905" style="zoom:80%;" />

​	<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240602203648299.png" alt="image-20240602203648299" style="zoom:80%;" />

​	<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240602203721969.png" alt="image-20240602203721969" style="zoom:80%;" />

### Day 14 

#### 	网络安全概念

​	![image-20240602165425841](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240602165425841.png)

​	![image-20240602165517722](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240602165517722.png)

​	一些方法：<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240602165606833.png" alt="image-20240602165606833" style="zoom:80%;" />

#### 	symmetric/public key要知道是什么

##### 	1. 对称加密（Symmetric Encryption）：

**基本原理**

**对称加密使用相同的密钥进行加密和解密**。这意味着加密和解密的双方必须共享同一个密钥，并确保密钥的安全性。如果密钥泄露，任何人都可以解密数据。

**加密过程**

1. **密钥生成**：生成一个随机的密钥，长度可以是128位、192位或256位等，具体取决于使用的加密算法。
2. **加密数据**：使用密钥和加密算法（如AES、DES、3DES）将明文数据加密为密文。
3. **传输密钥和密文**：将密文和密钥传输给接收方。密钥需要通过安全的渠道传输。
4. **解密数据**：接收方使用相同的密钥和加密算法，将密文解密回明文。

- **AES（Advanced Encryption Standard）**：一种常用的对称加密算法，广泛应用于各种安全协议和应用中。

![image-20240602170458164](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240602170458164.png)

##### 	2. 非对称加密（公钥）（Public-Key Cryptography）

**基本原理**

**公钥密码学使用一对密钥：公钥和私钥**。公钥可以公开，任何人都可以使用公钥加密数据，但只有拥有对应私钥的人才能解密数据。这种方法解决了对称加密中密钥传输的安全问题。

加密过程

1. **密钥生成**：生成一对密钥，公钥和私钥。公钥可以公开，而私钥必须保密。
2. **发布公钥**：将公钥分发给任何需要加密数据的人。
3. **加密数据**：发送方使用接收方的公钥和加密算法（如RSA、ECC）将明文数据加密为密文。
4. **传输密文**：将密文传输给接收方。
5. **解密数据**：接收方使用自己的私钥和加密算法，将密文解密回明文

- **RSA（Rivest-Shamir-Adleman）**：一种常用的公钥加密算法，广泛应用于安全通信和数字签名。

##### 	![image-20240602170952244](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240602170952244.png)

​	例子：

<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240602171050279.png" alt="image-20240602171050279" style="zoom:67%;" />



#### 	==Phishing attack 非常重要 定义 如何解决这个问题 （一个选择）==

​	常见客户端安全威胁：

​	![image-20240602161514793](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240602161514793.png)

​	**Phishing Attack**：

​	钓鱼攻击是一种网络攻击形式，攻击者伪装成可信赖的实体，诱骗受害者泄露敏感信息，如用户名、密码、信用卡号码等。通常，这些攻击通过电子邮件、短信、伪造网站或社交媒体平台进行。

​	措施：

​	![image-20240602162312127](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240602162312127.png)

防范钓鱼攻击：

**安全的网络浏览习惯**

- 避免访问可疑网站
- - **检查URL**：确保你访问的网站URL是正确的，特别是那些需要输入敏感信息的网站。
  - **HTTPS**：优先访问使用HTTPS协议的网站，这表示数据传输是加密的。

- 不点击未知链接
- - **悬停检查**：将鼠标悬停在链接上，查看实际的目标地址。确保它是合法和可信的。
  - **拒绝点击可疑链接**：即使链接看起来来自熟悉的联系人，如果感到可疑，最好不点击。

- 下载文件需谨慎
- - **来源可靠**：只从可信的来源下载文件，如官方应用商店或官方网站。
  - **病毒扫描**：下载文件后，使用防病毒软件进行扫描，以确保文件安全。


 **使用安全工具**

- 反钓鱼和防病毒软件
  - **安装和更新**：安装反钓鱼插件和防病毒软件，并保持其更新，以检测和阻止钓鱼攻击。
  - **实时保护**：启用实时保护功能，阻止恶意网站和下载。

- 防火墙和安全设置
  - **启用防火墙**：保护网络免受未经授权的访问。
  - **安全设置**：定期检查和更新设备和浏览器的安全设置。

**谨慎对待电子邮件**

- 验证发件人
  - **检查邮件地址**：仔细检查邮件地址，确保它来自可信的来源。
  - **怀疑内容**：如果邮件内容令人怀疑（如紧急请求、过于诱人的报价等），不要立即行动。

- 不打开未知附件
  - **扫描附件**：如果需要打开附件，先用防病毒软件扫描。
  - **避免敏感操作**：不要通过邮件提供敏感信息，如密码或银行信息。

### Day 15

#### 	*Web accessibility* means that websites and web applications are designed so that people with disabilities or other constraints can use them.

​	<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240601171457297.png" alt="image-20240601171457297" style="zoom:80%;" />

​	Disabilities 的分类：

#### 	**temporary disability 十分重要 知道暂时性残障是怎样的 定义以及例子（会有一个选择）**

​		**暂时性残疾（temporary disability）**是指用户在某一段时间内由于某种原因（如受伤或生病）而暂时失去某些功能或能力，从而影响其与Web内容互动的能力。这些残疾并不是永久性的，随着时间的推移或康复，这些障碍会消失。

​	例子

1. **手部受伤**

   - **情景**：一个人在滑雪时摔伤了手腕，需要用石膏固定。
   - **影响**：无法使用鼠标或键盘进行精细的操作。
   - **解决方法**：提供语音控制或屏幕阅读器支持，允许用户使用语音命令或键盘快捷键进行导航。

2. **眼部感染或手术后**

   - **情景**：一个人接受了眼部手术，需要几天时间恢复视力。
   - **影响**：视力模糊，难以阅读屏幕上的文字。
   - **解决方法**：使用大字体、高对比度模式，以及屏幕阅读器。

3. **声音嘶哑或失声**

   - **情景**：一个人患了喉炎，暂时失去了说话的能力。
   - **影响**：无法使用语音识别软件进行输入。
   - **解决方法**：提供其他输入方式，如键盘输入或触摸输入。

4. **耳部感染或听力损失**

   - **情景**：一个人因耳部感染暂时失去了听力。
   - **影响**：无法听到音频内容或视频中的声音。
   - **解决方法**：提供字幕和转录服务，确保音频内容有文本替代。

5. **手部手术或受伤**

   - **情景**：一个人进行了手部手术，需要一段时间才能恢复使用手指。
   - **影响**：打字速度变慢或无法使用键盘。
   - **解决方法**：支持语音输入和屏幕阅读器，允许用户使用语音进行操作。

   环境残障是指用户在特定环境中由于周围条件的限制而无法正常使用计算机和网络。*这些障碍不是由用户的身体状况引起的，而是由于环境因素导致的。*

   - **暂时性残疾**：在用户康复后，这些障碍会消失。
   - **环境残障**：当用户离开特定环境后，这些障碍会消失。

​	<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240601171717577.png" alt="image-20240601171717577" style="zoom:80%;" />

​	<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240601171842019.png" alt="image-20240601171842019" style="zoom:80%;" />

​		 <img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240601172223670.png" alt="image-20240601172223670" style="zoom:80%;" />

​	可行性四个原则：<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20240601173435938.png" alt="image-20240601173435938" style="zoom:80%;" />





### 垃圾箱///

#### 1、常见的应用层协议有哪些？各层协议有哪些主要代表，分别是实现了什么功能？

	在网络通信中，协议被分成不同的层次，每层负责特定的功能。这种分层结构最常见的是OSI（Open Systems Interconnection）模型和TCP/IP模型。以下是常见的应用层协议以及各层协议的主要代表和功能。

常见的应用层协议

应用层是OSI和TCP/IP模型中最顶层，直接为用户提供网络服务。常见的应用层协议包括：

1. **HTTP（HyperText Transfer Protocol）**:
   - 用途：用于万维网数据传输，主要用于网页浏览。
   - 特点：无状态，使用TCP端口80。

2. **HTTPS（HTTP Secure）**:
   - 用途：是HTTP的安全版本，通过SSL/TLS加密数据(Encrypt data over SSL/TLS)。
   - 特点：安全，使用TCP端口443。

3. **FTP（File Transfer Protocol）**:
   - 用途：用于文件传输。
   - 特点：使用两个端口（控制端口21和数据端口20），支持不同传输模式（主动和被动模式）。

4. **SMTP（Simple Mail Transfer Protocol）**:
   - 用途：用于发送电子邮件。
   - 特点：使用TCP端口25。

5. **IMAP（Internet Message Access Protocol）**:
   - 用途：用于电子邮件读取和管理。
   - 特点：支持邮箱的多种操作，使用TCP端口143。

6. **POP3（Post Office Protocol 3）**:
   - 用途：用于电子邮件的下载。
   - 特点：简单的邮件读取协议，使用TCP端口110。

7. **DNS（Domain Name System）**:
   - 用途：将域名解析为IP地址。
   - 特点：使用UDP端口53。

8. **DHCP（Dynamic Host Configuration Protocol）**:
   - 用途：动态分配IP地址。
   - 特点：使用UDP端口67和68。

9. **Telnet**:
   - 用途：远程登录和管理。
   - 特点：使用TCP端口23，数据未加密。

10. **SSH（Secure Shell）**:
    - 用途：安全的远程登录和管理。
    - 特点：使用TCP端口22，数据加密。

各层协议及其主要代表和功能

OSI模型分为七层，每层协议及其主要功能如下：

1. **物理层（Physical Layer）**：
   - 功能：定义物理设备标准，包括电缆、集线器等。
     - **以太网（Ethernet）**：定义了电缆类型、信号标准、接口等，确保数据能通过物理媒介进行传输。
  - **光纤（Fiber Optics）**：利用光脉冲传输数据，提供高速、长距离的数据传输。
     - **Wi-Fi**：无线通信标准，利用无线电波进行数据传输。

2. **数据链路层（Data Link Layer）**：
   - 功能：提供节点到节点的数据传输，定义帧格式。
     - **以太网（Ethernet）**：规定了帧结构、地址（MAC地址）、数据封装和解封装，提供错误检测。
  - **PPP（Point-to-Point Protocol）**：用于点对点链路上的数据传输，提供链路控制、认证和错误检测。

3. **网络层（Network Layer）**：
   - 功能：负责数据包传输，包括路由选择和逻辑地址（IP地址）的管理。
     - **IP（Internet Protocol）**：提供数据包的路由和地址管理，是互联网的核心协议。
  - **ICMP（Internet Control Message Protocol）**：用于诊断和报告网络通信错误（如ping命令）。
     - **ARP（Address Resolution Protocol）**：将IP地址解析为物理地址（MAC地址）。

4. **传输层（Transport Layer）**：
   - 功能：提供端到端的通信服务，包括错误检测和流量控制。
     - **TCP（Transmission Control Protocol）**：提供可靠的连接，确保数据按顺序、无误地传输。
  - **UDP（User Datagram Protocol）**：提供无连接的传输服务，数据包可以快速传输，但不保证可靠性。

5. **会话层（Session Layer）**：
   - 功能：管理会话，建立、维护和终止通信会话。
     - **NetBIOS（Network Basic Input/Output System）**：提供网络通信和会话管理。
  - **RPC（Remote Procedure Call）**：允许程序调用远程服务器上的程序。

6. **表示层（Presentation Layer）**：
   - 功能：数据的翻译、加密和压缩。
     - **SSL/TLS（Secure Sockets Layer/Transport Layer Security）**：提供数据加密，确保传输安全。
  - **MIME（Multipurpose Internet Mail Extensions）**：用于电子邮件中的多媒体数据格式化和编码。

7. **应用层（Application Layer）**：
   - 功能：**负责直接为用户和应用程序提供网络服务，通过一系列协议实现数据表示、消息格式化、资源共享和应用服务等功能**。(**Responsible for providing network services directly to users and applications**, through a series of protocols to achieve data representation, message formatting, resource sharing and application services and other functions)它是用户和网络之间的桥梁，使各种网络应用能够顺利运行并满足用户需求。
     - **HTTP（HyperText Transfer Protocol）**：用于万维网的数据传输，主要用于网页浏览。
     - **FTP（File Transfer Protocol）**：用于文件传输。
     - **SMTP（Simple Mail Transfer Protocol）**：用于发送电子邮件。
     - **DNS（Domain Name System）**：将域名解析为IP地址。

TCP/IP模型简化为四层：

1. **网络接口层（Link Layer）**：
   - 功能：对应OSI模型的物理层和数据链路层。
   - 代表协议/技术：以太网（Ethernet）、Wi-Fi。

2. **网络层（Internet Layer）**：
   - 功能：对应OSI模型的网络层，负责路由和逻辑地址。
   - 代表协议/技术：IP（IPv4、IPv6）、ICMP、ARP（Address Resolution Protocol）。

3. **传输层（Transport Layer）**：
   - 功能：提供端到端的通信和数据传输服务。
   - 代表协议/技术：TCP、UDP。

4. **应用层（Application Layer）**：
   - 功能：对应OSI模型的应用层、会话层和表示层，为用户提供应用服务。
   - 代表协议/技术：HTTP、FTP、SMTP、DNS等。

网络协议按层次分为多个功能层，每层负责特定的网络功能。从物理传输到应用服务，每层都有特定的协议来实现其功能。常见的应用层协议如HTTP、FTP、SMTP等，直接服务于用户，而底层协议如IP、TCP、以太网等则支持基础的网络通信和数据传输。

#### 2、DNS的作用；

1. **域名解析 (Domain Name Resolution)**

   - **将域名转换为IP地址 (Translate domain names into IP addresses)**：DNS的核心功能是将人类可读的域名（如 www.example.com）解析为机器可读的IP地址（如 192.0.2.1）。这是因为*网络通信依赖于IP地址*，而人类更容易记住和使用域名。

2. **负载均衡 (Load Balancing)**

   - **流量分配 (Distribute traffic)**：通过DNS轮询技术，可以将用户请求分配到多个服务器上，从而实现负载均衡。这有助于提高服务的可用性和性能。
   - **地理位置分配 (Geographical traffic distribution)**：基于地理位置的DNS可以将用户请求定向到地理上更近的服务器，减少延迟，提高访问速度。

3. **服务发现 (Service Discovery)**

   - **查找网络服务 (Locate network services)**：某些应用和服务使用DNS来发现网络上的其他服务。例如，电子邮件服务器使用DNS的MX记录来查找邮件交换服务器。
   - **分布式服务架构 (Distributed service architecture)**：微服务架构中，DNS有助于不同服务之间的动态发现和通信。

4. **反向解析 (Reverse Lookup)**

   - **从IP地址到域名 (Translate IP addresses into domain names)**：反向DNS解析（rDNS）将IP地址解析为域名。这在网络日志分析、邮件服务器配置等情况下非常有用。
   - **验证和追踪 (Verification and tracking)**：反向解析可以帮助识别和验证访问者或邮件来源，提高安全性和可追溯性。

#### 3、HTML语法：block和inline元素的区别、基本语法规则等；

#### 4、Bootstrap的原理和作用；

1. **原理**

**响应式网格系统 (Responsive Grid System)**:

- **原理**: Bootstrap 使用一个包含 12 列的响应式网格系统，这允许开发者创建复杂的布局。通过调整列的宽度和位置，网格系统可以在不同的屏幕尺寸和设备上自动重新排列。
- **作用**: 确保网页在各种设备上都有良好的显示效果，从小屏幕的手机到大屏幕的桌面显示器。

**预定义的 CSS 类 (Predefined CSS Classes)**:
- **原理**: Bootstrap 提供了一系列预定义的 CSS 类，用于快速应用常见的样式和布局。例如，有用于按钮、表格、表单、导航栏等的类。
- **作用**: 简化了开发过程，减少了编写自定义 CSS 的需要，加速开发速度。

**组件 (Components)**:
- **原理**: Bootstrap 包含一组常见的用户界面组件，如导航栏、模态框、标签页、警告框等，这些组件是使用 HTML、CSS 和 JavaScript 构建的。
- **作用**: 提供了即插即用的 UI 组件，使开发者可以轻松地添加复杂的功能和样式到网页中，而无需从头开始构建。

**JavaScript 插件 (JavaScript Plugins)**:
- **原理**: Bootstrap 附带了一些 JavaScript 插件，用于实现动态行为和交互功能，如模态框、轮播图、工具提示等。
- **作用**: 增强了网页的互动性和用户体验，减少了开发者编写复杂 JavaScript 代码的工作量。

**响应式实用工具 (Responsive Utilities)**:
- **原理**: 提供了一组用于显示和隐藏内容的实用工具类，这些类可以根据设备的屏幕尺寸来调整内容的可见性。

- **作用**: 帮助开发者根据设备类型和屏幕尺寸调整网页内容的显示，优化用户体验。

  

2. **作用**

**快速开发 (Rapid Development)**:
- **作用**: 通过使用预定义的样式和组件，开发者可以更快地构建和部署网页和应用程序，大大缩短开发周期。

**一致性 (Consistency)**:
- **作用**: Bootstrap 提供了一致的设计规范和组件，确保应用的各个部分在视觉和交互上保持一致，提升用户体验。

**跨浏览器兼容性 (Cross-Browser Compatibility)**:
- **作用**: Bootstrap 经过详细的测试和优化，能够在现代浏览器（如 Chrome、Firefox、Safari、Edge 等）中表现良好，减少了开发者处理浏览器兼容性问题的负担。

**响应式设计 (Responsive Design)**:
- **作用**: 通过响应式网格系统和实用工具，开发者可以轻松创建适应不同屏幕尺寸和设备的网页，提升用户在移动设备上的体验。

**社区支持 (Community Support)**:
- **作用**: Bootstrap 拥有庞大的社区和丰富的资源，包括文档、教程、插件等，开发者可以从中获得帮助和灵感。

**开源 (Open Source)**:
- **作用**: 作为一个开源项目，Bootstrap 可以自由使用、修改和分发，这使得它成为一个灵活且可定制的工具。

Bootstrap 是一个强大的前端框架，通过其响应式网格系统、预定义的 CSS 类、组件和 JavaScript 插件，使得网页和应用程序的开发更加快速和高效。它不仅提供了开发一致性和跨浏览器兼容性，还增强了用户体验，特别是在移动设备上。Bootstrap 的庞大社区和开源性质也为开发者提供了丰富的资源和支持。

#### 5、JavaScript：对象的特性和使用、基本语法规则等；

#### 6、JSON格式及其典型应用实例；

#### 7、DOM模型的原理和作用；

#### 8、Node.js:异步程序（asynchronous programs）如何实现、

#### 9、Socket.IO的原理和基本使用；

#### 10、Web应用的自动测试；尤其熟悉一下Jest的一些测试功能和实例；Marick's matrix;

#### 11、关系型和非关系型数据库的定义、基本原理；尤其NoSQL；

#### 12、Temporary disability包含哪些；

#### 13、Attribute-Based Access Control；

#### 14、如何防范钓鱼攻击；

#### 15、对称加密和非对称加密（公钥）基本原理、通信过程；

#### 16、CSS的基本使用、原理等；

=======(上面是选择题、填空题（给定术语选择填空位置），复习策略自行决定)=======

#### 1、HTML+CSS的简单网页（熟悉语法规则细节、渲染效果，能对给定的代码进行纠错）；

#### 2、JavaScript基本使用（熟悉语法规则细节，能对给定的代码进行纠错、改写，能预判程序执行的结果，能分析代码的基本功能）；