```
chess
checkboard 
├── 8x8 array
├── Alternating black and white.
    ├── for black and white respectively find one picture, aim to extanding more skins.
    ├── the checkboard can adapt to resolution.
```

对于整个棋盘有一个数据结构，对于棋盘上的每一个棋格也分配一个数据结构。

建立棋盘坐标系，起始坐标 $$(0, 0)$$ ，最大坐标 $$(7, 7)$$ 。标准国际象棋坐标系相对棋盘坐标系偏移量为 $$(-1, -1)$$ 。

```
+--------> y
|
|
v x
```

