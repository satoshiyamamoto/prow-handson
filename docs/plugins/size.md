# Size

PRのソースの変更の行数に対して以下のようにラベルがつく。
```
# ラベル: 行数
XS:  9行以下
S:   10-29
M:   30-99
L:   100-499
Xl:  500-599
Xxl: 1000行以上
```

## 設定

plugins.yamlで行数の変更ができる。

```plugins.yaml
size:
  s:   10
  m:   30
  l:   100
  xl:  500
  xxl: 1000
```