-- Store the key to be checked


-- The player's entered key (for example, input from a TextBox or another method)
local check = "[FREE] Key"  -- You would replace this with the input value from the player

-- Check if the key matches
if check == _G.Key then
    -- Key is valid
  
_G.ERER = true
_G.ERER2 = true



if not _G.ERER2 then
    _G.ERER2 = false 
end

task.spawn(function()
    while true do  -- ลูปแบบต่อเนื่อง
        task.wait(5)  -- หยุดรอสั้นๆ เพื่อหลีกเลี่ยงการแฮงค์

        if _G.ERER2 then


    -- จำลองการกดปุ่มเมาส์ขวา
    VirtualUser:CaptureController()
    VirtualUser:ClickButton2(Vector2.new())
end
end
end)


if not _G.ERER then
    _G.ERER = false  -- กำหนดค่าเริ่มต้นให้เป็น false
end

task.spawn(function()
    while true do  -- ลูปแบบต่อเนื่อง
        task.wait(0)  -- หยุดรอสั้นๆ เพื่อหลีกเลี่ยงการแฮงค์

        if _G.ERER then

local ReplicatedStorage = game:GetService("ReplicatedStorage")
local player = game.Players.LocalPlayer
local inventory = ReplicatedStorage.playerstats[player.Name].Inventory
local G = {}  -- สมมุติว่ามีตัวแปร G ที่คุณใช้

for _, item in pairs(inventory:GetChildren()) do
    if string.find(item.Name, "^Sundial Totem") then  -- ตรวจสอบว่าเริ่มต้นด้วย "Ancient Megalodon"
        if item:FindFirstChild("Stack") then
            local StackValue = item.Stack.Value
            if StackValue > 100 then
_G.over = false
_G.Totem = true
_G.Button = true

            elseif StackValue < 5 then
_G.over = true
_G.Totem = false
_G.Button = false
            end
            end
            end
            end
end
end
end)



if not _G.over then
    _G.over = false  -- กำหนดค่าเริ่มต้นให้เป็น false
end

task.spawn(function()
    while true do  -- ลูปแบบต่อเนื่อง
        task.wait(0)  -- หยุดรอสั้นๆ เพื่อหลีกเลี่ยงการแฮงค์

        if _G.over then
 game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1148, 135, -1075) 
game:service('VirtualInputManager'):SendKeyEvent(true, "E", false, game)
game:service('VirtualInputManager'):SendKeyEvent(false, "E", false, game)
local player = game:GetService("Players").LocalPlayer


local overPrompt = player.PlayerGui:FindFirstChild("over") and player.PlayerGui.over:FindFirstChild("prompt")
if overPrompt and overPrompt.confirm then
    local confirmButtonOver = overPrompt.confirm
    for _, connection in pairs(getconnections(confirmButtonOver.MouseButton1Click)) do
        connection.Function(confirmButtonOver)
    end
end
end
end
end)

if not _G.over2 then
    _G.over2 = false  -- กำหนดค่าเริ่มต้นให้เป็น false
end

task.spawn(function()
    while true do  -- ลูปแบบต่อเนื่อง
        task.wait(10)  -- หยุดรอสั้นๆ เพื่อหลีกเลี่ยงการแฮงค์

        if _G.over2 then
 local player = game:GetService("Players").LocalPlayer

-- ค้นหา GUI "over" และ "prompt"
local overPrompt = player.PlayerGui:FindFirstChild("over") and player.PlayerGui.over:FindFirstChild("prompt")
if overPrompt and overPrompt.deny then
    -- แทนที่ปุ่ม confirm ด้วยปุ่ม deny
    local denyButton = overPrompt.deny
    for _, connection in pairs(getconnections(denyButton.MouseButton1Click)) do
        connection.Function(denyButton)
    end
end


end
end
end)


if not _G.Totem then
    _G.Totem = false  -- กำหนดค่าเริ่มต้นให้เป็น false
end

task.spawn(function()
    while true do  -- ลูปแบบต่อเนื่อง
        task.wait(0)  -- หยุดรอสั้นๆ เพื่อหลีกเลี่ยงการแฮงค์

        if _G.Totem then

-- ตรวจสอบว่า "Sundial Totem" อยู่ใน Backpack ของผู้เล่น
local player = game:GetService("Players").LocalPlayer
local totem = player.Backpack:FindFirstChild("Sundial Totem")

-- ถ้าพบ "Sundial Totem" ใน Backpack
if totem then
    -- ตั้งค่าให้ "Sundial Totem" เป็นเครื่องมือที่ผู้เล่นถือ
    player.Character:WaitForChild("Humanoid"):EquipTool(totem)
 
end
end
end
end)




if not _G.Button then
    _G.Button = false  -- กำหนดค่าเริ่มต้นให้เป็น false
end

