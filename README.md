local library = loadstring(game:HttpGet("https://pastebin.com/raw/nBq2D86q"))()
local window = library:new("")

local creds = window:Tab("信息",'16060333448')

local bin = creds:section("玩家信息",true)

    bin:Label("你的用户名:"..game.Players.LocalPlayer.Character.Name)
    bin:Label("你的注入器:"..identifyexecutor())
    
    local bin = creds:section("作者信息",true)
    bin:Label("没有官群想啥呢")
    bin:Label("作者:玖玖归一")
    bin:Label("该脚本完全免费")
    bin:Label("请不要倒卖")
    bin:Label("不更新了")
    
local credits = creds:section("关闭",true)

credits:Toggle("脚本框架变小一点", "", false, function(state)
        if state then
        game:GetService("CoreGui")["frosty"].Main.Style = "DropShadow"
        else
            game:GetService("CoreGui")["frosty"].Main.Style = "Custom"
        end
    end)
    credits:Button("关闭脚本",function()
        game:GetService("CoreGui")["frosty"]:Destroy()
    end)
local creds = window:Tab("通用",'16060333448')

local credits = creds:section("内容",true)
    credits:Button("飞行",function()
    loadstring(game:HttpGet("https://pastebin.com/raw/gqv7PXAa"))()
end)

    credits:Button("人物旋转",function()
    loadstring(game:HttpGet('https://pastebin.com/raw/r97d7dS0', true))()
end)

    credits:Button("甩人",function()
    loadstring(game:HttpGet("https://pastebin.com/raw/zqyDSUWX"))()
end)

    credits:Button("隐身工具",function()
    loadstring(game:HttpGet("https://gist.githubusercontent.com/skid123skidlol/cd0d2dce51b3f20ad1aac941da06a1a1/raw/f58b98cce7d51e53ade94e7bb460e4f24fb7e0ff/%257BFE%257D%2520Invisible%2520Tool%2520(can%2520hold%2520tools)",true))()
end)

    credits:Button("修改攻击体积",function()
    loadstring(game:HttpGet("https://shz.al/CpRJ"))()
end)

    credits:Button("飞车",function()
    loadstring(game:HttpGet("https://pastebin.com/raw/G3GnBCyC", true))()
end）

    credits:Button("光影V4",function()
    loadstring(game:HttpGet("https://shz.al/aMka"))()
end)

local creds = window:Tab("背上只因剑",'16060333448')

local credits = creds:section("内容",true)
    credits:Button("背上只因剑",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/ToraIsMe/ToraIsMe/main/0SwordWarriors"))()
end)

local creds = window:Tab("doors",'16060333448')

local credits = creds:section("doors",true)
    credits:Button("最强",function()
    loadstring(game:HttpGet("\104\116\116\112\115\58\47\47\112\97\115\116\101\98\105\110\46\99\111\109\47\114\97\119\47\54\53\84\119\84\56\106\97"))()
end)

    credits:Button("doors极端",function()
    loadstring(game:HttpGet('https://github.com/HollowedOutMods/MayhemMode/blob/main/loader.lua?raw=true'))()
end)

    credits:Button("doors通用",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/GamingScripter/Darkrai-X/main/Games/Doors"))()
end)

    credits:Button("doors变形",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/ChronoAccelerator/Public-Scripts/main/Morphing/MorphScript.lua"))();
end)

    credits:Button("牛b功能",function()
    loadstring("\112\114\105\110\116\40\34\32\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\34\104\116\116\112\115\58\47\47\114\97\119\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\75\73\78\71\72\85\66\48\49\47\66\108\97\99\107\75\105\110\103\47\109\97\105\110\47\66\108\97\99\107\75\105\110\103\37\50\48\68\111\111\114\115\37\50\48\77\111\98\105\108\101\34\41\41\40\41\32\34\41\10")()
end)

    credits:Button("自动过rooms",function()
    loadstring(game:HttpGet('\x68\x74\x74\x70\x73\x3A\x2F\x2F\x68\x2E\x6C\x6B\x6D\x63\x2E\x61\x73\x69\x61\x2F\x73\x63\x72\x69\x70\x74\x2F\x64\x6F\x6F\x72\x73\x72\x6F\x6F\x6D\x2E\x6C\x75\x61'))()
end)

    credits:Button("doors4",function()
    loadstring(game:HttpGet(("https://raw.githubusercontent.com/mstudio45/poopdoors_edited/main/poopdoors_edited.lua"),true))()
end)

    credits:Button("doors5",function()
    loadstring(game:HttpGet(('https://pastebin.com/raw/R8QMbhzv')))()
end)

    credits:Button("doors6",function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/RTrade/Voidz/main/Games.lua'),true))()
end)

local creds = window:Tab("力量传奇",'16060333448')

local credits = creds:section("内容",true)
    credits:Button("力量传奇",function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/jynzl/main/main/Musclas%20Legenos.lua'))()
end)

local creds = window:Tab("刀刃球",'16060333448')

local credits = creds:section("内容",true)
    credits:Button("刀刃1",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/jiankeQWQ/jiankeV3/main/daorenqiu"))()
end)

    credits:Button("刀刃2",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/1f0yt/community/main/RedCircleBlock"))()
end)

    credits:Button("刀刃自动格挡",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Hosvile/Refinement/main/MC%3ABlade%20Ball%20Parry%20V4.0.0",true))()
end)

local creds = window:Tab("监狱人生",'16060333448')

local credits = creds:section("内容",true)
    credits:Button("监狱吊打一切",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Denverrz/scripts/master/PRISONWARE_v1.3.txt"))();
end)

    credits:Button("监狱人生2",function()
    loadstring(game:HttpGet(("https://raw.githubusercontent.com/i1nfinity/Project-X/master/Prison%20Breaker%20X"), true))()
end)

local creds = window:Tab("彩虹朋友",'16060333448')

local credits = creds:section("内容",true)
    credits:Button("彩虹朋友1",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/JNHHGaming/Rainbow-Friends/main/Rainbow%20Friends"))()
end)

    credits:Button("彩虹朋友2",function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/Ihaveash0rtnamefordiscord/BorkWare/main/Scripts/' .. game.GameId .. ".lua"))(' Watermelon ? ')
end)

local creds = window:Tab("战斗勇士",'16060333448')

local credits = creds:section("内容",true)
    credits:Button("战斗勇士1",function()
    loadstring(game:HttpGet("https://projecthook.xyz/scripts/free.lua"))()
end)

local creds = window:Tab("俄州",'16060333448')

local credits = creds:section("内容",true)
    credits:Button("俄州1",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Bebo-Mods/BeboScripts/main/Ohio.lua", true))()
end)

    credits:Button("俄州2",function()
    loadstring(game:HttpGet("\104\116\116\112\115\58\47\47\115\99\114\105\112\116\115\46\118\105\115\117\114\117\115\46\100\101\118\47\111\104\105\111\47\115\111\117\114\99\101"))()
end)

    credits:Button("俄州3",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/jiankeQWQ/jiankeV3/main/ehaiezhou"))()
end)

    credits:Button("俄州死亡笔记",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/dingding123hhh/tt/main/%E6%AD%BB%E4%BA%A1%E7%AC%94%E8%AE%B0%20(1).txt"))()
end)

local creds = window:Tab("动感星期五",'16060333448')

local credits = creds:section("内容",true)
    credits:Button("动感星期五1",function()
    loadstring(game:HttpGet("https://scriptblox.com/raw/XMAS-Event-or-Funky-Friday-script-delta-and-fluxus-7093"))()
end)

local creds = window:Tab("一路向西",'16060333448')

local credits = creds:section("内容",true)
    credits:Button("一路向西1",function()
    loadstring(game:GetObjects("rbxassetid://10040701935")[1].Source)()
end)

    credits:Button("一路向西2",function()
    loadstring(game:GetObjects("rbxassetid://10040722920")[1].Source)()
end)

    credits:Button("一路向西3",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/linnblin/linnb/main/linnb"))()
end)

local creds = window:Tab("小偷模拟器",'16060333448')

local credits = creds:section("内容",true)
    credits:Button("小偷模拟器",function()
    loadstring(game:HttpGet(("https://raw.githubusercontent.com/adrician/Thief-Simulator---GUI/main/Thief%20sim.lua"),true))()
end)

local creds = window:Tab("bf",'16060333448')

local credits = creds:section("内容",true)
    credits:Button("bf汉化",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/XiaoYunCN/Xiao-Yun-UWU/main/%E6%B5%B7%E8%B4%BC%E7%8E%8Bbf.lua", true))()
end)

    credits:Button("bf2",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Minhtriettt/Free-Script/main/MTriet-Hub.lua"))()
end)

local creds = window:Tab("忍者大亨",'16060333448')

local credits = creds:section("内容",true)
    credits:Button("刷钱",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/AliCode14/scripts/main/ScriptHub.lua"))()
end)

local creds = window:Tab("造船寻宝",'16060333448')

local credits = creds:section("内容",true)
    credits:Button("造船寻宝1",function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/urmomjklol69/GoldFarmBabft/main/GoldFarm.lua'),true))()
end)

local creds = window:Tab("迅速传奇",'16060333448')

local credits = creds:section("内容",true)
    credits:Button("迅速传奇1",function()
    loadstring(game:HttpGet("https://pastebin.com/raw/cwCdNqds"))()
end)

local creds = window:Tab("最强战场",'16060333448')

local credits = creds:section("内容",true)
    credits:Button("最强战场1",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Nicuse/RobloxScripts/main/SaitamaBattlegrounds.lua"))()
end)

local creds = window:Tab("鲨口求生",'16060333448')

local credits = creds:section("内容",true)
    credits:Button("鲨口求生",function()
    loadstring(game:HttpGet("https://pastebin.com/raw/YYVLbzVg", true))()
end)

local creds = window:Tab("战争大亨",'16060333448')

local credits = creds:section("内容",true)
    credits:Button("战争大亨",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Nivex123456/War-Tycoon/main/Script"))()
end)

local creds = window:Tab("伐木大亨",'16060333448')

local credits = creds:section("内容",true)
    credits:Button("伐木大亨1",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/frencaliber/LuaWareLoader.lw/main/luawareloader.wtf",true))()
end)

local creds = window:Tab("兵工厂",'16060333448')

local credits = creds:section("内容",true)
    credits:Button("兵工厂",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/ZinityDrops/OwlHubLin
