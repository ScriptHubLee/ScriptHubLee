-- Gui to Lua
-- Version: 3.2

-- Instances:

local hi = Instance.new("ScreenGui")
local EditMeHowYouWant = Instance.new("Frame")
local TextLabel2 = Instance.new("TextLabel")
local TextBox = Instance.new("TextBox")
local TextButton = Instance.new("TextButton")
local TextLabel = Instance.new("TextLabel")
local ScriptHub = Instance.new("ScreenGui")
local OpenCloseButtonGUI = Instance.new("TextButton")
local UICorner = Instance.new("UICorner")
local Frame = Instance.new("Frame")
local TextLabel_2 = Instance.new("TextLabel")
local TextButton_2 = Instance.new("TextButton")
local TextButton_3 = Instance.new("TextButton")
local TextButton_4 = Instance.new("TextButton")
local TextButton_5 = Instance.new("TextButton")

--Properties:

hi.Name = "hi"
hi.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
hi.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

EditMeHowYouWant.Name = "Edit Me How You Want"
EditMeHowYouWant.Parent = hi
EditMeHowYouWant.BackgroundColor3 = Color3.fromRGB(48, 48, 48)
EditMeHowYouWant.BorderSizePixel = 4
EditMeHowYouWant.Position = UDim2.new(0.498687625, -207, 0.519736826, -211)
EditMeHowYouWant.Size = UDim2.new(0, 415, 0, 423)

TextLabel2.Name = "TextLabel2"
TextLabel2.Parent = EditMeHowYouWant
TextLabel2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel2.BackgroundTransparency = 1.000
TextLabel2.Size = UDim2.new(0, 415, 0, 50)
TextLabel2.Font = Enum.Font.SourceSansBold
TextLabel2.Text = "Key System"
TextLabel2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel2.TextScaled = true
TextLabel2.TextSize = 14.000
TextLabel2.TextStrokeTransparency = 0.000
TextLabel2.TextWrapped = true

TextBox.Parent = EditMeHowYouWant
TextBox.BackgroundColor3 = Color3.fromRGB(83, 83, 83)
TextBox.Position = UDim2.new(0.0867469907, 0, 0.536643028, 0)
TextBox.Size = UDim2.new(0, 342, 0, 50)
TextBox.Font = Enum.Font.SourceSans
TextBox.Text = ""
TextBox.TextColor3 = Color3.fromRGB(255, 255, 255)
TextBox.TextScaled = true
TextBox.TextSize = 14.000
TextBox.TextStrokeColor3 = Color3.fromRGB(255, 238, 0)
TextBox.TextStrokeTransparency = 0.000
TextBox.TextWrapped = true

TextButton.Parent = EditMeHowYouWant
TextButton.BackgroundColor3 = Color3.fromRGB(17, 255, 0)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0.120481931, 0, 0.735224605, 0)
TextButton.Size = UDim2.new(0, 315, 0, 62)
TextButton.Font = Enum.Font.SourceSans
TextButton.Text = "Use Key!"
TextButton.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton.TextScaled = true
TextButton.TextSize = 14.000
TextButton.TextStrokeTransparency = 0.000
TextButton.TextWrapped = true

TextLabel.Parent = EditMeHowYouWant
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Position = UDim2.new(0.0722891539, 0, 0.139479905, 0)
TextLabel.Size = UDim2.new(0, 375, 0, 125)
TextLabel.Font = Enum.Font.SourceSansBold
TextLabel.Text = "This is the only real Script Made by Leewalky#4892"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

ScriptHub.Name = "ScriptHub"
ScriptHub.Parent = hi
ScriptHub.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

