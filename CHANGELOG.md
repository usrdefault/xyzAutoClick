# v3.9.6 - 22.08.2026 (d.m.y)
## New
- Click points: several positions on screen clicked one after another, each with a randomisation radius and an optional stop once the list has been played through.
- Custom stop zones: several can be drawn, and each one can stop, pause or start the clicker.
- Process whitelist / blacklist: clicking stops depending on the application in the foreground.
- Automatic stop on Alt+Tab and Win+Tab.
- Master switch: a key that globally allows or blocks the clicker, with "MASTER OFF" shown in red in the title.
- Keybinds to switch pages and to flip every major setting.
- Status bar at the bottom of the window: active preset, version, reason for the last stop.
- Keyboard clicking in addition to mouse clicking, with letter case control.
- Hold mode for the duty cycle, which keeps the button pressed continuously.
- Appearance: background image, window and panel opacity, adjustable blur, and per-page customisation.
- Customisable taskbar icon, following the theme and the accent colour.
- New accent colour picker: a built-in palette plus a hex field, replacing the Windows colour dialog.
- New app icon, in a light and a dark variant.
- The window position is remembered between launches.
- Logs and crash reports, viewable and exportable from Maintenance.
- "Check for update" button and a preview of what's new before installing.
- Portable build, which keeps all of its data inside its own folder.
## Changed
- The app is now named xyzAutoClick, with its own installer, its own data folders and its own update channel.
- The Advanced panel was rebuilt, and the Settings panel reorganised with a side menu.
- New font, so numbers no longer shift as values change.
- Lower memory use once no setting has been touched for a while.
- The installer now bundles the Windows runtime libraries, avoiding startup failures on some machines.
- Scrolling on number fields accepts Shift, Ctrl and Shift+Ctrl for larger steps.
## Fixed
- The requested click speed is actually reached, including at high speeds.
- The mouse cursor no longer behaves erratically while the clicker runs.
- Several crashes on startup and when opening the Zones panel.
- The hotkey no longer triggers itself from the clicks the app generates.
- The window no longer flashes at the wrong size or position on launch.
- Double click uses the Windows double-click timing and works correctly with the click duration.
