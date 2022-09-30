# Merge Sort Projesi
---

Bu bir [patika.dev](www.patika.dev) projesidir.

## [16,21,11,8,12,22] -> Merge Sort

### 1) Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

```
                [16,21,11,8,12,22]
1.Adım:       [16,21,11]   [8,12,22]
2.Adım:    [16] [21,11]      [8,12] [22]
3.Adım:  [16]  [21]  [11]       [8]  [12]  [22] 
4.Adım:     [16] [11,21]    [8,12] [22]
5.Adım:        [11,16,21]  [8,12,22]
6.Adım:          [8,11,12,16,21,22]
```

### 2) Big-O gösterimini yazınız.

2^x=n      x=log(n)

Cevap: O(logn)
