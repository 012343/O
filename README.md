local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()

local Window = Rayfield:CreateWindow({
   Name = "South Bronx | Free Script | South Bronx: The Trenches❗",
   LoadingTitle = "0_12343 Free Script",
   LoadingSubtitle = "Created by 0_12343",
   ConfigurationSaving = {
      Enabled = true,
      FolderName = nil, -- Create a custom folder for your hub/game
      FileName = "South Bronx Hub"
   },
    Discord = {
        Enabled = false,
        Invite = "",
        RememberJoins = false
    },
   KeySystem = false, -- Enable key system
    KeySettings = {
        Title = "Key System",
        Subtitle = "Created by yDxvxd",
        Note = "To get the key, add ydxvxd.xyz on discord",
        FileName = "MAGMA HUB KEY",
        SaveKey = true, -- Key won't be saved permanently
        GrabKeyFromSite = false,
        Key = {"https://pastebin.com/8CNh8LDk"} -- List of accepted keys or key URLs
    }
})

Rayfield:Notify({
   Title = "Welcome To MAGMA HUB",
   Content = "Thanks for using our script!",
   Duration = 5,
   Image = nil,
   Actions = { -- Notification Buttons
      Ignore = {
         Name = "...",
         Callback = function()
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
         print("Join Discord https://discord.gg/NBvmSdxfz9")
      end
   },
},
})

local InfoTab = Window:CreateTab("Info", nil) -- Title, Image
local InfoSection = InfoTab:CreateSection("Info")

local PlayerTab = Window:CreateTab("Player", nil) -- Title, Image
local PlayerSection = PlayerTab:CreateSection("Player")

local ESPTab = Window:CreateTab("ESP", nil) -- Title, Image
local ESPSection = ESPTab:CreateSection("ESP")

local AimlockTab = Window:CreateTab("Aimlock", nil) -- Title, Image
local AimlockSection = AimlockTab:CreateSection("Aimlock")

local AutofarmTab = Window:CreateTab("AutoFarm", nil) -- Title, Image
local Section = AutofarmTab:CreateSection("Autofarm")

local InfYTab = Window:CreateTab("Inf Yeld")
local InfYSection = InfYTab:CreateSection("InfY")

-- Player Tab - Walk Speed
local Slider = PlayerTab:CreateSlider({
    Name = "Walk Speed",
    Range = {0, 23},
    Increment = 1,
    Suffix = "Speed",
    CurrentValue = 16,
    Flag = "Slider1", -- Ensure the flag is unique
    Callback = function(Value)
        local player = game.Players.LocalPlayer
        if player and player.Character and player.Character:FindFirstChild("Humanoid") then
            player.Character.Humanoid.WalkSpeed = Value
        end
    end
})

local Button = PlayerTab:CreateButton({
    Name = "Instant interact",
    Callback = function()
         for i,v in pairs(game:GetService("Workspace"):GetDescendants()) do
    if v:IsA("ProximityPrompt") then
        v["HoldDuration"] = 0
    end
end
 
 
game:GetService("ProximityPromptService").PromptButtonHoldBegan:Connect(function(v)
    v["HoldDuration"] = 0
end) 
   end,
})

-- Textbox to input aim lock key
local KeyInput = AimlockTab:CreateInput({
    Name = "AimLock Key",
    PlaceholderText = "Enter Key (Any Key)",
    RemoveTextAfterFocusLost = false,
    Callback = function(inputKey)
        AimLockKey = inputKey:lower()
        Rayfield:Notify({
            Title = "Key Updated",
            Content = "Aimlock key updated to: " .. AimLockKey,
            Duration = 3
        })
    end
})

-- Textbox to input prediction factor
local PredictionInput = AimlockTab:CreateInput({
    Name = "AimLock Prediction",
    PlaceholderText = "Enter Prediction (0.1 - 1)",
    RemoveTextAfterFocusLost = false,
    Callback = function(inputPrediction)
        local newPrediction = tonumber(inputPrediction)
        if newPrediction then
            PredictionFactor = newPrediction
            Rayfield:Notify({
                Title = "Prediction Updated",
                Content = "Prediction factor set to: " .. tostring(PredictionFactor),
                Duration = 3
            })
        else
            Rayfield:Notify({
                Title = "Invalid Input",
                Content = "Please enter a valid number for prediction.",
                Duration = 3
            })
        end
    end
})

