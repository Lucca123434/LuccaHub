-- Lucca Hub Script para Blox Fruits
local LuccaHub = Instance.new("ScreenGui")
local MainFrame = Instance.new("Frame")
local AutoFarmButton = Instance.new("TextButton")
local TeleportButton = Instance.new("TextButton")
local ESPButton = Instance.new("TextButton")
local GodModeButton = Instance.new("TextButton")
local SpeedHackButton = Instance.new("TextButton")
local SoulGuitarButton = Instance.new("TextButton")
local CDKButton = Instance.new("TextButton")
local TTKButton = Instance.new("TextButton")
local SanguineArtButton = Instance.new("TextButton")
local CloseButton = Instance.new("TextButton")

-- Propriedades do GUI
LuccaHub.Name = "LuccaHub"
LuccaHub.Parent = game.CoreGui

MainFrame.Name = "MainFrame"
MainFrame.Parent = LuccaHub
MainFrame.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
MainFrame.Position = UDim2.new(0.5, -100, 0.5, -250)
MainFrame.Size = UDim2.new(0, 200, 0, 450)

AutoFarmButton.Name = "AutoFarmButton"
AutoFarmButton.Parent = MainFrame
AutoFarmButton.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
AutoFarmButton.Position = UDim2.new(0.1, 0, 0.05, 0)
AutoFarmButton.Size = UDim2.new(0, 160, 0, 30)
AutoFarmButton.Text = "Auto Farm"

TeleportButton.Name = "TeleportButton"
TeleportButton.Parent = MainFrame
TeleportButton.BackgroundColor3 = Color3.fromRGB(0, 255, 0)
TeleportButton.Position = UDim2.new(0.1, 0, 0.15, 0)
TeleportButton.Size = UDim2.new(0, 160, 0, 30)
TeleportButton.Text = "Teleport"

ESPButton.Name = "ESPButton"
ESPButton.Parent = MainFrame
ESPButton.BackgroundColor3 = Color3.fromRGB(0, 0, 255)
ESPButton.Position = UDim2.new(0.1, 0, 0.25, 0)
ESPButton.Size = UDim2.new(0, 160, 0, 30)
ESPButton.Text = "ESP"

GodModeButton.Name = "GodModeButton"
GodModeButton.Parent = MainFrame
GodModeButton.BackgroundColor3 = Color3.fromRGB(255, 255, 0)
GodModeButton.Position = UDim2.new(0.1, 0, 0.35, 0)
GodModeButton.Size = UDim2.new(0, 160, 0, 30)
GodModeButton.Text = "God Mode"

SpeedHackButton.Name = "SpeedHackButton"
SpeedHackButton.Parent = MainFrame
SpeedHackButton.BackgroundColor3 = Color3.fromRGB(255, 165, 0)
SpeedHackButton.Position = UDim2.new(0.1, 0, 0.45, 0)
SpeedHackButton.Size = UDim2.new(0, 160, 0, 30)
SpeedHackButton.Text = "Speed Hack"

SoulGuitarButton.Name = "SoulGuitarButton"
SoulGuitarButton.Parent = MainFrame
SoulGuitarButton.BackgroundColor3 = Color3.fromRGB(128, 0, 128)
SoulGuitarButton.Position = UDim2.new(0.1, 0, 0.55, 0)
SoulGuitarButton.Size = UDim2.new(0, 160, 0, 30)
SoulGuitarButton.Text = "Pegar Soul Guitar"

CDKButton.Name = "CDKButton"
CDKButton.Parent = MainFrame
CDKButton.BackgroundColor3 = Color3.fromRGB(0, 128, 128)
CDKButton.Position = UDim2.new(0.1, 0, 0.65, 0)
CDKButton.Size = UDim2.new(0, 160, 0, 30)
CDKButton.Text = "Pegar CDK"

TTKButton.Name = "TTKButton"
TTKButton.Parent = MainFrame
TTKButton.BackgroundColor3 = Color3.fromRGB(128, 128, 0)
TTKButton.Position = UDim2.new(0.1, 0, 0.75, 0)
TTKButton.Size = UDim2.new(0, 160, 0, 30)
TTKButton.Text = "Pegar TTK"

SanguineArtButton.Name = "SanguineArtButton"
SanguineArtButton.Parent = MainFrame
SanguineArtButton.BackgroundColor3 = Color3.fromRGB(255, 0, 255)
SanguineArtButton.Position = UDim2.new(0.1, 0, 0.85, 0)
SanguineArtButton.Size = UDim2.new(0, 160, 0, 30)
SanguineArtButton.Text = "Pegar Sanguine Art"

CloseButton.Name = "CloseButton"
CloseButton.Parent = MainFrame
CloseButton.BackgroundColor3 = Color3.fromRGB(128, 128, 128)
CloseButton.Position = UDim2.new(0.1, 0, 0.95, 0)
CloseButton.Size = UDim2.new(0, 160, 0, 30)
CloseButton.Text = "Close"

-- Funções dos botões
AutoFarmButton.MouseButton1Click:Connect(function()
    print("Auto Farm ativado")
    -- Adicione o código de auto farm aqui
end)

TeleportButton.MouseButton1Click:Connect(function()
    print("Teleporte ativado")
    -- Adicione o código de teleporte aqui
end)

ESPButton.MouseButton1Click:Connect(function()
    print("ESP ativado")
    -- Adicione o código de ESP aqui
end)

GodModeButton.MouseButton1Click:Connect(function()
    print("God Mode ativado")
    -- Adicione o código de God Mode aqui
end)

SpeedHackButton.MouseButton1Click:Connect(function()
    print("Speed Hack ativado")
    -- Adicione o código de Speed Hack aqui
end)

SoulGuitarButton.MouseButton1Click:Connect(function()
    print("Pegando Soul Guitar")
    -- Adicione o código para pegar a Soul Guitar aqui
end)

CDKButton.MouseButton1Click:Connect(function()
    print("Pegando CDK")
    -- Adicione o código para pegar a CDK aqui
end)

TTKButton.MouseButton1Click:Connect(function()
    print("Pegando TTK")
    -- Adicione o código para pegar a TTK aqui
end)

SanguineArtButton.MouseButton1Click:Connect(function()
    print("Pegando Sanguine Art")
    -- Adicione o código para pegar a Sanguine Art aqui
end)

CloseButton.MouseButton1Click:Connect(function()
    LuccaHub:Destroy()
end)
