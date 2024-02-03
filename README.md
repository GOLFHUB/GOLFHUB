# Remote spy

```
loadstring(game:HttpGet("https://raw.githubusercontent.com/Hosvile/Refinement/main/Forked/M%3ASimpleSpy%20V3",true))()
```

# Dark Dex v3

```
loadstring(game:HttpGet("https://github.com/Hosvile/DEX-Explorer/releases/latest/download/main.lua", true))()
```

# Hydroxide(remote spy upgraded)

```
local owner = "Hosvile"
local branch = "revision"

local function webImport(file)
    return loadstring(game:HttpGetAsync(("https://raw.githubusercontent.com/%s/MC-Hydroxide/%s/%s.lua"):format(owner, branch, file)), file .. '.lua')()
end

webImport("init")
webImport("ui/main")
```

# Find Position(Vector3)

```
setclipboard(tostring(game.Players.LocalPlayer.Character.HumanoidRootPart.Position))
```

# Find placeid
```
MapPlaceId = game.PlaceId
setclipboard('Place ID : '..MapPlaceId)
```
