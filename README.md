-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local HaxFrame = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local Frame = Instance.new("Frame")
local UICorner_2 = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local PlayerButton = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local PlayerFrame = Instance.new("Frame")
local ListFrame = Instance.new("Frame")
local UICorner_4 = Instance.new("UICorner")
local TextButton = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local TextButton_2 = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local TextButton_3 = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local TextButton_4 = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local CloseButton = Instance.new("TextButton")
local UICorner_9 = Instance.new("UICorner")
local TextButton_5 = Instance.new("TextButton")
local UICorner_10 = Instance.new("UICorner")
local Frame_2 = Instance.new("Frame")
local UICorner_11 = Instance.new("UICorner")
local ListFrame2 = Instance.new("Frame")
local UICorner_12 = Instance.new("UICorner")
local TextButton_6 = Instance.new("TextButton")
local UICorner_13 = Instance.new("UICorner")
local TextButton_7 = Instance.new("TextButton")
local UICorner_14 = Instance.new("UICorner")
local TextButton_8 = Instance.new("TextButton")
local UICorner_15 = Instance.new("UICorner")
local TextButton_9 = Instance.new("TextButton")
local UICorner_16 = Instance.new("UICorner")
local CloseButton_2 = Instance.new("TextButton")
local UICorner_17 = Instance.new("UICorner")
local TextButton_10 = Instance.new("TextButton")
local UICorner_18 = Instance.new("UICorner")
local WorldButton = Instance.new("TextButton")
local UICorner_19 = Instance.new("UICorner")
local WorldFrame = Instance.new("Frame")
local TextButton_11 = Instance.new("TextButton")
local UICorner_20 = Instance.new("UICorner")
local Frame_3 = Instance.new("Frame")
local UICorner_21 = Instance.new("UICorner")

--Properties:

ScreenGui.Parent = game.CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

HaxFrame.Name = "HaxFrame"
HaxFrame.Parent = ScreenGui
HaxFrame.BackgroundColor3 = Color3.fromRGB(33, 33, 33)
HaxFrame.BackgroundTransparency = 0.070
HaxFrame.Position = UDim2.new(0.299903572, 0, 0.127009645, 0)
HaxFrame.Size = UDim2.new(0, 512, 0, 463)

UICorner.Parent = HaxFrame

Frame.Parent = HaxFrame
Frame.BackgroundColor3 = Color3.fromRGB(255, 0, 4)
Frame.Position = UDim2.new(-0.00174403191, 0, -0.000420160475, 0)
Frame.Size = UDim2.new(0, 512, 0, 38)

UICorner_2.Parent = Frame

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Position = UDim2.new(0, 0, 1.49011612e-08, 0)
TextLabel.Size = UDim2.new(0, 512, 0, 38)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Xypyt Hub | V2"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

PlayerButton.Name = "PlayerButton"
PlayerButton.Parent = HaxFrame
PlayerButton.BackgroundColor3 = Color3.fromRGB(149, 0, 2)
PlayerButton.Position = UDim2.new(0, 0, 0.10799136, 0)
PlayerButton.Size = UDim2.new(0, 106, 0, 21)
PlayerButton.Font = Enum.Font.SourceSans
PlayerButton.Text = "Player"
PlayerButton.TextColor3 = Color3.fromRGB(255, 255, 255)
PlayerButton.TextScaled = true
PlayerButton.TextSize = 14.000
PlayerButton.TextWrapped = true

UICorner_3.Parent = PlayerButton

PlayerFrame.Name = "PlayerFrame"
PlayerFrame.Parent = HaxFrame
PlayerFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
PlayerFrame.BackgroundTransparency = 1.000
PlayerFrame.Position = UDim2.new(0.220703125, 0, 0.0799136087, 0)
PlayerFrame.Size = UDim2.new(0, 399, 0, 426)
PlayerFrame.Visible = false

ListFrame.Name = "ListFrame"
ListFrame.Parent = PlayerFrame
ListFrame.BackgroundColor3 = Color3.fromRGB(0, 166, 255)
ListFrame.Position = UDim2.new(0.0545066893, 0, 0.0657276958, 0)
ListFrame.Size = UDim2.new(0, 145, 0, 15)
ListFrame.Visible = false

