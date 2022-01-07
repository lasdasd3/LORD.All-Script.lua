local PlaceId = game.PlaceId

if PlaceId == 3956818381 then
	loadstring(game:HttpGet("https://raw.githubusercontent.com/lasdasd3/L-O-R-D-X-HUB-N-I-N-J-A/main/README.md"))()
elseif PlaceId == 2753915549 or PlaceId == 4442272183 or PlaceId == 7449423635 then
_G.Team = "Pirate" --Marine Or Pirate
loadstring(game:HttpGet("https://raw.githubusercontent.com/lasdasd3/LORD-X-Trash/main/README.md"))()
elseif PlaceId == 4996049426 then
    loadstring(game:HttpGet("https://raw.githubusercontent.com/lasdasd3/AllStar.lua/main/README.md"))()
else
	game.Players.LocalPlayer:kick("Dont Have This Game")
	wait(1)
	game:Shutdown()
end
