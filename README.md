# PeakGameCoopMod
🧗‍♂️ Comprehensive cheat mod for PEAK climbing game - infinite stamina, player ESP, teleportation, auto-revive &amp; more. MelonLoader-based with full multiplayer support.
# PeakGameCoopMod
<img width="882" height="421" alt="Screenshot 2025-07-10 170028" src="https://github.com/user-attachments/assets/c415d061-3779-48ed-8a55-db5a3869892f" />


A comprehensive cheat mod for the PEAK climbing game that provides various gameplay enhancements and utilities for multiplayer sessions.

## 🎯 Features

### Core Cheats
- **Infinite Stamina** - Never run out of stamina while climbing
- **No Fall Damage** - Survive any fall without taking damage
- **Player ESP** - See all players through walls with colored indicators
- **Auto-Revive** - Automatically revive dead/passed out players

### Player Management
- **Revive System** - Revive all dead players at checkpoints
- **Teleportation** - Teleport players to each other or bring all to you
- **Kill/Passout Menu** - Force players into different states
- **Stamina Boost** - Give all players extra stamina

### Utility Features
- **Backpack Viewer** - Inspect other players' inventories
- **Player Legend** - Color-coded player identification
- **GUI Menu** - Easy-to-use interface for all features
- **Controller Support** - Works with both keyboard and gamepad

## 🚀 Installation

### Prerequisites
- [MelonLoader](https://melonwiki.xyz/#/) installed
- PEAK game (Steam version)
- .NET Framework 4.7.2 or higher

### Steps
1. Download the latest release from the releases page
2. Place `PeakNoclipMod.dll` in your `PEAK/Mods` folder
3. Launch the game - the mod will load automatically
4. Look for the mod menu in the top-left corner

## 🎮 Controls

### Keyboard Controls
| Key | Function |
|-----|----------|
| `F1` | Toggle main menu visibility |
| `F3` | Debug stamina system info |
| `F4` | Toggle infinite stamina |
| `F5` | Toggle no fall damage |
| `F6` | Toggle player ESP |
| `F7` | Revive all dead players |
| `F8` | Toggle auto-revive |
| `F9` | Give all players stamina |
| `F10` | Toggle teleport menu |
| `B` | Toggle backpack viewer |
| `K` | Toggle kill/passout menu |

### Controller Controls
| Button | Function |
|--------|----------|
| D-Pad Left | Toggle main menu |
| D-Pad Right | Toggle infinite stamina (when menu open) |
| D-Pad Up | Toggle no fall damage (when menu open) |
| D-Pad Down | Toggle player ESP (when menu open) |

## 📋 Menu System

### Main Menu
The primary interface appears in the top-left corner and includes:
- Toggle switches for all main features
- Quick access buttons for common actions
- Real-time feature status indicators

### Teleport Menu (`F10`)
- Select any player as source and destination
- One-click "Teleport All To Me" function
- Visual player selection interface

### Backpack Viewer (`B`)
- View any player's inventory contents
- See equipped items and backpack status
- Real-time inventory monitoring

### Kill/Passout Menu (`K`)
- Individual player targeting
- Kill, passout, or fall actions
- Mass action buttons for all players

## 🔧 Technical Details

### Architecture
- Built with MelonLoader framework
- Uses Harmony for runtime patching
- Photon networking integration for multiplayer
- Unity GUI system for interface

### Networking
- All actions are synchronized across multiplayer sessions
- Uses Photon RPC calls for reliable networking
- Master client validation for some actions

### Compatibility
- Game Version: PEAK (LandCrab Studios)
- MelonLoader Version: Compatible with latest
- Multiplayer: Fully supported

## ⚠️ Important Notes

### Fair Play
This mod is intended for:
- Private servers with friends
- Testing and experimentation
- Content creation and streaming

**Do not use in public lobbies or competitive play** - this ruins the experience for other players.

### Safety Features
- Auto-revive prevents permanent character loss
- Checkpoint-based revival system
- Stamina restoration after teleportation
- Error handling for network issues

### Performance
- Minimal performance impact
- Efficient ESP rendering
- Smart update loops to prevent lag

## 🐛 Troubleshooting

### Common Issues

**Mod not loading:**
- Ensure MelonLoader is properly installed
- Check that the DLL is in the correct Mods folder
- Verify game compatibility

**Features not working:**
- Make sure you're in a multiplayer session
- Check that you have proper network permissions
- Some features require master client status

**ESP not showing:**
- Ensure other players are in the game
- Check that ESP is enabled (F6)
- Verify camera and rendering settings

### Debug Information
Press `F3` to get detailed stamina system information in the console. This helps diagnose issues with the infinite stamina feature.

## 📝 Changelog

### Version 1.0.0
- Initial release
- All core features implemented
- Full multiplayer support
- GUI interface complete

## 👨‍💻 Development

### Building from Source
1. Clone the repository
2. Reference required assemblies:
   - MelonLoader.dll
   - UnityEngine.dll
   - Assembly-CSharp.dll (from PEAK)
3. Build with .NET Framework 4.7.2

### Contributing
- Report bugs via GitHub issues
- Submit feature requests
- Pull requests welcome for improvements

## 📄 License

This project is for educational and entertainment purposes. Please respect the game developers and use responsibly.

## ⚡ Credits

- **Author:** AaronParkerRealty
- **Framework:** MelonLoader
- **Game:** PEAK by LandCrab Studios

---

**Disclaimer:** This mod modifies game behavior and should only be used in appropriate contexts. The developers are not responsible for any consequences of using this mod.
