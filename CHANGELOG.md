## Plugin Manager (dd-mm-yyyy)

### 0.3.4 (14-05-2023)

- Optimize new plugin detection mechanism.

### 0.3.3 (13-05-2023)

- Print the number and names of the client supported plugins which are newly added to the plugin manager.

### 0.3.2 (30-04-2023)

- Fix sometimes same sound would repeat twice when pressing a button.
- Low key attempt to experiment with staging branch by changing current tag in `plugin_manager.py`.
- Assume underscores as spaces when searching for plugins in game.

### 0.3.1 (04-03-2023)

- Resize the plugin window to limit the overlapping of plugin description.

### 0.3.0 (12-02-2023)

- Displays a tutorial button in the plugin window, whenever there is a supported url present in the plugin data.

### 0.2.2 (18-01-2023)

- Auto add new line breaks in long plugin descriptions.
- Fixed an issue where pressing back on the main plugin manager window would play the sound twice.

### 0.2.1 (17-12-2022)

- Add Google DNS as a fallback for Jio ISP DNS blocking resolution of raw.githubusercontent.com domain.

### 0.2.0 (05-12-2022)

- Removed `on_plugin_manager_prompt` and replaced it with the in-game's plugin settings ui

### 0.1.10 (05-12-2022)

- Added Discord and Github textures on buttons

### 0.1.9 (03-12-2022)

- Search now filters on author names and plugin description.

### 0.1.8 (30-11-2022)

- Use HTTPS for all network requests (now that the Android bug has been resolved as of v1.7.11).

### 0.1.7 (03-10-2022)

- Added New Option in settings for Notifying new plugins.
- Added a Discord Button to join Bombsquad's Official Discord server.


### 0.1.6 (15-09-2022)

- Distinguish the settings button with a cyan color (previously was green) in plugin manager window.
- Clean up some internal code.


### 0.1.5 (08-09-2022)

- Plugin files that export classes besides plugin or game, now work.