task.spawn(function()
    while true do  -- ลูปแบบต่อเนื่อง
        task.wait(1)  -- หยุดรอสั้นๆ เพื่อหลีกเลี่ยงการแฮงค์

        if _G.Button then
    game:GetService'VirtualUser':CaptureController()
    game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 670))
end
end
end)




_G.PartMegalodon = true
_G.CFrameMegalodon = true





if not _G.CFrameMegalodon then
    _G.CFrameMegalodon = false  -- กำหนดค่าเริ่มต้นให้เป็น false
end

task.spawn(function()
    while true do  -- ลูปแบบต่อเนื่อง
        task.wait(0)  -- หยุดรอสั้นๆ เพื่อหลีกเลี่ยงการแฮงค์

        if _G.CFrameMegalodon then

local target = workspace.zones.fishing:FindFirstChild("Megalodon Default") -- ค้นหาเป้าหมาย

if target then
    -- ตรวจสอบว่ามี HumanoidRootPart ของผู้เล่น
    local player = game.Players.LocalPlayer
    local character = player.Character or player.CharacterAdded:Wait()
    local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

    -- วาร์ปตัวละครไปยังตำแหน่งของเป้าหมาย
    humanoidRootPart.CFrame = target.CFrame * CFrame.new(0, 10, 0)  -- การยกตัวขึ้นเล็กน้อยจากตำแหน่งเป้าหมาย
end


end
end
end)





if not _G.PartMegalodon then
    _G.PartMegalodon = false  -- กำหนดค่าเริ่มต้นให้เป็น false
end

task.spawn(function()
    while true do  -- ลูปแบบต่อเนื่อง
        task.wait(3)  -- หยุดรอสั้นๆ เพื่อหลีกเลี่ยงการแฮงค์

        if _G.CFrameMegalodon then



-- ค้นหาเป้าหมายใน workspace.zones.fishing
local fishingZone = workspace.zones.fishing:FindFirstChild("Megalodon Default")

-- ตรวจสอบว่าพบเป้าหมายหรือไม่
if fishingZone then
_G.AutoReel1V2 = true
_G.AutoReel1 = true
_G.Autoshake = true
_G.AutoTool = true
_G.ERER  = false
_G.Totem = false
_G.Button = false
    -- สร้างบล็อกในตำแหน่งของ Megalodon Default
    local block = Instance.new("Part")
    block.Size = Vector3.new(4, 1, 4)  -- ขนาดบล็อก
    block.Position = fishingZone.Position + Vector3.new(0, 5, 0)  -- วางบล็อกด้านบนของเป้าหมาย
    block.Anchored = true  -- ทำให้บล็อกไม่ตก
    block.Color = Color3.fromRGB(255, 0, 0)  -- สีของบล็อก
    block.Parent = workspace  -- เพิ่มบล็อกลงใน workspace
else
_G.AutoTool = false
_G.ERER  = true
end
end
end
end)





if not _G.AutoTool then
    _G.AutoTool = false  -- กำหนดค่าเริ่มต้นให้เป็น false
end

task.spawn(function()
    while true do  -- ลูปแบบต่อเนื่อง
        task.wait(0)  -- หยุดรอสั้นๆ เพื่อหลีกเลี่ยงการแฮงค์

        if _G.AutoTool then



   
   local player = game:GetService("Players").LocalPlayer
local backpack = player.Backpack

-- Check for tools in the player's backpack
for _, item in pairs(backpack:GetChildren()) do
    if item:IsA("Tool") and string.find(item.Name, "Rod") then
        -- Ensure the item is not "Crab Cage" before equipping
        if item.Name ~= "Crab Cage" then
            local humanoid = player.Character:WaitForChild("Humanoid")
            humanoid:EquipTool(item)  -- Equip the rod item
            break  -- Stop searching after finding the first match
        end
    end
end

-- Check for tools in the player's character (not workspace.D3B3XxX)
local rodItem = nil
for _, item in pairs(player.Character:GetChildren()) do
    if item:IsA("Tool") and string.find(item.Name, "Rod") then
        -- Ensure the item is not "Crab Cage" before equipping
        if item.Name ~= "Crab Cage" then
            rodItem = item  -- Found the rod in the character, not the "Crab Cage"
            break  -- Stop searching after finding the first match
        end
    end
end

-- If a "Rod" item is found in the player's character, trigger the cast event
if rodItem then
    local events = rodItem:FindFirstChild("events")
    if events and events:FindFirstChild("cast") then
        -- Fire the cast event with arguments
        local args = {
            [1] = 99999999999999,
            [2] = 1
        }
        events.cast:FireServer(unpack(args))
    end
end
end
end
end)


          
if not _G.Autoshake then
    _G.Autoshake = false
end

