--переменные
local RS = game:GetService("RunService")
local vc3 = Vector3.new
local vacbypass2 = true
local Middle = math.huge
local Down = math.huge
local Up = 16e16
local vacbypass = false --  убирает нахуй все кастомные теги хрп и вроде  не детектит большое кол-во anticheats
local issueerrorfix2
local forceupdate = RS.RenderStepped:Wait()
local step = false
local LastStep = step
local plr = game:GetService("Players").LocalPlayer
local character = plr.Character
local upr = character:FindFirstChild("UpperTorso")
local hrp = character:FindFirstChild("HumanoidRootPart")
local zzs = plr.Character.HumanoidRootPart.CFrame
local hrppos = hrp.CFrame
local MovingToPosition = MoveTo
local AnotherRoot = character.LowerTorso.Root:Clone(0.1)
-- инвис
