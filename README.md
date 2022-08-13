-- by hakganinennesi
-- Prsion Life Script

-- Instances:

local Shop = Instance.new("ScreenGui")
local ShopFrame = Instance.new("Frame")
local Gamepasses = Instance.new("ScrollingFrame")
local UltimateJumpPower = Instance.new("TextButton")
local UICorner = Instance.new("UICorner")
local UltimateSpeed = Instance.new("TextButton")
local UICorner_2 = Instance.new("UICorner")
local TeleportPolicebase = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local TeleportCriminalbase = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local TeleportPrison = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local UIAspectRatioConstraint = Instance.new("UIAspectRatioConstraint")
local UITextSizeConstraint = Instance.new("UITextSizeConstraint")
local TextLabel_2 = Instance.new("TextLabel")
local UIAspectRatioConstraint_2 = Instance.new("UIAspectRatioConstraint")
local UITextSizeConstraint_2 = Instance.new("UITextSizeConstraint")
local UICorner_6 = Instance.new("UICorner")
local TextButton = Instance.new("TextButton")
local ShopButton = Instance.new("TextButton")

--Properties:

Shop.Name = "Shop"
Shop.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
Shop.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

ShopFrame.Name = "ShopFrame"
ShopFrame.Parent = Shop
ShopFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ShopFrame.BackgroundTransparency = 1.000
ShopFrame.Position = UDim2.new(0.23133415, 0, 0.160148978, 0)
ShopFrame.Size = UDim2.new(0, 526, 0, 365)

Gamepasses.Name = "Gamepasses"
Gamepasses.Parent = ShopFrame
Gamepasses.Active = true
Gamepasses.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Gamepasses.BorderColor3 = Color3.fromRGB(255, 255, 255)
Gamepasses.Position = UDim2.new(0.197113618, 0, 0.0275503453, 0)
Gamepasses.Size = UDim2.new(0, 525, 0, 322)
Gamepasses.BottomImage = ""
Gamepasses.MidImage = ""
Gamepasses.ScrollingEnabled = false
Gamepasses.TopImage = ""

UltimateJumpPower.Name = "Ultimate Jump Power"
UltimateJumpPower.Parent = Gamepasses
UltimateJumpPower.BackgroundColor3 = Color3.fromRGB(53, 53, 53)
UltimateJumpPower.Position = UDim2.new(0.317809224, 0, 0.296826333, 0)
UltimateJumpPower.Size = UDim2.new(0, 200, 0, 50)
UltimateJumpPower.Font = Enum.Font.SourceSans
UltimateJumpPower.Text = "Ultimate Jump Power"
UltimateJumpPower.TextColor3 = Color3.fromRGB(255, 255, 255)
UltimateJumpPower.TextSize = 25.000
UltimateJumpPower.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.Humanoid.JumpPower =300
end)

UICorner.Parent = UltimateJumpPower

UltimateSpeed.Name = "Ultimate Speed"
UltimateSpeed.Parent = Gamepasses
UltimateSpeed.BackgroundColor3 = Color3.fromRGB(53, 53, 53)
UltimateSpeed.Position = UDim2.new(0.546845138, 0, 0.204001099, 0)
UltimateSpeed.Size = UDim2.new(0, 200, 0, 50)
UltimateSpeed.Font = Enum.Font.SourceSans
UltimateSpeed.Text = "Utlimate Speed"
UltimateSpeed.TextColor3 = Color3.fromRGB(255, 255, 255)
UltimateSpeed.TextSize = 25.000
UltimateSpeed.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 80
end)

UICorner_2.Parent = UltimateSpeed

TeleportPolicebase.Name = "Teleport Police base"
TeleportPolicebase.Parent = Gamepasses
TeleportPolicebase.BackgroundColor3 = Color3.fromRGB(53, 53, 53)
TeleportPolicebase.Position = UDim2.new(0.546845138, 0, 0.0972060412, 0)
TeleportPolicebase.Size = UDim2.new(0, 200, 0, 50)
TeleportPolicebase.Font = Enum.Font.SourceSans
TeleportPolicebase.Text = "Teleport Police base"
TeleportPolicebase.TextColor3 = Color3.fromRGB(255, 255, 255)
TeleportPolicebase.TextSize = 25.000
TeleportPolicebase.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(848.039978, 99.9899826, 2304.01953, -0.0968298912, 3.04834913e-08, 0.995300949, 1.96133119e-08, 1, -2.87192901e-08, -0.995300949, 1.67402625e-08, -0.0968298912)
end)

