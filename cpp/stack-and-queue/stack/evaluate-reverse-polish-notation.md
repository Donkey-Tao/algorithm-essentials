## Evaluate Reverse Polish Notation


### 描述

Evaluate the value of an arithmetic expression in Reverse Polish Notation.

Valid operators are `+, -, *, /`. Each operand may be an integer or another expression.

Some examples:

```
  ["2", "1", "+", "3", "*"] -> ((2 + 1) * 3) -> 9
  ["4", "13", "5", "/", "+"] -> (4 + (13 / 5)) -> 6
```


### 分析

无


### 递归版

{% codesnippet "./code/evaluate-reverse-polish-notation-1."+book.suffix, language=book.suffix %}{% endcodesnippet %}


### 迭代版

{% codesnippet "./code/evaluate-reverse-polish-notation-2."+book.suffix, language=book.suffix %}{% endcodesnippet %}