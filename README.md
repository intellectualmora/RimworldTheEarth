# RimworldTheEarth
欢迎大家提供更精确的数据给我做地球
You're welcome to provide more accurate data for my rimworld Earth project.

Data Format
tileId,longitude,latitude,elevation,hilliness,biome,waterCovered,rainfall,swampiness
```
0,-179,-89,2700,Mountainous,IceSheet,False,165,0.04125
1,-178,-89,2700,Mountainous,IceSheet,False,157,0.03925
2,-177,-89,2700,Mountainous,IceSheet,False,162,0.0405
```
## Hilliness
```
enum Hilliness
  {
    Undefined,
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
