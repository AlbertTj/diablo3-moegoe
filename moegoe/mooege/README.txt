
 Latest compatible version: 8815 (patch 14)
 You can now login with user: test@, password: (anything).
 We no longer support MooExt. 
 World Improvements
 Quest - Captain Rumford (Outside Town Gate)
 NPC Gossip
 Scoundrel and Templar can be hired
 Some Waypoints Working
 Some Map Portals Working
 Npcs and Monsters in Game
 Auction House Enabled 
 Character Level and Time played saves in database
 Killing Spree Combo Bonus EXP (kill at least 6 mobs )
 New Icon for Mooege.exe 
 Multiplayer Working


 Alternate Method to load the MPQs
 1. Copy the D3 Beta MPQs folder to your Hard drive directory such as c:/MPQs.
 2. Rename the copied folder as MPQ.
 3. Open config.ini with notepad thats in the Mooege folder
 4. Edit line: 
 Old - Persistent storage settings [Storage]Root = AssetsMPQRoot=${Root}/MPQ
 New - Persistent storage settings [Storage]Root = AssetsMPQRoot=C:MPQ

 This way you dont have to keep copying the D3 Beta MPQ folder to every new Mooege update. 

 All you have to do is edit the config.ini with each new update with the above example. 

 But you have to make sure you have the copied MPQ folder sitting in the C: directory of your computer so its path is C:MPQ


 How to Setup Multiplayer
--------------------------
 Game Host Instruction for Public Game:
 Open Ports 1999 and 1345
 Edit config.ini (Host Only)
 [NAT] Enabled = true
 PublicIP = 109.90.139.208 ; You need to change this to your router's public interface IP

 Game Joiner Instruction for Public Game:
 Diablo III.exe" -launch -auroraaddress 109.90.139.208:1345 (Host Public IP)


 Game Host Instruction for Local Game:
 Edit config.ini (Host Only)
 [NAT] Enabled = false
 PublicIP = 127.0.0.1 ; <---- You need to change to this

 Game Joiner Instruction for Local Game:
 "Diablo III.exe" -launch -auroraaddress (This needs to be Hosts Lan IP)