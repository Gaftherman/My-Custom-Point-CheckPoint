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

This counter will increase according to how many checkpoints have been taken and will decrease depending on how many times you have respawned (to respawn you need to be dead and press you +alt1 key binded).



