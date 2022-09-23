# My-Custom-Point-CheckPoint
> Based on the existing default checkpoint in SC.

## Installation Guide

[Download this repository](https://github.com/Gaftherman/My-Custom-Point-CheckPoint/archive/refs/heads/main.zip) and extract it's contents inside `Steam\steamapps\common\Sven Co-op\svencoop\`

That should look like this:

```
└── 📁svencoop
    └── 📁scripts
        └── 📁maps
            └── 📁Gaftherman
                ├── 📄point_checkpoint.as
                └── 📁pcp_misc   
                    ├── 📄think.as
                    ├── 📄misc.as
                    └── 📄cbasekeepdata.as
```

Now, in you map script you need to add:

```angelscript

#include "Gaftherman/point_checkpoint"

void MapInit()
{
    RegisterPointCheckpoint(); 
}
```

And there is, you installed my Custom Point CheckPoint. 🎉🎉🎉🎉🎉🎉

## What is new/changed in this script?

In this modification/creation made by me, taking as a problem that the original checkpoint is very accessible for trolling, I decided to create my own kind of checkpoint.

Now, if you start a map with this script installed, you will noticed a counter at the top left. 

![](https://i.imgur.com/QxCsUDO.png)

This counter will increase according to how many checkpoints have been taken.

![Picking CP](https://user-images.githubusercontent.com/71413659/191890921-6bc774fd-902b-40f8-9f34-81f074ce8339.gif)

And will decrease depending on how many times you have respawned (to respawn you need to be dead, have at least 1 checkpoint taken and press you +alt1 key binded).

![Suicide and Respawn](https://user-images.githubusercontent.com/71413659/191894060-63a488bc-792c-466d-a5d4-40a1625e3ac8.gif)

>⚠️This counter is personal, by this I mean that if they take 2 checkpoints and you used 1, you will have 1 checkpoint to respawn while your teammates will have 2 more to respawn.

