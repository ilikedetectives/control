To unlock the Astral Dive Suit open your DX11/DX12 executable with an hexadecimal editor (like "HxD")

THESE EDITS ARE THE SAME FOR BOTH DX11/DX12 Executables.

for EGS users, try to use the second edit below (Adress 147ACA 75 --> EB) before the first one that unlock all outfits. It's possible that it will unlock only the Astral Dive suit/Urban reponse and you will be able to keep them between floors without additional edit. If it's not working with the second one only, edit also the first one in addition.
GOG users follow Steam instructions

With Hxd:

1) Backup your executable just in case.

2) Open your *.exe in HxD . Go to the "Search Menu" then "Go To".

3) For STEAM ULTIMATE EDITION 1.13 Past the adress:  1B905B
    (For STEAM ULTIMATE EDITION 1.12 Past the adress:  1B8FDB)
    For EGS VERSION 1.12 / 1.13  Past the adress: 1BAFBB

4) You should arrive to this Hex value: 8B

5) Replace the entire following string: 8B 4B 04 8D 41 01 83 F8 03 77 12
     with this new string: B8 01 00 00 00 89 43 04 EB 06 90

6) Save the file then launch the game.

WARNING: This will unlock ALL outfits of the game (including the Astral Dive Suit"/"Urban Response Gear and the new AWE extension suit). So don't use it if you don't want to unlock all outfits before obtain them normally during the game walktrough.

IMPORTANT NOTE: If the Astral suit disappears when you change floors/zones edit this in addition to the previous one edit:

For STEAM ULTIMATE EDITION 1.13 : Go to the adress 145B09 and change the 75 value to EB
(For STEAM ULTIMATE EDITION 1.12 : Go to the adress 145AEA and change the 75 value to EB)
For EGS VERSION 1.12 / 1.13  : Go to the adress 147ACA and change the 75 value to EB
(For EGS VERSION 1.10  : Go to the adress 1383EA and change the 75 value to EB)
