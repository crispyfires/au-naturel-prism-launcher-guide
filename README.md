__DISCLAIMER__: This guide is not affiliated with the developers of the Au Naturel modpack in any way. If there is anything wrong with this guide, please open an issue here instead of asking them for support.

__NOTE__: This guide has been tested and confirmed working using Prism Launcher 10.0.5 and Eclipse Temurin JRE 25.0.2. I will __not__ be supporting older JRE versions.

## Downloading the modpack
1. Open Prism Launcher
2. Select "Add Instance" in the top-left corner
3. On the left-hand pane, select "CurseForge"
4. In the search bar, search for "Au Naturel"
5. Select Au Naturel in the left pane of the modpack browsing area
6. Select "OK" in the bottom right corner
7. A pop-up saying "Blocked mods found" should show up – these mods you must download manually. Select "open missing" in the bottom-left of the pop-up to open these in a web browser.
8. In the web browser, open each tab and the download for each missing mod will automatically start.
9. Wait for the rest of the modpack download to finish

## Setting up the modpack
1. Once the download is completed, right click on the Au Naturel icon on the Prism Laucher main menu
2. Select "Edit"
3. Select "Settings" in the left-hand pane
4. Select to the Java tab
5. Tick "Skip Java compatibility checks"
6. Select "Detect" and choose the 25.02 JRE
7. Tick "Memory"
8. Set "Maximum Memory Usage" to "16000"
9. Set PermGen Size to "512"
10. Tick "Java Arguments"
11. Copy and paste this string into the box:

```
-XX:+UseCompressedOops -XX:+UseStringDeduplication -XX:+UseCompactObjectHeaders -XX:+UseZGC
```

12. Navigate to "Mods" on the left-hand pane
13. Search for "Tan's Huge Trees" (__NOT__ Tan's Huge Fast Trees, that's a different mod)
14. Disable it by clicking the ticked box in the mod entry

You're done, now run the game and enjoy :) If you have any suggestions, feel free to open an issue or pull request.