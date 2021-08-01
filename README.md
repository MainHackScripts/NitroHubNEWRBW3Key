local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/wally2", true))()
local w = library:CreateWindow('Whitelist')



local box = w:Box('Username', {

}, function(keyy)


if keyy ==  tostring("vob") then  --- vob = key
    local sound = Instance.new("Sound", game.Workspace)
sound.SoundId = "rbxassetid://1839997929"
sound:Play()
    print("Correct Username")
    game:GetService"StarterGui":SetCore("SendNotification", { Title = "System", Text = "Correct Username", Duration = 3 })
    
    local box = w:Box('Password', {

}, function(no)

if no == tostring("123") then
    local sound = Instance.new("Sound", game.Workspace)
sound.SoundId = "rbxassetid://1839997929"
sound:Play()
    print("Correct Password")
     game:GetService"StarterGui":SetCore("SendNotification", { Title = "System", Text = "Correct Password", Duration = 3 })
     game:GetService"CoreGui":FindFirstChild"ScreenGui":Destroy()
     loadstring(game:HttpGet("https://raw.githubusercontent.com/MainHackScripts/NitroHubNEWRBW3Script/main/README.md"))()
     else
         local sound = Instance.new("Sound", game.Workspace)
sound.SoundId = "rbxassetid://6692725713"
sound:Play()
          game:GetService"StarterGui":SetCore("SendNotification", { Title = "System", Text = "InCorrect Password", Duration = 3 })
          print("InCorrect Password")
         end
end)
    else
        local sound = Instance.new("Sound", game.Workspace)
sound.SoundId = "rbxassetid://6692725713"
sound:Play()
        game:GetService"StarterGui":SetCore("SendNotification", { Title = "System", Text = "InCorrect Username", Duration = 3 })
        print("InCorrect Username")
    end
 
end)

test = game.Players.LocalPlayer.AccountAge
test1 = game.Players.LocalPlayer.Name
test2 = game.Players.LocalPlayer.DisplayName
local w1 = library:CreateWindow('Stats')
w1:Section('AccountAge')
w1:Section(test)
w1:Section('DisplayName')
w1:Section(test1)
