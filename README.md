# 🐉 Dragon Addon for Minecraft Bedrock

An immersive addon that adds rideable dragons, dragon training mechanics, and fantasy structures inspired by dragon training themes.

## ✨ Features

### Phase 1: Foundation ✅ LIVE
- ✅ Dragon entities with custom models
- ✅ Rideable dragon mechanics
- ✅ Dragon variants (Sky Drake, Shadow Drake)
- ✅ Dragon eggs and taming staff items

### Phase 2: Coming Soon 🔄
- 🔄 Dragon training/taming system
- 🔄 Hunter camps and structures
- 🔄 Dragon stables and cages
- 🔄 More dragon variants (Storm, Flame, Ice)

## 🐉 Dragons Included

1. **Sky Drake** - Fast, agile, common dragon
   - Blue coloring
   - 100 HP
   - Flies anywhere

2. **Shadow Drake** - Dark, powerful, night dragon
   - Black/dark coloring
   - 120 HP
   - Avoids sunlight, perfect for night flying

## 🎮 Quick Start

### Spawn a Dragon
```bash
/summon dragon:sky_drake ~ ~ ~
/summon dragon:shadow_drake ~ ~ ~
```

### Get Items
```bash
/give @s dragon:dragon_taming_staff
/give @s dragon:dragon_egg
```

### Ride Your Dragon
1. **Right-click** the dragon to mount
2. **WASD** - Move forward/backward/strafe
3. **Space** - Fly upward
4. **Shift** - Fly downward
5. **Look around** - Control flight direction

## 📥 Installation

**Windows:**
1. Download addon folder
2. Copy to `%appdata%\.minecraft\behavior_packs`
3. Also copy to `%appdata%\.minecraft\resource_packs`
4. Launch Minecraft
5. Create new world → Enable both packs
6. Done! 🎉

**See INSTALLATION.md for other platforms**

## 📁 Project Structure

```
Dragon Addon/
├── addon_manifest.json          (Main config)
├── README.md                    (This file)
├── INSTALLATION.md              (Setup guide)
├── behaviors/
│   ├── entities/               (Dragon definitions)
│   │   ├── sky_drake.json
│   │   └── shadow_drake.json
│   └── items/                  (Custom items)
│       ├── dragon_egg.json
│       └── dragon_taming_staff.json
└── resources/
    ├── entity/                 (Client-side entities)
    ├── render_controllers/     (Rendering rules)
    ├── models/                 (3D geometry)
    ├── textures/               (Skins)
    └── texts/                  (Language)
```

## 📋 Commands

```bash
# Spawn dragons
/summon dragon:sky_drake ~ ~ ~
/summon dragon:shadow_drake ~ ~ ~

# Get items
/give @s dragon:dragon_taming_staff
/give @s dragon:dragon_egg

# Named dragon
/summon dragon:sky_drake ~ ~ ~ {CustomName: "My Dragon"}

# Kill all dragons
/kill @e[type=dragon:sky_drake]
```

## 🎯 Version
**v1.0.0** - Initial Release

## 📝 License
Free to use and modify for personal use

## 🐛 Known Issues
- Textures are placeholder (will be improved)
- Models are geometric shapes (will be enhanced)

## 🚀 Roadmap

### v1.1.0
- [ ] Storm Drake
- [ ] Flame Drake
- [ ] Ice Drake
- [ ] Hunter camp structure

### v2.0.0
- [ ] 100+ dragon variants
- [ ] Advanced taming system
- [ ] Dragon breeding
- [ ] Dragon cages

Enjoy flying your dragons! 🐉