-- Aim Lock Button with user-defined key and prediction factor
local Button = AimlockTab:CreateButton({
    Name = "Activate AimLock",
    Callback = function()
        local Players = game:GetService("Players")
        local RunService = game:GetService("RunService")
        local LocalPlayer = Players.LocalPlayer
        local CamlockState = false
        local enemy = nil

        -- Function to find nearest enemy and lock onto their head
        local function FindNearestEnemy()
            local ClosestDistance, ClosestPlayer = math.huge, nil
            local CenterPosition = Vector2.new(
                game:GetService("GuiService"):GetScreenResolution().X / 2,
                game:GetService("GuiService"):GetScreenResolution().Y / 2
            )
            for _, Player in ipairs(Players:GetPlayers()) do
                if Player ~= LocalPlayer then
                    local Character = Player.Character
                    if Character and Character:FindFirstChild("Head") and Character.Humanoid.Health > 0 then
                        local Position, OnScreen = workspace.CurrentCamera:WorldToViewportPoint(Character.Head.Position)
                        if OnScreen then
                            local Distance = (CenterPosition - Vector2.new(Position.X, Position.Y)).Magnitude
                            if Distance < ClosestDistance then
                                ClosestPlayer = Character.Head -- Target the Head
                                ClosestDistance = Distance
                            end
                        end
                    end
                end
            end
            return ClosestPlayer
        end

        -- Function to apply prediction to the enemy position
        local function GetPredictedPosition(enemyHead)
            if enemyHead and enemyHead.Velocity then
                return enemyHead.Position + (enemyHead.Velocity * PredictionFactor)
            end
            return enemyHead.Position
        end

        -- Camera lock loop
        RunService.Heartbeat:Connect(function()
            if CamlockState and enemy then
                local targetPosition = GetPredictedPosition(enemy)
                workspace.CurrentCamera.CFrame = CFrame.new(workspace.CurrentCamera.CFrame.p, targetPosition)
            end
        end)

        -- Keybind to toggle aim lock with the user-defined key
        LocalPlayer:GetMouse().KeyDown:Connect(function(key)
            if key == AimLockKey then
                CamlockState = not CamlockState
                if CamlockState then
                    enemy = FindNearestEnemy()
                else
                    enemy = nil
                end
            end
        end)
    end
})

-- ESP Tab - Boxes
local Button = ESPTab:CreateButton({
    Name = "ESP Boxes",
    Callback = function()
        local settings = {
            defaultcolor = Color3.fromRGB(255, 0, 0),
            teamcheck = false,
            teamcolor = true
        }

        local runService = game:GetService("RunService")
        local players = game:GetService("Players")
        local localPlayer = players.LocalPlayer
        local camera = workspace.CurrentCamera

        local espCache = {}

        -- Function to create ESP box for a player
        local function createEsp(player)
            local drawings = {}
            -- Create the main ESP box
            drawings.box = Drawing.new("Square")
            drawings.box.Thickness = 1
            drawings.box.Filled = false
            drawings.box.Color = settings.defaultcolor
            drawings.box.Visible = false
            drawings.box.ZIndex = 2

            -- Create the outline for the box
            drawings.boxoutline = Drawing.new("Square")
            drawings.boxoutline.Thickness = 3
            drawings.boxoutline.Filled = false
            drawings.boxoutline.Color = Color3.new()
            drawings.boxoutline.Visible = false
            drawings.boxoutline.ZIndex = 1

            espCache[player] = drawings
        end

        -- Function to remove ESP when a player leaves
        local function removeEsp(player)
            if espCache[player] then
                for _, drawing in pairs(espCache[player]) do
                    drawing:Remove()
                end
                espCache[player] = nil
            end
        end

        -- Function to update ESP box position
        local function updateEsp(player, esp)
            local character = player.Character
            if character and character:FindFirstChild("HumanoidRootPart") then
                local position, visible = camera:WorldToViewportPoint(character.HumanoidRootPart.Position)
                esp.box.Visible = visible
                esp.boxoutline.Visible = visible

                if visible then
                    -- Calculate box size and position based on distance
                    local scaleFactor = 1 / (position.Z * math.tan(math.rad(camera.FieldOfView / 2)) * 2) * 1000
                    local width, height = math.round(4 * scaleFactor), math.round(5 * scaleFactor)
                    local x, y = math.round(position.X), math.round(position.Y)

                    esp.box.Size = Vector2.new(width, height)
                    esp.box.Position = Vector2.new(x - width / 2, y - height / 2)
                    esp.box.Color = settings.teamcolor and player.TeamColor.Color or settings.defaultcolor

                    esp.boxoutline.Size = esp.box.Size
                    esp.boxoutline.Position = esp.box.Position
                end
            else
                esp.box.Visible = false
                esp.boxoutline.Visible = false
            end
        end

        -- Apply ESP to all current players
        for _, player in pairs(players:GetPlayers()) do
            if player ~= localPlayer then
                createEsp(player)
            end
        end

        -- Handle new players joining the game
        players.PlayerAdded:Connect(function(player)
            createEsp(player)
        end)

        -- Handle players leaving the game
        players.PlayerRemoving:Connect(function(player)
            removeEsp(player)
        end)

        -- Continuously update the ESP boxes for all players
        runService.RenderStepped:Connect(function()
            for player, drawings in pairs(espCache) do
                if settings.teamcheck and player.Team == localPlayer.Team then
                end

                if player ~= localPlayer then
                    updateEsp(player, drawings)
                end
            end
        end)
    end
})

