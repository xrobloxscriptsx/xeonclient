local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Xeon Client", "BloodTheme")

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
