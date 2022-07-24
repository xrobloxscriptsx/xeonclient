local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("DragonWare - steal others time & flex your sword", "BloodTheme")

--MAIN
local Scripts = Window:NewTab("Scripts")
local ScriptSection = Scripts:NewSection("MAIN")


ScriptSection:NewButton("InfYield", "infyield script", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end)


ScriptSection:NewToggle("sonic", "speed", function(state)
    if state then
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 75
    else
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 16
    end
end)

ScriptSection:NewButton("Reach", "reech", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/xrobloxscriptsx/reach/main/README.md'))()
end)


ScriptSection:NewButton("Inf Jump", "giveu infinite jumps leave and rejoin for no inf jump", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/xrobloxscriptsx/infjump/main/README.md'))()
end)


ScriptSection:NewButton("Owl Hub", "just owl hub?", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/CriShoux/OwlHub/master/OwlHub.txt"))();
end)


ScriptSection:NewToggle("Super Sonic", "super speed", function(state)
    if state then
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 100
    else
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 16
    end
end)


ScriptSection:NewToggle("Super Human", "sonic and JumpPower", function(state)
    if state then
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 70
        game.Players.LocalPlayer.Character.Humanoid.JumpPower = 135
    else
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 16
        game.Players.LocalPlayer.Character.Humanoid.JumpPower = 50
    end
end)


ScriptSection:NewKeybind("toggle speed", "when press c u get speed", Enum.KeyCode.C, function()
	game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 50
end)


--COMBAT


local Combat = Window:NewTab("Combat")
local CombatSection = Combat:NewSection("Manual")


CombatSection:NewButton("Reach", "reech", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/xrobloxscriptsx/reach/main/README.md'))()
end)


CombatSection:NewTextBox("MORE THINGS SOON", "soon", function(txt)
	print(txt)
end)


local AutoSection = Auto:NewSection("AutoMatic")


AutoMaticSection:NewButton("AutoFarm dont work", "Click C to teleport to player", function()
   print(willy)
end)
