# mouse-translator

https://neal2018.github.io/mouse-translator/

![img](pics/before.png)

=>

![img](pics/after.png)

核心代码：

```js
content.replaceAll(/\p{Unified_Ideograph}(?![^\[]*\])/ug, "吱")
```
