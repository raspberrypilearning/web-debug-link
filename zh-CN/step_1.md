请记住，`<a>`（anchor）标签用于创建到另一个网页的链接（而不是“link”标签，后者用于链接到字体等资源）。

还要检查 `href` 属性的网址（URL）是否正确。

网址中域名后面的部分（例如“projects.raspberrypi.org”）区分大小写，因此你需要确保大写字母匹配。

此示例使用正确的 HTML 链接到在新浏览器选项卡中打开的网页：

--- code ---
---
language: HTML
filename: index.html
line_numbers: false
---

<a href="https://projects.raspberrypi.org/zh-CN/raspberrypi/web-intro" target="_blank">制作一个像这样的网页！</a>

--- /code ---
