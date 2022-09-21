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

Each time a player takes this type of checkpoint, his counter will be increased by +1.

![](https://i.imgur.com/F3g9T4L.png)
![](https://i.imgur.com/34l0CCx.png)
![](https://i.imgur.com/WkOJ8El.png)

Now, when you are spectating, you can press your +alt1 key to respawn.


