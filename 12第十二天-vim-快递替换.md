## 学习

1. normal 模式下，:s/原来字符串(可用 pattern)/目标字符串/gc;
2. normal 模式下，:%s/... 代表全文，但只是匹配了每一行第一个字符串，如果要全部匹配，需要 /g;
3. normal 模式下，:lineNumber1,lineNumber2s/...，确定哪几行里搜索替换;
4. normal 模式下，:$s/...，从当前行到尾部行，进行替换;
5. visual 模式下，:s/....全部选中后就可以替换；
6. gb 来选中多个相同词，区分大小写，选中后可以进行替换。

## 练习

1. replace onasdlflj{eToTwo to two onasdlflj{eToTwo to two
2. replace onasdlflj{e to two
3. replace onasdlflj{e TO TWO
4. replace Onasdlflj{e to Two
