# 🐉 Dragon Addon Installation Guide

## 📥 Easy Installation Steps

### **Windows 10/11:**

1. **Download** the addon files
2. **Find** your Minecraft folder:
   - Press `Windows Key + R`
   - Type: `%appdata%\.minecraft`
   - Press Enter

3. **Create folders** if they don't exist:
   - `behavior_packs`
   - `resource_packs`

4. **Copy** the entire `Dragon Addon` folder to BOTH:
   - `behavior_packs` folder
   - `resource_packs` folder

5. **Launch** Minecraft Bedrock Edition
6. **Create New World** → Settings → Enable both packs
7. **Enjoy!** 🐉

---

### **Mac:**

1. Go to: `~/Library/Application Support/minecraft`
2. Find or create `behavior_packs` and `resource_packs` folders
3. Copy addon folder to both
4. Launch Minecraft and enable packs

---

### **Nintendo Switch:**

1. Go to: Game storage → Minecraft
2. Find `behavior_packs` and `resource_packs`
3. Copy addon folder to both
4. Restart Minecraft

---

### **Android:**

1. Go to: `Internal Storage → games → com.mojang`
2. Find or create `behavior_packs` and `resource_packs`
3. Copy addon folder to both
4. Restart Minecraft

---

### **iOS:**

1. Use a file manager app
2. Navigate to: `Minecraft → behavior_packs` and `resource_packs`
3. Copy addon folder to both
4. Open Minecraft and enable

---

## ✅ Verify Installation

In-game, run:
```
/summon dragon:sky_drake ~ ~ ~
```

If a dragon appears, **you're all set!** 🎉

---

## 🎮 First Time Setup

### **Spawn Dragons:**
```bash
/summon dragon:sky_drake ~ ~ ~
/summon dragon:shadow_drake ~ ~ ~
```

### **Get Items:**
```bash
/give @s dragon:dragon_taming_staff
/give @s dragon:dragon_egg
```

### **Ride:**
1. Right-click dragon
2. Use **WASD** to fly
3. **Space** to go up, **Shift** to go down

---

## 🔧 Troubleshooting

**Dragons don't appear?**
- ✅ Check BOTH packs are activated
- ✅ Restart Minecraft completely
- ✅ Make sure addon folder is in correct location

**No textures (white/pink dragon)?**
- ✅ Verify resource pack is enabled
- ✅ Update Minecraft to latest version

**Game crashes?**
- ✅ Disable other addons temporarily
- ✅ Verify addon_manifest.json is correct

**Can't mount dragon?**
- ✅ Make sure behavior pack is active
- ✅ Try standing still and right-clicking

---

## 📋 Useful Commands

```bash
# Summon with custom name
/summon dragon:sky_drake ~ ~ ~ {CustomName: "Toothless"}

# Kill all dragons
/kill @e[type=dragon:sky_drake]
/kill @e[type=dragon:shadow_drake]

# Teleport to dragon
/tp @s @e[type=dragon:sky_drake,limit=1]

# Count dragons
/execute as @e[type=dragon:sky_drake] run say Hello
```

---

## 🆘 Still Having Issues?

1. Delete addon completely
2. Re-download fresh copy
3. Follow steps again carefully
4. Make sure folder structure matches exactly
5. Restart Minecraft multiple times

---

## 🎉 You're Ready!

Enjoy your dragon adventure! 🐉✨
