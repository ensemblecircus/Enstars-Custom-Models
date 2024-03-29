Mads (ensemblecircus)

Enstars Custom Models Pack

# Resources #
## Blockbench: ## 
I made use of InTheLittleWood's custom hats and items tutorial. \n
Link: https://youtu.be/Cw8PPPEl_IQ?si=hfROSz7kzTfO0ZPc
His tutorial is very helpful, aside from 2 points: 
### 1 ###
The code for his carved_pumpkin.json causes the original carved pumpkin item texture to not appear. The code in the file should be:
    {
    "parent": "minecraft:block/carved_pumpkin",

    "overrides": [
    {"predicate": {"custom_model_data":1}, "model": "block/custom/tutorial"}
    ]
    }
        As a side note, JSON files do not allow for commenting, which I learned
        in the process of creating this pack.
    This solution was provided by reddit user dragonmaster95 under this post:
        link: https://www.reddit.com/r/Blockbench/comments/10ggvej/messed_up_carved_pumpkin_texture_in_game/

### 2 ###
His method of adding custom items requires commands to acquire them.

## Minecraft ##
The implementation of custom models is possible primarily through the use of
the Minecraft feature, custom model data. The tutorial I looked at as a
supplement to InTheLittleWood's tutorial was by Simplexity-Development on
GitHub.\n
Link: https://github.com/Simplexity-Development/Custom_Model_Data_Guide

## Minecraft Assets ## 
I had to look at a few minecraft assets in order to debug some issues, and 
mcasset.cloud was extremely helpful to me. \n
Link: https://mcasset.cloud/1.20.4/

## Optifine: ##
I am using Optifine for 1.20.4, and its Custom Item Textures (CIT) feature.
Optifine is required for this pack to be used. 
I made use of the short guide to using Optifine's CIT feature under this reddit
post: 
Link: https://www.reddit.com/r/mcresourcepack/comments/r90g8o/how_do_i_make_a_custom_item_model_made_in_block/

## Ensemble Stars ## 
I made use of Ensemble Stars!! (the game), the Ensemble Stars Wiki, and
gradualcolors's Ensemble Stars Assets Drive for reference when making the
textures.

# Issues #
- [RESOLVED] ~~CIT not working with 1.20.4~~

# Plans # 
- REMOVE TEST MODELS
- Plan first release
    - Plan naming conventions

## Textures ## 
### Release 1 ###
- Unit Nuis
- Kohaku Fairy

### Unplanned Additions ###
- Kohaku nui
- Kohaku muppet
- Kohaku fairy
- Tiny bee (maybe)
- bkubstars
- Cat ears
- gun. (reskinned crossbow)
- Double Face logo
- Alkaloid hat
- Alkaloid jacket + gloves (renamed chestplate(for every kind))
    - Alkaloid_Spade
    - Alkaloid_Diamond
    - Alkaloid_Heart
    - Alkaloid_Club
- Tatsumi car model
- Wataru's hair

# Complete #
2/29/2024
- Ensured usage of CIT works
- Naming conventions set:
    - Naming will always use "(Character/Unit) (Color) (Item Type) (Item Specification)"
    - Each part is only applicable when necessary, the goal is for each name to be as concise as possible
    - How the unit names will be written: 
        - Fine
        - Trickstar
        - Alkaloid
        - Ryuseitai
        - Crazy B
        - Eden
        - Valkyrie
        - 2wink
        - Rabits
        - Undead
        - Akatsuki
        - Knights
        - Switch
        - MaM
        - Double Face