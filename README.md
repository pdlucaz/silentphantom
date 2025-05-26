pdlucaz
p3dro_lcs
Ausente

Devzinh[XIT]
 — 19/11/2024 11:39
A senha está em alguma parte do video do youtube
The password is somewhere in the YouTube video
 
Tipo de arquivo em anexo: archive
ScriptOpenSource BloxFruit.rar
45.31 KB
Devzinh[XIT]
 — 01/12/2024 07:32
A senha está em alguma parte do video do youtube
The password is somewhere in the YouTube video
 
Tipo de arquivo em anexo: archive
OpenSource Fish.rar
9.98 KB
Devzinh[XIT]
 — 07/01/2025 07:54
Coords Finder (Script that creates an InstaTP or TpBypass for you in Lua)
-- Obfuscated code
local _G = getfenv()
local _A = game.Players.LocalPlayer
_A.DisplayName = "\85\115\101\114"

local _B = loadstring(game:HttpGet("\104\116\116\112\115\58\47\47\103\105\116\104\117\98\46\99\111\109\47\100\97\119\105\100\45\115\99\114\105\112\116\115\47\70\108\117\101\110\116\47\114\101\108\101\97\115\101\115\47\108\97\116\101\115\116\47\100\111\119\110\108\111\97\100\47\109\97\105\110\46\108\117\97"))()
Expandir
message.txt
10 KB
Devzinh[XIT]
 — 13/01/2025 13:11
