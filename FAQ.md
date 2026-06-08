# BethINI Pie — FAQ

**Q: Do I need to run this as Administrator?**  
A: Only if your game is installed in a protected directory (like Program Files). For most users with Steam in a custom path, Administrator is not required.

**Q: Will this conflict with my mods?**  
A: BethINI Pie only edits INI files. It does not touch mod files, plugins, or BSAs. It's compatible with every mod manager (MO2, Vortex, NMM).

**Q: What's the difference between "Recommended" and "High" preset?**  
A: The vanilla "High" preset uses outdated values tuned for 2011 hardware. "Recommended" uses community-researched values that improve both performance and visual quality on modern systems.

**Q: I applied settings but the game looks the same.**  
A: Make sure the game is fully closed before applying. Also verify that your mod manager isn't overwriting the INI files — some MO2 configurations redirect INIs to a different path.

**Q: Can I undo my changes?**  
A: Yes. BethINI Pie creates dated backups in the BethINI_Backups folder inside your game's Documents directory. Use File → Restore Backup.

**Q: Is this safe for modded Skyrim with 500+ mods?**  
A: Yes. The INI settings BethINI Pie manages are separate from mod plugin order and mesh/texture replacers. Many large mod lists (Wabbajack, etc.) recommend running BethINI Pie as part of setup.

**Q: It's not finding my game installation.**  
A: Use File → Setup → manually point BethINI Pie to your game's Documents folder (e.g. Documents/My Games/Skyrim Special Edition).
