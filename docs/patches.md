## Patches

### AudioMod Resources Patch

AudioMod was basically hard-coded to read resources (the sound files for mods) from the appdata minecraft folder, instead of wherever Minecraft is _actually_ being run from. So, installing the resources _properly_ did not actually work as intended. This patch fixes that, so it will use the resources from the correct Minecraft instance (this modpack). Without this patch, we would either have to install the mod resources into your appdata .minecraft folder, or have no custom sounds at all!