UICorner_4.Parent = ListFrame

TextButton.Parent = ListFrame
TextButton.BackgroundColor3 = Color3.fromRGB(0, 81, 255)
TextButton.Position = UDim2.new(-0.00630051177, 0, 0.160405442, 0)
TextButton.Size = UDim2.new(0, 145, 0, 18)
TextButton.Font = Enum.Font.SourceSans
TextButton.Text = "100"
TextButton.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton.TextScaled = true
TextButton.TextSize = 14.000
TextButton.TextWrapped = true

UICorner_5.Parent = TextButton

TextButton_2.Parent = ListFrame
TextButton_2.BackgroundColor3 = Color3.fromRGB(0, 81, 255)
TextButton_2.Position = UDim2.new(-0.00630051177, 0, 0.343969911, 0)
TextButton_2.Size = UDim2.new(0, 145, 0, 18)
TextButton_2.Font = Enum.Font.SourceSans
TextButton_2.Text = "200"
TextButton_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_2.TextScaled = true
TextButton_2.TextSize = 14.000
TextButton_2.TextWrapped = true

UICorner_6.Parent = TextButton_2

TextButton_3.Parent = ListFrame
TextButton_3.BackgroundColor3 = Color3.fromRGB(0, 81, 255)
TextButton_3.Position = UDim2.new(-0.00630051177, 0, 0.526979685, 0)
TextButton_3.Size = UDim2.new(0, 145, 0, 18)
TextButton_3.Font = Enum.Font.SourceSans
TextButton_3.Text = "300"
TextButton_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_3.TextScaled = true
TextButton_3.TextSize = 14.000
TextButton_3.TextWrapped = true

UICorner_7.Parent = TextButton_3

TextButton_4.Parent = ListFrame
TextButton_4.BackgroundColor3 = Color3.fromRGB(0, 81, 255)
TextButton_4.Position = UDim2.new(-0.00630051177, 0, 0.705551147, 0)
TextButton_4.Size = UDim2.new(0, 145, 0, 18)
TextButton_4.Font = Enum.Font.SourceSans
TextButton_4.Text = "400"
TextButton_4.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_4.TextScaled = true
TextButton_4.TextSize = 14.000
TextButton_4.TextWrapped = true

UICorner_8.Parent = TextButton_4

CloseButton.Name = "CloseButton"
CloseButton.Parent = ListFrame
CloseButton.BackgroundColor3 = Color3.fromRGB(0, 150, 225)
CloseButton.Position = UDim2.new(-0.00630051177, 0, 0.869836867, 0)
CloseButton.Size = UDim2.new(0, 145, 0, 18)
CloseButton.Font = Enum.Font.SourceSans
CloseButton.Text = "CLOSE"
CloseButton.TextColor3 = Color3.fromRGB(255, 255, 255)
CloseButton.TextScaled = true
CloseButton.TextSize = 14.000
CloseButton.TextWrapped = true

UICorner_9.Parent = CloseButton

TextButton_5.Parent = PlayerFrame
TextButton_5.BackgroundColor3 = Color3.fromRGB(0, 166, 255)
TextButton_5.Position = UDim2.new(0.0545066372, 0, 0.0305164326, 0)
TextButton_5.Size = UDim2.new(0, 145, 0, 30)
TextButton_5.Font = Enum.Font.SourceSans
TextButton_5.Text = "WalkSpeed"
TextButton_5.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_5.TextScaled = true
TextButton_5.TextSize = 14.000
TextButton_5.TextWrapped = true

UICorner_10.Parent = TextButton_5

Frame_2.Parent = PlayerFrame
Frame_2.BackgroundColor3 = Color3.fromRGB(79, 79, 79)
Frame_2.BackgroundTransparency = 0.500
Frame_2.Position = UDim2.new(0.025062656, 0, 0, 0)
Frame_2.Size = UDim2.new(0, 6, 0, 426)

UICorner_11.Parent = Frame_2

ListFrame2.Name = "ListFrame2"
ListFrame2.Parent = PlayerFrame
ListFrame2.BackgroundColor3 = Color3.fromRGB(0, 166, 255)
ListFrame2.Position = UDim2.new(0.503128231, 0, 0.0657276958, 0)
ListFrame2.Size = UDim2.new(0, 145, 0, 15)
ListFrame2.Visible = false

