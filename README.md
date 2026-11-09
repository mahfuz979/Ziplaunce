# Multiverse Launcher

A native Android launcher starter with 2D, 3D-depth styling, and Minecraft-inspired block styling.

## Build an APK using a phone (GitHub Actions)
1. Create a new GitHub repository.
2. Upload the contents of this folder to the repository root.
3. Open the repository's **Actions** tab.
4. Select **Build Android APK** and tap **Run workflow** (or push to `main`).
5. Open the completed workflow run, find **Artifacts**, and download `MultiverseLauncher-debug`.
6. Extract the ZIP and install `app-debug.apk`. Android may ask you to allow installation from that source.
7. Open the app, then choose it as the Home app when Android prompts. You can also change the default Home app in Android Settings.

## Notes
- This is an initial functional launcher foundation: it lists launchable apps and opens them.
- The 3D mode currently uses Android view depth, elevation, and perspective styling; it is not a full 3D game engine.
- Minecraft mode is a Minecraft-inspired visual theme and does not include Minecraft game assets.
- Some system apps may not appear because Android controls app visibility.
- A debug APK is suitable for testing. A signed release APK is needed for public distribution.