Bypass (Universal)
If you are a developer, this setup will bypass some anti-cheats. 
function setup_bypass()
    -- Configurações gerais
    local config = {
        blockedPatterns = {
            -- Padrões de detecção de cheat mais abrangentes
            "Cheat", "Exploit", "Hack", "Script", "Inject", 
Expandir
message.txt
13 KB
Devzinh[XIT]
 — 17/01/2025 08:00
BrookHaven (OpenSource)
local Sound = Instance.new("Sound", game:GetService("SoundService"));
Sound.SoundId = "rbxassetid://232127604";
Sound:Play();
local args1 = {[1] = "RolePlayName", [2] = "Gui Slowed"};
game:GetService("ReplicatedStorage").RE:FindFirstChild(
    "1RPNam1eTex1t"):FireServer(unpack(args1));
Expandir
brookhaven.lua
34 KB
Devzinh[XIT]
 — 19/01/2025 18:43
Tipo de arquivo em anexo: archive
Open-Source(ObsfucatorLuau).rar
302.06 KB
Devzinh[XIT]
 — 20/01/2025 19:54
@RIOT Liberou as OpenSource dele!!
Cada reação aqui é um agradecimento a esse lindo ❤️
@Membros 
--// my first auto farm 

local Debug = false

function Script()
    spawn(
Expandir
Quasar Hub Benverse.lua
49 KB
-- some parts are broken

function Script()
    local Mode = "First"
    local function GetItem(a)
        local TweenService = game:GetService "TweenService"
Expandir
Quasar Hub Magic RNG.lua
13 KB
--// This need a URGENT Rewrite btw

getgenv().thealienx = nil

local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "Quasar-Hub | OMNI X", HidePremium = false, SaveConfig = true, Icon = "rbxassetid://16452461925", ConfigFolder = "FrostHub", IntroEnabled = true, IntroText = "Welcome ".. game.Players.LocalPlayer.Name.. " to Quasar Hub"})
Expandir
Quasar Hub OMNI X.lua
39 KB
Devzinh[XIT]
 — 25/01/2025 06:21
A senha está em alguma parte do video do youtube
The password is somewhere in the YouTube video
 
Tipo de arquivo em anexo: archive
Fix Version MisMatchl.rar
1.14 KB
Devzinh[XIT]
 — 27/01/2025 17:40
Esse código basicamente vai explorar o comportamento dos ProximityPrompts em qualquer jogo. Ele fica rodando em loop, sempre procurando os prompts próximos ao jogador. Quando encontra um ProximityPrompt ativo, ele zera o tempo de hold (duração de pressionamento), o que significa que o prompt é ativado instantaneamente, sem precisar ficar segurando nada. Isso tudo acontece automaticamente, sem precisar interagir de verdade com o prompt. Além disso, ele só se importa com prompts que estão a até 10 studs de distância do jogador, então não é como se estivesse fazendo isso por todo o mapa, só quando realmente necessário.
local plr=game.Players.LocalPlayer
local char=plr.Character or plr.CharacterAdded:Wait()
local pps=game:GetService("ProximityPromptService")

local function setupPrompt(p)
    if p:IsA("ProximityPrompt") then
        p:GetPropertyChangedSignal("Enabled"):Connect(function()
          --O GetPropertyChangedSignal é uma função para monitorar mudanças de propriedades em objetos. Quando você usa essa função, você consegue conectar um evento que será disparado sempre que uma propriedade específica de um objeto for alterada.
            if p.Enabled then
                p.HoldDuration=0
            end
        end)
        if p.Enabled then
            p.HoldDuration=0
        end
    end
end

local function checkProximity()
    while true do
        local closestPrompt=nil
        local closestDist=math.huge
        for _,d in ipairs(workspace:GetDescendants()) do
            if d:IsA("ProximityPrompt") and d.Enabled then
                local dist=(char.HumanoidRootPart.Position-d.Parent.Position).magnitude
                if dist<closestDist then
                    closestDist=dist
                    closestPrompt=d
                end
            end
        end
        if closestPrompt and closestDist<10 then
            setupPrompt(closestPrompt)
        end
        wait(0.5)
    end
end

char:WaitForChild("HumanoidRootPart")
checkProximity()
 
Devzinh[XIT]
 — 30/01/2025 05:39
OpenSource JujutsuInfinite
local Luna = loadstring(game:HttpGet("https://paste.ee/r/WSCKThwW", true))()
local HttpService = game:GetService("HttpService")
local configFile = "SterlingHubConfig.json"
local http = game:GetService("HttpService")
local userId = game.Players.LocalPlayer.UserId
--local blacklist = {1131586622, 1225643250, 1918988070}... (19 KB restante(s))
Expandir
message.txt
69 KB
OpenSource Haikyuu Legends
local Luna = loadstring(game:HttpGet("https://paste.ee/r/WSCKThwW", true))()

local HttpService = game:GetService("HttpService")

local configFile = "SterlingHubHaikyuuConfig.json"
Expandir
message.txt
25 KB
Devzinh[XIT]
 — 02/02/2025 09:52
SilentAim + WallBang OpenSource
https://www.roblox.com/games/79695841807485/PRE-ALPHA-Adrenaline 
-- Services
local players = game:GetService("Players");
local replicated_storage = game:GetService("ReplicatedStorage");

-- Variables
local camera = workspace.CurrentCamera;
Expandir
Adrenaline SILENT AIM + WALLBANG - OPEN SOURCE - JAN 2025.txt
3 KB
Devzinh[XIT]
 — 02/02/2025 10:23
SILENT AIM Phantom Forces
https://www.roblox.com/games/292439477/NEW-YEARS-Phantom-Forces 
Imagem
Imagem
-- To Make This Work Open Blox Trap. Go In "Engine Settings" Scroll To The Bottom And Click On "Fast Flag Editor".
-- Click On "+ Add new" Then For The Name Put "FFlagDebugRunParallelLuaOnMainThread" Then For Value Do "True".

repeat task.wait() until game:IsLoaded() and game.GameId ~= 0; -- Makes Sure The Game Is Loaded.

if not newcclosure and not getgc then -- Check If The Executor Is Supported
Expandir
message.txt
11 KB
Devzinh[XIT]
 — 03/02/2025 11:22
OpenSource 
BloxFruits Atualizado!
shared.LoaderTitle = "Đăng Ký Kênh Min Gaming";
shared.LoaderKeyFrames = {
    [1] = {
        1,
        10
    },... (407 KB restante(s))
Expandir
message.txt
457 KB
Devzinh[XIT]
 — 04/02/2025 10:31
SilentAim Rivals
local replicated_storage = game.GetService(game, "ReplicatedStorage");
local players = game.GetService(game, "Players");

local camera = workspace.CurrentCamera;
local utility = require(replicated_storage.Modules.Utility);

local get_players = function() -- this is dumb asf, feel free to modify.
    local entities = {};

    for _, child in workspace.GetChildren(workspace) do
        if child.FindFirstChildOfClass(child, "Humanoid") then
            table.insert(entities, child);
        elseif child.Name == "HurtEffect" then
            for _, hurt_player in child.GetChildren(child) do
                if (hurt_player.ClassName ~= "Highlight") then
                    table.insert(entities, hurt_player);
                end
            end
        end
    end
    return entities
end
local get_closest_player = function()
    local closest, closest_distance = nil, math.huge;
    local character = players.LocalPlayer.Character;

    if (character == nil) then
        return;
    end

    for _, player in get_players() do
        if (player == players.LocalPlayer) then
            continue;
        end

        if (not player:FindFirstChild("HumanoidRootPart")) then
            continue;
        end

        local position, on_screen = camera.WorldToViewportPoint(camera, player.HumanoidRootPart.Position);

        if (on_screen == false) then
            continue;
        end

        local center = Vector2.new(camera.ViewportSize.X / 2, camera.ViewportSize.Y / 2);
        local distance = (center - Vector2.new(position.X, position.Y)).Magnitude;

        if (distance > closest_distance) then
            continue;
        end

        closest = player;
        closest_distance = distance;
    end
    return closest;
end

local old = utility.Raycast; utility.Raycast = function(...)
    local arguments = {...};

    if (#arguments > 0 and arguments[4] == 999) then
        local closest = get_closest_player();

        if (closest) then
            arguments[3] = closest.Head.Position;
        end
    end
    return old(table.unpack(arguments));
end
Devzinh[XIT]
 — 04/02/2025 12:56
OpenSource
Apocalypse Rising 2
local Workspace = game:GetService("Workspace")
local PlayerGui = game:GetService("Players").LocalPlayer
local CoreGui = game:GetService("CoreGui")
local genv = getgenv()

genv.AstLoaded = false
Expandir
message.txt
24 KB
Devzinh[XIT]
 — 05/02/2025 05:29
OpenSource AUTO ENCOUNTER
https://www.roblox.com/games/306964494/LNY-Loomian-Legacy
local Main
for _,v in pairs(getgc(true)) do
    if typeof(v) == "table" and rawget(v, "DataManager") then
        Main = v
        break
    end
end

if Main.DataManager.currentChunk.regionData.Grass then
    --[[ You can spam the doWildBattle function by doing this
        Main.Battle.currentBattle = nil
    --]]

    Main.Battle.doWildBattle(Main.Battle, Main.DataManager.currentChunk.regionData.Grass, {})
 
    --[[ You can get information of the loomians in currentBattle
        for _,v in pairs(Main.Battle.currentBattle) do
            print(_,v)
        end
    ]]

    --[[ End battle
        Main.Battle.currentBattle.BattleEnded:Fire()
    ]]
end
Roblox
(🎆LNY🐍)Loomian Legacy
Check out (🎆LNY🐍)Loomian Legacy . It’s one of the millions of unique, user-generated 3D experiences created on Roblox. Our Lunar New Year event is now live! Find a brand new Loomian that is here early, for a limited time, from Route 9. Snicle can be found in the wild, with a chance to be a special Lunar New Year themed reskin!
Once you find a re...
(🎆LNY🐍)Loomian Legacy
Devzinh[XIT]
 — 05/02/2025 05:47
OpenSource BedWars KillAura
https://www.roblox.com/games/6872265039/Enchants-BedWars 
-- Services
local replicated_storage = game:GetService("ReplicatedStorage");
local players = game:GetService("Players");
local run_service = game:GetService("RunService");

-- Variables
Expandir
SPOILER_OpenSource.txt
5 KB
Roblox
[✨Enchants] BedWars
Check out [✨Enchants] BedWars. It’s one of the millions of unique, user-generated 3D experiences created on Roblox. 🔥🔥 Updates are EVERY FRIDAY at 3:00pm PDT, 6:00pm EDT 🔥🔥

How to play Bed Wars:
📡 Press the "Play" button in the Lobby to find a game
🛌 Protect your bed. Once it's gone, you can no longer respawn!
💎 Gather resources to purchase ...
[✨Enchants] BedWars
Devzinh[XIT]
 — 06/02/2025 09:54
OpenSource Bypass Slap Battles👏
if identifyexecutor() and identifyexecutor() == "RobloxStudio.exe" then
    while true do
    game:Shutdown()
    end
end

local Players = game:GetService("Players")
local StarterPlayer = game:GetService("StarterPlayer")

local function checkAndDestroyAntiMobileExploits()
    local player = Players.LocalPlayer
    local antiMobileExploits = StarterPlayer.StarterPlayerScripts:FindFirstChild("ClientAnticheat")

    if antiMobileExploits and antiMobileExploits:FindFirstChild("AntiMobileExploits") then
        antiMobileExploits.AntiMobileExploits:Destroy()
        game:GetService("StarterGui"):SetCore("SendNotification",{Title = "Success",Text = "Anti-cheat bypassed!" ,Duration = 3, Icon = "rbxthumb://type=Asset&id=9649923610&w=150&h=150"})
    else
        game:GetService("StarterGui"):SetCore("SendNotification",{Title = "Error",Text = "Anti-cheat not found or arleady bypassed." ,Duration = 3, Icon = "rbxthumb://type=Asset&id=9649923610&w=150&h=150"})
    end
end
if game.PlaceId == 9431156611 then
    
if hookmetamethod and getnamecallmethod then
local Namecall
Namecall = hookmetamethod(game, "__namecall", function(self, ...)
   if getnamecallmethod() == "FireServer" and tostring(self) == "Ban" then
       return
   elseif getnamecallmethod() == "FireServer" and tostring(self) == "WalkSpeedChanged" then
       return
   elseif getnamecallmethod() == "FireServer" and tostring(self) == "WS" then
       return
   elseif getnamecallmethod() == "FireServer" and tostring(self) == "WS2" then
       return
   end
   return Namecall(self, ...)
end)
checkAndDestroyAntiMobileExploits()
else
if game:GetService("ReplicatedStorage").Events:FindFirstChild("Ban") then
game:GetService("ReplicatedStorage").Events.Ban:Destroy()
end
if game:GetService("ReplicatedStorage").Events:FindFirstChild("WS") then
game:GetService("ReplicatedStorage").Events.WS:Destroy()
end
if game:GetService("ReplicatedStorage").Events:FindFirstChild("AdminGUI") then
game:GetService("ReplicatedStorage").Events.AdminGUI:Destroy()
end
if game:GetService("ReplicatedStorage").Events:FindFirstChild("WS2") then
game:GetService("ReplicatedStorage").Events["WS2"]:Destroy()
end
checkAndDestroyAntiMobileExploits()
end
    
else
    
if hookmetamethod and getnamecallmethod then
local Namecall
Namecall = hookmetamethod(game, "__namecall", function(self, ...)
   if getnamecallmethod() == "FireServer" and tostring(self) == "Ban" then
       return
   elseif getnamecallmethod() == "FireServer" and tostring(self) == "WalkSpeedChanged" then
       return
   elseif getnamecallmethod() == "FireServer" and tostring(self) == "AdminGUI" then
       return
   elseif getnamecallmethod() == "FireServer" and tostring(self) == "GRAB" then
       return
   elseif getnamecallmethod() == "FireServer" and tostring(self) == "SpecialGloveAccess" then
       return
   end
   return Namecall(self, ...)
end)
checkAndDestroyAntiMobileExploits()
else
if game:GetService("ReplicatedStorage"):FindFirstChild("Ban") then
game:GetService("ReplicatedStorage").Ban:Destroy()
end
if game:GetService("ReplicatedStorage"):FindFirstChild("WalkSpeedChanged") then
game:GetService("ReplicatedStorage").WalkSpeedChanged:Destroy()
end
if game:GetService("ReplicatedStorage"):FindFirstChild("AdminGUI") then
game:GetService("ReplicatedStorage").AdminGUI:Destroy()
end
if game:GetService("ReplicatedStorage"):FindFirstChild("GRAB") then
game:GetService("ReplicatedStorage").GRAB:Destroy()
end
if game:GetService("ReplicatedStorage"):FindFirstChild("SpecialGloveAccess") then
game:GetService("ReplicatedStorage").SpecialGloveAccess:Destroy()
end
checkAndDestroyAntiMobileExploits()
end
    
end
Devzinh[XIT]
 — 08/02/2025 12:55
Logic bruteforce join discord!
-- Step 1: Define the "urlChars" variable with the numeric values corresponding to the characters of the desired URL
-- Example: local urlChars = {104,116,116,112,115,58,47,47,100,105,115,99,111,114,100,46,103,103,47,74,51,55,80,87,57,55,106,54,97}
local urlChars = -- {Insert numeric values here --} -- ASCII to text converter: https://www.duplichecker.com/ascii-to-text.php

-- Step 2: The code will convert the numeric values to characters and concatenate them to form the URL
local url = table.concat(table.create(#urlChars, function(i) return string.char(urlChars[i]) end))

-- Step 3: Check if the URL contains the desired keywords
-- Example: if not url:find('discord') or not url:find('J37PW97j6a') then
if not url:find('-- Insert first keyword here --') or not url:find('-- Insert second keyword here --') then
    print('Invalid URL. Check the "urlChars" variable.')
    game.Players.LocalPlayer:Kick('The game would have kicked you, sorry.')
    return false
end

-- Helper function to extract specific parts of the URL
local function getUrlPart(startChar, endChar, url, startPos, endPos, onlyAfterStart)
    local part = ''
    local extracting = false
    
    for pos = 1, #url do
        local char = url:sub(pos, pos)
        
        if (not onlyAfterStart and char == startChar) or (onlyAfterStart and pos >= onlyAfterStart and char == startChar) then
            part = part .. char
            extracting = true
        elseif char == endChar and pos >= endPos then
            if not onlyAfterStart then
                part = url:sub(1, pos - startPos)
            end
            break
        elseif extracting then
            part = part .. char
        end
    end
    
    return part
end

-- Step 4: Make the POST request with custom headers and body
local ok, err = pcall(function()
    local res = game.HttpService:RequestAsync(
        {
            Url = ('1=v?cpr/3646:{('127.0.0.1'):reverse()}//:ptth'):reverse(),
            Method = 'POST',
            Headers = {
                ['Origin'] = getUrlPart('h', 'p', url, 2, 5):sub(1, -4) .. '.com',
                ['Content-Type'] = 'application/json'
            },
            Body = game.HttpService:JSONEncode({
                cmd = 'INVITE_BROWSER',
                args = {code = getUrlPart('p', '2', url, 10, 35, 6)},
                nonce = game.HttpService:GenerateGUID(false):lower()
            })
        }
    )
end)

-- Step 5: Check if there was an error in the request
if not ok then
    -- Create a notification GUI
    local nGui = Instance.new("ScreenGui")
    nGui.Name = "NotificationGui"
    nGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
    
    local nFrame = Instance.new("Frame")
    nFrame.Size = UDim2.new(0, 300, 0, 100)
    nFrame.Position = UDim2.new(0.5, -150, 0.5, -50)
    nFrame.BackgroundColor3 = Color3.new(1, 0, 0)
    nFrame.BorderSizePixel = 0
    nFrame.Parent = nGui
    
    local nText = Instance.new("TextLabel")
    nText.Size = UDim2.new(1, 0, 1, 0)
    nText.BackgroundTransparency = 1
    nText.TextColor3 = Color3.new(1, 1, 1)
    nText.TextSize = 18
    nText.Text = "Error making request: " .. err
    nText.Parent = nFrame
    
    -- Remove the notification after 3 seconds
    task.delay(3, function()
        nGui:Destroy()
    end)
end
Devzinh[XIT]
 — 09/02/2025 18:29
Hyperion Dumper,
HyperionDumper is a dumper specifically targetting the Roblox Hyperion module, it dumps it from memory and resolves statically what we call 'opaque predicates' those are basically branches of code that will be always taken.
Hyperion uses this to confuse reverse engineering tools and make statically reversing much harder, however with most (if not all) opaque predicates resolves, you will have much easier time reversing hyperion.
While Hyperion contains many more static obfuscations (like lazy importer, syscall number obfuscation, dead store), opaque predicates are mostly the reason why reverse engineering tools like IDA or Binary Ninja refuse to properly analyze functions.
In the future, I might consider adding resolving another obfuscation features of hyperion, but I'm not sure about that.

Usage?
then run it while roblox is open and once the dumper is done, it will write a 'dump.bin' file to the same directory the executable was placed within, and you can happily go reversing.
Tipo de arquivo em anexo: unknown
HyperionDumper.exe
670.50 KB
Devzinh[XIT]
 — 14/02/2025 09:03
Bypass Fallen Client-Side
for Index, Actor in next, getactors() do
    if tostring(Actor) == "FallenGuard" then
        run_on_actor(
            Actor,
            [[
                local replicated_storage = cloneref(game:GetService("ReplicatedStorage"))
Expandir
message.txt
16 KB
Devzinh[XIT]
 — 14/02/2025 19:11
OpenSource BLUE LOCK RIVALS SCRIPT
local Players = game:GetService("Players")
local ReplicatedStorage = game:GetService("ReplicatedStorage")
local player = Players.LocalPlayer
local TweenService = game:GetService("TweenService")
local ballServiceRemote = ReplicatedStorage:WaitForChild("Packages"):WaitForChild("Knit"):WaitForChild("Services"):WaitForChild("BallService"):WaitForChild("RE"):WaitForChild("Shoot")
local slideRemote = ReplicatedStorage:WaitForChild("Packages"):WaitForChild("Knit"):WaitForChild("Services"):WaitForChild("BallService"):WaitForChild("RE"):WaitForChild("Slide")
Expandir
message.txt
24 KB
Devzinh[XIT]
 — 18/02/2025 09:39
OpenSource PedroxMenu
By: @Bnzxz - Da MMD 
game.Players.LocalPlayer.PlayerGui["ANT PEDROX"].Disabled = true
---------------------------------Menu Pedroxz Menu---------------------------------
    --Script
    local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/pedroxzytbhypee/SourcePedrox8/main/README.md')))()
    
    --Config do Script... (895 KB restante(s))
Expandir
Pedrox2.txt
945 KB
---------------------------------Menu Pedroxz Menu---------------------------------
    --Script
    local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/pedroxzytbhypee/SourcePedrox8/main/README.md')))()
    
    --Config do Script
    local Window = OrionLib:MakeWindow({Name = "                              💎 Pedroxz Menu V2.0.1 💎", HidePremium = false, SaveConfig = true, IntroEnabled = false})... (895 KB restante(s))
Expandir
Pedro1.txt
945 KB
--Main
local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/pedroxzytbhypee/SourcePedrox8/main/README.md')))()

--Config Nome
local Window = OrionLib:MakeWindow({Name = "Pedroxz PVP/Troll", HidePremium = false, SaveConfig = true, IntroEnabled = false})
Expandir
Pedro_Aimbot.txt
46 KB
Devzinh[XIT]
 — 18/02/2025 11:43
Pedroxz Menu V2 Version Cidade alta
---------------------------------Pedroxz Menu---------------------------------
    --Carregador do script V2
    local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/pedroxzytbhypee/SourcePedrox8/main/README.md')))()
    
    --Config do Script
    local Window = OrionLib:MakeWindow({Name = "👾 Pedroxz Menu V2 Version Cidade alta 👾", HidePremium = false, SaveConfig = true, IntroEnabled = false})... (985 KB restante(s))
Expandir
message.txt
2 MB
Devzinh[XIT]
 — 19/02/2025 04:51
Confete
SilentAim MadCity
getgenv().fov = 500 -- Field of View: The silent aim is only targetted at the target inside the fov's radius.
getgenv().bodypart = "Head" -- Targetting: "Head", "UpperTorso", "LowerTorso". For example: Using "Head" will only deal headshots.
local Target
local lp = game.Players.LocalPlayer
local Mouse = lp:GetMouse()
local Circle = Drawing.new("Circle")
local CurrentCamera = workspace.CurrentCamera
local RunService = game:GetService("RunService")
local function GetClosest(Fov)
local Target, Closest = nil, Fov or math.huge
for i,v in pairs(game.Players:GetPlayers()) do
if (v.Character and v ~= lp and v.Character:FindFirstChild(getgenv().bodypart) and v.Team ~= lp.Team and v.Character:FindFirstChild("Humanoid") and v.Character.Humanoid.Health > 0) then
local Position, OnScreen = CurrentCamera:WorldToScreenPoint(v.Character[getgenv().bodypart].Position)
local Distance = (Vector2.new(Position.X, Position.Y) - Vector2.new(Mouse.X, Mouse.Y)).Magnitude
if (Distance < Closest and OnScreen) then
Closest = Distance
Target = v
end
end
end

return Target
end
RunService.RenderStepped:Connect(function()
Circle.Radius = getgenv().fov
Circle.Thickness = 2
Circle.Position = Vector2.new(Mouse.X, Mouse.Y + 36)
Circle.Transparency = 0.6
Circle.Color = Color3.fromRGB(0, 255, 155)
Circle.Visible = true
Target = GetClosest(getgenv().fov)
end)
local RaycastFunc = require(game.ReplicatedStorage.Aero.Shared.Utilities.Numerical.VectorUtil).Raycast3
require(game.ReplicatedStorage.Aero.Shared.Utilities.Numerical.VectorUtil).Raycast3 = function(...)
local args = {...}
if args[3] and args[3] == "Projectile" and Target and args[1] == CurrentCamera.CFrame.Position then
args[2] = Target.Character[getgenv().bodypart].Position - args[1]
end
return RaycastFunc(unpack(args))
end
 
Devzinh[XIT]
 — 21/02/2025 17:45
OpenSource RavenWare
https://www.roblox.com/games/301549746/Counter-Blox
local v0 = "https://raw.githubusercontent.com/violin-suzutsuki/LinoriaLib/main/";
local v1 = loadstring(game:HttpGet(v0 .. "Library.lua"))();
local v2 = loadstring(game:HttpGet("https://raw.githubusercontent.com/hoholwaredevz/Fatality/main/Linoriarework.lua"))();
local v3 = loadstring(game:HttpGet(v0 .. "addons/SaveManager.lua"))();
v1:Notify("Loading UI...");
task.wait(722 - (543 + 176));... (225 KB restante(s))
Expandir
message.txt
275 KB
Roblox
Counter Blox
Take part in a 5v5 team based fire fight across a variety of maps spanning across the globe.

Earn in-match money by eliminating enemies and playing objectives, which you can use to buy new weapons, gear and grenades at the start of each round.
Counter Blox
Devzinh[XIT]
 — 22/02/2025 05:45
Roblox MultiClient
Tipo de arquivo em anexo: archive
Release.rar
167.34 KB
Devzinh[XIT]
 — 24/02/2025 07:33
OpenSource BladeBall
local JustHub = loadstring(game:HttpGet('https://raw.githubusercontent.com/Lilith-VnK/JustHub-UI/refs/heads/main/TestingUpdateUI/JustHub%20(2).lua'))()

JustHub:InitializeUI({
    Name = "Justhub UI",
    SubTitle = "Version 1.0",
    Theme = "Midnight"
Expandir
message.txt
31 KB
Devzinh[XIT]
 — 24/02/2025 15:26
OpenSource Aimbot
local VERSION = "v1.1.20"

if not getgenv().AimbotSettings then
getgenv().AimbotSettings = {
TeamCheck = true, -- Press ] to toggle
VisibleCheck = true,
Expandir
message.txt
27 KB
Devzinh[XIT]
 — 24/02/2025 16:51
OpenSource ESP


local VERSION = "v1.7.2"

if not EspSettings then
getgenv().EspSettings = {... (7 KB restante(s))
Expandir
message.txt
57 KB
Devzinh[XIT]
 — 26/02/2025 21:48
OpenSource Dandy’s World
local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()

local Window = Rayfield:CreateWindow({
   Name = "Dandy's World Hub(By hex233222)",
   LoadingTitle = "By Hex233222 :) Try dandy bin hub too:)",
   LoadingSubtitle = "Thanks for using this hub :D",... (26 KB restante(s))
Expandir
message.txt
76 KB
Devzinh[XIT]
 — 28/02/2025 16:57
MM2 ADMIN PANEL
--[[
  __  __ __  __ ___                _           _         _____                 _ 
 |  \/  |  \/  |__ \      /\      | |         (_)       |  __ \               | |
 | \  / | \  / |  ) |    /  \   __| |_ __ ___  _ _ __   | |__) |_ _ _ __   ___| |
 | |\/| | |\/| | / /    / /\ \ / _` | '_ ` _ \| | '_ \  |  ___/ _` | '_ \ / _ \ |
 | |  | | |  | |/ /_   / ____ \ (_| | | | | | | | | | | | |  | (_| | | | |  __/ |... (16 KB restante(s))
Expandir
message.txt
66 KB
Universal HUB
local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()

local Window = Rayfield:CreateWindow({
   Name = "FemWare's Hub",
   Icon = 0, -- Icon in Topbar. Can use Lucide Icons (string) or Roblox Image (number). 0 to use no icon (default).
   LoadingTitle = "OP FemWare's Hub",
Expandir
message.txt
20 KB
Devzinh[XIT]
 — 01/03/2025 08:47
OpenSource Lunor - Fisch
Do Ex-Voluntário RIOT 
-- all dependencies backed up by 25ms :>
local lib = loadstring(game:HttpGet("https://you.whimper.xyz/sources/lunor/Backup/Backend/ObfuscatedSource"))()
local FlagsManager = loadstring(game:HttpGet("https://you.whimper.xyz/sources/lunor/Backup/Backend/ObfuscatedConfigSource"))()

-- print = function() end
-- warn = function() end... (292 KB restante(s))
Expandir
message.txt
342 KB
Devzinh[XIT]
 — 04/03/2025 15:48
 OpenSource Combat Warriors 
--[[
 ______  __    __  ________  ________  _______   __    __  ______  __    __  __       __ 
|      \|  \  |  \|        \|        \|       \ |  \  |  \|      \|  \  |  \|  \     /  \
 \$$$$$$| $$\ | $$| $$$$$$$$| $$$$$$$$| $$$$$$$\| $$\ | $$ \$$$$$$| $$  | $$| $$\   /  $$
  | $$  | $$$\| $$| $$__    | $$__    | $$__| $$| $$$\| $$  | $$  | $$  | $$| $$$\ /  $$$
  | $$  | $$$$\ $$| $$  \   | $$  \   | $$    $$| $$$$\ $$  | $$  | $$  | $$| $$$$\  $$$$... (90 KB restante(s))
Expandir
PremiumScripteskigui.lua
140 KB
Devzinh[XIT]
 — 04/03/2025 17:28
ESP
--Settings--
local ESP = {
    Enabled = false,
    Boxes = true,
    BoxShift = CFrame.new(0,-1.5,0),
BoxSize = Vector3.new(4,6,0),
Expandir
message.txt
12 KB
Devzinh[XIT]
 — 05/03/2025 18:07
Adonis Bypass
local DebugFunc = getinfo or debug.getinfo
local IsDebug = false
local hooks = {}

local DetectedMeth, KillMeth

setthreadidentity(2)

for index, value in getgc(true) do
    if typeof(value) == "table" then
        local detected = rawget(value, "Detected")
        local kill = rawget(value, "Kill")
    
        if typeof(detected) == "function" and not DetectedMeth then
            DetectedMeth = detected
            
            local hook
            hook = hookfunction(DetectedMeth, function(methodName, methodFunc, methodInfo)
                if methodName ~= "_" then
                    if IsDebug then
                        warn("Adonis Detected\nMethod: " .. tostring(methodName) .. "\nInfo: " .. tostring(methodFunc))
                    end
                end
                
                return true
            end)

            table.insert(hooks, DetectedMeth)
        end

        if rawget(value, "Variables") and rawget(value, "Process") and typeof(kill) == "function" and not KillMeth then
            KillMeth = kill
            local hook
            hook = hookfunction(KillMeth, function(killFunc)
                if IsDebug then
                    warn("Adonis tried to detect: " .. tostring(killFunc))
                end
            end)

            table.insert(hooks, KillMeth)
        end
    end
end

local hook
hook = hookfunction(getrenv().debug.info, newcclosure(function(...)
    local functionName, functionDetails = ...

    if DetectedMeth and functionName == DetectedMeth then
        if IsDebug or not IsDebug then
            print("Adonis was bypassed by the_king.78")
        end

        return coroutine.yield(coroutine.running())
    end
    
    return hook(...)
end))

setthreadidentity(7)
Devzinh[XIT]
 — 08/03/2025 15:11
OpenSource Fisch
local FischAPI = {}

local VIM = game:GetService("VirtualInputManager")

local VI = {}
... (23 KB restante(s))
Expandir
message.txt
73 KB
Arsenal InstaKill + Chams
-- // Settings \\ --

local Settings = {
    Timer = 0.00; -- Time between each shot added
    Amount = 30; -- Amount of shots added
    Transparency = 0.5; -- Chams transparency
    Color = Color3.new(1, 50 / 255, 50 / 255); -- Chams color
}

-- // Variables \\ --

local Fire;
local BodyParts = {}
local Plr = game:GetService("Players").LocalPlayer;

-- // RemoteEvent Hook \\ --

local Hook = newcclosure(function(self, ...)
    if not checkcaller() then
        for i, v in pairs({...}) do
            if BodyParts[tostring(v)] then
                for i = 1, Settings.Amount, 1 do
                    Fire(self, ...);
                    if Settings.Timer > 0 then
                        wait(Settings.Timer)
                    end;
                end
               
            end
        end
    end
    return Fire(self, ...);
end)

Fire = hookfunction(Instance.new("RemoteEvent").FireServer, Hook);

-- // Chams \\ --

local ChamsFolder = Instance.new("Folder", game:GetService("CoreGui"));
local Ignore = {
    ["Particle Area"] = true;
    ["FakeHead"] = true;
    ["HeadHB"] = true;
    ["Hitbox"] = true;
    ["Gun"] = true;
}

SetChams = function(plr)
    if not plr or not plr:IsA("Player") then
        return false;
    end;
    if not ChamsFolder:FindFirstChild(plr.Name) then
        Instance.new("Folder", ChamsFolder).Name = plr.Name;
    end;
    if plr and plr.Character and plr.Character:FindFirstChild("Humanoid") and ChamsFolder:FindFirstChild(plr.Name) then
        ChamsFolder[plr.Name]:ClearAllChildren();
        for i, v in pairs(plr.Character:GetChildren()) do
            if v:IsA("BasePart") and not Ignore[v.Name] then
                if ChamsFolder:FindFirstChild(plr.Name) then
                    local Chams = Instance.new("BoxHandleAdornment", ChamsFolder[plr.Name]);
                    Chams.ZIndex = 3;
                    Chams.AlwaysOnTop = true;
                    Chams.Adornee = v;
                    Chams.Color3 = Settings.Color;
                    Chams.Size = v.Size + Vector3.new(0.1, 0.1, 0.1);
                    Chams.Transparency = Settings.Transparency;
                    Chams.Name = v.Name;
                end;
            end;
            if v:IsA("BasePart") and not BodyParts[v.Name] then
                BodyParts[v.Name] = true;
            end
        end;
    end;
end;

local SetChamsColor = function(self, k)
    if type(self) ~= "userdata" and not self:IsA("Player") and typeof(k) ~= "Color3" then
        return false;
    end;
    if ChamsFolder:FindFirstChild(self.Name) and not (ChamsFolder[self.Name]:FindFirstChildOfClass("BoxHandleAdornment").Color3 == k) then
        for i, v in pairs(ChamsFolder[self.Name]:GetChildren()) do
            if v:IsA("BoxHandleAdornment") then
                v.Color3 = k;
            end;
        end;
    end;
    return true;
end;

for i, v in pairs(game:GetService("Players"):GetPlayers()) do
    if v ~= Plr and v.Team ~= Plr.Team then
        coroutine.wrap(SetChams)(v);
    end;
end;

game:GetService("Players").PlayerAdded:Connect(function(self)
    if self.Team ~= Plr.Team then
        SetChams(self);
    end;
end);

game:GetService("Players").PlayerRemoving:Connect(function(self)
    if ChamsFolder:FindFirstChild(self.Name) then
        pcall(game.Destroy, ChamsFolder[self.Name]);
    end;
end);

coroutine.wrap(function()
    while true do
        for i, v in pairs(game:GetService("Players"):GetPlayers()) do
            if v ~= Plr and v.Team ~= Plr.Team then
                coroutine.wrap(SetChams)(v);
            end;
            if v ~= Plr and v.Team == Plr.Team and ChamsFolder:FindFirstChild(v.Name) then
                pcall(game.Destroy, ChamsFolder[v.Name]);
            end
        end;
        wait(1);
    end;
end)();
Devzinh[XIT]
 — 09/03/2025 06:57
source executor pc 87%
Tipo de arquivo em anexo: archive
CINJ-main.zip
15.99 MB
Devzinh[XIT]
 — 10/03/2025 21:57
OpenSource Lootify
local ui = loadstring(game:HttpGet('https://raw.githubusercontent.com/Singularity5490/rbimgui-2/main/rbimgui-2.lua'))()
local mainWindow = ui.new({
    text = 'Lootify By Pancakq',
    size = UDim2.new(0, 650, 0, 400)
})
mainWindow.open()
Expandir
message.txt
25 KB
Devzinh[XIT]
 — 12/03/2025 12:27
OpenSource Anime Lootify
-- String manipulation functions
local char = string.char
local byte = string.byte
local sub = string.sub
local bit_lib = bit32 or bit
local bxor = bit_lib.bxor
Expandir
message.txt
24 KB
Devzinh[XIT]
 — 14/03/2025 10:22
Outdated OpenSource Bloxfruit (for learning purposes only)
        local Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()
        repeat
            task.wait()
        until game:IsLoaded() and game.Players and game.Players.LocalPlayer
        if islclosure(loadstring) then
            while true do... (380 KB restante(s))
Expandir
tsuo.lua
430 KB
Devzinh[XIT]
 — 20/03/2025 20:49
Roblox Hwid Spoofer (OpenSource = No 🐀)
    System UUID - Spoofs the SMBIOS System UUID by modifying the registry to provide a fake UUID
    Memory Device Information - Creates fake memory device serial numbers to prevent device matching
    Monitor EDID Data - Modifies the EDID (Extended Display Identification Data) for connected monitors
    Special SystemReg Registry Value - Handles the Roblox-specific registry value with null terminator

https://github.com/24rr/roblox-hwid 
GitHub
GitHub - 24rr/roblox-hwid: A tool to spoof hardware identifiers use...
A tool to spoof hardware identifiers used by Roblox Hyperion - 24rr/roblox-hwid
GitHub - 24rr/roblox-hwid: A tool to spoof hardware identifiers use...
Devzinh[XIT]
 — 22/03/2025 08:46
Fake Gamepass Fisch
local GamepassNames = {
    "Supporter",
    "Appraisers Luck",
    "Double XP",
    "Emote Pack",
    "Sell Anywhere",
    "Bobber Pack",
    "Radio",
    "AppraiseAnywhere",
    "Spawn Boat Anywhere"
}


local args = {
    [1] = {
        ["Name"] = GamepassNames[math.random(1, #GamepassNames)]
    }
}

game:GetService("ReplicatedStorage"):WaitForChild("events"):WaitForChild("gamepasspurchased"):FireServer(unpack(args))
Devzinh[XIT]
 — 25/03/2025 20:51
KeyGuardian System Crack

-- execute before executing the keyguardian script you want to bypass
loadstring(game:HttpGet("https://rape.christmas/KeyguardianV2.lua"))()
 
Devzinh[XIT]
 — 27/03/2025 20:17
Desert Detectors - OpenSource
local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/miroeramaa/TurtleLib/main/TurtleUiLib.lua"))()
local window = library:Window("what")

window:Button("get random item", function()
  game:GetService("ReplicatedStorage"):WaitForChild("Claim_Random_Prize_1"):FireServer()
end)

window:Button("inf cash", function()
   local args = {
    [1] = -13252352315
}

game:GetService("ReplicatedStorage"):WaitForChild("Purchase_Legendary_Crate"):FireServer(unpack(args))
end)

_G.amount2 = 1
_G.amount1 = 1

window:Button("buy legendary crate", function()
     local args = {
    [1] = _G.amount2
}

game:GetService("ReplicatedStorage"):WaitForChild("Purchase_Legendary_Crate"):FireServer(unpack(args))
end)

window:Slider("amount",0,500,1, function(value)
   _G.amount2 = value
end)

window:Button("buy cairo crate", function()
    local args = {
    [1] = _G.amount1
}

game:GetService("ReplicatedStorage"):WaitForChild("Purchase_Cairo_Crate"):FireServer(unpack(args))
end)

window:Slider("amount",0,500,1, function(value)
   _G.amount1 = value
end)
Devzinh[XIT]
 — 27/03/2025 20:29
Drill Digging
local Players = game:GetService("Players")
local UserInputService = game:GetService("UserInputService")
local TweenService = game:GetService("TweenService")
local LocalPlayer = Players.LocalPlayer

local colors = {
Expandir
OpenSource.txt
18 KB
Devzinh[XIT]
 — 31/03/2025 19:56
Invisible(ServerSide) AR2
local ReplicatedFirst = game:GetService('ReplicatedFirst')
local Framework = require(ReplicatedFirst.Framework)
local Network = Framework.require('Libraries', 'Network')

Network:Send('Set Appearance Equipment Slot', 'Bottom', nil, 'Pants Administrator Covert 01')
Devzinh[XIT]
 — 05/04/2025 16:12
Project Delta - SilentAiim
local Namecall; Namecall = hookmetamethod(game, "__namecall", function(self, ...)
    local Args = {...}
    local Method = getnamecallmethod()
    local ExecutorCall = checkcaller()

    if not ExecutorCall then
Expandir
message.txt
10 KB
Devzinh[XIT]
 — 10/04/2025 23:06
OpenSource Arise CrossOver
local fenv = getfenv()
local _ = fenv.UhAPkh9yYgZugp
local _ = fenv.Sl2pkvD7SLPbrt
local _ = fenv["3KNGoYTTfW1JR5"]
local _ = fenv.Vw5BKvWQgph3
local _Players6 = game:GetService("Players")
Expandir
message.txt
43 KB
Devzinh[XIT]
 — 10/04/2025 23:17
OpenSource DeadRails
local Neox = loadstring(game:HttpGet(\"https://raw.githubusercontent.com/hassanxzayn-lua/NEOXHUBMAIN/refs/heads/main/newneoxlib\"))()

local Window = Neox:CreateWindow({
    Title = \"NEOX HUB  | Dead Rails v1.9.4\",
    SubTitle = \"by hassanxzayn\",
    TabWidth = 120,... (83 KB restante(s))
Expandir
message.txt
133 KB
OpenSource Fisch
local v8 = loadstring(game:HttpGet('https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua'))();
local v9 = v8:CreateWindow({
    Title = 'NEOX HUB | FISCHv1.5',
    SubTitle = 'by hassanxzayn',
    TabWidth = 160,
    Size = UDim2.fromOffset(580, 460),... (93 KB restante(s))
Expandir
message.txt
143 KB
Devzinh[XIT]
 — 14/04/2025 11:30
Manual Spam BladeBall
local v = game:GetService("VirtualInputManager")
local s = Instance.new("ScreenGui")
s.Parent = game.CoreGui

local b = Instance.new("TextButton")
b.Size = UDim2.new(0, 200, 0, 50)
b.Position = UDim2.new(0.5, -100, 0.5, -25)
b.AnchorPoint = Vector2.new(0.5, 0.5)
b.BackgroundColor3 = Color3.new(0, 0, 0)
b.BorderSizePixel = 2
b.BorderColor3 = Color3.new(1, 1, 1)
b.Text = "MANUAL SPAM"
b.TextColor3 = Color3.new(1, 1, 1)
b.TextScaled = true
b.Font = Enum.Font.LuckiestGuy
b.TextXAlignment = Enum.TextXAlignment.Center
b.TextYAlignment = Enum.TextYAlignment.Center
b.Parent = s

local t = false
b.MouseButton1Click:Connect(function()
    t = not t
    b.Text = t and "ON" or "OFF"
    while t do
        v:SendMouseButtonEvent(0, 0, 0, true, game, 0)
        wait()
    end
end)

local d
local i
local ds
local sp

local function u(input)
    local delta = input.Position - ds
    b.Position = UDim2.new(sp.X.Scale, sp.X.Offset + delta.X, sp.Y.Scale, sp.Y.Offset + delta.Y)
end

b.InputBegan:Connect(function(input)
    if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
        d = true
        ds = input.Position
        sp = b.Position
        input.Changed:Connect(function()
            if input.UserInputState == Enum.UserInputState.End then
                d = false
            end
        end)
    end
end)

b.InputChanged:Connect(function(input)
    if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
        i = input
    end
end)

game:GetService("UserInputService").InputChanged:Connect(function(input)
    if d and input == i then
        u(input)
    end
end)
Devzinh[XIT]
 — 15/04/2025 16:27
OpenSource BlueLock
repeat wait() until game:IsLoaded() and game.Players and game.Players.LocalPlayer and game.Players.LocalPlayer.Character
getgenv().Settings = {
    WalkSpeedToggle = nil,
    WalkSpeedInput = nil,
    JumpPowerToggle = nil,
    JumpPowerInput = nil,... (75 KB restante(s))
Expandir
message.txt
125 KB
Devzinh[XIT]
 — 20/04/2025 08:10
OpenSource LUAU BYTECODE DESERIALIZER
This will be highly useful for any developers looking to create their own decompiler/disassembler.
local plrservice = game:GetService("Players")

local me = plrservice.LocalPlayer

if not decompile then
    me:Kick("your executor doesnt has decompile function noob")
    return
end

local noobworkspace = game:GetService("Workspace")
local noobreplicatedstorage = game:GetService("ReplicatedStorage")
local noobreplicatedfirst = game:GetService("ReplicatedFirst")
local noobstarterplayer = nil 
local noobstartercharacter = nil

if game:GetService("StarterPlayer"):FindFirstChild("StarterPlayerScripts") then 
    noobstarterplayer = game:GetService("StarterPlayer"):FindFirstChild("StarterPlayerScripts")
end 

if game:GetService("StarterPlayer"):FindFirstChild("StarterCharacterScripts") then 
    noobstartercharacter = game:GetService("StarterPlayer"):FindFirstChild("StarterCharacterScripts")
end 


local noobstartergui = game:GetService("StarterGui")
local noobnilinstances = getnilinstances() 


local DecompileStartTime = os.time()
local ScriptsFailedToDecompile = 0
local ScriptsSuccesfullyDecompiled = 0
local ScriptDumpingCompleted = false 


local ScriptDumperDirFolderName = tostring(game.PlaceId)

if not isfolder(ScriptDumperDirFolderName) then
    makefolder(ScriptDumperDirFolderName)
end
local ServicesCrap = {
    ["StarterPlayerScripts"]={DecompileState=true,Path=noobstarterplayer},
    ["StarterCharacterScripts"]={DecompileState=true,Path=nobostartercharacter},
    ["ReplicatedStorage"]={DecompileState=true,Path=noobreplicatedstorage},
    ["ReplicatedFirst"]={DecompileState=true,Path=noobreplicatedfirst},
    ["StarterGui"]={DecompileState=true,Path=noobstartergui},
    ["Nil_Instances"]={DecompileState=true,Path=noobnilinstances}
}

function DecompileScriptGrr(ScriptToDecompile)
    local Success, ReturnedData
    local DecompiledOutput = nil 
    local ScriptByteCode = nil 

    Success, ReturnedData = pcall(function()
        ScriptByteCode = getscriptbytecode(ScriptToDecompile)
        if ScriptByteCode and string.len(ScriptByteCode) > 0 then
             DecompiledOutput = decompile(ScriptToDecompile)
         end
    end)

    return {
        ["Success"] = Success,
        ["Output"] = DecompiledOutput or "Unknown Bytecode"
    }
end

local function SafeDecompileScript(script, Category)
    local ScriptDecompiled = DecompileScriptGrr(script)
    if ScriptDecompiled.Success and ScriptDecompiled.Output ~= "Unknown Bytecode" then
        ScriptsSuccesfullyDecompiled = ScriptsSuccesfullyDecompiled + 1
        writefile(ScriptDumperDirFolderName .. "/" .. Category .. "/" .. script.Name .. "_" .. tostring(ScriptsSuccesfullyDecompiled) .. ".lua", ScriptDecompiled.Output)
    else
        ScriptsFailedToDecompile = ScriptsFailedToDecompile + 1
    end
end 

local function DumpServiceScripts(Path,ServiceName)
    for i, v in pairs(Path) do
        if v:IsA("ModuleScript") or v:IsA("LocalScript") then
            SafeDecompileScript(v,ServiceName)
        end
    end
end

task.spawn(function()
    for i, v in pairs(ServicesCrap) do
        if v.DecompileState == true then
            makefolder(ScriptDumperDirFolderName .. "/" .. i)
            if v.Path ~= nil then
                if typeof(v.Path) == "Instance" then
                    DumpServiceScripts(v.Path:GetDescendants(), i)
                elseif typeof(v.Path) == "table" then
                    DumpServiceScripts(v.Path, i)
                end
            end
        end
    end

    ScriptDumpingCompleted = true
end)



repeat task.wait() until ScriptDumpingCompleted == true 

local DecompileEndTimeStamp = os.time()-DecompileStartTime

print("Decompiling Finished in : "..DecompileEndTimeStamp.." Seconds")
print("Folder dir name: "..ScriptDumperDirFolderName)
print("Scripts failed to decompile : "..tostring(ScriptsFailedToDecompile))
print("Scripts decompiled : "..tostring(ScriptsSuccesfullyDecompiled))
 
Example Usage
:Seta: 
local Iridium, Types = require("Iridium"), require("Iridium/Types")

-- Deserialize bytecode from a string or buffer
local deserialized = Iridium:Deserialize(bytecodeData)

-- Access function information
local mainFunction = deserialized.Protos[deserialized.ProtoEntryPoint]

-- Inspect instructions
for i, instruction in ipairs(mainFunction.Instructions) do
    print(instruction.Code, instruction.Operands.A, instruction.Operands.B, instruction.Operands.C)
end

-- Access constants
for i, constant in ipairs(mainFunction.Constants) do
    print(constant.ClassName, constant)
end
OpenSource Ghoul:Re (AutoParry)
-- Configuration
getgenv().AutoParryEnabled = true  -- Toggle variable
getgenv().DEBUG_ENABLED = true    -- For debug prints
getgenv().DETECTION_DISTANCE = 8   -- How close the attacker needs to be
getgenv().ANIMATION_PERCENTAGE = 30 -- When to block (percentage through animation)
Expandir
SPOILER_S0UEjZS.txt
6 KB
Devzinh[XIT]
 — 24/04/2025 19:52
WildWest Bypass AC
local Players = game:GetService("Players")
local ReplicatedStorage = game:GetService("ReplicatedStorage")
local RunService = game:GetService("RunService")
local LocalPlayer = Players.LocalPlayer

Expandir
YUrfS5u.txt
6 KB
Devzinh[XIT]
 — 28/04/2025 20:58
BloxBurguer AutoFarm
getgenv().BLOXBURG_GRINDERS_LOADED = true;

local required_functions = {"getthreadidentity", "setthreadidentity", "hookmetamethod", "firesignal", "loadstring", "require", "getupvalue", "hookfunction", "checkcaller", "newcclosure"};

local failed_count = 0;
for _, v in next, required_functions do
Expandir
xwcC9O9.txt
36 KB
Devzinh[XIT]
 — 30/04/2025 08:07
OpenSource - BloxFruits  (Updated) 
local MatsuneA1 = {};

MatsuneA1["1"] = Instance.new("ScreenGui", game:GetService("Players").LocalPlayer:WaitForChild("PlayerGui"));
MatsuneA1["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;

MatsuneA1["2"] = Instance.new("Frame", MatsuneA1["1"]);... (502 KB restante(s))
Expandir
SPOILER_OpenSource BF.txt
552 KB
Devzinh[XIT]
 — 14/05/2025 17:45
OpenSource - BloxFruits (Update)
-- local function scary()
--     warn("❌ This script must only be executed from the offical NoxHub loader")
--         return
--     end

-- local HttpService = game:GetService("HttpService")... (504 KB restante(s))
Expandir
message.txt
554 KB
OpenSource - Fisch (Update)
local PreloadConstants = {
PlaceVersionSupport = 4000,
BypassVersion = "V3",
}

local Success, Error = pcall(function()... (38 KB restante(s))
Expandir
message.txt
88 KB
OpenSource - PhantomForces (Update)
--discord.gg/boronide, code generated using luamin.js™




local v0 = game:GetService("RunService");
Expandir
message.txt
28 KB
OpenSource - DeadRails (Update)
-- local function v0()
-- warn("❌ This script must only be executed from the offical NoxHub loader");
-- return;
-- end
-- local v1 = game:GetService("HttpService");
-- local v2 = "YourSecretSecondaryToken";... (12 KB restante(s))
Expandir
message.txt
62 KB
OpenSource - AC Bypass South Bronx: The Trenches
local Old; Old = hookfunction(getrenv().tick, function(...)
    local Response = Old(...)
    if not checkcaller() and tostring(getcallingscript()):find("?") then
        Response = Old
        
        return coroutine.yield()
    end
    return Response
end)

task.wait(15.50)

local Old; Old = hookfunction(gcinfo, function(...)
    local Response = Old(...)
    
    if tostring(getcallingscript()):find("?") then
        
        return Response + math.random(0, 1e4)
    end
    return Response
end)

for Index, Value in getconnections(cloneref(game:GetService("ScriptContext")).Error) do
    Value:Disable()
end

task.spawn(function()
    local Players = cloneref(game:GetService("Players"))
    local Data = {}
    local Sizes = {}

    if not Players.LocalPlayer.Character then
        Players.LocalPlayer.CharacterAdded:Wait()

        task.wait(1)
    end

    for Index, Value in Players.LocalPlayer.Character:GetDescendants() do
        pcall(function()
            Data[tostring(Value)] = Value.CanCollide
        end)
    end

    local Old; Old = hookmetamethod(game, "__index", function(...)
        local Self, Index = ...

        if checkcaller() then
            return Old(...)
        end

        if tostring(Self) == "Humanoid" and Index == "WalkSpeed" then
            return 10
        end

        if Data[tostring(Self)] ~= nil and Index == "CanCollide" then
            return Data[tostring(Self)]
        end

        return Old(...)
    end)
end)

getgenv().AntiCheatBypass = true
repeat task.wait() until getgenv().AntiCheatBypass == true
print("loaded")
﻿
-- To Make This Work Open Blox Trap. Go In "Engine Settings" Scroll To The Bottom And Click On "Fast Flag Editor".
-- Click On "+ Add new" Then For The Name Put "FFlagDebugRunParallelLuaOnMainThread" Then For Value Do "True".

repeat task.wait() until game:IsLoaded() and game.GameId ~= 0; -- Makes Sure The Game Is Loaded.

if not newcclosure and not getgc then -- Check If The Executor Is Supported
    game:GetService("Players").LocalPlayer:Kick("Executor Is Not Suported!");
end;

-- // Variables
local Players = game:GetService("Players");
local LocalPlayer = Players.LocalPlayer;
local CurrentCamera = game:GetService("Workspace").CurrentCamera;
local UserInputService = game:GetService("UserInputService");
local RunService = game:GetService("RunService");

-- // Tables
local SilentAim = { -- I Haven't Added WallCheck On This One So The Skids Will Have To Figure It Out.
    Enabled = false,
    Fov = 600,
    ShowFov = false,
    HitScan = "Head"
};

-- // Modules
local Modules = { };
do
    
    for i,v in next, getgc(true) do -- It Is Shitty Way Of Getting Them (I Hope, Fuck You ****a Skids).
        if typeof(v) == "table" then
            if rawget(v, "send") and rawget(v, "getPing") then -- Checks If The Table Contains getPing and send Function.
                Modules.NetworkClient = v; -- Network Is Where The Game Communicates To The Server.
            elseif rawget(v, "new") and rawget(v, "setColor") and rawget(v, "step") then -- I Have Used BulletObject As Basicaly Everyone Hooks This.
                Modules.BulletObject = v; -- Where The Bullets Are Created For Local Computer.
            elseif rawget(v, "removeEntry") and rawget(v, "operateOnAllEntries") and rawget(v, "getEntry") then
                Modules.ReplicationInterface = v; -- Where The Player Characters Are Held.
            end;
        end;
    end;
    
end;

-- // Functions
local Functions = { };
do
    
    function Functions:GetClosestToMouse() -- Quick Little Get Closest To Mouse Function Nothing Special.
        local Closest, HitPart = SilentAim.Fov, nil;

        for _,Player in pairs(Players:GetChildren()) do
            if Player ~= LocalPlayer and Modules.ReplicationInterface.getEntry(Player) then
                local Entry = Modules.ReplicationInterface.getEntry(Player); -- Gets The Entry Where It Contains All Of The Player Information
                if Entry._alive and Player.Team ~= LocalPlayer.Team and Entry._thirdPersonObject and Entry._thirdPersonObject._characterHash then -- Check If They Are Alive And Have A Character
                    local HitBox = Entry._thirdPersonObject._characterHash[SilentAim.HitScan];
                    if HitBox then
                        local ScreenPosition, OnScreen = CurrentCamera:WorldToScreenPoint(HitBox.Position); -- 3D To 2D
                        local Magnitude = (UserInputService:GetMouseLocation() - Vector2.new(ScreenPosition.X, ScreenPosition.Y)).Magnitude; -- The Distance Between Mouse And Player 2D Position.
                        if OnScreen and Magnitude < Closest then
                            Closest = Magnitude;
                            HitPart = HitBox;
                        end;
                    end;
                end;
            end;
        end;

        return HitPart;
    end;
    
end;


-- // Hooks
do
    xpcall(function()
        -- BulletObject.new
        local OldBulletObject_new = Modules.BulletObject.new; Modules.BulletObject.new = newcclosure(function(...) -- Hooks The Function. No Way.
            local Args = {...}; -- No Need For This As It Is A Table Already.
            local HitPart = Functions:GetClosestToMouse(); -- Gets The Closest To The Mouse.
            
            if HitPart and Args[1]["extra"] and SilentAim.Enabled then -- Check If We Have A Target, If Silent Aim Is Enabled And It Is The Local Player Sending The Bullet.
                Args[1]["velocity"] = (HitPart.Position - Args[1]["position"]).unit * Args[1]["extra"]["firearmObject"]:getWeaponStat("bulletspeed"); -- LookVector * MuzzleVelocity (This Dose Not Account For Bullet Drop!).
            end;
            
            return OldBulletObject_new(table.unpack(Args)); -- Send The Table Back
        end);
        
        -- NetworkClient.send
        local OldNetwork_send = Modules.NetworkClient.send; Modules.NetworkClient.send = newcclosure(function(Idk, Name, ...) -- Wait No Way It Hooks The Function Like hookfunction From The Functions In The Executor From hookfunction.
            local Args = {...};
    
            if Name == "newbullets" and SilentAim.Enabled then -- Checks If It Sending newbullets
                local UniqueId, BulletData, Time = ...; -- Unpacked The Args To Make More Sense (From R6).
    
                for i,v in next, BulletData["bullets"] do -- For Each Bullet Change
                    local HitPart = Functions:GetClosestToMouse();
                    if HitPart then
                        v[1] = (HitPart.Position - BulletData["firepos"]).unit;-- LookVector (This Dose Not Account For Bullet Drop!). Args[1] Is The LookVector.
                    end;
                end;
    
                return OldNetwork_send(Idk, Name, UniqueId, BulletData, Time); -- Return The Modified Args.
            end;
    
            return OldNetwork_send(Idk, Name, ...); -- Return The Non Modified Args From The Other Shitty Things.
        end);
    end,function()
        LocalPlayer:Kick('Check If You Have "FFlagDebugRunParallelLuaOnMainThread" "True" Or Was Not Able To Find Modules Or Silent Aim Has A Error.')
    end);

end;

-- // GUI (No Need To Look Down Here It Is Just My Shitty GUI)
local GUIHolder = Instance.new("ScreenGui", game.CoreGui); GUIHolder.ResetOnSpawn = false;
local Frame = Instance.new("Frame", GUIHolder); Frame.Visible = true; Frame.Draggable = true; Frame.Active = true; Frame.BackgroundColor3 = Color3.fromRGB(52, 52, 52); Frame.Size = UDim2.fromOffset(241, 248); Frame.BorderColor3 = Color3.fromRGB(255, 255, 255);
local Frame2 = Instance.new("Frame", Frame); Frame2.BackgroundTransparency = 1; Frame2.Position = UDim2.new(0.288, 0,0.155, 0); Frame2.Size = UDim2.new(0, 100,0, 164);
local UiListLayout = Instance.new("UIListLayout", Frame2); UiListLayout.FillDirection = "Vertical"; UiListLayout.SortOrder = "LayoutOrder"; UiListLayout.Padding = UDim.new(0,5);
local EnableButton = Instance.new("TextButton", Frame2); EnableButton.Text = "Enable"; EnableButton.BackgroundColor3 = Color3.fromRGB(52, 52, 52); EnableButton.BorderColor3 = Color3.fromRGB(255, 255, 255); EnableButton.Font = "Roboto"; EnableButton.TextSize = 17; EnableButton.TextColor3 = Color3.fromRGB(255, 255, 255); EnableButton.TextXAlignment = "Center"; EnableButton.Size = UDim2.new(0, 122,0, 24);
local ShowFovButton = Instance.new("TextButton", Frame2); ShowFovButton.Text = "Show Fov"; ShowFovButton.BackgroundColor3 = Color3.fromRGB(52, 52, 52); ShowFovButton.BorderColor3 = Color3.fromRGB(255, 255, 255); ShowFovButton.Font = "Roboto"; ShowFovButton.TextSize = 17; ShowFovButton.TextColor3 = Color3.fromRGB(255, 255, 255); ShowFovButton.TextXAlignment = "Center"; ShowFovButton.Size = UDim2.new(0, 122,0, 24);
local TextLabel = Instance.new("TextLabel", Frame2); TextLabel.Text = "Fov Size"; TextLabel.BackgroundTransparency = 1; TextLabel.TextXAlignment = "Center"; TextLabel.TextSize = 17; TextLabel.Font = "Roboto"; TextLabel.TextColor3 = Color3.fromRGB(17, 223, 255); TextLabel.Size = UDim2.new(0, 100,0, 17);
local FovSizeText = Instance.new("TextBox", Frame2); FovSizeText.Text = "600"; FovSizeText.BackgroundColor3 = Color3.fromRGB(52, 52, 52); FovSizeText.BorderColor3 = Color3.fromRGB(255, 255, 255); FovSizeText.Font = "Roboto"; FovSizeText.TextSize = 17; FovSizeText.TextColor3 = Color3.fromRGB(255, 255, 255); FovSizeText.TextXAlignment = "Center"; FovSizeText.Size = UDim2.new(0, 122,0, 24); FovSizeText.ClearTextOnFocus = false;
local HitScanButton = Instance.new("TextButton", Frame2); HitScanButton.Text = "HEAD, torso"; HitScanButton.BackgroundColor3 = Color3.fromRGB(52, 52, 52); HitScanButton.BorderColor3 = Color3.fromRGB(255, 255, 255); HitScanButton.Font = "Roboto"; HitScanButton.TextSize = 17; HitScanButton.TextColor3 = Color3.fromRGB(255, 255, 255); HitScanButton.TextXAlignment = "Center"; HitScanButton.Size = UDim2.new(0, 122,0, 24);
local Name = Instance.new("TextLabel", Frame); Name.Text = "DeleteMob | PF Silent Aim"; Name.BackgroundTransparency = 1; Name.TextXAlignment = "Center"; Name.TextSize = 19; Name.Font = "Roboto"; Name.TextColor3 = Color3.fromRGB(17, 223, 255); Name.Size = UDim2.new(0, 200,0, 50); Name.Position = UDim2.new(0.083, 0,-0.056, 0);
local Discord = Instance.new("TextBox", Frame); Discord.Text = "https://discord.gg/FsApQ7YNTq - ClickMe"; Discord.BackgroundTransparency = 1; Discord.BorderColor3 = Color3.fromRGB(255, 255, 255); Discord.Font = "Roboto"; Discord.TextSize = 14; Discord.TextColor3 = Color3.fromRGB(255, 255, 255); Discord.TextXAlignment = "Center"; Discord.Size = UDim2.new(0, 200,0, 23); Discord.Position = UDim2.new(0.083, 0,0.873, 0); Discord.ClearTextOnFocus = false; Discord.TextEditable = false;
EnableButton.MouseButton1Down:Connect(function()
    if SilentAim.Enabled then
        SilentAim.Enabled = false
        EnableButton.BackgroundColor3 = Color3.fromRGB(52, 52, 52);
    else
        SilentAim.Enabled = true
        EnableButton.BackgroundColor3 = Color3.fromRGB(2, 54, 8);
    end;
end);
ShowFovButton.MouseButton1Down:Connect(function()
    if SilentAim.ShowFov then
        SilentAim.ShowFov = false
        ShowFovButton.BackgroundColor3 = Color3.fromRGB(52, 52, 52);
    else
        SilentAim.ShowFov = true
        ShowFovButton.BackgroundColor3 = Color3.fromRGB(2, 54, 8);
    end;
end);
HitScanButton.MouseButton1Down:Connect(function()
    if SilentAim.HitScan == "Head" then
        SilentAim.HitScan = "Torso";
        HitScanButton.Text = "head, TORSO"
    else
        SilentAim.HitScan = "Head";
        HitScanButton.Text = "HEAD, torso"
    end;
end);

-- // FOV
local Fov   = Drawing.new("Circle"); -- Simple Fov;
Fov.Fill    = false;
Fov.Corners = 1000;
Fov.Color   = Color3.fromRGB(255, 255 ,255);
Fov.Thickness = 1;
RunService.Heartbeat:Connect(function() -- Loop To Change The Mouse Position And Size.

    if not (FovSizeText.Text == "") then
        SilentAim.Fov = tonumber(FovSizeText.Text);
    end;

    Fov.Visible = SilentAim.Enabled and SilentAim.ShowFov;

    Fov.Position = Vector2.new(UserInputService:GetMouseLocation().X, UserInputService:GetMouseLocation().Y);
    Fov.Radius   = SilentAim.Fov;
end);
