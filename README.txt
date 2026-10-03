Admin Crucifix - Forge 1.16.5 (Forge 36.2.39, JDK 8)

EASIEST: BUILD THE JAR ONLINE (no installs)
1. Create a free GitHub repo and upload everything in this folder
   (keep the .github folder).
2. Open the Actions tab -> "Build jar" -> wait ~3 minutes.
3. Download the "admin-crucifix-jar" artifact; the file inside
   (doorscrucifix-1.0.0.jar, not the -sources one) goes in .minecraft/mods.

LOCAL BUILD: install JDK 8 + Gradle 7.4.2, run "gradle build" here, jar is in build/libs/.

USE (operators, permission level 2+)
- /give @s doorscrucifix:admin_crucifix
- Hold right-click ~1.5s: charge animation, then burst kills every non-player mob within 16 blocks.
- Sneak + right-click a player: bans them. Undo with /pardon <name>.

ITEMS (all operator-only)
- /give @s doorscrucifix:admin_crucifix   hold right-click: kill burst; sneak+right-click player: BAN
- /give @s doorscrucifix:knockback_stick  hit anything: launched far (game caps speed ~3.9 blocks/tick)
- /give @s doorscrucifix:admin_gun        right-click: instant beam, 1000 damage, 100 block range
- /give @s doorscrucifix:admin_bible      right-click: menu of online players; click a name to teleport to them
                                          (top button switches to "Bring player to me")
