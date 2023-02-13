local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "Key System", HidePremium = false, SaveConfig = true, IntroEnabled = false})
local Tab = Window:MakeTab({
	Name = "KeySystem",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
local Section = Tab:AddSection({
	Name = "EnterKey"
})
getgenv().Key = 'Nigger'

Tab:AddTextbox({
	Name = "Key: N_gger",
	Default = "",
	TextDisappear = true,
	Callback = function(Value)
		if Value == Key then
            OrionLib:Destroy()
            loadstring(game:HttpGet("https://raw.githubusercontent.com/DomTechGaming/mynew/main/.gitignore"))()
        end
	end	  
})
