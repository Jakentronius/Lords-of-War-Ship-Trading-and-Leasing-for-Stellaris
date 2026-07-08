# Ship Market

A Stellaris mod (v0.9.39, for Stellaris 4.4.x) that adds a galactic ship trading economy: buy, sell, and lease fleets with AI empires through a custom HUD-integrated market interface, with live-market pricing, diplomatic deal offers, and Lord of War civics and edicts.

## Manual installation

1. Click the green **Code** button above → **Download ZIP**, and extract it.
2. Copy the extracted folder into your Stellaris mod directory, renaming it to `ship_market`:
   - **Windows:** `Documents\Paradox Interactive\Stellaris\mod\ship_market`
   - **macOS:** `~/Documents/Paradox Interactive/Stellaris/mod/ship_market`
   - **Linux:** `~/.local/share/Paradox Interactive/Stellaris/mod/ship_market`
3. In the same `mod` directory, create a text file named `ship_market.mod` containing:

   ```
   name="Ship Market"
   version="0.9.39"
   picture="thumbnail.png"
   tags={
   	"Gameplay"
   	"Economy"
   	"Diplomacy"
   }
   supported_version="4.4.*"
   path="mod/ship_market"
   ```

4. Launch Stellaris, open the launcher's **Playsets** screen, and enable **Ship Market**.

Save-game safe to add; achievement-incompatible (like all mods that change game files).
