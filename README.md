# ModUtils
Core library for mods by Acitulen.  
  
**⚠️WARNING⚠️ This version of ModUtils is designed to function with VotV 0.9.0n. Using older or newer versions of the game may cause errors!**  

If you have any suggestions or encounter a bug, you can submit it as an issue on my [GitHub repository](https://github.com/Acitulen/ModUtils).

---

# Features: 

- **Config system:** adds the **Mod configs** category to the game settings (also opened with **Ctrl+Shift+C** in game).
- **Save system:** saves mod variables without creating extra save files.
- **DataTable merging:** merges mod DataTables into the game. Compatible with **Fusion**.

---

## Manual installation guide.

<details>
<summary>Install unreal shimloader</summary>

1. Copy `dwmapi.dll` into the `GAME/Binaries/Win64` directory. Its new path should be `GAME/Binaries/Win64/dwmapi.dll`.
2. Copy the contents of the `UE4SS` folder in the package into `GAME/Binaries/Win64`.

`GAME/Binaries/Win64` should now contain the following *new* files and folders:
- `GAME-Win64-Shipping.exe`
- `ue4ss.dll`
- `UE4SS-settings.ini`
- `dwmapi.dll` ← *This is the unreal-shimloader binary. It will load UE4SS for you.*
- `Mods/`
</details>

<details>
<summary>Install ModUtils</summary>

1. Copy `ModUtils.pak` from the `pak` folder to `GAME/Content/Paks/LogicMods` directory. 
2. Copy the contents of the `mod` folder into the `GAME/Binaries/Win64/Mods/Acitulen-ModUtils` directory.  
*You need to create the `Acitulen-ModUtils` folder manually.
</details>
