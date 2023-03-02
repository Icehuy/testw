local window = library:New({name = "shootware"})

local rage = window:Tab({name = "Combat"})
local aa = window:Tab({name = "Anti Aim"})
local visuals = window:Tab({name = "Visuals"})
local misc = window:Tab({name = "Misc"})
local exploits = window:Tab({name = "Exploits"})
local settings = window:Tab({name = "Settings"})


local rage_ragebot = rage:Section({name = "Auto Shoot"})
local rage_silent = rage:Section({name = "Silent Aim"})
local rage_sett= rage:Section({name = "Settings", side = "right"})
local rage_hbex = rage:Section({name = "Hitbox Expander", side = "right"})

local aa_angle = aa:Section({name = "Angle"})
local aa_fl = aa:Section({name = "Fake Lag"})
local aa_desync = aa:Section({name = "Desync", side = "right"})

local visuals_esp = visuals:Section({name = "ESP"})
local visuals_world = visuals:Section({name = "World", side = "right"})
local visuals_self = visuals:Section({name = "Self"})
local visuals_game = visuals:Section({name = "Game", side = "right"})


local exploits_desync = exploits:Section({name = "Character Mover"})
local exploits_desyncmanual = exploits:Section({name = "Manual", side = "right"})

local misc_movement = misc:Section({name = "Movement"})
local misc_tp = misc:Section({name = "Teleport"})

local settings_ui = settings:Section({name = "UI"})
local settings_config = settings:Section({name = "Config"})
local settings_game = settings:Section({name = "Other", side = "right"})
local settings_cretids = settings:Section({name = "Credits", side = "right"})
