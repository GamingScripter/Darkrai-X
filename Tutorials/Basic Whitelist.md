# Roblox Basic Whitelist System (Username)
Hello, Here Is A Simple Way To Make A Basic Whitelist System For Your Roblox Script!

**Protection Level :** Level 1 (Noobs Can't Bypass It)

## Step 1

**First Open Your Text Editor
And Copy/Type This**

```lua
local Allowed = -- Read Further To Know What To Put Here
if Allowed[game.Players.LocalPlayer.Name] then
print("Whitelisted Script")
else
print("Not Whitelisted Script")
end
```

## Step 2

**Open You Suggested Or Mostly Used Raw Text Maker**

I Will Suggest To Use GitHub Or Pastebin!

Type This In It -
```lua
return {
["Username"] = true,
["Username"] = true -- put "," in end if you want to make another one execpt the last one
}
```

**Get The Raw File Link And Add It In This**
```lua
loadstring(game:HttpGet("Raw txt link here", true))()
```

## Step 3

```lua
local Allowed = loadstring(game:HttpGet("Raw Txt link here", true))()
if Allowed[game.Players.LocalPlayer.Name] then
print("Whitelisted Script")
else
print("Not Whitelisted Script")
end
```

ENJOY!

---

# Roblox Basic Whitelist System (User ID)

Hello, Here Is A Simple Way To Make A Basic Whitelist System For Your Roblox Script!

**Protection Level :** Level 1.3 (Noobs Can't Bypass It)

## Step 1

**First Open Your Text Editor
And Copy/Type This**

```lua
local Allowed = -- Read Further To Know What To Put Here
if Allowed[game.Players.LocalPlayer.UserId] then
print("Whitelisted Script")
else
print("Not Whitelisted Script")
end
```

## Step 2

**Open You Suggested Or Mostly Used Raw Text Maker**

I Will Suggest To Use GitHub Or Pastebin!

Type This In It -
```lua
return {
["UserId"] = true,
["UserId"] = true -- put "," in end if you want to make another one execpt the last one
}
```

**Get The Raw File Link And Add It In This
```lua
loadstring(game:HttpGet("Raw txt link here", true))()
```

## Step 3

```lua
local Allowed = loadstring(game:HttpGet("Raw Txt link here", true))()
if Allowed[game.Players.LocalPlayer.UserId] then
print("Whitelisted Script")
else
print("Not Whitelisted Script")
end
```

ENJOY!
