与主题 [inside](https://github.com/ike-c/hexo-theme-inside) 兼容版本
在 `layout/index.js` line 28: [<%- theme_static('js') -%>](https://github.com/ike-c/hexo-theme-inside/blob/ef9df78191ce2a89ba4b4d89b2679a956a255233/layout/index.ejs#L28) 前添加
```
<%- js("https://cdnjs.cloudflare.com/ajax/libs/jquery/3.3.1/jquery.min.js") %>
<%- js("lib/crypto-js") %>
<%- js("lib/blog-encrypt") %>
<%- css("css/blog-encrypt") %>
```
