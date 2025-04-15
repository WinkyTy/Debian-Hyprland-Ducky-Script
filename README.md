**Important: Read BEFORE Using**

I created this script solely for learning purposes, using the DUCKY language. It is not intended to be useful for experienced users who is capable of finding that script anyways. 
Please note that I only developed the DUCKY script, and all information regarding Hyprland or JaKoolit's kit can be found on their respective GitHub pages. I would like to extend a big thank you to the creators of these projects for their excellent work.

**hyprvm's official hub:** https://github.com/hyprwm/Hyprland

**JaKoolit's hub:** https://github.com/JaKooLit/Debian-Hyprland

This script, which consists of three separate scripts, is designed to install JaKoolit's Debian-Hyprland auto-install script with minimal user interaction. The default delays are intentionally set to be longer than necessary, allowing users to manually adjust them if needed. The default delay window for entering the sudo password is 10 seconds, which should be sufficient for two attempts. If you encounter any issues, simply cancel the script.

The reason for creating three separate scripts instead of one is that the installation time can vary significantly depending on the system's power capabilities and the time since the last update. Users are free to combine the scripts into one and adjust the delay to their preference.

Each script will reopen the Terminal using the default SUPER+T combination. Please ensure that your terminal opens with this combination or edit the script accordingly.

The script has been partially tested on a Kali VM using Flipper Zero BadUsb app. Updates may be released in the future.

**Please READ EACH SCRIPT Carefully Before Using**

1. The first script will edit the sources.list, uncomment the deb_src part, and perform a full system upgrade, which may take some time.
2. The second script will attempt to set up SDDM and reboot the system. It is highly recommended to perform this step manually or stop the script after the command is injected.
3. The third script will load the auto-install script from JaKoolit's GitHub page and check some early settings. The script will enable all options except for pokemons and ROG RGB. Please follow the on-screen instructions carefully, as the delays are intentionally set to be slow (one second between each interaction).

I plan to tweak some settings in the future based on user feedback and may release additional installation variants. Stay tuned!
