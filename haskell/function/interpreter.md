
# Function

## 中置関数

*は2つの数を引数にとり、2つの数で囲む。

```sh
ghci> 8 * 7
56
```

## 前置関数

関数succはひとつの引数をとり、後者(successor)を返す。

```sh
ghci> succ 8
9
```

関数max,minは2つ引数をとる。

```sh
ghci> min 9 10
9

# ``で囲むことで中置関数として呼び出せる
ghci> 9 `min` 10
9
```

```sh
ghci> succ(succ 9)
11
```