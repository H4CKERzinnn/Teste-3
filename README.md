-- UI bem simples, sem libs externas
local ScreenGui = Instance.new("ScreenGui", game.CoreGui)
local Frame = Instance.new("Frame", ScreenGui)
Frame.Size = UDim2.new(0, 300, 0, 200)
Frame.Position = UDim2.new(0.5, -150, 0.5, -100)
Frame.BackgroundColor3 = Color3.fromRGB(30, 30, 30)

local Title = Instance.new("TextLabel", Frame)
Title.Size = UDim2.new(1, 0, 0, 30)
Title.Text = "Hzin Vendas"
Title.TextColor3 = Color3.new(1, 1, 1)
Title.BackgroundColor3 = Color3.fromRGB(50, 50, 50)

local Button = Instance.new("TextButton", Frame)
Button.Size = UDim2.new(1, -20, 0, 30)
Button.Position = UDim2.new(0, 10, 0, 50)
Button.Text = "Ativar Aimbot Rage"
Button.BackgroundColor3 = Color3.fromRGB(80, 80, 80)
Button.TextColor3 = Color3.new(1, 1, 1)
Button.MouseButton1Click:Connect(function()
    print("Aimbot Rage ativado")
    -- aqui você colocaria o código real do aimbot, se tiver
end)