UICorner_12.Parent = ListFrame2

TextButton_6.Parent = ListFrame2
TextButton_6.BackgroundColor3 = Color3.fromRGB(0, 81, 255)
TextButton_6.Position = UDim2.new(-0.00630051177, 0, 0.160405442, 0)
TextButton_6.Size = UDim2.new(0, 145, 0, 18)
TextButton_6.Font = Enum.Font.SourceSans
TextButton_6.Text = "100"
TextButton_6.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_6.TextScaled = true
TextButton_6.TextSize = 14.000
TextButton_6.TextWrapped = true

UICorner_13.Parent = TextButton_6

TextButton_7.Parent = ListFrame2
TextButton_7.BackgroundColor3 = Color3.fromRGB(0, 81, 255)
TextButton_7.Position = UDim2.new(-0.00630051177, 0, 0.343969911, 0)
TextButton_7.Size = UDim2.new(0, 145, 0, 18)
TextButton_7.Font = Enum.Font.SourceSans
TextButton_7.Text = "200"
TextButton_7.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_7.TextScaled = true
TextButton_7.TextSize = 14.000
TextButton_7.TextWrapped = true

UICorner_14.Parent = TextButton_7

TextButton_8.Parent = ListFrame2
TextButton_8.BackgroundColor3 = Color3.fromRGB(0, 81, 255)
TextButton_8.Position = UDim2.new(-0.00630051177, 0, 0.526979685, 0)
TextButton_8.Size = UDim2.new(0, 145, 0, 18)
TextButton_8.Font = Enum.Font.SourceSans
TextButton_8.Text = "300"
TextButton_8.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_8.TextScaled = true
TextButton_8.TextSize = 14.000
TextButton_8.TextWrapped = true

UICorner_15.Parent = TextButton_8

TextButton_9.Parent = ListFrame2
TextButton_9.BackgroundColor3 = Color3.fromRGB(0, 81, 255)
TextButton_9.Position = UDim2.new(-0.00630051177, 0, 0.705551147, 0)
TextButton_9.Size = UDim2.new(0, 145, 0, 18)
TextButton_9.Font = Enum.Font.SourceSans
TextButton_9.Text = "400"
TextButton_9.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_9.TextScaled = true
TextButton_9.TextSize = 14.000
TextButton_9.TextWrapped = true

UICorner_16.Parent = TextButton_9

CloseButton_2.Name = "CloseButton"
CloseButton_2.Parent = ListFrame2
CloseButton_2.BackgroundColor3 = Color3.fromRGB(0, 150, 225)
CloseButton_2.Position = UDim2.new(-0.00630051177, 0, 0.869836867, 0)
CloseButton_2.Size = UDim2.new(0, 145, 0, 18)
CloseButton_2.Font = Enum.Font.SourceSans
CloseButton_2.Text = "CLOSE"
CloseButton_2.TextColor3 = Color3.fromRGB(255, 255, 255)
CloseButton_2.TextScaled = true
CloseButton_2.TextSize = 14.000
CloseButton_2.TextWrapped = true

UICorner_17.Parent = CloseButton_2

TextButton_10.Parent = PlayerFrame
TextButton_10.BackgroundColor3 = Color3.fromRGB(0, 166, 255)
TextButton_10.Position = UDim2.new(0.503128171, 0, 0.0305164326, 0)
TextButton_10.Size = UDim2.new(0, 145, 0, 30)
TextButton_10.Font = Enum.Font.SourceSans
TextButton_10.Text = "Jump Power"
TextButton_10.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_10.TextScaled = true
TextButton_10.TextSize = 14.000
TextButton_10.TextWrapped = true

UICorner_18.Parent = TextButton_10

WorldButton.Name = "WorldButton"
WorldButton.Parent = HaxFrame
WorldButton.BackgroundColor3 = Color3.fromRGB(149, 0, 2)
WorldButton.Position = UDim2.new(0, 0, 0.198704094, 0)
WorldButton.Size = UDim2.new(0, 106, 0, 21)
WorldButton.Font = Enum.Font.SourceSans
WorldButton.Text = "World"
WorldButton.TextColor3 = Color3.fromRGB(255, 255, 255)
WorldButton.TextScaled = true
WorldButton.TextSize = 14.000
WorldButton.TextWrapped = true

