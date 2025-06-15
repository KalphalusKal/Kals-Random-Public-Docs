<!-- Yes this .md formatting sucks -->
# Downgrading Steam Games
This isnt guarenteed to work for every game, just made this public so theres a decent guide
Theres images set to a small size so that you can click them to see what your looking for without them being in the way

## Finding the IDs
Go to [steamdb.info](https://steamdb.info/), search for your game, and click your game
Now select the App ID and note it down somewhere

<img src="https://github.com/user-attachments/assets/8a779575-0d00-4208-8e55-d5e966db505f" alt="SteamDB Among Us Game ID Highlighted" height="100">

Then go to the "Depots" tab and note the Depot ID you want
Now click the Depot ID
  If theres multiple and only one has a stated file size, thats the one you want
  Make sure you dont click the one under "Branches"
  
<img src="https://github.com/user-attachments/assets/a3130137-6400-4a11-a0f2-851804851e30" alt="SteamDB Among Us Depot ID/Tab Highlighted/Selected" height="100">

Now go to the "Manifests" tab and find the ID that was released the same day as the version you want. Note this ID down

<img src="https://github.com/user-attachments/assets/19756a96-6108-457d-bdd9-b602764fdb6e" alt="SteamDB Among Us Manifest ID Selected" height="100">

## Downloading/Installing the older version
Fully close Steam and relaunch it by pressing Win+R and running ```C:\Program Files (x86)\Steam\steam.exe -console```
Now that Steam is loaded you should see a "Console" tab, open it.

<img src="https://github.com/user-attachments/assets/09335745-fd3a-4019-947f-8f500da5b66b" alt="Steam Console tab" height="100">

In the textbox, run ```download_depot gameid depotid manifestid```
  This will take a while, just wait for it to say it succeeded.

<img src="https://github.com/user-attachments/assets/4315ef2c-1b98-487f-86e9-5e6237608233" alt="Steam Console tab running download_depot 945360 945361 1110308242604365209" height="100">

When it says "Depot download complete :", press Win+R and type ```C:\Program Files (x86)\Steam\steamapps\content```
Then open the folder called "app_gameid"
Now copy the "depot_depotid" folder to wherever you want and rename the folder to something along the lines of "Among Us v16.0.5s"
Then create a txt in the game install folder called "steam_appid" and set the contents to the Game ID

<img src="https://github.com/user-attachments/assets/02788f22-a849-469d-9bc4-523fbd9291f1" alt="steam_appid.txt in Notepad set to Among Us" height="100">

Now right click the EXE and hit "Create Shortcut"
Rename the shortcut to what you want it to show as in the Start Menu
Press Win+R and type ```%appdata%\Microsoft\Windows\Start Menu\Programs```
Now drag the shortcut into the Start Menu\Programs folder

## Now your done!
When loading, make sure steam is open beforehand otherwise you wont be able to play online.
<!-- Yes I still play among us, its still fun and mods make it better (Like ToUr)-->
