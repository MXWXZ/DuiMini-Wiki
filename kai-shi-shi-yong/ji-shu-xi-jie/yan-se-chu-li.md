# 颜色处理

## 颜色位定义

DuiMini采用ARGB作为颜色格式，有7位和9位两种。 七位时为RGB，Alpha值均为255，各位含义：

* 第1位固定标识符`#`
* 第2-3位为红色Hex
* 第4-5位为绿色Hex
* 第6-7位为蓝色Hex

  例如：`#000000`为100%黑色，`#FFFFFF`为100%白色

九位时为ARGB各位含义：

* 第1位固定标识符`#`
* 第2-3位为透明度Hex
* 第4-5位为红色Hex
* 第6-7位为绿色Hex
* 第8-9位为蓝色Hex

例如：`#FF000000`为100%黑色，`#FFFFFFFF`为100%白色

## 常用颜色名：

| 名称 | 代码 |
| :---: | :---: |
| black | \#000000 |
| white | \#FFFFFF |
| red | \#FF0000 |
| green | \#00FF00 |
| blue | \#0000FF |
| yellow | \#FFFF00 |
| cyan | \#00FFFF |
| purple | \#FF00FF |
| gray | \#C0C0C0 |
| transparent | \#00000000 |
