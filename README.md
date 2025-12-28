# LuminUI Libary
Made By @Leviform

Links

[Scriptblox.com](https://scriptblox.com/u/AutoCracked)

[rscripts.net](https://rscripts.net/@Leviform)


---

installation is important
```lua
local LuminUI = loadstring(game:HttpGet("https://r4-sec.vercel.app/files/3f14dd7a9e416747eb4521507cb53ee6"))()
```

Notify optional
```lua
LuminUI:Notify({
    Title = "Success",
    Content = "Action completed successfully!",
    Duration = 5  -- Stays for 5 seconds (default is 3)
})
```

Window os very important ill add more features soon

```lua
local LuminUI = LuminUI:CreateWindow({
    Name = "LuminUI | Release 1.0"
})
```

Adding tabs

```lua
local Tab = LuminUI:CreateTab("tab")
local Tab = LuminUI:CreateTab("home", "wifi") -- lucide.dev icon
```

Adding section

```lua
Tab:AddLabel("section")
```

adding toggle

```lua
Tab:AddToggle("random toggle", false, function(value)
    print("Toggle:", value)
end)
```

adding button

```lua
Tab:AddButton("random button", function()
    print("Button clicked!")
end)
```

adding slider

```lua
Tab:AddSlider("random slider", 0, 100, 10, function(value)
    print("Slider value:", value)
end)
```

adding paragraph 

```lua
Tab:AddParagraph("Welcome", "This is a paragraph with a title and content that automatically wraps and resizes based on the text length.")
```
Adding dropdown

```lua
Tab:AddDropdown("Select Weapon", {"Sword", "Bow", "Staff", "Axe", "Dagger"}, "Sword", function(value)
    print("Weapon selected:", value)
end)
```
