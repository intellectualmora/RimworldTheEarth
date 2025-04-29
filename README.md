# RimworldTheEarth
- 这是模组用到的地球数据，数据是360*180个样本所以比较粗糙，植被分布也是估计的没确切数据，所以欢迎大家提供数据给我。
- This is the Earth data used by the mod. The data consists of 360×180 samples, so it is relatively coarse. The vegetation distribution is also estimated, as there is no precise data available. Contributions of more accurate data are very welcome!

## Data Format
tileId,longitude,latitude,elevation,hilliness,biome,waterCovered,rainfall,swampiness

## Hilliness
```
enum Hilliness
  {
    Flat,
    SmallHills,
    LargeHills,
    Mountainous,
    Impassable
  }
```
## biome
```
enum biome{
    IceSheet,
    Tundra,
    BorealForest,
    TemperateForest,
    Desert,
    SeaIce,
    Ocean,
    Lake
    }
```
## Example
```
0,-179,-89,2700,Mountainous,IceSheet,False,165,0.04125
1,-178,-89,2700,Mountainous,IceSheet,False,157,0.03925
2,-177,-89,2700,Mountainous,IceSheet,False,162,0.0405
```