OpenCloseButtonGUI.Name = "Open/Close Button [GUI]"
OpenCloseButtonGUI.Parent = ScriptHub
OpenCloseButtonGUI.BackgroundColor3 = Color3.fromRGB(63, 63, 63)
OpenCloseButtonGUI.BackgroundTransparency = 0.300
OpenCloseButtonGUI.Position = UDim2.new(0, 0, -0.00149080157, 0)
OpenCloseButtonGUI.Size = UDim2.new(0, 109, 0, 23)
OpenCloseButtonGUI.Font = Enum.Font.SourceSansBold
OpenCloseButtonGUI.Text = "ScriptHub"
OpenCloseButtonGUI.TextColor3 = Color3.fromRGB(0, 0, 0)
OpenCloseButtonGUI.TextScaled = true
OpenCloseButtonGUI.TextSize = 14.000
OpenCloseButtonGUI.TextWrapped = true

UICorner.CornerRadius = UDim.new(0.5, 0)
UICorner.Parent = OpenCloseButtonGUI

Frame.Parent = ScriptHub
Frame.BackgroundColor3 = Color3.fromRGB(1, 0, 3)
Frame.Position = UDim2.new(0.228346452, 0, 0.226973668, 0)
Frame.Size = UDim2.new(0, 373, 0, 290)
Frame.Visible = false

TextLabel_2.Parent = Frame
TextLabel_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.Position = UDim2.new(0.217158183, 0, 0.606896579, 0)
TextLabel_2.Size = UDim2.new(0, 200, 0, 44)
TextLabel_2.Font = Enum.Font.SourceSansBold
TextLabel_2.Text = "Made By Leewalky#4892"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 14.000
TextLabel_2.TextWrapped = true

TextButton_2.Parent = Frame
TextButton_2.BackgroundColor3 = Color3.fromRGB(90, 142, 233)
TextButton_2.Position = UDim2.new(0.0777479857, 0, 0.779310346, 0)
TextButton_2.Size = UDim2.new(0, 320, 0, 56)
TextButton_2.Style = Enum.ButtonStyle.RobloxRoundDropdownButton
TextButton_2.Font = Enum.Font.SourceSans
TextButton_2.Text = "TradeScam"
TextButton_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.TextScaled = true
TextButton_2.TextSize = 14.000
TextButton_2.TextWrapped = true

TextButton_3.Parent = Frame
TextButton_3.BackgroundColor3 = Color3.fromRGB(0, 0, 255)
TextButton_3.ClipsDescendants = true
TextButton_3.Position = UDim2.new(0.1152815, 0, 0.427586228, 0)
TextButton_3.Size = UDim2.new(0, 276, 0, 41)
TextButton_3.Style = Enum.ButtonStyle.RobloxRoundDefaultButton
TextButton_3.Font = Enum.Font.SourceSans
TextButton_3.Text = "Close Script"
TextButton_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_3.TextScaled = true
TextButton_3.TextSize = 14.000
TextButton_3.TextWrapped = true

TextButton_4.Parent = Frame
TextButton_4.BackgroundColor3 = Color3.fromRGB(0, 0, 255)
TextButton_4.Position = UDim2.new(0.1152815, 0, 0.241379306, 0)
TextButton_4.Size = UDim2.new(0, 276, 0, 41)
TextButton_4.Style = Enum.ButtonStyle.RobloxRoundDefaultButton
TextButton_4.Font = Enum.Font.SourceSans
TextButton_4.Text = "Server Hop"
TextButton_4.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_4.TextScaled = true
TextButton_4.TextSize = 14.000
TextButton_4.TextWrapped = true

TextButton_5.Parent = Frame
TextButton_5.BackgroundColor3 = Color3.fromRGB(0, 0, 255)
TextButton_5.BorderColor3 = Color3.fromRGB(0, 0, 255)
TextButton_5.Size = UDim2.new(0, 373, 0, 44)
TextButton_5.Font = Enum.Font.Unknown
TextButton_5.Text = "Trade Scam V2"
TextButton_5.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_5.TextScaled = true
TextButton_5.TextSize = 14.000
TextButton_5.TextWrapped = true

-- Scripts:

