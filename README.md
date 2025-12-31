# InhibitSleep

This plugin polls DMS media devices and will disable sleep if one is found. This provides similar functionality to Caffeine GNOME extension, without having to manually click the button. I made it for a minimal operating system I am creating based on Universal Blue images, the operating system utilizes MangoWC (a tiling/scrolling compsitor for wayland) and DankMaterialShell to provide a complete desktop environment. Matugen is used to apply colorscheme to DMS and other apps such as VSCODE, Discord, Obsidian, Neovim, Kitty and colors used by MangoWC.

The plugin has a widget that has a coffee cup icon, when sleep is inhibited, the icon's color changes to the primary accent color, when sleep is not being inhibited, the icon is 30% opacity light gray.

## How to use
1) Clone this repository in ~/.config/DankMaterialShell/plugins
2) Restart DMS Shell
3) Enable the plugin in settings