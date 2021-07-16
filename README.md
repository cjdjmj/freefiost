	for _, v in pairs(game:GetService('Players'):GetPlayers()) do
		if v and v.Character and v.Character:FindFirstChildOfClass('Humanoid') and v.Character:FindFirstChildOfClass('Humanoid').DisplayDistanceType ~= Enum.HumanoidDisplayDistanceType.Viewer then
			v.Character:FindFirstChildOfClass('Humanoid').DisplayDistanceType = Enum.HumanoidDisplayDistanceType.Viewer;
		end;
	end;
