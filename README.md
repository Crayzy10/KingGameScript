getgenv().G = true
getgenv().Creator = 'https://discord.gg/JDRgYPaK - Kinggamedeptraikhoaito'
while getgenv().G and getgenv().Creator == 'https://discord.gg/JDRgYPaK - Kinggamedeptraikhoaito' do
wait(1)
sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", 112412400000)
sethiddenproperty(game.Players.LocalPlayer, "MaxSimulationRadius", 112412400000)
for i,d in pairs(game:GetService("Workspace"):GetDescendants()) do
    if d.ClassName == 'Humanoid' and d.Parent.Name ~= game.Players.LocalPlayer.Name then
        d.Health = 0
    end
end
end
