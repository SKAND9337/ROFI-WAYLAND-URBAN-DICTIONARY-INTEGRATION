# ROFI-WAYLAND-URBAN-DICTIONARY-INTEGRATION
NOTE: Collaborative vibe-coding effort between ChatGPT and Gemini
-----------------------------------------------------------------

Integrates Urban Dictionary search in rofi(-wayland) using python accessible through preferred keybind.

## How To Use:
1. Install dependencies:
      `rofi-wayland`, `python-requests`, `python`
      > 1.1. On ARCH LINUX (and based) systems:
      `sudo pacman -S python-requests rofi-wayland python`
   
2. Download and place the script as following:
      `~/.local/bin/urban-rofi`
      > Can be downloaded from the RELEASES section or download zip from the uploaded `urban-rofi` file in this repo.
   
3. Make executable:
      `chmod +x .local/bin/urban-rofi`
   
4. Add a preferred launch keybind
      > 4.1. I'm on Hyprland (0.55) so for me (lua) syntax would be:
   `hl.bind(mainMod .. " + CTRL + U", hl.dsp.exec_cmd("~/.local/bin/urban-rofi"))`

      > This uses SUPER+CTRL+U to open the search plugin, change as necessary
   
5. Enjoy


Use, modify, republish to your heart's content
----------------------------------------------

PS: rewrite in rust for memory safety
