<div align="center">
  <h1><img src="https://capsule-render.vercel.app/api?type=waving&amp;color=0:BBF7D0,55:86EFAC,100:5BD68C&amp;height=205&amp;section=header&amp;text=ALauncher&amp;fontColor=0B351A&amp;fontSize=88&amp;fontAlignY=40" alt="ALauncher" width="100%"></h1>
  <p><strong>Minecraft: Java Edition, your way.</strong></p>
  <p>A Windows launcher for creating game setups, managing content, and backing up your changes.</p>
  <p><a href="https://github.com/illililiiililii/Alauncher/releases"><img src="https://img.shields.io/badge/Download%20for%20Windows%20x64-005F10?style=for-the-badge" alt="Download for Windows x64" height="32"></a></p>
  <p><a href="README.md">한국어</a> · English</p>
  <p><a href="https://github.com/illililiiililii/Alauncher/releases/latest">Latest stable release</a> · <a href="#current-features">Current features</a> · <a href="LICENSE.md">License</a></p>
</div>

## Download

Choose a version on the [Releases page](https://github.com/illililiiililii/Alauncher/releases) and expand **Assets**.

- The **installer** ends in `-setup.exe`. The **standalone build** is a separate `.exe` you can run without installing.
- The features below cover the [0.2.13 development preview](https://github.com/illililiiililii/Alauncher/releases/tag/v0.2.13). Each release lists its changes and what has been verified.
- To find previews in the launcher, open **Settings → About → Check for updates** and include development previews. In the Korean interface, the option is **개발 미리보기도 확인**.

## Current features

### Instances and launching

- Create, duplicate, delete, and favorite instances for different Minecraft versions and mod loaders. Search your instances or show only favorites.
- Choose Vanilla, Fabric, Forge, NeoForge, or OptiFine. Availability depends on the version and loader combination. You can also import supported custom version JSON files and find or install a compatible Java runtime.
- Use a separate game folder, explicitly opt into the official Minecraft folder, or share selected folders with another instance. You can also copy an existing official launcher installation and the worlds, settings, and content you choose into a separate instance.
- Set Java, RAM, JVM arguments, resolution, and fullscreen per instance. Create, edit, duplicate, delete, or export launch presets as shareable JSON. Use a preset once or make it the default. Choose what the launcher window does when the game starts.
- Play or jump to content management or settings after creating an instance. Track progress, cancel preparation, and review job history.

### Accounts and skins

- Sign in with Microsoft and switch the default account used by the launcher. The app checks Minecraft ownership and the Java profile and protects sign-in credentials with Windows Credential Manager. Offline profiles are available for local testing.
- Preview PNG skins on classic (Steve) and slim (Alex) 3D models. Rotate or zoom in, switch between full-body and face views, try animations, adjust capes and backgrounds, and save the preview as a PNG. Review the target account and changes before applying a skin.

### Content discovery and installation

- Browse or search Modrinth for mods, modpacks, resource packs, and shaders. Use automatic or manual search, categories, pagination, and sorting by downloads, relevance, newest uploads, recently updated, or followers.
- Read project descriptions, licenses, screenshots, changelogs, and published compatibility details. Paste a Modrinth project or version link, or pick the release and target instance from the catalog.
- Save favorites and recent views by content type on this PC. Choose shortcuts for popular or recently uploaded resource packs and shaders, or for shaders in lower-load categories. You can also turn off or clear history by content type.

### Mods and packs

- Add multiple local JARs, organize installed mods in virtual folders, and enable or disable them in batches. Review known dependencies, conflicts, and file changes before installing, removing, or updating mods.
- Pin individual mod versions. Set launcher-wide, per-instance, or per-mod update policies for stable releases, beta, alpha, holding the current version, or notifications only.
- Import or export supported `.mrpack` files, compare a pack with the current instance, and sync after a backup. Check tracked packs for updates or repair only the selected missing or damaged JARs.
- Add resource-pack and shader ZIP files from Modrinth or your PC, enable or disable them, and archive or restore them. Using shaders in Minecraft requires a compatible Iris or OptiFine setup.
- Reuse verified Modrinth JARs from the shared cache to avoid downloading the same file again.

### Worlds, screenshots, and playtime

- View world names, icons, versions, game modes, last played dates, and sizes by instance, and open their folders. The World Center is read-only.
- Search screenshots by instance, sort them by date, preview PNGs, or export a copy.
- Review total and per-instance playtime and recent launches on this PC. Playtime measures how long the game process was running.

### Backups, storage, and downloads

- Make manual snapshots or opt into automatic backups while the launcher is idle. Review and restore earlier snapshots, and set how many to keep. Supported mod, pack, and graphics changes use a protective backup before applying.
- View drive and launcher storage separately. Inspect individual files, select eligible caches or archived items for cleanup, and estimate the space you can reclaim. You can also move launcher data using a verified copy.
- Check download progress and job history. Pause, resume, or cancel supported jobs. The launcher verifies downloaded files against the hashes required for each job.

### Personalization and accessibility

- Move, resize, hide, or pin home widgets. Save layout presets or reset the layout. Put play controls, recent or favorite instances, screenshots, downloads, and worlds where you want them.
- Choose light, dark, or system appearance, design themes including Classic, and animation settings. Use collapsible navigation, keyboard navigation, `Ctrl+K` quick actions, and settings search.

### Optimization and troubleshooting

- Inspect CPU, GPU, memory, storage, Java, and game settings. Get RAM, JVM, graphics, and compatible performance-mod recommendations. Review supported RAM or graphics changes before applying them and restore earlier settings when needed.
- Opt into CPU and memory monitoring for the game process. Review relevant logs and crash reports, possible causes, suggested fixes, and supported file checks or repairs.
- The optional local AI assistant can help with mod searches, error explanations, and draft settings after you install a model on compatible hardware. Applying changes requires your review.

### Direct friends and servers

- Send, accept, or decline friend requests using friend codes. You can also remove or block friends. Choose per friend whether to share online status, game activity, and the game version.
- In the experimental LAN invitation feature, invite a friend to a single-player world you have opened to LAN. Both players need a directly reachable network connection and matching Minecraft and loader versions. Join through **Direct Connection** in Minecraft.
- Set up dedicated servers on your PC using Vanilla, Paper, Purpur, Fabric, Forge, NeoForge, or a supported custom JAR. Manage the console, save and stop or restart, view and manage players and operator, allow, and ban lists, diagnose local connectivity, and back up server data. Minecraft EULA acceptance is required to start a server.

### Launcher updates

- Check for stable versions manually or opt into automatic checks. Manual checks can also include development previews.
- Review the version and changes before approving the update. The launcher verifies signed update metadata and file integrity. Supported updates can roll back to the previous launcher if the new version fails to start.

## License and contact

Official builds are free for personal use. The source code is private. Contact the rights holder and obtain a prior written agreement for source access, commercial use, or integration into another service. [License and agreement terms](LICENSE.md) · [Rights holder profile](https://github.com/illililiiililii)

<sub>ALauncher is an independent launcher and is not an official Mojang or Microsoft product.</sub>
