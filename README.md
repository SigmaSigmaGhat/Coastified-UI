# Coastified-UI
Hey! This UI Library was made for ROBLOX! I am not the official owner of who ever made this.

# WARNING!!!
This may not work! All of this was ripped from the source code, i really dont recommened for you to use this.. Just use Rayfield UI or Orion Library UI!

# Booting Coastified
```lua
local Lib = loadstring(game:HttpGet("https://raw.githubusercontent.com/laagginq/ui-libraries/main/coastified/src.lua"))()
```
# Create Window
```lua
local Window = Lib:Window("Name", "Name", Enum.KeyCode.RightShift)
```
# Create Tab
```lua
local Test = Window:Tab("Tab")
```
# Create Toggle
```lua
Test:Toggle('Toggle',function(state)
    print(“Hello World!”)
end)
```
# Create Slider
```lua
Test:Slider('Slider',1,200,75,function(Value)
    print(Value)
end)
```
# Create ColorPicker
```lua
Test:Colorpicker("Color",Color3.fromRGB(0,0,0), function(color)
    print(color)
end)
```
# Create DropDown
```lua
Test:Dropdown("Part",{'Head',"UpperTorso","HumanoidRootPart","LowerTorso"}, function(objective)
    print(objective)
end)
```

