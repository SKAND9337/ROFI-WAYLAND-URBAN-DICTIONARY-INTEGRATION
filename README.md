# ROFI-WAYLAND-URBAN-DICTIONARY-INTEGRATION

NOTE: Collaborative vibe-coding effort between ChatGPT and Gemini
-----------------------------------------------------------------

Integrates Urban Dictionary search in rofi(-wayland) accessible through preferred keybind.

## How To Use:
1. Install dependencies:
      `rofi-wayland`, `python-requests`
1.1. On ARCH LINUX (and based) systems:
      `sudo pacman -S python-requests rofi-wayland`
   
3. Download and place the script as following:
      `~/.local/bin/urban-rofi`
   
5. Make executable:
      `chmod +x .local/bin/urban-rofi`
   
6. Add a preferred launch keybind
6.1. I'm on Hyprland (0.55) so for me (lua) syntax would be:
   `hl.bind(mainMod .. " + CTRL + U", hl.dsp.exec_cmd("~/.local/bin/urban-rofi"))`
   This uses SUPER+CTRL+U to open the search plugin, change as necessary
   
7. Enjoy


Use, modify, republish however you want
---------------------------------------
