# BoothLab for WWE 2K26

BoothLab chooses who sits at the commentary table in each arena, and where. It comes with
BoothSwap, the plugin that does it in the game.

- **Booths:** a commentary team plus the chairs they sit in. Give one booth to every arena,
  or a different one to each arena.
- **Seats from a PropsSet:** a vanilla arena's, one from your Tribute BakeMe, or any PropsSet
  file. BoothLab only reads PropsSets; it never changes them.
- **Up to 4 at the table:** the 4th voice can sit at the table too, also at ringside next to a
  stage table.
- **Staff:** replace the ring announcer, the 4th voice and the timekeeper, and seat them at a
  chair of the PropsSet.
- **Side tables:** a ringside commentary table turned in the PropsSet works like a normal one.
  Wrestlers take the cover off, climb, walk on it, get off and put their opponent on it.
- **Chairs with no commentary table:** with a regular table or one of your own, pick where each
  commentator looks. They still get scared and run when someone comes close.

BoothSwap doesn't change any of the game's code.

## Download

Get **BoothLab.exe** from the [latest release](../../releases/latest). That's all you need:
the plugin travels inside the app.

Rather not run an .exe? The same release has **BoothSwap_manual.zip**: the plugin, an example
settings file with every line explained, and a README to install and uninstall by hand.

## Install

1. You need a plugin loader that loads `plugins\*.dlp` from the game folder (CakeHook does).
2. Run **BoothLab.exe**. You can keep it anywhere. It finds the game through Steam.
3. Click **Install plugin**.
4. Make your booths, give them to arenas and click **Save**. Changes apply from the next match
   you load.

## Updates

When BoothLab starts it checks this page for a newer version. If there is one, click
**Update now**: the app updates itself and, with the game closed, the plugin too.

## Uninstall

In BoothLab: the settings button (top right) > **Uninstall BoothSwap**. Type the code it shows.
The plugin and its logs go to the Recycle Bin; your booths and settings go too only if you tick
that box. BoothLab never touches your plugin loader or other mods.

## Notes

- The ring announcer doesn't get scared: the game has no reaction for them.
- On a turned side table, dragging the opponent there and smashing them still lines up as if
  the table weren't turned.
- When the game gets updated, BoothSwap does nothing until a new version comes out.
- This is a beta. If something goes wrong, share `plugins\boothswap.log`.
