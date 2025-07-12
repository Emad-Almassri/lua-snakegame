# Lua Snake Game 🐍

A simple Snake game built using the LÖVE 2D framework and modern Lua programming techniques.

## 🎮 Game Features

- 🟢 Menu and Playing Game States
- 🐍 Snake that moves continuously
- 🍎 Random food spawning
- 🎯 Score increases on eating food
- 💥 Game over on wall or self collision
- 💾 High score saving/loading using Lua 5.4's `<close>` feature
- 🧠 Vector2 math operations with custom metamethods
- 🧩 Modular Entity-Component system
- ⌨️ Input handling using Command pattern
- 📣 (Bonus) Event system using Observer pattern

## 🧪 Quick Test Checklist

- [x] Game starts with menu
- [x] Snake moves and can change direction
- [x] Food spawns and increases score
- [x] High score saves/loads correctly
- [x] Vector2 math operations work
- [x] Game over detection works
- [x] Bonus: Event system functions as expected

## 📁 Project Structure

```
snake_game/
├── main.lua              -- Entry point
├── gamestate.lua         -- State manager
├── entity.lua            -- Entity system
├── vector2.lua           -- Math utilities
├── highscore.lua         -- Save/load system
├── input.lua             -- Input handling
├── events.lua            -- Event system (bonus)
├── snake_game.lua        -- Core game logic
└── states/
    ├── menu_state.lua    -- Menu state
    └── game_state.lua    -- Playing state
```

## 🛠 Modern Lua Feature Used

This game uses **Lua 5.4's `to-be-closed` variables** in `highscore.lua`:

```lua
local file <close> = io.open("highscore.txt", "w")
```

This ensures that the file is **automatically closed**, even if an error occurs—making resource management cleaner and safer.

## 🚀 How to Run

1. Make sure [LÖVE 2D](https://love2d.org) is installed.
2. Navigate to the project folder.
3. Run the game with:

```bash
love .
```

## 📦 Submission Requirements

✅ All required source files are included  
✅ Project structure is followed  
✅ Game runs correctly with Love2D  
✅ README includes modern Lua feature explanation  
✅ Bonus system implemented  

## 👨‍💻 Author

Emad Al-Massri
Assignment: Lua Game Programming  

---

Enjoy the game! 🎉
