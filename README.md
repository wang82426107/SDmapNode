# SDmapNode
一款轻量级SpriteKit瓦片地图,包含着数组形式,txt形式,TML文件形式创建瓦片地图.一行代码生成瓦片地图.

使用的时候只需要把工程中的SDmapNode文件夹拖到你的工程中就行. 然后添加支持库  ``` libz.tbd ```

数组形式创建
```
SDmapNode *mapNode = [[SDmapNode alloc]initWithAtlasName:@"map" tileSize:CGSizeMake(16, 16) tileCodes:[self tileCodesArray]];
    

```

txt文件形式创建
```
SDmapNode *mapNode = [[SDmapNode alloc]initWithTextFileName:@"background"];
```

TML文件形式创建
```
    SDmapNode *mapNode = [[SDmapNode alloc]initWithTMLFileName:@"map.tmx"];

```

作者:神经骚栋QQ:676758285

SDmapNode 详细介绍请点击[这里](http://www.jianshu.com/p/1184f4d52b77)




