# Functor

Factorとは、全体を移せる(map over)ものの型クラス。

```hs
class Fanctor f where
    fmap :: (a -> b) -> f a -> f b
```

fは1つの型引数を取る型コンストラクタ。

リストのfmapはmap。

```sh
ghci> fmap (*2) [1..3]
[2,4,6]
ghci> map (*2) [1..3]
[2,4,6]
```

# Maybe

```hs
instance Functor Maybe where
    fmap f (Just x) = Just (f x)
    fmap f Nothing = Nothing
```