UICorner_19.Parent = WorldButton

WorldFrame.Name = "WorldFrame"
WorldFrame.Parent = HaxFrame
WorldFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
WorldFrame.BackgroundTransparency = 1.000
WorldFrame.Position = UDim2.new(0.220703125, 0, 0.0799136087, 0)
WorldFrame.Size = UDim2.new(0, 399, 0, 426)
WorldFrame.Visible = false

TextButton_11.Parent = WorldFrame
TextButton_11.BackgroundColor3 = Color3.fromRGB(0, 166, 255)
TextButton_11.Position = UDim2.new(0.0545066372, 0, 0.0305164326, 0)
TextButton_11.Size = UDim2.new(0, 145, 0, 30)
TextButton_11.Font = Enum.Font.SourceSans
TextButton_11.Text = "Spawn a part"
TextButton_11.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_11.TextScaled = true
TextButton_11.TextSize = 14.000
TextButton_11.TextWrapped = true

UICorner_20.Parent = TextButton_11

Frame_3.Parent = WorldFrame
Frame_3.BackgroundColor3 = Color3.fromRGB(79, 79, 79)
Frame_3.BackgroundTransparency = 0.500
Frame_3.Position = UDim2.new(0.025062656, 0, 0, 0)
Frame_3.Size = UDim2.new(0, 6, 0, 426)

UICorner_21.Parent = Frame_3

-- Scripts:

local function UWVL_fake_script() -- PlayerButton.LocalScript 
	local script = Instance.new('LocalScript', PlayerButton)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.PlayerFrame.Visible = true
		script.Parent.Parent.WorldFrame.Visible = false
		script.Parent.Parent.WorldButton.BackgroundColor3 = Color3.fromRGB(149, 0, 2)
		script.Parent.Parent.WorldButton:TweenSize(UDim2.new(0, 106,0, 21),"Out","Back")
		script.Parent.BackgroundColor3 = Color3.fromRGB(255,0,4)
		script.Parent:TweenSize(UDim2.new(0, 116,0, 21),"Out","Back")
	end)
end
coroutine.wrap(UWVL_fake_script)()
local function ADRLEU_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	local player = game.Players.LocalPlayer
	
	script.Parent.MouseButton1Click:Connect(function()
		player.Character.Humanoid.WalkSpeed = 100
	end)
end
coroutine.wrap(ADRLEU_fake_script)()
local function BFKMI_fake_script() -- TextButton_2.LocalScript 
	local script = Instance.new('LocalScript', TextButton_2)

	local player = game.Players.LocalPlayer
	
	script.Parent.MouseButton1Click:Connect(function()
		player.Character.Humanoid.WalkSpeed = 200
	end)
end
coroutine.wrap(BFKMI_fake_script)()
local function XKSWONA_fake_script() -- TextButton_3.LocalScript 
	local script = Instance.new('LocalScript', TextButton_3)

	local player = game.Players.LocalPlayer
	
	script.Parent.MouseButton1Click:Connect(function()
		player.Character.Humanoid.WalkSpeed = 300
	end)
end
coroutine.wrap(XKSWONA_fake_script)()
local function GRTEC_fake_script() -- TextButton_4.LocalScript 
	local script = Instance.new('LocalScript', TextButton_4)

	local player = game.Players.LocalPlayer
	
	script.Parent.MouseButton1Click:Connect(function()
		player.Character.Humanoid.WalkSpeed = 400
	end)
end
coroutine.wrap(GRTEC_fake_script)()
local function CEFCESH_fake_script() -- CloseButton.LocalScript 
	local script = Instance.new('LocalScript', CloseButton)

	script.Parent.MouseButton1Click:Connect(function()
		wait(0.1)
		local ListFrame = script.Parent.Parent
		ListFrame:TweenSize(UDim2.new(0, 145,0, 15),"Out","Back")
		wait(0.5)
		ListFrame.Visible = false
	end)
