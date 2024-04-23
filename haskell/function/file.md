# File

baby.hsというファイルをつる。

```hs
doubleMe x = x + x
```

```sh
ghci> :l baby
[1 of 2] Compiling Main             ( baby.hs, interpreted )
Ok, one module loaded.
ghci> doubleMe 9
18
ghci> doubleMe 8.3
16.6
```