# Merge Sort Projesi
```
[16,21,11,8,12,22] -> Merge Sort
```

* Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

```
            [16,21,11,8,12,22]
        [16,21,11]      [8,12,22]       -> 2^x=n
      [16]  [21,11]    [8,12]  [22]     -> 2^x=n
    [16]  [21]  [11]    [8]  [12] [22]  -> 2^x=n
      [16] [11,21]        [8,12] [22]   -> 2^x=n
      [11,16,21]            [8,12,22]   -> 2^x=n
            [8,11,12,16,21,22]          -> 2^x=n
```

* Big-O gösterimini yazınız.
```
n times 2^x => O(nlogn)
```

[patika.dev](www.patika.dev)

[patika.dev/efecetinalp](https://app.patika.dev/efecetinalp)
