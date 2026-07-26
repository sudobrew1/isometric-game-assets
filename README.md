# Isometric Game Assets

Central asset collection for 2D isometric games, rendered with Blender. This repo holds tilesets for now. Sprites for animated actors, props, structures, and effects will be added at a later time.

## Repo Structure

```
├── tilesets/
│   ├── terrain/        # ground tiles + 16-tile corner-mask blend sets
│   ├── structures/     # buildings, walls, static placeables
│   └── props/          # decorative / non-interactive objects
├── sprites/
│   ├── units/          # animated actors (per-direction sheets)
│   └── fx/             # effects, particles, overlays
├── source/
│   ├── blend/          # .blend source files (never rendered directly into the game)
│   └── masks/          # paintable terrain masks (two terrain types via Mix node)
```

*Maintained by [sudobrew1](https://github.com/sudobrew1).*