local Button = ESPTab:CreateButton({
    Name = "ESP Names",
    Callback = function()
    -- Services
local players = game:GetService("Players")
local runService = game:GetService("RunService")
local camera = workspace.CurrentCamera
local localPlayer = players.LocalPlayer

-- Table to store the ESP drawings
local nameEspCache = {}

-- Function to create name ESP for a player
local function createNameEsp(player)
    if player == localPlayer then return end -- Don't show name for local player

    local drawing = Drawing.new("Text")
    drawing.Text = player.Name
    drawing.Size = 8  -- Smaller text size
    drawing.Color = Color3.new(1, 1, 1) -- White text
    drawing.Outline = true
    drawing.OutlineColor = Color3.new(0, 0, 0) -- Black outline
    drawing.Center = true
    drawing.Visible = false

    nameEspCache[player] = drawing
end
-- Function to remove the ESP drawing when a player leaves
local function removeNameEsp(player)
    if nameEspCache[player] then
        nameEspCache[player]:Remove()
        nameEspCache[player] = nil
    end
end

-- Function to update the ESP name position
local function updateNameEsp(player, drawing)
    local character = player.Character
    if character and character:FindFirstChild("Head") then
        local headPosition = character.Head.Position
        local screenPosition, onScreen = camera:WorldToViewportPoint(headPosition)

        if onScreen then
            -- Offset below the head for the name label
            drawing.Position = Vector2.new(screenPosition.X, screenPosition.Y + 20) -- Adjusted offset below the head
            drawing.Visible = true
        else
            drawing.Visible = false
        end
    else
        drawing.Visible = false
    end
end

-- Apply name ESP to all current players
for _, player in pairs(players:GetPlayers()) do
    createNameEsp(player)
end

-- Handle new players joining the game
players.PlayerAdded:Connect(function(player)
    createNameEsp(player)
end)

-- Handle players leaving the game
players.PlayerRemoving:Connect(function(player)
    removeNameEsp(player)
end)

-- Continuously update the name ESPs for all players
runService.RenderStepped:Connect(function()
    for player, drawing in pairs(nameEspCache) do
        updateNameEsp(player, drawing)
    end
    end)
    end,
 })

local Button = ESPTab:CreateButton({
   Name = "ESP ShowGuns By SergiuPro",
   Callback = function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/SergiuPro211/SouthCottonFREE/main/ShowGuns"))()
   end,
})

local Button = InfYTab:CreateButton({
   Name = "Inf Yeld",
    Callback = function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'),true))()
    end,
})

local Button = AutofarmTab:CreateButton({
   Name = "Box AutoFarm To Truck",
   Callback = function()
         Wait(3)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-552, 4, -83)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-552, 4, -86)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-549, 4, -83)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-546, 4, -83)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-544, 4, -83)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-541, 4, -83)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-538, 4, -83)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-536, 4, -82)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-532, 3, -81)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-530, 3, -81)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-528, 3, -81)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-527, 3, -81)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-524, 3, -81)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-521, 3, -81)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-518, 3, -81)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-515, 3, -80)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-513, 3, -80)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-511, 3, -80)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-508, 3, -79)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-505, 3, -79)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-499, 3, -79)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-495, 3, -78)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-492, 3, -78)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-487, 3, -78)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-483, 3, -77)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-479, 3, -77)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-474, 3, -77)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-471, 3, -76)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-468, 3, -76)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-463, 3, -76)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-460, 3, -76)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-458, 4, -76)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-455, 4, -75)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-452, 4, -75)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-452, 4, -75)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-449, 4, -75)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-445, 4, -74)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-440, 3, -74)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-437, 3, -74)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-434, 3, -74)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-430, 3, -73)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-427, 3, -73)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-424, 3, -73)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-421, 3, -73)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-418, 3, -72)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-415, 3, -72)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-413, 3, -72)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-410, 3, -72)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-407, 3, -72)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-404, 3, -72)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-401, 3, -72)
   end,
})

local Button = AutofarmTab:CreateButton({
   Name = "Box AutoFarm From Truck",
   Callback = function()
         Wait(3)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-401, 3, -72)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-404, 3, -72)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-407, 3, -72)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-410, 3, -72)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-413, 3, -72)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-415, 3, -72)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-418, 3, -72)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-421, 3, -73)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-424, 3, -73)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-427, 3, -73)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-430, 3, -73)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-434, 3, -74)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-437, 3, -74)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-440, 3, -74)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-445, 4, -74)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-449, 4, -75)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-452, 4, -75)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-455, 4, -75)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-458, 4, -76)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-460, 3, -76)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-463, 3, -76)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-468, 3, -76)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-471, 3, -76)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-474, 3, -77)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-479, 3, -77)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-483, 3, -77)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-487, 3, -78)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-492, 3, -78)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-495, 3, -78)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-499, 3, -79)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-505, 3, -79)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-508, 3, -79)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-511, 3, -80)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-513, 3, -80)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-515, 3, -80)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-518, 3, -81)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-521, 3, -81)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-524, 3, -81)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-527, 3, -81)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-528, 3, -81)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-530, 3, -81)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-532, 3, -81)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-536, 4, -82)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-538, 4, -83)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-541, 4, -83)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-544, 4, -83)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-546, 4, -83)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-549, 4, -83)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-552, 4, -83)

Wait(0.5)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

humanoidRootPart.CFrame = CFrame.new(-552, 4, -86)
   end,
})
