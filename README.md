bk-readability
==============

bokan's readability.what is the tools only i used.

用来提取网页的主要内容区域。代码摘自evernote悦读，目前仅供自己测试使用。

### 下面是一个简单的例子

var app = require('bk-readability');
app.getHTMLByURL("http://www.open-open.com/lib/view/open1330790006405.html",function (html,title,doc) {
  console.log(html);
  console.log(title);

})
