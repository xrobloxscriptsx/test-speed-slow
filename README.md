local UserInputService = game:GetService("UserInputService")
local Player = game.Players.LocalPlayer
UserInputService.InputBegan:Connect(function(input)
	if input.KeyCode == Enum.KeyCode.C then
		Player.Character.Humanoid.WalkSpeed = 16
	elseif input.KeyCode == Enum.KeyCode.C then
			Player.Character.Humanoid.WalkSpeed = 16
	end
end)
UserInputService.InputEnded:Connect(function(input)
	if input.KeyCode == Enum.KeyCode.C then
		Player.Character.Humanoid.WalkSpeed = 16
	elseif input.KeyCode == Enum.KeyCode.C then
			Player.Character.Humanoid.WalkSpeed = 16
	end
end)
