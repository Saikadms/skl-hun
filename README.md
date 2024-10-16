if game.PlaceId == 4924922222 then

local Rayfield = loadstring(game:HttpGet('https://[Log in to view URL]'))()

local Window = Rayfield:CreateWindow({
   Name = "Brookhaven Script 🏡",
   LoadingTitle = "BYJoxHub",
   LoadingSubtitle = "by JOX_JHK",
   ConfigurationSaving = {
      Enabled = false,
      FolderName = nil, -- Create a custom folder for your hub/game
      FileName = "BYJoxHub"
   },
   Discord = {
      Enabled = false,
      Invite = "noinvitelink", -- The Discord invite code, do not include discord.gg/. E.g. discord.gg/ABCD would be ABCD
      RememberJoins = true -- Set this to false to make them join the discord every time they load it up
   },
   KeySystem = true, -- Set this to true to use our key system
   KeySettings = {
      Title = "BYJoxHub|KeySystem",
      Subtitle = "KeySystem",
      Note = "Je te le donne mon reuf",
      FileName = "Key", -- It is recommended to use something unique as other scripts using Rayfield may overwrite your key file
      SaveKey = false, -- The user's key will be saved, but if you change the key, they will be unable to use your script
      GrabKeyFromSite = false, -- If this is true, set Key below to the RAW site you would like Rayfield to get the key from
      Key = {"BYJOX974_Key"} -- List of keys that will be accepted by the system, can be RAW file links (pastebin, github etc) or simple strings ("hello","key22")
   }
})
