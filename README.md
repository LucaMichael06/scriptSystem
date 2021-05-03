-- Gui to Lua
-- Version: 3.2

-- Instances:

local Main = Instance.new("ScreenGui")
local Frame = Instance.new("ImageLabel")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local Home = Instance.new("TextButton")
local HomeVisible = Instance.new("Frame")
local TextVisible = Instance.new("Frame")
local TextLabel_3 = Instance.new("TextLabel")
local Scripts = Instance.new("TextButton")
local ScriptVisible = Instance.new("Frame")
local CmdXVisible = Instance.new("Frame")
local Cmd_X = Instance.new("TextButton")

--Properties:

Main.Name = "Main"
Main.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

Frame.Name = "Frame"
Frame.Parent = Main
Frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame.BackgroundTransparency = 1.000
Frame.Position = UDim2.new(0.353125006, 0, 0.288438618, 0)
Frame.Size = UDim2.new(0, 563, 0, 354)
Frame.Image = "http://www.roblox.com/asset/?id=4916571112"
Frame.ScaleType = Enum.ScaleType.Slice
Frame.SliceCenter = Rect.new(100, 100, 100, 100)
Frame.SliceScale = 0.120

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Position = UDim2.new(-0.081705153, 0, 0, 0)
TextLabel.Size = UDim2.new(0, 200, 0, 50)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Scripts"
TextLabel.TextColor3 = Color3.fromRGB(170, 0, 0)
TextLabel.TextSize = 20.000

TextLabel_2.Parent = Frame
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.Position = UDim2.new(0.717584372, 0, 0, 0)
TextLabel_2.Size = UDim2.new(0, 200, 0, 50)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "Made by Luca"
TextLabel_2.TextColor3 = Color3.fromRGB(170, 0, 0)
TextLabel_2.TextSize = 20.000

Home.Name = "Home"
Home.Parent = Frame
Home.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Home.BackgroundTransparency = 1.000
Home.Position = UDim2.new(0, 0, 0.192090392, 0)
Home.Size = UDim2.new(0, 200, 0, 50)
Home.Font = Enum.Font.SourceSans
Home.Text = "Home"
Home.TextColor3 = Color3.fromRGB(170, 0, 0)
Home.TextSize = 40.000

HomeVisible.Name = "HomeVisible"
HomeVisible.Parent = Frame
HomeVisible.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
HomeVisible.BackgroundTransparency = 1.000
HomeVisible.Position = UDim2.new(0.458259314, 0, 0.358757049, 0)
HomeVisible.Size = UDim2.new(0, 100, 0, 100)

TextVisible.Name = "TextVisible"
TextVisible.Parent = HomeVisible
TextVisible.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextVisible.BackgroundTransparency = 1.000
TextVisible.Position = UDim2.new(0.550000012, 0, 1.47000003, 0)
TextVisible.Size = UDim2.new(0, 100, 0, 100)

TextLabel_3.Parent = TextVisible
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.Position = UDim2.new(-1.20000005, 0, -2.05999994, 0)
TextLabel_3.Size = UDim2.new(0, 340, 0, 52)
TextLabel_3.Font = Enum.Font.SourceSans
TextLabel_3.Text = "Script Made By Luca"
TextLabel_3.TextColor3 = Color3.fromRGB(170, 0, 0)
TextLabel_3.TextSize = 30.000

Scripts.Name = "Scripts"
Scripts.Parent = Frame
Scripts.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Scripts.BackgroundTransparency = 1.000
Scripts.Position = UDim2.new(0, 0, 0.333333343, 0)
Scripts.Size = UDim2.new(0, 200, 0, 59)
Scripts.Font = Enum.Font.SourceSans
Scripts.Text = "Scripts"
Scripts.TextColor3 = Color3.fromRGB(170, 0, 0)
Scripts.TextSize = 40.000

ScriptVisible.Name = "ScriptVisible"
ScriptVisible.Parent = Frame
ScriptVisible.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ScriptVisible.BackgroundTransparency = 1.000
ScriptVisible.Position = UDim2.new(0.539964497, 0, 0.596045196, 0)
ScriptVisible.Size = UDim2.new(0, 100, 0, 100)

CmdXVisible.Name = "CmdXVisible"
CmdXVisible.Parent = ScriptVisible
CmdXVisible.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
CmdXVisible.BackgroundTransparency = 1.000
CmdXVisible.Size = UDim2.new(0, 100, 0, 100)
CmdXVisible.Visible = false

Cmd_X.Name = "Cmd_X"
Cmd_X.Parent = CmdXVisible
Cmd_X.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Cmd_X.BackgroundTransparency = 1.000
Cmd_X.Position = UDim2.new(-0.50999999, 0, -1.40999997, 0)
Cmd_X.Size = UDim2.new(0, 242, 0, 50)
Cmd_X.Font = Enum.Font.SourceSans
Cmd_X.Text = "CmdX"
Cmd_X.TextColor3 = Color3.fromRGB(170, 0, 0)
Cmd_X.TextSize = 35.000

-- Scripts:

local function REAAA_fake_script() -- Home.LocalScript 
	local script = Instance.new('LocalScript', Home)

	Home.MouseButton1Down:connect(function()
		TextVisible.Visible = true
		CmdXVisible.Visible = false
	end)
end
coroutine.wrap(REAAA_fake_script)()
local function EXRAHX_fake_script() -- Scripts.LocalScript 
	local script = Instance.new('LocalScript', Scripts)

	Scripts.MouseButton1Down:connect(function()
		TextVisible.Visible = false
		CmdXVisible.Visible = true
	end)
end
coroutine.wrap(EXRAHX_fake_script)()
local function JGPE_fake_script() -- Cmd_X.LocalScript 
	local script = Instance.new('LocalScript', Cmd_X)

	Cmd_X.MouseButton1Down:connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/CMD-X/CMD-X/master/Source",true))()
	end)
end
coroutine.wrap(JGPE_fake_script)()
