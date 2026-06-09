# 🍎 Blox Fruit Auto Fruit Sniper

A highly optimized and fully automated Roblox Lua script for **Blox Fruits**. This script is designed to handle the entire fruit sniping process entirely on its own—so you can sit back and let it do the work!

✅ **STATUS: Tested and Working Perfectly!**

## 🌟 The Ultimate Automatic Workflow

This script operates on a seamless, zero-interaction loop:

1. 🔍 **Find (Automatic):** Continuously scans the map in real-time to detect any spawned Devil Fruits.
2. 🚁 **Collect (Automatic):** Bypasses walls using No-clip and tweens (flies) your character directly to the nearest fruit to pick it up instantly.
3. 🎒 **Store (Automatic):** Attempts to safely store the collected fruit in your inventory, with a built-in 3-retry system to ensure it gets stored even if there's lag.
4. 🔄 **Server Hop (Automatic):** Once the map is clear or a fruit is stored, the script automatically hops to a new server to find more fruits, repeating the process infinitely.

## ✨ Features

- **100% Fully Automated Cycle:** Find > Collect > Store > Server Hop.
- **In-Game Live GUI:** Beautiful on-screen notification system that logs every action in real-time.
- **Fruit ESP Overlay:** Visualizes spawned fruits directly on your screen.
- **Smart Tweening & No-Clip:** Navigates smoothly to the fruit without getting stuck behind walls or terrain.
- **Anti-AFK:** Prevents Roblox from kicking you for inactivity while farming.
- **Retry Logic:** Failsafe mechanisms built-in for fruit storing.

## ⚙️ Configuration

Main settings are located at the top of the `BloxFruit_AutoFruit.lua` file. Tweak them to fit your playstyle:

```lua
getgenv().AutoFruitSniper   = true   -- Master toggle for the script
getgenv().FruitESP          = true   -- Show ESP on fruits
getgenv().TweenSpeed        = 300    -- Flight speed (studs/sec)
getgenv().StoreRetries      = 3      -- Max store attempts before giving up
getgenv().HopDelay          = 3      -- Seconds to wait before server hop
getgenv().ScanInterval      = 0.5    -- How often to scan for fruits (seconds)
getgenv().AntiAFK           = true   -- Prevent AFK kick
```

## 🚀 Usage

1. Open **Blox Fruits** in Roblox.
2. Open your preferred Lua executor.
3. Copy and execute the code from `BloxFruit_AutoFruit.lua`.
4. The script will inject, display a GUI, and instantly start finding, collecting, storing, and server hopping automatically!

## ⚠️ Disclaimer

- This project is provided for **educational and learning purposes only**, demonstrating Lua automation techniques.
- Use at your own risk. Using automation scripts may go against the Roblox or Blox Fruits terms of service.
