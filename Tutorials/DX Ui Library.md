# Darkrai X | Ui Library

Hello, Darkrai X Have A Ui Library!
Welp, It's Not The Best But It's Also Not The Worst!

Here Is A Image Of The Ui Library

<img src="https://raw.githubusercontent.com/GamingScripter/Darkrai-X/main/images/IMG_20220808_213955.jpg">

## Tutorial

#### Ui Library

---

```lua
local DarkraiX = loadstring(game:HttpGet(("https://raw.githubusercontent.com/natoloe009/ka/main/darkrai%20x%20src.lua"),true))()
```

This Will Be Your Starting If This Is Not In Your Script Then It Will Not Work!

## Toggle Ui Library

---

```lua
DarkraiX:ToggleUi()
```
Just Put This In Your Toggle Button :)

## Creating Window

---

```lua
local Library = DarkraiX:Window("Darkrai X","","",Enum.KeyCode.RightControl);

--[[
DarkraiX:Window(
1 = Name Of Your Ui Library (string)
2 = Game Name (You Can Keep This Empty To Get The Current Game Name!) (string)
3 = A Logo If You Have One! (string)
4 = Ui Library Toggle (I'll Not Prefer Touching It) (function)
);
]]
```

## Creating Tabs

---

```lua
Tab1 = Library:Tab("Main")

--[[
Library:Tab(
1 = Your Tab Name! (string)
)
]]
```

## Button

---

```lua
Tab1:Button("Button",function()
    print("hi")
end)

--[[
Tab1:Button(
1 = Button Name (string)
2 = callback (function)
]]
```

Button Is Just A Clickable Thing Which Executes A Function/Script When Clicked!
## Toggle

---

```lua
Tab1:Toggle("Toggle",false,function(value)
print(value)
    end)

--[[
Tab1:Toggle(
1 = name (string)
2 = wether it should be true already or false (bool)
3 = callback (function)
)
]]
```

Toggle Is Basically A Switch That Turns On And Off A Scripts Or A Function <br /> If You Have Done It Correctly! <br /> Or In Simple Language It's A Bool

## Slider

---

```lua
Tab1:Slider("Slider",1,100,25,function(value)
        print(value)
    end)

--[[
Tab1:Slider(
1 = Name (string)
2 = Minimum (number)
3 = Maximum (number)
4 = Currently How Much (number)
)
]]
```

Slider Is Just To Adjust Ammount Of Text You Need <br /> Example : <br />
```
print(value)
```
Outcome :
```
1
21
29
10
42
```

Oh Btw, This Slider Is Fixed For Mobile!

## Drop-down

---

```lua
Tab1:Dropdown("Dropdown",{"yo","sus","pro"},function(value)
            print(value)
end)

--[[
Tab1:Dropdown(
1 = Name (string)
2 = Options (table)
)
]]
```

Dropdown Is A Thing Used To Adjust Tables In "LUA" <br />

## Textbox

---

```lua
Tab1:Textbox("Textbox","",true,function(value)
print(value)
end)

--[[
Tab1:Textbox(
1 = Name (string)
2 = Current Text (string)
3 = State (bool)
4 = callback (function)
)
]]
```

Just A Textbox :]

## Seperator

---

```lua
Tab1:Seperator("Seperator")

--[[
Tab1:Seperator(
1 = Name (string)
)
```

## Line

---

```lua
Tab1:Line()
```
