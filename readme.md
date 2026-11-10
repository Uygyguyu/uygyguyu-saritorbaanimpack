# saritorba.ytyp ve saritorba2.ydr yi animasyon menunuzun stream klasoruna atin 

# Animlist.lua
```lua 
["saritorba"] = {
    "anim@gangops@morgue@table@",
    "body_search",
    "Sari Torba",
    AnimationOptions = {
        Prop = 'saritorba2',
        PropBone = 24816,
        PropPlacement = {
            -0.1,
            0.0,
            0.0,
            -90.0,
            0.0,
            2.0
        },
        EmoteLoop = true,
        EmoteMoving = false,
    }
},
```
# fxmanifest.lua
```lua 
data_file 'DLC_ITYP_REQUEST' 'stream/saritorba.ytyp'
```
