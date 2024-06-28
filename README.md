## Moonlight-Embedded Launcher

This repo contains a Moonlight-Embedded Launcher, specifically designed for handheld Linux devices. Built using the Love2D framework from scratch. This user-friendly interface enhances Moonlight Embedded, an open-source client for Sunshine and NVIDIA GameStream on embedded Linux systems.

![Showcase](https://github.com/JanTrueno/Moonlight-Embedded-Launcher-Love2D-/blob/main/images/example.jpg)
### Key Features:

1.  **Ease of Use**:
    
    -   Simple navigation with handheld-friendly controls (A for Select, B for Back/Skip splash, D-pad for Navigation/Scroll).
    -   Quick access to all essential settings and menus.
    -   Native controller support using SDL.
2.  **Pairing and Connectivity**:
    
    -   Easy pairing process with a built-in numpad to set the IP address of the host device.
    -   Automatic pairing with Sunshine ensures seamless device connectivity.
3.  **App Management**:
    
    -   Fetch and display apps configured in Sunshine.
    -   Reload Apps function to update the list of available applications from Sunshine.
4.  **Customizable Settings**:
    
    -   Set and adjust resolution, bitrate, remote optimizations, and codec settings directly within the launcher.
    -   Allows for tailored streaming experiences based on your preferences and device capabilities.
5.  **Visuals**:
    
    -   Original pixel art created by me.
    -   Four different themes to customize the launcher's appearance.
    -   Selectable background music.
    -   Animated splash screen and pixel art in the background.
6.  **Interactive Menus**:
    
    -   Scrollable menus and settings for easy navigation and adjustments.

![Themes](https://github.com/JanTrueno/Moonlight-Embedded-Launcher-Love2D-/blob/main/images/themeshowcase.png)

### Additional Information:

-   A PortMaster package is provided on the release page.
-   Place all the sourcecode into your Love2D folder and run the gui folder which containts the sourcecode.
-   If you wish to make this work on other platforms, refer to the shell script available in the PortMaster package. The launcher has some minor hardcoded variables built-in the main.lua required for a seemless experience on PortMaster.
-   This code is available under the GNU GPLv3 license. Please give credit to the [original developer](https://github.com/JanTrueno) when using or modifying it.
