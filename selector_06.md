# 属性选择器：E[attr*="value"]

匹配具有att属性、且值中含有val的E元素

例：
```javascript
<!DOCTYPE html>
<html>
<head>
<style type="text/css">
p[title*="val"] {text-decoration:underline;}
</style>
</head>
<body>
<div style="width:733px; border: 1px solid #666; padding:5px;">
<p title="have val word">匹配具有att属性、且值中含有val的E元素</p>
</div>
</body>
</html>
```