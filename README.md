local whitelist = {
    "ablanidelim",
    "ItzSwara31",
    "Arda1420",
    "Tpsciawain", 
    "madridhayatimolmus", --1 hafta
    "252531_werza",
    "qazztr",
    "31cihasanxd",
    "azemessi3a",
    "Arda1420",
    "Zzz_tps2",
    "2525israfil",
    "itsh0r",
    "tpsciawain", --me
    "harunisteaq9", 
    "Alexnimo2022" -- giveaway winner
}

if table.find(whitelist, game.Players.LocalPlayer.Name) then
        local id = game.PlaceId
if id == 335760407 or 13762482705 then
game.StarterGui:SetCore("SendNotification",{
			Title = "Loading...";
			Text = "Loading will take some seconds...";
			Duration = 5;
})
    loadstring(game:HttpGet("https://raw.githubusercontent.com/ArdaAkpinar/gk/main/README.md"))()
else
    game.Players.LocalPlayer:Kick("It's not TPS SS!")
end
else
    loadstring(game:HttpGet("https://raw.githubusercontent.com/ArdaAkpinar/kicked1/main/README.md"))();
end
