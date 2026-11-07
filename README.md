# Auto-Halloween-Games-ps99-1-4-games

# Setup config before using!

```lua
local ITEM_CONFIG = _G.ITEM_CONFIG or {
    Broomstick  = { api = "Broomstick",  games = { [1] = true, [2] = false, [3] = false, [4] = true } },
    LuckyCharm  = { api = "LuckyCharm",  games = { [1] = true, [2] = true, [3] = true, [4] = true } },
    TreatMagnet = { api = "TreatMagnet", games = { [1] = true, [2] = true, [3] = true, [4] = true, [5] = true } },
}
```
Or use ready:
```lua
local ITEM_CONFIG = _G.ITEM_CONFIG or {
    Broomstick  = { api = "Broomstick",  games = { [1] = true, [2] = false, [3] = false, [4] = true } },
    LuckyCharm  = { api = "LuckyCharm",  games = { [1] = true, [2] = true, [3] = true, [4] = true } },
    TreatMagnet = { api = "TreatMagnet", games = { [1] = true, [2] = true, [3] = true, [4] = true, [5] = true } },
}
loadstring(game:HttpGet('https://raw.githubusercontent.com/dantlome-ops/Auto-Halloween-Games-ps99-1-4-games/refs/heads/main/AutoGames'))()
```
