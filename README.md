**A complete 720x720 overlay pack for devices like the Anbernic RG Cube and RG Rotate**

Design goals: maximum use of screen space, no grids, and a consistent look across systems.
- Handhelds: styled as if you’re looking through the front lens of the device.
- Consoles: sober and photorealistic.

# Contents
1. [Arcade - Capcom CPS](https://github.com/Atodarack/720p-square-overlays/tree/main#cps)
2. [Bandai - WonderSwan Color]()
3. [NEC - PC Engine]()
4. [Nintendo - Game Boy]()
5. [Nintendo - Game Boy Color]()
6. [Nintendo - Game Boy Advance]()
7. [Nintendo - Nintendo Entertainment System]()
8. [Nintendo - Super Nintendo Entertainment System]()
9. [Nintendo - Nintendo 64]()
10. [Sega - Game Gear]()
11. [Sega - Master System]()
12. [Sega - Mega Drive]()
13. [Sega - Saturn]()
14. [Sega - Dreamcast]()
15. [SNK - Neo Geo Pocket]()
16. [SNK - Neo Geo Pocket Color]()
17. [SNK - Neo Geo]()
18. [Sony - PlayStation Portable]()
19. [Sony - PlayStation]()

# Notes

Credits & reuse: Most of the handheld overlays are edited versions of other creators’ work, mainly to remove the grids. Original authors are credited in each system’s section. The console overlays are entirely my own creation and are free to reuse for any purpose.

# Installation

Download the .zip file from the Releases section and extract it into your ~\RetroArch\overlays folder. This will create a 720p-square folder containing all the necessary files.

For the content to be scaled and positioned correctly, follow the configuration guide below for each system.

# [Arcade - Capcom CPS](https://github.com/Atodarack/720p-square-overlays/tree/main/overlays/cps)
## Horizontal
![CPS_Horizontal_composite](https://github.com/user-attachments/assets/1e7e8cc7-fd62-4797-a895-061245bcfbc3)

## Configuration
<details>
  <summary>Click for installation and settings</summary>

  ### Settings:

  #### 1. Apply the Overlay:
  
    Quick Menu > On-Screen Overlay

         Display Overlay > ON

         Overlay Preset...
           > Navigate to /RetroArch/overlays/720p-square and select cps.cfg

         Overlay Opacity > 1.00
 
  #### 2. Scaling Settings:
    
      Main Menu > Settings > Video > Scaling
    
          Integer Scale > OFF
    
          Integer Scale Axis > Y
    
          Integer Scale Scaling > (shouldn't matter)
    
          Aspect Ratio > Custom
    
            Custom Aspect Ratio (X Position) > 0
    
            Custom Aspect Ratio (Y Position) > 70
    
            Custom Aspect Ratio (Width) > 720
            
            Custom Aspect Ratio (Height) > 540
    
          Viewport Anchor Bias X > 0.00
    
          Viewport Anchor Bias Y > 0.50
    
          Bilinear Filtering > OFF
    
          Crop Overscan > ON

  #### 3. Save an Override

      Quick Menu > Overrides > Save Content Directory Overrides
</details>

### Notes: 
Since we saved the configuration for the directory, for vertical games you'll need to do a per game configuration, it shouldn't be an issue since there's only a few of them.

## Vertical
![CPS_Vertical_composite](https://github.com/user-attachments/assets/98e5cfc2-eff5-441b-9cd8-f8cdd5ca1bd2)

## Configuration
<details>
  <summary>Click for installation and settings</summary>

  ### Settings:

  #### 1. Apply the Overlay:
  
    Quick Menu > On-Screen Overlay

         Display Overlay > ON

         Overlay Preset...
           > Navigate to Navigate to /RetroArch/overlays/720p-square and select cps.cfg

         Overlay Opacity > 1.00
 
  #### 2. Scaling Settings:
    
      Main Menu > Settings > Video > Scaling
    
          Integer Scale > OFF
    
          Integer Scale Axis > Y
    
          Integer Scale Scaling > (shouldn't matter)
    
          Aspect Ratio > Custom
    
            Custom Aspect Ratio (X Position) > 0
    
            Custom Aspect Ratio (Y Position) > 0
    
            Custom Aspect Ratio (Width) > 540
            
            Custom Aspect Ratio (Height) > 720
    
          Viewport Anchor Bias X > 0.50
    
          Viewport Anchor Bias Y > 0.00
          
          Bilinear Filtering > OFF
    
          Crop Overscan > ON

  #### 3. Save an Override

      Quick Menu > Overrides > Save Game Directory Overrides
</details>

