# Changelog
- All changes will be Update here.
---

## [v1.4.3-r+1.21.4] - Update

### Changes

- **Total Updates** : Updated most of the Mods, Resource and Sharder Packs to Latest
- **Minor Patch Changes** : A minor config Patch, for better stability. 

## [v1.3.3-r+1.21.4] - Mod Cleanup & Versioning Update

### Changes

- **Mod Removals**  
  - ❌ **MaLiLib**: Removed due to high memory usage and limited benefit for the modpack's purpose.  
  - ❌ **Litematica**: Removed for the same reason as MaLiLib — excessive memory consumption that contradicts the lightweight survival-focused intent of the modpack.

- **Mod Updates**  
  - 🔼 **BSL Shaders** updated to **v10.0**  
  - 🔼 **Dynamic FPS** updated to **v3.9.4**  
  - 🔼 **Fabric API** updated to **v0.119.3**  
  - 🔼 **Fabric Language Kotlin** updated to **v1.13.3+kotlin.2.1.21**  
  - 🔼 **Fabrishot** updated to **v1.14.4**  
  - 🔼 **LambDynamicLights** updated to **v4.1.3**  
  - 🔼 **PolyTone** updated to **v3.3.20**  
  - 🔼 **ViaFabricPlus** updated to **v4.0.5-BACKPORT**  
  - 🔼 **Xaero's Minimap** updated to **v25.2.6**  
  - 🔼 **Xaero's World Map** updated to **v1.39.9**

---

### Versioning Scheme Overhaul

The versioning format has been revised from a single-line scheme (`v0.0.0-x`) to a dual-format scheme (`v0.0.0-x+0.0.0`) to better align with Minecraft's rapid and incompatible version changes.

#### 📌 What Changed?
- **Old Scheme**: `v0.0.0-x`  
- **New Scheme**: `v0.0.0-x+MinecraftVersion`  
  - Example: `v1.3.3-r+1.21.4`

#### 🔍 Why This Change?
Minecraft’s 1.21.4 release brought significant backend changes, making previous mod compatibility assumptions unreliable. Tying the modpack version directly to the Minecraft version ensures clarity, better maintenance, and user awareness about version-specific support.

#### 🧩 Versioning Breakdown
- `vX.0.0-x`: Major Update  
- `v0.X.0-x`: Mod Update  
- `v0.0.X-x`: Patch Update  

**Build Types**:
- `-a`: Alpha Build  
- `-b`: Beta Build  
- `-r`: Release Build  

**Minecraft Version Tag**:
- `+1.21.4`: Indicates compatibility with Minecraft 1.21.4  

#### 🛠️ How This Helps
- Ensures users instantly know what Minecraft version the modpack targets  
- Avoids confusion caused by similar modpack versions across incompatible Minecraft builds  
- Improves update tracking, compatibility checks, and version rollback/forward planning


## [v1.2.2-r] - First Release for Survival+
### Changes
- **Configuration Optimizations**: Modified numerous mod configurations to ensure the best performance and stability for overall gameplay.
- **LambDynamicLights**: Updated to the latest version **4.1.2+1.21.4** for improved lighting performance and compatibility.

