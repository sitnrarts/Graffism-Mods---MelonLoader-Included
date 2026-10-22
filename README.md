# Install the Graffism mods

You need Graffism on Steam. This download includes `MelonLoader.Installer.exe`. That is the right installer (MelonLoader 0.7.3). Use that file.

Close Graffism before you start.

## 1. Install the loader

1. Double-click `MelonLoader.Installer.exe` in this folder.
2. If Windows blocks it, click **More info**, then **Run anyway**.
3. Click **Select** and choose `Graffism.exe`.
   In Steam: right-click **Graffism** → **Manage** → **Browse local files**.
4. Leave the version on **0.7.3**.
5. Click **Install**.

Open Graffism from Steam once. The first launch is slow, and a console window opens. That means the loader is working. Close the game.

## 2. Add the mods

The mods are in the folder. Copy files into the same Graffism folder that has `Graffism.exe`.

Every mod has a `.dll` inside its `Mods` folder. Copy each `.dll` into the game’s `Mods` folder.

Two mods also have a `UserData` folder. Copy those folders into the game’s `UserData` folder:

- `dist\GraffismCanPack\UserData\GraffismCanPack`
- `dist\GraffismAmbience\UserData\GraffismAmbience`

If Windows asks about `Mods` or `UserData`, merge them. Add the new files into the folders that are already there.

Start Graffism. The console lists the mods it loaded.

## What you get

**Can Pack** adds more spray cans. In the item menu, open **CANS** and go past Kobra. Use a real PNG or JPG for a can skin. Flame colors are in `UserData\GraffismCanPack\colors.txt`. In multiplayer, players with this pack see each other’s custom cans.

**Can Color** keeps a color on the can you set it on. Grab another can to use a different color. Works with the normal cans and with Can Pack.

**Overlap** lets two people spray the same spot. Everyone in the lobby needs this mod.

**Hand Grab** moves you when you hold the left trigger and move that hand. Speed is the **Hand grab speed** slider in Options.

**Ambience** turns the outdoor sky slowly and plays outdoor sound on rooftop, skatepark, trainyard, elevated station, urban canal, and desert.

**Sketch** is a photo you can hold while you paint. Put PNG or JPG files in `Documents\Graffism\Projector`. In the item menu, open **Tools** and grab Sketch.

**Open Lobby** lets you paint as soon as the map loads. You can skip Ready. Password lobbies still ask for the password.

## If a mod is missing

Look in `Graffism\MelonLoader\Latest.log`.

- The loader version is 0.7.3.
- The mod’s name is in the log.
- Its `.dll` is inside `Graffism\Mods`.

To try the loader again, close the game and run `MelonLoader.Installer.exe` on `Graffism.exe` once more.

To remove a mod, close the game and delete its `.dll` from `Mods`.
