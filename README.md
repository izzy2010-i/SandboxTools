# Sandbox Tools

A cheat menu mod for **Minecraft Java 1.21.4** (Fabric). It only works in your own single-player worlds and LAN worlds you open. On other people's servers the menu is greyed out.

## What it does

| Key | What happens |
|---|---|
| Right Shift | Opens the cheat menu |
| G | Fly on/off (works in survival) |
| C (hold) | Zoom |
| B | Lists nearby diamonds, ancient debris, emeralds, gold and iron with coordinates |
| H | Full health and hunger, puts out fire |

The menu also has: **God mode** (no damage), **No fall damage**, **Fullbright** (see in the dark), **Speed boost** and **High jump**.

You can change any key in **Options → Controls → Key Binds → Sandbox Tools**.

## Build the mod file (one time)

You need a computer that lets you install programs.

1. Install **Java 21** (JDK): https://adoptium.net (pick "Temurin 21").
2. Install **IntelliJ IDEA Community Edition** (free): https://www.jetbrains.com/idea/download
3. In IntelliJ: **File → Open** and pick this `SandboxTools` folder. Wait for it to finish loading (the bar at the bottom). The first time it downloads Minecraft, so it can take several minutes.
4. Open the **Gradle** panel on the right side → `sandboxtools` → `Tasks` → `build` → double-click **build**.
5. The mod file appears at `build/libs/sandboxtools-1.0.0.jar`.

If the build says it can't find a version, go to https://fabricmc.net/develop, pick 1.21.4, and copy the version numbers it shows into `gradle.properties`.

## Install it

1. Install the **Fabric Loader** for 1.21.4: https://fabricmc.net/use/installer
2. Download **Fabric API** for 1.21.4: https://modrinth.com/mod/fabric-api
3. Press **Win + R**, type `%appdata%\.minecraft`, press Enter. Open (or create) the `mods` folder.
4. Put both files in `mods`: `sandboxtools-1.0.0.jar` and the Fabric API `.jar`.
5. In the Minecraft Launcher, pick the **fabric-loader-1.21.4** profile and press Play.
