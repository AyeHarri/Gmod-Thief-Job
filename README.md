TEAM_THIEF = DarkRP.createJob("Thief", {
    color = Color(255, 107, 0, 255),
    model = {"models/captainbigbutt/vocaloid/miku_append.mdl"},
    description = [[You are a thief, Break into peoples bases and steal their stuff! Rob Banks! And hide from the police!]],
    weapons = {"weapon_shotgun"},
    command = "Thief",
    max = 25,
    salary = 65,
    admin = 0,
    vote = false,
    hasLicense = false,
    candemote = false,
    category = "Citizens",
    PlayerSpawn = function(ply)
        ply:SetMaxHealth(100)
        ply:SetHealth(100)
        ply:SetArmor(99)
    end
})
