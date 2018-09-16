# jquery-i18n

### 前端Jq国际化 配置

``` js
jQuery.i18n.properties({    // 加载资浏览器语言对应的资源文件
  name:'strings',           // 资源文件名称
  path:'resources/i18n/',   // 资源文件路径
  mode:'map',               // 用Map的方式使用资源文件中的值
  language: 'zh',           // 引入语言类型
  callback: function() {    // 加载成功后设置显示内容
    $.i18n.prop('string_username') // 语言替换格式
  }
});
```
***
### 语言文件
>  /resources/i18n/*.properties
