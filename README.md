git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:BigBoski/leagueoflegends.git
git push -u origin master


git add .
git commit -m "commit message"
git push heroku master

db.Champions.save({
    name: "Illaoi",
    description: "All who encounter Illaoi are struck by her presence. An intense woman, the priestess is fully committed to the experience of living. She takes what she wants, destroys what she hates, and revels in everything she loves.",
    passivename: "Prophet of an Elder God",
    passivedesc: "Illaoi and the Vessels she creates spawn Tentacles on nearby impassible terrain. Tentacles swing at spirits, Vessels, and victims of Illaoi's Harsh lesson. Tentacles deal physical damage to enemies hit, and will heal Illaoi if they damage a champion.",
    abilityonename: "Tentacle Smash",
    abilityonedesc: "Increases the damage dealt by Tentacles. When activated, Illaoi smashes down a Tentacle that deals physical damage",
    abilitytwoname: "Harsh Lesson",
    abilitytwodesc: "Illaoi leaps to her target, dealing physical damage and causing nearby Tentacles to also swing at the target.",
    abilitythreename: "Test of Spirit",
    abilitythreedesc: "Illaoi rips the spirit from a foe's body, forcing it to stand before her. Spirits echo a percentage of the damage they take to the original target. If killed, or if the target gets too far from the spirit, the target will become a Vessel and begin spawning Tentacles.",
    abilityfourname: "Leap of Faith",
    abilityfourdesc: "Illaoi smashes her idol into the ground, dealing physical damage to nearby enemies. A Tentacle spawns for each enemy champion hit."
})