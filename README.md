# minigame 2
## Devlog
1. I'm not sure if this was technically a bug (well it is but it didn't have to do with any code I created, just something that was already there), but the prop health decreased unexpectedly when I pushed it up a staircase. The prop health decreases when it enters any trigger, but both the staircase and the spell are counted as triggers. To fix it, I would just add an if statement checking to make sure the trigger's tag is spell before the rest of the method gets called.
2. It gets the sprite renderer component, then specifically gets the color part of the sprite renderer (when it uses the .color) and sets it to a newly created color object with the intial values to be (r, 0.2f, 0.2f).

## Open-Source Assets
- Pixel art environment & character sprites: https://assetstore.unity.com/packages/2d/environments/pixel-art-top-down-basic-187605