-- ฟังก์ชันหลักที่ทำงานตลอดเวลา
task.spawn(function()
    while true do
        task.wait(0.005)  -- หยุดรอสั้นๆ เพื่อหลีกเลี่ยงการแฮงค์

        -- ถ้าค่า _G.FastShake เป็น true ให้ทำงาน
        if _G.Autoshake then
            -- ลูปเพื่อจำลองการคลิกปุ่ม 10,000 ครั้ง
                    local player = game.Players.LocalPlayer
                    local GUI = player:WaitForChild("PlayerGui")
                    local shakeui = GUI:WaitForChild("shakeui")
                    local VirtualInputManager = game:GetService("VirtualInputManager")

                    -- Locate the button and interact with it
                    local button = shakeui.safezone:FindFirstChild("button")
                    if button and button:IsA("ImageButton") and button.Visible then
                        game:GetService("GuiService").SelectedCoreObject = button
                        VirtualInputManager:SendKeyEvent(true, Enum.KeyCode.Return, false, game)
                        VirtualInputManager:SendKeyEvent(false, Enum.KeyCode.Return, false, game)
                    end
                end
            end
        end)

    



if not _G.AutoReel1 then
    _G.AutoReel1 = false  -- กำหนดค่าเริ่มต้นให้เป็น false
end

task.spawn(function()
    while true do  -- ลูปแบบต่อเนื่อง
        task.wait(0.005)  -- หยุดรอสั้นๆ เพื่อหลีกเลี่ยงการแฮงค์

        if _G.AutoReel1 then

                    local reelfinished = game:GetService("ReplicatedStorage"):WaitForChild("events"):WaitForChild("reelfinished")
                    local LocalPlayer = game.Players.LocalPlayer

                    for _, v in pairs(LocalPlayer.PlayerGui:GetChildren()) do
                        if v:IsA("ScreenGui") and v.Name == "reel" then
                            if v:FindFirstChild("bar") then
                                reelfinished:FireServer(100, true)
                            end
                        end
                    end
                end
       
        end

        -- Auto Reel 2 logic
if not _G.AutoReel1V2 then
    _G.AutoReel1V2 = false  -- กำหนดค่าเริ่มต้นให้เป็น false
end

task.spawn(function()
    while true do  -- ลูปแบบต่อเนื่อง
        task.wait(0.005)  -- หยุดรอสั้นๆ เพื่อหลีกเลี่ยงการแฮงค์

        if _G.AutoReel1V2 then

                    local reelfinished = game:GetService("ReplicatedStorage").Link.events.reelfinished
                    local LocalPlayer = game.Players.LocalPlayer

                    for _, v in pairs(LocalPlayer.PlayerGui:GetChildren()) do
                        if v:IsA("ScreenGui") and v.Name == "reel" then
                            if v:FindFirstChild("bar") then
                                reelfinished:FireServer(100, true)
                            end
                        end
                    end
                end
      
        end
    end)
end)


local ReplicatedStorage = game:GetService("ReplicatedStorage")
local player = game.Players.LocalPlayer
local inventory = ReplicatedStorage.playerstats[player.Name].Inventory

-- สร้าง UI
local screenGui = Instance.new("ScreenGui")
screenGui.Parent = player:WaitForChild("PlayerGui")

local frame = Instance.new("Frame")
frame.Size = UDim2.new(0.3, 0, 0.1, 0)  -- กำหนดขนาด UI
frame.Position = UDim2.new(0.35, 0, 0.1, 0)  -- กำหนดตำแหน่ง UI
frame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)  -- สีพื้นหลัง
frame.BorderSizePixel = 0
frame.Parent = screenGui

local textLabel = Instance.new("TextLabel")
textLabel.Size = UDim2.new(1, 0, 1, 0)  -- ขนาดของ TextLabel
textLabel.BackgroundTransparency = 1  -- ทำให้ไม่มีพื้นหลัง
textLabel.TextColor3 = Color3.fromRGB(255, 255, 255)  -- สีข้อความ
textLabel.Font = Enum.Font.SourceSansBold
textLabel.TextSize = 24  -- ขนาดตัวอักษร
textLabel.Text = "กำลังโหลด..."  -- ข้อความเริ่มต้น
textLabel.Parent = frame

-- ฟังก์ชันอัปเดตข้อมูล
local function updateMegalodonCount()
    local count = 0
    for _, item in pairs(inventory:GetChildren()) do
        if string.find(item.Name, "Megalodon") then  -- ตรวจสอบว่ามีคำว่า "Megalodon" ในชื่อ
            if item:FindFirstChild("Stack") then
                count = count + item.Stack.Value
            end
        end
    end

    -- อัปเดต UI
    if count > 0 then
        textLabel.Text = "Megalodon = " .. count
    else
        textLabel.Text = "Megalodon = 0"
    end
end

-- อัปเดตข้อมูลทุกวินาที
while true do
    updateMegalodonCount()
    wait(1)  -- รอ 1 วินาทีก่อนอัปเดตรอบถัดไป
end
else

end
