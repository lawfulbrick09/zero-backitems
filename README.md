# zero-backitems
Thanks to Renzu(https://github.com/renzuzu/renzu_itemback) for the original script this is just a update for the script where you can set default attachments for weapons so that modular weapons( such as the ones from markomods) can be given default atachments so that they do not apear as only the reciver.
```lua
-- add a table with the models to the config make sure they are also in the components.lua
    ["WEAPON_GLOCK17"] = {
        defaultcomps = {"glock17_barrel1","glock17_mag1","glock17_slide1"},
        model="w_pi_glock17", 
        back_bone = 23553,
        x = 0.03,
        y = 0.04,
        z = -0.19,
        x_rotation = 68.38,
        y_rotation = 19.700000000001,
        z_rotation = 173.89,
    },
```
