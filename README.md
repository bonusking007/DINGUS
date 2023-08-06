wait(5)

local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Bonus X hub (Dingus)", "DarkTheme")

local Tab = Window:NewTab("Hider")
local Section = Tab:NewSection("Hider")

Section:NewButton("DONE ALL TASK", "1 click", function()
    local args = {
        [1] = 1
    }
    
    game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("InvokeTaskCompleted"):InvokeServer(unpack(args))
    
    local args = {
        [1] = 2
    }
    
    game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("InvokeTaskCompleted"):InvokeServer(unpack(args))
    
    local args = {
        [1] = 3
    }
    
    game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("InvokeTaskCompleted"):InvokeServer(unpack(args))
    
    local args = {
        [1] = 4
    }
    
    game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("InvokeTaskCompleted"):InvokeServer(unpack(args))
    
    local args = {
        [1] = 5
    }
    
    game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("InvokeTaskCompleted"):InvokeServer(unpack(args))
    
    local args = {
        [1] = 6
    }
    
    game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("InvokeTaskCompleted"):InvokeServer(unpack(args))
    
    local args = {
        [1] = 7
    }
    
    game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("InvokeTaskCompleted"):InvokeServer(unpack(args))
    
    local args = {
        [1] = 8
    }
    
    game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("InvokeTaskCompleted"):InvokeServer(unpack(args))
    
    local args = {
        [1] = 9
    }
    
    game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("InvokeTaskCompleted"):InvokeServer(unpack(args))
    
    local args = {
        [1] = 10
    }
    
    game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("InvokeTaskCompleted"):InvokeServer(unpack(args))
    
    local args = {
        [1] = 11
    }
    
    game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("InvokeTaskCompleted"):InvokeServer(unpack(args))
    
    local args = {
        [1] = 12
    }
    
    game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("InvokeTaskCompleted"):InvokeServer(unpack(args))
    
    local args = {
        [1] = 13
    }
    
    game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("InvokeTaskCompleted"):InvokeServer(unpack(args))
    
    local args = {
        [1] = 14
    }
    
    game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("InvokeTaskCompleted"):InvokeServer(unpack(args))
    
    local args = {
        [1] = 15
    }
    
    game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("InvokeTaskCompleted"):InvokeServer(unpack(args))
end)

local Tab = Window:NewTab("Hunter")
local MainSection = Tab:NewSection("Hunter")

MainSection:NewButton("ESP", "just use esp to kill them", function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/zachisfunny/esp-unversal/main/script'),true))()
end)

local Tab = Window:NewTab("TeleportHub")
local ScriptSection = Tab:NewSection("TeleportHub")

ScriptSection:NewButton("Click", "TeleportHub", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Patskorn/Teleport/main/All-Map-Pro-Max.lua"))()
end)

local Tab = Window:NewTab("AntiAFK")
local ScriptSection = Tab:NewSection("AntiAFK")

ScriptSection:NewButton("Click", "AntiAFK", function()
    wait(0.5)local ba=Instance.new("ScreenGui")
local ca=Instance.new("TextLabel")local da=Instance.new("Frame")
local _b=Instance.new("TextLabel")local ab=Instance.new("TextLabel")ba.Parent=game.CoreGui
ba.ZIndexBehavior=Enum.ZIndexBehavior.Sibling;ca.Parent=ba;ca.Active=true
ca.BackgroundColor3=Color3.new(0.176471,0.176471,0.176471)ca.Draggable=true
ca.Position=UDim2.new(0.698610067,0,0.098096624,0)ca.Size=UDim2.new(0,370,0,52)
ca.Font=Enum.Font.SourceSansSemibold;ca.Text="Anti Afk"ca.TextColor3=Color3.new(0,1,1)
ca.TextSize=22;da.Parent=ca
da.BackgroundColor3=Color3.new(0.196078,0.196078,0.196078)da.Position=UDim2.new(0,0,1.0192306,0)
da.Size=UDim2.new(0,370,0,107)_b.Parent=da
_b.BackgroundColor3=Color3.new(0.176471,0.176471,0.176471)_b.Position=UDim2.new(0,0,0.800455689,0)
_b.Size=UDim2.new(0,370,0,21)_b.Font=Enum.Font.Arial;_b.Text="discord.gg/BV69gMsDf3"
_b.TextColor3=Color3.new(0,1,1)_b.TextSize=20;ab.Parent=da
ab.BackgroundColor3=Color3.new(0.176471,0.176471,0.176471)ab.Position=UDim2.new(0,0,0.158377,0)
ab.Size=UDim2.new(0,370,0,44)ab.Font=Enum.Font.ArialBold;ab.Text="Status: Active"
ab.TextColor3=Color3.new(0,1,1)ab.TextSize=20;local bb=game:service'VirtualUser'
game:service'Players'.LocalPlayer.Idled:connect(function()
bb:CaptureController()bb:ClickButton2(Vector2.new())
ab.Text="Roblox kicked you but we didnt let them!"wait(2)ab.Text="Status : Active"end)
end)

local Tab = Window:NewTab("infiniteyield")
local infSection = Tab:NewSection("infiniteyield")

infSection:NewButton("Click", "infiniteyield", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end)
