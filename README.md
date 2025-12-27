# LuminUI Libary
Made By @Leviform

Links

[Scriptblox.com](https://scriptblox.com/u/AutoCracked)

[rscripts.net](https://rscripts.net/@Leviform)


---

installation is important
```
local LuminUI = loadstring(game:HttpGet("https://r4-sec.vercel.app/files/3f14dd7a9e416747eb4521507cb53ee6"))()
```

Notify optional
```
Window:Notify({
    Title = "Success",
    Content = "Action completed successfully!",
    Duration = 5  -- Stays for 5 seconds (default is 3)
})
```

Window os very important ill add more features soon

```
local Window = Library:CreateWindow({
    Name = "LuminUI | Jul 7 2021"
})
```

Adding tabs

```
local Tab = Window:CreateTab("tab")
```

Adding section

```
Tab:AddLabel("section")
```

adding toggle

```
Tab:AddToggle("random toggle", false, function(value)
    print("Toggle:", value)
end)
```

adding button

```
Tab:AddButton("random button", function()
    print("Button clicked!")
end)
```

adding slider

```
AimbotTab:AddSlider("random slider", 0, 100, 10, function(value)
    print("Slider value:", value)
end)
```

adding paragraph 

```
Tab:AddParagraph("Welcome", "This is a paragraph with a title and content that automatically wraps and resizes based on the text length.")
```
