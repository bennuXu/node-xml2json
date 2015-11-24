##xml2json Node.js Library
基于Node.js版的xml to json

### 使用方法：  
安装：  
<pre>
$ npm install -g node-xml2json
</pre>

使用：  
<pre>
var xml2json = require(&quot;node-xml2json&quot;);
var xml      = &quot;&lt;xml&gt;hello&lt;/xml&gt;&quot;;
var json     = xml2json.parser( xml );
console.log( json.xml )
</pre>

详细用法：  
[http://www.thomasfrank.se/xml_to_json.html](http://www.thomasfrank.se/xml_to_json.html)

测试：  
<pre>
..\node_modules\node-xml2json\test\node test.js
</pre>

## 更新日志：
version 1.0.0 [2015-11-22]
* 在[https://github.com/Kenshin/js-pagination](https://github.com/Kenshin/js-pagination)的基础上，修改长数字字符串转换的问题
* xml对象转换Json对象

## 版权和许可：
Licensed under MIT or GPL Version 2 licenses
