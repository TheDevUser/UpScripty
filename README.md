

# Installing UpScripty
## UpScripty is a script to modify your roblox client.
#### Installing UpScripty is simple copy the loadstring below and paste it into your executor.

```Lua
loadstring(game:HttpGet('https://pastebin.com/raw/PPgvwLs1', true))()
```

# Status
#### UpScripty has just been created and are adding more cheats to the Menu.

# UI
## Ubstract Framework/UI Lib

#### Note: Asbtract UI was note made by me.

#### Asbtract UI Engine

```Lua
local Abstract = loadstring(game:HttpGet("https://raw.githubusercontent.com/AbstractPoo/Main/AbstractUI/AbstractUI"))()
local UI = Abstract:Create("UI Library", UDim2.new(0, 420, 0, 450))
UI:Divider("Divider")

UI:Button("Button", "Description for button", function()
    print("Button clicked")
end)

UI:Toggle("Toggle", "Description for toggle", false, function(state)
    print(state)
end)

UI:Dropdown("Dropdown", "Description for dropdown", {"Option1", "Option2", "Option3"}, function(value)
    print(value)
end)

UI:Slider("Slider", "Description for slider", 0, 100, 50, function(value)
    print(value)
end)
```

#### Abstract UI Docs:
https://abstractpoo.gitbook.io/abstract-ui-1/toggle