### Instructions
- **For Low-End Devices**: This modpack is designed for low-end devices. Adjust render distance and disable shaders for smoother gameplay.
- **For High-End Devices**: Tweak shader settings and configure Bobby mod according to your preferences for enhanced visuals.
- **Litematica Mod Warning**: Litematica offers advanced features that may be considered as hacks on public servers. Use it responsibly. If banned or muted, we are not responsible.
- **Bug Reporting**: There might still be some bugs. If you face any issues:
  - Report them in the [MineVerse Discord](https://discord.gg/uuSYkzahBj).
  - Or create an issue on GitHub: [Survival+ Repository](https://github.com/Krithiv-7/SurvivalPlus).

### Plans Ahead
- Begin work on ensuring full compatibility for a **Minecraft version 1.21.5** modpack soon.
- Further optimization for better performance across more diverse system configurations.
- Addressing any reported bugs and enhancing stability.
- Evaluate and potentially add new mods to enrich the modpack experience.

## [v1.2.1-b] - Update for Survival+
### Mod Additions
- [Xaero's Minimap](https://modrinth.com/mod/xaeros-minimap): A lightweight and customizable minimap mod to enhance navigation.
- [Litematica](https://modrinth.com/mod/litematica): A schematic mod for improved building and planning in Minecraft.
- [MaLiLib](https://modrinth.com/mod/malilib): A library mod required as a dependency for Litematica.
  
### Changes
- **Configuration Optimizations**:
  - Adjusted **render distance settings** to balance visual quality and performance for smoother gameplay.
  - Fine-tuned **entity rendering options** to reduce the strain on lower-end systems while maintaining an immersive experience.
  - Optimized **lighting configurations** to improve frame rates during dynamic light scenarios.
  - Modified **memory allocation settings** for better resource management, ensuring stability across a wide range of hardware setups.
  - Updated **shader presets** to enhance visual performance without significant impact on system resources.

## [v1.1.0-a] - Update for Survival+

- This changelog for Survival+ v1.1.0-a adds three new mods (Bobby, Jade, and ViaFabricPlus) and updates LambDynamicLights for better performance. Future plans include focusing on optimization, addressing performance issues.

### Mod Additions
- [Bobby](https://modrinth.com/mod/bobby): Allows rendering of distant chunks beyond server render distance for improved exploration.
- [Jade](https://modrinth.com/mod/jade): A powerful in-game HUD to display block and entity information.
- [ViaFabricPlus](https://modrinth.com/mod/viafabricplus): Enables compatibility for players using different Minecraft versions.

### Changes
- **Updated**: [LambDynamicLights](https://modrinth.com/mod/lambdynamiclights) updated from `4.1.0+1.21.4` to `4.1.1+1.21.4` for improved performance and stability.

- This changelog for Survival+ v1.1.0-a adds three new mods (Bobby, Jade, and ViaFabricPlus) and updates LambDynamicLights for better performance. Future plans include focusing on optimization, addressing performance issues.


## [v1.0.0-a] - Initial Alpha Release for Survival+
### Major Updates
- **Initial Release**: This version introduces the foundational elements of the Survival+ modpack.

### Mods Included
- [Entity Model Features (EMF)](https://modrinth.com/mod/entity-model-features): Adds support for OptiFine's Custom Entity Models (CEM) for improved entity customization.
- [Entity Texture Features (ETF)](https://modrinth.com/mod/entitytexturefeatures): Provides OptiFine-like features for custom entity textures without needing OptiFine.
- [3D Skin Layers](https://modrinth.com/mod/3dskinlayers): Enhances player skins by adding 3D layers, making them more dynamic and realistic.
- [AppleSkin](https://modrinth.com/mod/appleskin): Adds useful information about food/hunger mechanics to the HUD.
- [Better Mount HUD](https://modrinth.com/mod/better-mount-hud): Improves the HUD for mounts, displaying more information.
- [Better Stats](https://modrinth.com/mod/better-stats): Revamps the statistics screen with additional details and better visuals.
- [BetterF3](https://modrinth.com/mod/betterf3): Customizes the F3 debug overlay for a cleaner experience.
- [Chest Tracker](https://modrinth.com/mod/chest-tracker): Tracks and searches through chests for easier organization.
- [Cloth Config](https://modrinth.com/mod/cloth-config): Provides a UI library for mod configuration.
- [Continuity](https://modrinth.com/mod/continuity): Adds connected textures and seamless transitions between blocks.
- [Cubes Without Borders](https://modrinth.com/mod/cubes-without-borders): Enhances chunk rendering for better visuals.
- [Debugify](https://modrinth.com/mod/debugify): Fixes vanilla Minecraft bugs for a smoother experience.
- [Dynamic FPS](https://modrinth.com/mod/dynamic-fps): Reduces resource usage when Minecraft is in the background.
- [E4MC](https://modrinth.com/mod/e4mc): Opens your world to LAN.
- [Enhanced Block Entities (EBE)](https://modrinth.com/mod/ebe): Improves the performance of block entities by optimizing their rendering.
- [EntityCulling](https://modrinth.com/mod/entityculling): Prevents rendering of out-of-sight entities for performance improvements.
- [Fabric API](https://modrinth.com/mod/fabric-api): Core library required for most Fabric mods.
- [Fabric Language Kotlin](https://modrinth.com/mod/fabric-language-kotlin): Adds Kotlin language support for Fabric mods.
- [Fabrishot](https://modrinth.com/mod/fabrishot): Supports high-resolution screenshots.
- [FastQuit](https://modrinth.com/mod/fastquit): Speeds up quitting time in Minecraft.
- [FerriteCore](https://modrinth.com/mod/ferrite-core): Optimizes memory usage in Minecraft.
- [Forge Config API Port](https://modrinth.com/mod/forge-config-api-port): Adds Forge's config API to Fabric.
- [ImmediatelyFast](https://modrinth.com/mod/immediatelyfast): Boosts rendering performance.
- [Iris](https://modrinth.com/mod/iris): Enables shader support with compatibility for the Sodium mod.
- [ItemPhysic Lite](https://modrinth.com/mod/itemphysic-lite): Adds realistic physics to dropped items.
- [LambDynamicLights](https://modrinth.com/mod/lambdynamiclights): Adds dynamic lighting to light-emitting items.
- [Lithium](https://modrinth.com/mod/lithium): Improves server-side performance with optimizations.
- [MixinTrace](https://modrinth.com/mod/mixintrace): Provides debugging tools for mixins used by mods.
- [Mod Menu](https://modrinth.com/mod/modmenu): Adds a menu for managing mods in Minecraft.
- [ModelFix](https://modrinth.com/mod/modelfix): Fixes model rendering issues in Minecraft.
- [ModernFix](https://modrinth.com/mod/modernfix): Resolves performance issues in modern Minecraft versions.
- [MoreCulling](https://modrinth.com/mod/moreculling): Enhances entity culling for performance.
- [No Chat Reports](https://modrinth.com/mod/no-chat-reports): Disables chat reporting for player privacy.
- [OptiGUI](https://modrinth.com/mod/optigui): Provides optimized GUI rendering for performance.
- [Paginated Advancements](https://modrinth.com/mod/paginatedadvancements): Organizes the advancements screen into multiple pages.
- [Polytone](https://modrinth.com/mod/polytone): Adds multi-tone sound support.
- [Puzzle](https://modrinth.com/mod/puzzle): Enables resource pack features like custom models and animations.
- [Reese's Sodium Options](https://modrinth.com/mod/reeses-sodium-options): Adds additional options and features to Sodium settings.
- [RRLS](https://modrinth.com/mod/rrls): Enhances lighting system for better visuals.
- [ReplayMod](https://modrinth.com/mod/replaymod): Provides tools for recording and replaying gameplay.
- [Sodium](https://modrinth.com/mod/sodium): Optimizes client-side performance.
- [Sodium Extra](https://modrinth.com/mod/sodium-extra): Adds extra features to the Sodium mod.
- [TCDCommons](https://modrinth.com/mod/tcdcommons): A common library for other mods.
- [Yet Another Config Lib (YACL)](https://modrinth.com/mod/yacl): Simplifies mod configuration with an easy-to-use UI.
- [Xaero's World Map](https://modrinth.com/mod/xaeros-world-map): Adds a world map for better navigation.
- [YOSBR](https://modrinth.com/mod/yosbr): Optimizes server-side performance.
- [Zoomify](https://modrinth.com/mod/zoomify): Adds a zoom functionality to Minecraft.

### Resource Packs
- [Eating Animation Resource Pack](https://modrinth.com/resourcepack/eating-animation-resource-pack): Enhances eating animations for better visuals.
- [Prime's HD Textures](https://modrinth.com/resourcepack/primes-hd-textures): Improves texture quality for a high-definition look.
- [Redstone Tweaks](https://modrinth.com/resourcepack/redstone-tweaks): Improves the visuals and usability of redstone contraptions.
- [Visible Ores (Advanced)](https://modrinth.com/resourcepack/visible-ores(advance)): Highlights ores for easier mining.

### Shaders
- [BSL Shaders](https://modrinth.com/shader/bsl-shaders): Adds beautiful lighting, shadows, and visual effects to Minecraft.

### Notes
- This alpha build is intended for testing and feedback.
- Expect further updates and improvements in future versions.

---

## Versioning Scheme
- **vX.0.0-x**: Major Update
- **v0.X.0-x**: Mod Update
- **v0.0.X-x**: Patch Update

**Build Types**:
- **v0.0.0-a**: Alpha Build
- **v0.0.0-b**: Beta Build
- **v0.0.0-r**: Release Build
