local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))() --Библиотеки

---------------------------------------------------

local Window = Rayfield:CreateWindow({
   Name = "Game: The SCP Elevator",
   Icon = 0, -- Icon in Topbar. Can use Lucide Icons (string) or Roblox Image (number). 0 to use no icon (default).
   LoadingTitle = "Loading...",
   LoadingSubtitle = "by 111.111.111.111",
   ShowText = "Rayfield", -- for mobile users to unhide rayfield, change if you'd like
   Theme = "Default", -- Check https://docs.sirius.menu/rayfield/configuration/themes

   ToggleUIKeybind = "K", -- The keybind to toggle the UI visibility (string like "K" or Enum.KeyCode)

   DisableRayfieldPrompts = false,
   DisableBuildWarnings = false, -- Prevents Rayfield from warning when the script has a version mismatch with the interface

   ConfigurationSaving = {
      Enabled = true,
      FolderName = nil, -- Create a custom folder for your hub/game
      FileName = "The SCP Elevator"
   },

   Discord = {
      Enabled = false, -- Prompt the user to join your Discord server if their executor supports it
      Invite = "noinvitelink", -- The Discord invite code, do not include discord.gg/. E.g. discord.gg/ ABCD would be ABCD
      RememberJoins = true -- Set this to false to make them join the discord every time they load it up
   },

   KeySystem = false, -- Set this to true to use our key system
   KeySettings = {
      Title = "Untitled",
      Subtitle = "Key System",
      Note = "No method of obtaining the key is provided", -- Use this to tell the user how to get a key
      FileName = "Key", -- It is recommended to use something unique as other scripts using Rayfield may overwrite your key file
      SaveKey = true, -- The user's key will be saved, but if you change the key, they will be unable to use your script
      GrabKeyFromSite = false, -- If this is true, set Key below to the RAW site you would like Rayfield to get the key from
      Key = {"JH6D-JF1F-WBX7-KWND-HAKS-19BR"} -- List of keys that will be accepted by the system, can be RAW file links (pastebin, github etc) or simple strings ("hello","key22")
   }
})

---------------------------------------------------


local Tab = Window:CreateTab("Main", 4483362458) -- Title, Image
local Section = Tab:CreateSection("S1")

---------------------------------------------------


local Button = Tab:CreateButton({
   Name = "+99999999999 Money!",
   Callback = function()
   local args = {
    [1] = -99999999999, -- change how many money U want.
    [2] = "[SCP] Card-L1",
    [3] = "Key Card"
}

game:GetService("ReplicatedStorage").Events.ShopEvents.BuyItemFromGUI:FireServer(unpack(args))
-- The function that takes place when the button is pressed
   end,
})

---------------------------------------------------

local Button = Tab:CreateButton({
   Name = "Invisible",
   Callback = function()
   loadstring(game:HttpGet('https://pastebin.com/raw/3Rnd9rHf'))() -- The function that takes place when the button is pressed
   end,
})

---------------------------------------------------

local Button = Tab:CreateButton({
   Name = "Touch Fling",
   Callback = function()
   loadstring(game:HttpGet("https://pastebin.com/raw/LgZwZ7ZB",true))() -- The function that takes place when the button is pressed
   end,
})

---------------------------------------------------

local Button = Tab:CreateButton({
   Name = "FE Illusion",
   Callback = function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/0Ben1/fe/main/obf_11l7Y131YqJjZ31QmV5L8pI23V02b3191sEg26E75472Wl78Vi8870jRv5txZyL1.lua.txt"))() -- The function that takes place when the button is pressed
   end,
})

---------------------------------------------------

local Button = Tab:CreateButton({
   Name = "Fly Gui",
   Callback = function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/XNEOFF/FlyGuiV3/main/FlyGuiV3.txt"))() -- The function that takes place when the button is pressed
   end,
})

---------------------------------------------------


local Button = Tab:CreateButton({
   Name = "Infinite Yield",
   Callback = function()
   loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))() -- The function that takes place when the button is pressed
   end,
})
