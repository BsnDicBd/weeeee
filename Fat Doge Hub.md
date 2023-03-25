local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Fat Doge Hub --- Be A Noob Exploiter", "Ocean")
    -- MAIN
    local Main = Window:NewTab("Main")
    local MainSection = Main:NewSection("Main")


    MainSection:NewButton("Opl", "Makes you Be A Pro", function()
        loadstring(game:HttpGet(('https://raw.githubusercontent.com/AltsegoD/script/master/OnePieceLegendary.lua')))()
    end)

    MainSection:NewButton("Opl 2", "Makes you do pro things", function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/ExolutionProject/Scripts/main/ExolutionPremiumHub.lua", false))()
    end)
    MainSection:NewButton("Infinite Yield", "FE Admin Commands", function()
        loadstring(game:HttpGet(('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'),true))()
    end)
    MainSection:NewButton("FruitWarriors", "FE", function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/XO-3S-CL-VCK-jf-3HDM/Products/main/Fruit-Warriors.lua"))()
    end)
    MainSection:NewButton("Pet Simulator X (Key Required)", "FE", function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Muhammad6196/Project-WD/main/Mainstring.lua"))()
    end) 
    MainSection:NewButton("Lucky Blocks BATTLEGROUNDS", "idk why i made this", function()
        loadstring(game:HttpGet("https://pastebin.com/raw/bnuxrGix"))()
    end)
   
    --LOCAL PLAYER
    local Player = Window:NewTab("Player")
    local PlayerSection = Player:NewSection("Player")

    PlayerSection:NewSlider("Walkspeed", "SPEED!!", 500, 16, function(s)
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s
    end)

    PlayerSection:NewSlider("Jumppower", "JUMP HIGH!!", 350, 50, function(s)
        game.Players.LocalPlayer.Character.Humanoid.JumpPower = s
    end)

    PlayerSection:NewButton("Reset WS/JP", "Resets to all defaults", function()
        game.Players.LocalPlayer.Character.Humanoid.JumpPower = 50
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 16
    end)


    --Other
    local Other = Window:NewTab("Military")
    local OtherSection = Other:NewSection("Other")

    OtherSection:NewButton("ACS Engine 2.0.1", "L", function()
        loadstring(game:HttpGet(('https://raw.githubusercontent.com/BsnDicBd/acs-engine/main/README.md'),true))()
    end)

    OtherSection:NewButton("Carbon Engine", "mode", function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/BsnDicBd/carbon-engine/main/README.md"))() 
    end)