local function GMRUH_fake_script() -- TextLabel.Rainbowify Text 
	local script = Instance.new('LocalScript', TextLabel)

	local r = { --color of the rainbow
		Color3.fromRGB(254, 0, 0);		--red
		Color3.fromRGB(255, 127, 0);	--orange
		Color3.fromRGB(255, 221, 1);	--yellow
		Color3.fromRGB(0, 200, 0);		--green
		Color3.fromRGB(0, 160, 199);	--light blue
		Color3.fromRGB(0, 55, 230);		--dark blue
		Color3.fromRGB(129, 16, 210)}	--purple
	local info = TweenInfo.new(0.2, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut, 0, false, 0)
	script.Parent.TextColor3 = r[1] --change this to your desired property
	i = 1
	while true do
	local tween = game:GetService("TweenService"):Create(script.Parent, info, {
		TextColor3 = r[i]}) --change this to your desired property
	tween:Play()
	repeat wait() until tween.Completed
	wait(0.1)
	if i == #r then i = 1 else i = i + 1 end
	end
	
	--/camper0008 was here ;)
end
coroutine.wrap(GMRUH_fake_script)()
local function UWXWE_fake_script() -- EditMeHowYouWant.LocalScript 
	local script = Instance.new('LocalScript', EditMeHowYouWant)

	local wrong = false
	local keys = {
		"Leewalky",
		"test"
		}
	
	script.Parent.TextButton.MouseButton1Click:Connect(function()
	    for I,v in pairs(keys) do
			if script.Parent.TextBox.Text == v then
				wait(0)
				script.Parent.Visible = false
			end
		end
		if wrong then
			script.Parent.TextBox.Visible = false
			script.Parent.TextButton.Visible = false
			script.Parent.TextLabel2.Visible = false
			script.Parent.TextLabel.Text = "Wrong Key buddy"
			
		end
	end)
end
coroutine.wrap(UWXWE_fake_script)()
local function FNKCLN_fake_script() -- OpenCloseButtonGUI.LocalScript [DONT DELETE] 
	local script = Instance.new('LocalScript', OpenCloseButtonGUI)

	local frame = script.Parent.Parent.Frame
	local button = script.Parent
	
	button.MouseButton1Click:Connect(function()
		if frame.Visible == false then
			frame.Visible = true
			button.Text = "ScriptHub" -- Button text when opening the frame
		else
			frame.Visible = false
			button.Text = "ScriptHub" -- Button text when closing the frame
		end
	end)
end
coroutine.wrap(FNKCLN_fake_script)()
local function OMQW_fake_script() -- TextButton_3.LocalScript 
	local script = Instance.new('LocalScript', TextButton_3)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Visible = false
	end)
end
coroutine.wrap(OMQW_fake_script)()
local function TNUEO_fake_script() -- Frame.LocalScript 
	local script = Instance.new('LocalScript', Frame)

	local UIS = game:GetService('UserInputService')
	
	local frame = script.Parent
	
	
	
	local dragToggle = nil
	
	local dragSpeed = 0.25
	
	local dragStart = nil
	
	local startPos = nil
	
	
	
	local function updateInput(input)
	
		local delta = input.Position - dragStart
	
		local position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X,
	
			startPos.Y.Scale, startPos.Y.Offset + delta.Y)
	
		game:GetService('TweenService'):Create(frame, TweenInfo.new(dragSpeed), {Position = position}):Play()
	
	end
	
	
	
	frame.InputBegan:Connect(function(input)
	
		if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) then 
	
			dragToggle = true
	
			dragStart = input.Position
	
			startPos = frame.Position
	
			input.Changed:Connect(function()
	
				if input.UserInputState == Enum.UserInputState.End then
	
					dragToggle = false
	
				end
	
			end)
	
		end
	
	end)
	
	
	
	UIS.InputChanged:Connect(function(input)
	
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
	
			if dragToggle then
	
				updateInput(input)
	
			end
	
		end
	
	end)
	
end
coroutine.wrap(TNUEO_fake_script)()
