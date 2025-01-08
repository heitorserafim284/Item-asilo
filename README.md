if game.PlaceId == 14236123211 then
local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "Title of the library", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})

--Values
G.autoTap true


--functions
function autoTap()
while G.autoTap true do game:GetService ("ReplicatedStorage") WaitForChild("Events") WaitForChild ("Damage IncreaseOnClickEvent" )
wait(.0000000000000001)
   end
end

local Tab Window:MakeTab({
Name "Auto Farm"
 Icon "rbxassetid:// 4483345998
 PremiumOnly false })

FarmTab: AddToggle({
 Nane "Auto Tap", Default false,
 Callback - Function(Value)
 _G.autoTap == Value
autoTap()
end
})