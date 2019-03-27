# SBCustomDeathSounds
Enables modders to specify custom death sounds for their species

# Are you a modder who wants to use this? Have a read
Implementing this into your species is easy!

In your species file, specify a `deathNoises` key in the json. This list is similar to `ouchNoises` in that it's a list of sounds. Here's an example implementation featured in my Spirit Guardian mod.
```
"ouchNoises" : [ "/sfx/humanoid/seinBadlyHurtRegularA.ogg", "/sfx/humanoid/seinBadlyHurtRegularB.ogg", "/sfx/humanoid/seinBadlyHurtRegularC.ogg", "/sfx/humanoid/seinBadlyHurtRegularD.ogg", "/sfx/humanoid/seinBadlyHurtRegularE.ogg" ],
"deathNoises" : [ "/sfx/humanoid/seinDeathRegularA.ogg", "/sfx/humanoid/seinDeathRegularB.ogg", "/sfx/humanoid/seinDeathRegularC.ogg", "/sfx/humanoid/seinDeathRegularD.ogg", "/sfx/humanoid/seinDeathRegularE.ogg" ],
```

**YOU *ARE* WELCOME TO UNPACK THIS AND PUT THE FILES INTO YOUR MOD SO THAT YOUR USERS DO NOT HAVE TO INSTALL THIS.** Just be sure to mention me and link this github repository.

# This is limited in its capabilities!
This does **NOT** work on NPCs yet! I may add this in the future depending on how high demand is.