end
coroutine.wrap(CEFCESH_fake_script)()
local function GGQQOQ_fake_script() -- TextButton_5.LocalScript 
	local script = Instance.new('LocalScript', TextButton_5)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.ListFrame.Visible = true
		local ListFrame = script.Parent.Parent.ListFrame
		ListFrame:TweenSize(UDim2.new(0, 145,0, 140),"Out","Back")
	end)
end
coroutine.wrap(GGQQOQ_fake_script)()
local function AKRH_fake_script() -- TextButton_6.LocalScript 
	local script = Instance.new('LocalScript', TextButton_6)

	local player = game.Players.LocalPlayer
	
	script.Parent.MouseButton1Click:Connect(function()
		player.Character.Humanoid.JumpPower = 100
	end)
end
coroutine.wrap(AKRH_fake_script)()
local function MDEGF_fake_script() -- TextButton_7.LocalScript 
	local script = Instance.new('LocalScript', TextButton_7)

	local player = game.Players.LocalPlayer
	
	script.Parent.MouseButton1Click:Connect(function()
		player.Character.Humanoid.JumpPower = 200
	end)
end
coroutine.wrap(MDEGF_fake_script)()
local function JPLLD_fake_script() -- TextButton_8.LocalScript 
	local script = Instance.new('LocalScript', TextButton_8)

	local player = game.Players.LocalPlayer
	
	script.Parent.MouseButton1Click:Connect(function()
		player.Character.Humanoid.WalkSpeed = JumpPower
	end)
end
coroutine.wrap(JPLLD_fake_script)()
local function LTZPVB_fake_script() -- TextButton_9.LocalScript 
	local script = Instance.new('LocalScript', TextButton_9)

	local player = game.Players.LocalPlayer
	
	script.Parent.MouseButton1Click:Connect(function()
		player.Character.Humanoid.JumpPower = 400
	end)
end
coroutine.wrap(LTZPVB_fake_script)()
local function VXEZA_fake_script() -- CloseButton_2.LocalScript 
	local script = Instance.new('LocalScript', CloseButton_2)

	script.Parent.MouseButton1Click:Connect(function()
		wait(0.1)
		local ListFrame2 = script.Parent.Parent
		ListFrame2:TweenSize(UDim2.new(0, 145,0, 15),"Out","Back")
		wait(0.5)
		ListFrame2.Visible = false
	end)
end
coroutine.wrap(VXEZA_fake_script)()
local function FTKZY_fake_script() -- TextButton_10.LocalScript 
	local script = Instance.new('LocalScript', TextButton_10)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.ListFrame2.Visible = true
		local ListFrame2 = script.Parent.Parent.ListFrame2
		ListFrame2:TweenSize(UDim2.new(0, 145,0, 140),"Out","Back")
	end)
end
coroutine.wrap(FTKZY_fake_script)()
local function QLHBY_fake_script() -- WorldButton.LocalScript 
	local script = Instance.new('LocalScript', WorldButton)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.WorldFrame.Visible = true
		script.Parent.Parent.PlayerFrame.Visible = false
		script.Parent.Parent.PlayerButton.BackgroundColor3 = Color3.fromRGB(149, 0, 2)
		script.Parent.Parent.PlayerButton:TweenSize(UDim2.new(0, 106,0, 21),"Out","Back")
		script.Parent.BackgroundColor3 = Color3.fromRGB(255,0,4)
		script.Parent:TweenSize(UDim2.new(0, 116,0, 21),"Out","Back")
	end)
end
coroutine.wrap(QLHBY_fake_script)()
local function TCLOAD_fake_script() -- TextButton_11.LocalScript 
	local script = Instance.new('LocalScript', TextButton_11)

	script.Parent.MouseButton1Click:Connect(function()
		local player = game.Players.LocalPlayer
		local part = Instance.new("Part", game.workspace)
		part.CFrame = player.Character.RightFoot.CFrame * CFrame.new(0,0,0)
	end)
end
coroutine.wrap(TCLOAD_fake_script)()
local function JRFBYPK_fake_script() -- ScreenGui.LocalScript 
	local script = Instance.new('LocalScript', ScreenGui)

	local frame = script.Parent.HaxFrame
	
	frame.Draggable = true
	frame.Active = true
	frame.Archivable = true
end
coroutine.wrap(JRFBYPK_fake_script)()
