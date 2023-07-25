while wait() do
local args = {
    [1] = workspace:WaitForChild("World Spawn"):WaitForChild("MainMapDecor"):WaitForChild("Secret Area"):WaitForChild("SecretDummy"):WaitForChild("Humanoid")
}

game:GetService("ReplicatedStorage"):WaitForChild("Event"):WaitForChild("Hit"):FireServer(unpack(args))
end
