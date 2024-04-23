# Python の文字列操作

## 文字数のカウント

countメソッドを使う。

```python
>>> "This is a pen.".count(" ")
3
>>> "This is a pen.".count(".")
1
```

## 前後の空白の除去

```python
>>> "   This is a pen.     ".strip()
'This is a pen.'
```

## 文字列の分割(リスト化)

```python
>>> "This is a pen.".split(" ")
['This', 'is', 'a', 'pen.']
```

## f文字列(f-strings)

```python
>>> f"\"This is a pen.\""
'"This is a pen."'
```