# GNT Revolution 3 Gecko Codes

These are codes that modify the game in various ways. You can add them to games by right clicking on the game in Dolphin and going to properties. Go to Gecko Codes and you can add them here by either going to Edit Config or hitting the Add button (Add button only exists in latest Dolphin versions).

## General

### Skip Intro Cutscenes [Nick]

```gecko
c2055264 00000005  
827c0018 2c13000d  
4082000c 3a60000e  
48000010 2c130010  
40820008 3a600000  
60000000 00000000
```

### Force 60 FPS [Nick]

```gecko
041712A8 60030000
```

### LNP Always Activated [Nick]

```gecko
0449ee00  3f8ccccd
0449ee04  3f8ccccd
0449ee08  3f8ccccd
```

### Replace Kiba with Rogue Ninja [Nick]

```gecko
C2155014 00000003  
2C00000F 40820008  
3800002B 90040028  
60000000 00000000
```

Note: The `0F` in `2C00000F` is Kiba. Replace the `0F` with other hex values to replace other characters. The `2B` in `3800002B` is Rogue Ninja. Replace the `2B` that with other values to load other characters.
