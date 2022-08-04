

local ScreenGui = Instance.new("ScreenGui")
local main = Instance.new("Frame")
local lable = Instance.new("TextLabel")
local projectmeow = Instance.new("TextButton")
local password = Instance.new("TextLabel")

--Properties:

ScreenGui.Parent = game.CoreGui

main.Name = "main"
main.Parent = ScreenGui
main.BackgroundColor3 = Color3.fromRGB(65, 65, 65)
main.BorderColor3 = Color3.fromRGB(65, 65, 65)
main.Position = UDim2.new(0.592630446, 0, 0.601255894, 0)
main.Size = UDim2.new(0, 380, 0, 219)
main.Active = true
main.Draggable = true

lable.Name = "lable"
lable.Parent = main
lable.BackgroundColor3 = Color3.fromRGB(126, 126, 126)
lable.BorderColor3 = Color3.fromRGB(126, 126, 126)
lable.Size = UDim2.new(0, 380, 0, 43)
lable.Font = Enum.Font.SourceSans
lable.Text = "PSX Hacking GUI | v1"
lable.TextColor3 = Color3.fromRGB(0, 0, 0)
lable.TextSize = 14.000

projectmeow.Name = "projectmeow"
projectmeow.Parent = main
projectmeow.BackgroundColor3 = Color3.fromRGB(33, 33, 33)
projectmeow.BorderColor3 = Color3.fromRGB(33, 33, 33)
projectmeow.Position = UDim2.new(0.0157894734, 0, 0.251141548, 0)
projectmeow.Size = UDim2.new(0, 181, 0, 151)
projectmeow.Font = Enum.Font.SourceSans
projectmeow.Text = "Project Meow"
projectmeow.TextColor3 = Color3.fromRGB(0, 0, 0)
projectmeow.TextSize = 25.000
projectmeow.MouseButton1Down:connect(function()
	loadstring(game:HttpGet"https://rawscripts.net/raw/Project-Meow_421")()
end)

password.Name = "password"
password.Parent = main
password.BackgroundColor3 = Color3.fromRGB(33, 33, 33)
password.BorderColor3 = Color3.fromRGB(33, 33, 33)
password.Position = UDim2.new(0.523684204, 0, 0.251141548, 0)
password.Size = UDim2.new(0, 175, 0, 151)
password.Font = Enum.Font.SourceSans
password.Text = "psx update sucks"
password.TextColor3 = Color3.fromRGB(0, 0, 0)
password.TextSize = 25.000
