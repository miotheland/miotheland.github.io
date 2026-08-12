# tag
https://fluid.ist/docs/guide/#tag-%E6%8F%92%E4%BB%B6

```
{% note success %}
文字 或者 `markdown` 均可
{% endnote %}
```

# flod
https://fluid.ist/docs/guide/#%E6%8A%98%E5%8F%A0%E5%9D%97
```
{% fold info @title %}
需要折叠的一段内容，支持 markdown
{% endfold %}
```

# checkbox
https://fluid.ist/docs/guide/#%E5%8B%BE%E9%80%89%E6%A1%86

```
{% cb text, checked?, incline?(true/false), disabled? %}
```
text：显示的文字
checked：默认是否已勾选，默认 false
incline: 是否内联（可以理解为后面的文字是否换行），默认 false disabled: 勾选框是否为不可点击的样式，默认 false