UICorner_3.Parent = TeleportPolicebase

TeleportCriminalbase.Name = "Teleport Criminal base"
TeleportCriminalbase.Parent = Gamepasses
TeleportCriminalbase.BackgroundColor3 = Color3.fromRGB(53, 53, 53)
TeleportCriminalbase.Position = UDim2.new(0.0716767758, 0, 0.0972060412, 0)
TeleportCriminalbase.Size = UDim2.new(0, 200, 0, 50)
TeleportCriminalbase.Font = Enum.Font.SourceSans
TeleportCriminalbase.Text = "Teleport Criminal base"
TeleportCriminalbase.TextColor3 = Color3.fromRGB(255, 255, 255)
TeleportCriminalbase.TextSize = 25.000
TeleportCriminalbase.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-920.510803, 95.327179, 2144.6709, 0, 0, -1, 0, 1, 0, 1, 0, 0)
end)

UICorner_4.Parent = TeleportCriminalbase

TeleportPrison.Name = "Teleport Prison"
TeleportPrison.Parent = Gamepasses
TeleportPrison.BackgroundColor3 = Color3.fromRGB(53, 53, 53)
TeleportPrison.Position = UDim2.new(0.0716767758, 0, 0.203105927, 0)
TeleportPrison.Size = UDim2.new(0, 200, 0, 50)
TeleportPrison.Font = Enum.Font.SourceSans
TeleportPrison.Text = "Teleport Prison Base"
TeleportPrison.TextColor3 = Color3.fromRGB(255, 255, 255)
TeleportPrison.TextSize = 25.000
TeleportPrison.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(914.501221, 99.9899826, 2443.53076, -0.999767363, 5.55477619e-08, -0.0215685107, 5.59893536e-08, 1, -1.98698995e-08, 0.0215685107, -2.10728839e-08, -0.999767363)
end)

UICorner_5.Parent = TeleportPrison

TextLabel.Parent = Gamepasses
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(-0.00170534477, 0, 0.424711734, 0)
TextLabel.Size = UDim2.new(0.185035497, 0, 0.184554458, 0)
TextLabel.Font = Enum.Font.PermanentMarker
TextLabel.Text = "by hakganinennesi"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextScaled = true
TextLabel.TextSize = 42.000
TextLabel.TextWrapped = true

UIAspectRatioConstraint.Parent = TextLabel
UIAspectRatioConstraint.AspectRatio = 8.453

UITextSizeConstraint.Parent = TextLabel
UITextSizeConstraint.MaxTextSize = 42

TextLabel_2.Parent = Gamepasses
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Position = UDim2.new(0.337342322, 0, 0.0149276294, 0)
TextLabel_2.Size = UDim2.new(0.324083179, 0, 0.0791667104, 0)
TextLabel_2.Font = Enum.Font.PermanentMarker
TextLabel_2.Text = "-Prison Life Hack-"
TextLabel_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 42.000
TextLabel_2.TextWrapped = true

UIAspectRatioConstraint_2.Parent = TextLabel_2
UIAspectRatioConstraint_2.AspectRatio = 8.453

UITextSizeConstraint_2.Parent = TextLabel_2
UITextSizeConstraint_2.MaxTextSize = 42

UICorner_6.Parent = Gamepasses

TextButton.Parent = Gamepasses
TextButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton.BackgroundTransparency = 1.000
TextButton.Position = UDim2.new(0.862857163, 0, -0.00677682366, 0)
TextButton.Size = UDim2.new(0, 72, 0, 50)
TextButton.Font = Enum.Font.SourceSans
TextButton.Text = "X"
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextSize = 30.000
TextButton.MouseButton1Click:Connect(function()
	Gamepasses.Visible = false
	ShopButton.Visible = true
end)

ShopButton.Name = "ShopButton"
ShopButton.Parent = Shop
ShopButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ShopButton.BorderSizePixel = 0
ShopButton.Position = UDim2.new(0, 0, 0.374301672, 0)
ShopButton.Size = UDim2.new(0, 100, 0, 50)
ShopButton.Font = Enum.Font.FredokaOne
ShopButton.Text = "Open"
ShopButton.TextColor3 = Color3.fromRGB(0, 0, 0)
ShopButton.TextScaled = true
ShopButton.TextSize = 14.000
ShopButton.TextWrapped = true
ShopButton.MouseButton1Click:Connect(function()
	Gamepasses.Visible = true
	ShopButton.Visible = false
	
end)
