# LevelDB-Notes
LevelDB source code reading Notes

### MemTable 

1. 随机数生成器:线性同余算法，拒绝采样与蓄水池采样。
```
skiplist.h
random.h
```
1. 内存键值对的编码：不定长编码和定长编码，Base 128 Varints

```
slice.h
dbformat.h
```



