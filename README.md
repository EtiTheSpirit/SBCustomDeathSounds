# SBCustomDeathSounds
Enables modders to specify custom death sounds for their species

# Are you a modder who wants to use this? Have a read
Implementing this into your species is easy!

In your species file, specify a `deathNoises` key in the json. This list is similar to `ouchNoises` in that it's a list of sounds. Here's an example implementation featured in my Spirit Guardian mod.
```
"ouchNoises" : [ "/sfx/humanoid/seinBadlyHurtRegularA.ogg", "/sfx/humanoid/seinBadlyHurtRegularB.ogg", "/sfx/humanoid/seinBadlyHurtRegularC.ogg", "/sfx/humanoid/seinBadlyHurtRegularD.ogg", "/sfx/humanoid/seinBadlyHurtRegularE.ogg" ],
"deathNoises" : [ "/sfx/humanoid/seinDeathRegularA.ogg", "/sfx/humanoid/seinDeathRegularB.ogg", "/sfx/humanoid/seinDeathRegularC.ogg", "/sfx/humanoid/seinDeathRegularD.ogg", "/sfx/humanoid/seinDeathRegularE.ogg" ],
```

**From there, you are open to two options**
1) Have your users subscribe to steam://url/CommunityFilePage/1695298616 / https://steamcommunity.com/sharedfiles/filedetails/?id=1695298616
2) Pack `player.config.patch` and the `scripts` folder into your mod (If your mod already patches `player.config`, just add the one line from my patch into your file). **If you use this method, please mention this github page.**

# This is limited in its capabilities!
This does **NOT** work on NPCs yet! I may add this in the future depending on how high demand is.
