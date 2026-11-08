# RetroArch 720×720 Square Overlays

A collection of RetroArch overlays designed for **720×720 square displays**, including devices such as the **Anbernic RG Cube** and **RG Rotate**.

**Design goals:** make the most of the available screen space, avoid distracting grid patterns, and maintain a consistent visual style across systems.

- **Handhelds:** designed to recreate the look of viewing a game through the original device’s screen lens.
- **Consoles:** clean, understated, and photorealistic.

# Table of Contents
1. [Arcade - Capcom CPS](#arcade---capcom-cps)
2. [Bandai - WonderSwan Color](#bandai---wonderswan-color)
3. [NEC - PC Engine](#nec---pc-engine)
4. [Nintendo - Game Boy](#nintendo---game-boy)
5. [Nintendo - Game Boy Color](#nintendo---game-boy-color)
6. [Nintendo - Game Boy Advance](#nintendo---game-boy-advance)
7. [Nintendo - Nintendo Entertainment System](#nintendo---nintendo-entertainment-system)
8. [Nintendo - Super Nintendo Entertainment System](#nintendo---super-nintendo-entertainment-system)
9. [Nintendo - Nintendo 64](#nintendo---nintendo-64)
10. [Sega - Game Gear](#sega---game-gear)
11. [Sega - Master System](#sega---master-system)
12. [Sega - Mega Drive](#sega---mega-drive)
13. [Sega - Saturn](#sega---saturn)
14. [Sega - Dreamcast](#sega---dreamcast)
15. [SNK - Neo Geo Pocket](#snk---neo-geo-pocket)
16. [SNK - Neo Geo Pocket Color](#snk---neo-geo-pocket-color)
17. [SNK - Neo Geo](#snk---neo-geo)
18. [Sony - PlayStation Portable](#sony---playstation-portable)
19. [Sony - PlayStation](#sony---playstation)

## Credits and Reuse

Most handheld overlays are modified versions of work by other creators, primarily adapted to remove grid patterns. The original creators are credited in the relevant system sections below.

All console overlays were created by me and may be reused for any purpose. For overlays based on other creators’ work, please refer to the original sources and their applicable terms.

## Installation

Download the `.zip` archive from the [Releases page](https://github.com/Atodarack/720p-square-overlays/releases) and extract it into your `~/RetroArch/overlays` directory. You should end up with a `720p-square` folder containing the overlay files.

To ensure each game is scaled and positioned correctly, follow the system-specific configuration instructions below. Menu names may vary depending on your RetroArch version or platform.

## [Arcade - Capcom CPS](https://github.com/Atodarack/720p-square-overlays/tree/main/overlays/cps)

### Horizontal

![CPS horizontal overlay](https://github.com/user-attachments/assets/1e7e8cc7-fd62-4797-a895-061245bcfbc3)

<details>
  <summary>Show RetroArch configuration</summary>

#### 1. Apply the overlay

```text
Quick Menu > On-Screen Overlay
    Display Overlay > ON
    Overlay Preset...
      > Navigate to /RetroArch/overlays/720p-square and select cps.cfg
    Overlay Opacity > 1.00
```

#### 2. Configure video scaling

```text
Main Menu > Settings > Video > Scaling
    Integer Scale > OFF
    Integer Scale Axis > Any (ignored when Integer Scale is OFF)
    Integer Scale Scaling > Any (ignored when Integer Scale is OFF)
    Aspect Ratio > Custom
        Custom Aspect Ratio (X Position) > 0
        Custom Aspect Ratio (Y Position) > 70
        Custom Aspect Ratio (Width) > 720
        Custom Aspect Ratio (Height) > 540
    Viewport Anchor Bias X > 0.00
    Viewport Anchor Bias Y > 0.00
    Bilinear Filtering > OFF
    Crop Overscan > ON
```

#### 3. Save an override

```text
Quick Menu > Overrides > Save Content Directory Overrides
```

</details>

#### Notes

Because this override applies to the entire content directory, vertical games need individual game overrides. Follow the vertical configuration below for those titles.

**Shader used:** `~/RetroArch/shaders/shaders_glsl/crt/zfast_crt.glslp`

### Vertical

![CPS vertical overlay](https://github.com/user-attachments/assets/98e5cfc2-eff5-441b-9cd8-f8cdd5ca1bd2)

<details>
  <summary>Show RetroArch configuration</summary>

#### 1. Apply the overlay

```text
Quick Menu > On-Screen Overlay
    Display Overlay > ON
    Overlay Preset...
      > Navigate to /RetroArch/overlays/720p-square and select cps_vertical.cfg
    Overlay Opacity > 1.00
```

#### 2. Configure video scaling

```text
Main Menu > Settings > Video > Scaling
    Integer Scale > OFF
    Integer Scale Axis > Any (ignored when Integer Scale is OFF)
    Integer Scale Scaling > Any (ignored when Integer Scale is OFF)
    Aspect Ratio > Custom
        Custom Aspect Ratio (X Position) > 0
        Custom Aspect Ratio (Y Position) > 0
        Custom Aspect Ratio (Width) > 540
        Custom Aspect Ratio (Height) > 720
    Viewport Anchor Bias X > 0.50
    Viewport Anchor Bias Y > 0.00
    Bilinear Filtering > OFF
    Crop Overscan > ON
```

#### 3. Save an override

```text
Quick Menu > Overrides > Save Game Overrides
```
</details>

#### Notes

**Shader used:** `~/RetroArch/shaders/shaders_glsl/crt/zfast_crt.glslp`

## [Bandai - WonderSwan Color](https://github.com/Atodarack/720p-square-overlays/tree/main/overlays/wonderswancolor)

### Horizontal

![WSC horizontal overlay](https://github.com/user-attachments/assets/80833c81-b424-439f-acd2-610b344dc7b5)

<details>
  <summary>Show RetroArch configuration</summary>

#### 1. Apply the overlay

```text
Quick Menu > On-Screen Overlay
    Display Overlay > ON
    Overlay Preset...
      > Navigate to /RetroArch/overlays/720p-square and select wonderswancolor.cfg
    Overlay Opacity > 1.00
```

#### 2. Configure video scaling

```text
Main Menu > Settings > Video > Scaling
    Integer Scale > OFF
    Integer Scale Axis > Any (ignored when Integer Scale is OFF)
    Integer Scale Scaling > Any (ignored when Integer Scale is OFF)
    Aspect Ratio > Custom
        Custom Aspect Ratio (X Position) > 0
        Custom Aspect Ratio (Y Position) > 124
        Custom Aspect Ratio (Width) > 720
        Custom Aspect Ratio (Height) > 462
    Viewport Anchor Bias X > 0.00
    Viewport Anchor Bias Y > 0.00
    Bilinear Filtering > OFF
    Crop Overscan > ON
```

#### 3. Save an override

```text
Quick Menu > Overrides > Save Content Directory Overrides
```

</details>

#### Notes

Because this override applies to the entire content directory, vertical games need individual game overrides. Follow the vertical configuration below for those titles.

**Shader used:** `~/RetroArch/shaders/shaders_glsl/handheld/lcd3x.glslp`

### Vertical

![WSC vertical overlay](https://github.com/user-attachments/assets/2c8da5a3-7421-4730-a9b4-e22dc459f938)

<details>
  <summary>Show RetroArch configuration</summary>

#### 1. Apply the overlay

```text
Quick Menu > On-Screen Overlay
    Display Overlay > ON
    Overlay Preset...
      > Navigate to /RetroArch/overlays/720p-square and select wonderswancolor_vertical.cfg
    Overlay Opacity > 1.00
```

#### 2. Configure video scaling

```text
Main Menu > Settings > Video > Scaling
    Integer Scale > OFF
    Integer Scale Axis > Any (ignored when Integer Scale is OFF)
    Integer Scale Scaling > Any (ignored when Integer Scale is OFF)
    Aspect Ratio > Custom
        Custom Aspect Ratio (X Position) > 129
        Custom Aspect Ratio (Y Position) > 0
        Custom Aspect Ratio (Width) > 462
        Custom Aspect Ratio (Height) > 720
    Viewport Anchor Bias X > 0.00
    Viewport Anchor Bias Y > 0.00
    Bilinear Filtering > OFF
    Crop Overscan > ON
```

#### 3. Save an override

```text
Quick Menu > Overrides > Save Game Overrides
```

</details>

#### Notes

**Shader used:** `~/RetroArch/shaders/shaders_glsl/handheld/lcd3x.glslp`

## [NEC - PC Engine](https://github.com/Atodarack/720p-square-overlays/tree/main/overlays/pcengine)

![PCE overlay](https://github.com/user-attachments/assets/ede6a896-c58a-401c-83fb-efc98c9ffa75)

<details>
  <summary>Show RetroArch configuration</summary>

#### 1. Apply the overlay

```text
Quick Menu > On-Screen Overlay
    Display Overlay > ON
    Overlay Preset...
      > Navigate to /RetroArch/overlays/720p-square and select pcengine.cfg
    Overlay Opacity > 1.00
```

#### 2. Configure video scaling

```text
Main Menu > Settings > Video > Scaling
    Integer Scale > OFF
    Integer Scale Axis > Any (ignored when Integer Scale is OFF)
    Integer Scale Scaling > Any (ignored when Integer Scale is OFF)
    Aspect Ratio > Custom
        Custom Aspect Ratio (X Position) > 0
        Custom Aspect Ratio (Y Position) > 70
        Custom Aspect Ratio (Width) > 720
        Custom Aspect Ratio (Height) > 540
    Viewport Anchor Bias X > 0.00
    Viewport Anchor Bias Y > 0.00
    Bilinear Filtering > OFF
    Crop Overscan > ON
```

#### 3. Save an override

```text
Quick Menu > Overrides > Save Content Directory Overrides
```

</details>

#### Notes

**Shader used:** `~/RetroArch/shaders/shaders_glsl/crt/zfast_crt.glslp`

## [Nintendo - Game Boy](https://github.com/Atodarack/720p-square-overlays/tree/main/overlays/gb)

![GB overlay](https://github.com/user-attachments/assets/376930cb-3521-4a5e-8bb3-eef00fc4133d)

<details>
  <summary>Show RetroArch configuration</summary>

#### 1. Apply the overlay

```text
Quick Menu > On-Screen Overlay
    Display Overlay > ON
    Overlay Preset...
      > Navigate to /RetroArch/overlays/720p-square and select gb.cfg
    Overlay Opacity > 1.00
```

#### 2. Configure video scaling

```text
Main Menu > Settings > Video > Scaling
    Integer Scale > OFF
    Integer Scale Axis > Any (ignored when Integer Scale is OFF)
    Integer Scale Scaling > Any (ignored when Integer Scale is OFF)
    Aspect Ratio > Custom
        Custom Aspect Ratio (X Position) > 0
        Custom Aspect Ratio (Y Position) > 25
        Custom Aspect Ratio (Width) > 720
        Custom Aspect Ratio (Height) > 648
    Viewport Anchor Bias X > 0.00
    Viewport Anchor Bias Y > 0.00
    Bilinear Filtering > OFF
    Crop Overscan > ON
```

#### 3. Save an override

```text
Quick Menu > Overrides > Save Content Directory Overrides
```

</details>

#### Notes

**Original overlay by:** [mugwomp93](https://github.com/mugwomp93/720x720_overlays/tree/main/720x720%20overlays/GB).

**Game Boy palette (Gambatte core):** `Quick Menu > Core Options > GB Colorization > Internal Palette > GB - Pocket`

**Shader used:** `~/RetroArch/shaders/shaders_glsl/handheld/lcd3x.glslp`

## [Nintendo - Game Boy Color](https://github.com/Atodarack/720p-square-overlays/tree/main/overlays/gbc)

![GBC overlay](https://github.com/user-attachments/assets/f0651c84-ec3e-4458-9dc9-688f67e73e6d)

<details>
  <summary>Show RetroArch configuration</summary>

#### 1. Apply the overlay

```text
Quick Menu > On-Screen Overlay
    Display Overlay > ON
    Overlay Preset...
      > Navigate to /RetroArch/overlays/720p-square and select gbc.cfg
    Overlay Opacity > 1.00
```

#### 2. Configure video scaling

```text
Main Menu > Settings > Video > Scaling
    Integer Scale > OFF
    Integer Scale Axis > Any (ignored when Integer Scale is OFF)
    Integer Scale Scaling > Any (ignored when Integer Scale is OFF)
    Aspect Ratio > Custom
        Custom Aspect Ratio (X Position) > 0
        Custom Aspect Ratio (Y Position) > 25
        Custom Aspect Ratio (Width) > 720
        Custom Aspect Ratio (Height) > 648
    Viewport Anchor Bias X > 0.00
    Viewport Anchor Bias Y > 0.00
    Bilinear Filtering > OFF
    Crop Overscan > ON
```

#### 3. Save an override

```text
Quick Menu > Overrides > Save Content Directory Overrides
```

</details>

#### Notes

**Original overlay by:** [mugwomp93](https://github.com/mugwomp93/720x720_overlays/tree/main/720x720%20overlays/GBC).

**Shader used:** `~/RetroArch/shaders/shaders_glsl/handheld/lcd3x.glslp`

## [Nintendo - Game Boy Advance](https://github.com/Atodarack/720p-square-overlays/tree/main/overlays/gba)

![GBA overlay](https://github.com/user-attachments/assets/e777291c-88c7-4ee6-a259-d76f77cfcc53)

<details>
  <summary>Show RetroArch configuration</summary>

#### 1. Apply the overlay

```text
Quick Menu > On-Screen Overlay
    Display Overlay > ON
    Overlay Preset...
      > Navigate to /RetroArch/overlays/720p-square and select gba.cfg
    Overlay Opacity > 1.00
```

#### 2. Configure video scaling

```text
Main Menu > Settings > Video > Scaling
    Integer Scale > OFF
    Integer Scale Axis > Any (ignored when Integer Scale is OFF)
    Integer Scale Scaling > Any (ignored when Integer Scale is OFF)
    Aspect Ratio > Core provided
    Viewport Anchor Bias X > 0.00
    Viewport Anchor Bias Y > 0.50
    Bilinear Filtering > OFF
    Crop Overscan > ON
```

#### 3. Save an override

```text
Quick Menu > Overrides > Save Content Directory Overrides
```

</details>

#### Notes

**Original overlay by:** [gonejack](https://github.com/gonejack/rgb30/blob/main/RGB30/RGB30_GBA_3x_HUI.png).

**Shader used:** `~/RetroArch/shaders/shaders_glsl/handheld/lcd3x.glslp`

## [Nintendo - Nintendo Entertainment System](https://github.com/Atodarack/720p-square-overlays/tree/main/overlays/nes)

![NES overlay](https://github.com/user-attachments/assets/ecabb783-e99d-4359-be9c-e1fd0ef7ed65)

<details>
  <summary>Show RetroArch configuration</summary>

#### 1. Apply the overlay

```text
Quick Menu > On-Screen Overlay
    Display Overlay > ON
    Overlay Preset...
      > Navigate to /RetroArch/overlays/720p-square and select nes.cfg
    Overlay Opacity > 1.00
```

#### 2. Configure video scaling

```text
Main Menu > Settings > Video > Scaling
    Integer Scale > OFF
    Integer Scale Axis > Any (ignored when Integer Scale is OFF)
    Integer Scale Scaling > Any (ignored when Integer Scale is OFF)
    Aspect Ratio > Custom
        Custom Aspect Ratio (X Position) > 0
        Custom Aspect Ratio (Y Position) > 70
        Custom Aspect Ratio (Width) > 720
        Custom Aspect Ratio (Height) > 540
    Viewport Anchor Bias X > 0.00
    Viewport Anchor Bias Y > 0.00
    Bilinear Filtering > OFF
    Crop Overscan > ON
```

#### 3. Save an override

```text
Quick Menu > Overrides > Save Content Directory Overrides
```

</details>

#### Notes

**Shader used:** `~/RetroArch/shaders/shaders_glsl/crt/zfast_crt.glslp`

## [Nintendo - Super Nintendo Entertainment System](https://github.com/Atodarack/720p-square-overlays/tree/main/overlays/snes)

![SNES overlay](https://github.com/user-attachments/assets/994cb08a-afdb-434c-a287-dc6ba6416109)

<details>
  <summary>Show RetroArch configuration</summary>

#### 1. Apply the overlay

```text
Quick Menu > On-Screen Overlay
    Display Overlay > ON
    Overlay Preset...
      > Navigate to /RetroArch/overlays/720p-square and select snes.cfg
    Overlay Opacity > 1.00
```

#### 2. Configure video scaling

```text
Main Menu > Settings > Video > Scaling
    Integer Scale > OFF
    Integer Scale Axis > Any (ignored when Integer Scale is OFF)
    Integer Scale Scaling > Any (ignored when Integer Scale is OFF)
    Aspect Ratio > Custom
        Custom Aspect Ratio (X Position) > 0
        Custom Aspect Ratio (Y Position) > 70
        Custom Aspect Ratio (Width) > 720
        Custom Aspect Ratio (Height) > 540
    Viewport Anchor Bias X > 0.00
    Viewport Anchor Bias Y > 0.00
    Bilinear Filtering > OFF
    Crop Overscan > ON
```

#### 3. Save an override

```text
Quick Menu > Overrides > Save Content Directory Overrides
```

</details>

#### Notes

**Shader used:** `~/RetroArch/shaders/shaders_glsl/crt/zfast_crt.glslp`

## [Nintendo - Nintendo 64](https://github.com/Atodarack/720p-square-overlays/tree/main/overlays/n64)

![N64 overlay](https://github.com/user-attachments/assets/1948157b-aa85-4973-9bfd-65fb6bec449b)

<details>
  <summary>Show RetroArch configuration</summary>

#### 1. Apply the overlay

```text
Quick Menu > On-Screen Overlay
    Display Overlay > ON
    Overlay Preset...
      > Navigate to /RetroArch/overlays/720p-square and select n64.cfg
    Overlay Opacity > 1.00
```

#### 2. Configure video scaling

```text
Main Menu > Settings > Video > Scaling
    Integer Scale > OFF
    Integer Scale Axis > Any (ignored when Integer Scale is OFF)
    Integer Scale Scaling > Any (ignored when Integer Scale is OFF)
    Aspect Ratio > Custom
        Custom Aspect Ratio (X Position) > 0
        Custom Aspect Ratio (Y Position) > 70
        Custom Aspect Ratio (Width) > 720
        Custom Aspect Ratio (Height) > 540
    Viewport Anchor Bias X > 0.00
    Viewport Anchor Bias Y > 0.00
    Bilinear Filtering > OFF
    Crop Overscan > ON
```

#### 3. Save an override

```text
Quick Menu > Overrides > Save Content Directory Overrides
```

</details>

#### Notes

Some Nintendo 64 games may require additional overscan adjustments to fit the overlay correctly. With the Mupen64Plus-Next core, go to `Quick Menu > Core Options > GlideN64 > Overscan Offset` and adjust the values as needed.

## [Sega - Game Gear](https://github.com/Atodarack/720p-square-overlays/tree/main/overlays/gamegear)

![GG overlay](https://github.com/user-attachments/assets/81fbf3c4-ccfa-4f90-a2e8-4231db879bfb)

<details>
  <summary>Show RetroArch configuration</summary>

#### 1. Apply the overlay

```text
Quick Menu > On-Screen Overlay
    Display Overlay > ON
    Overlay Preset...
      > Navigate to /RetroArch/overlays/720p-square and select gamegear.cfg
    Overlay Opacity > 1.00
```

#### 2. Configure video scaling

```text
Main Menu > Settings > Video > Scaling
    Integer Scale > OFF
    Integer Scale Axis > Any (ignored when Integer Scale is OFF)
    Integer Scale Scaling > Any (ignored when Integer Scale is OFF)
    Aspect Ratio > Custom
        Custom Aspect Ratio (X Position) > 0
        Custom Aspect Ratio (Y Position) > 25
        Custom Aspect Ratio (Width) > 720
        Custom Aspect Ratio (Height) > 648
    Viewport Anchor Bias X > 0.00
    Viewport Anchor Bias Y > 0.00
    Bilinear Filtering > OFF
    Crop Overscan > ON
```

#### 3. Save an override

```text
Quick Menu > Overrides > Save Content Directory Overrides
```

</details>

#### Notes

**Original overlay by:** [mugwomp93](https://github.com/mugwomp93/720x720_overlays/tree/main/720x720%20overlays/GG).

**Shader used:** `~/RetroArch/shaders/shaders_glsl/handheld/lcd3x.glslp`

## [Sega - Master System](https://github.com/Atodarack/720p-square-overlays/tree/main/overlays/mastersystem)

![SMS overlay](https://github.com/user-attachments/assets/da47e6be-3bf7-4ae6-9e9b-66154624b637)

<details>
  <summary>Show RetroArch configuration</summary>

#### 1. Apply the overlay

```text
Quick Menu > On-Screen Overlay
    Display Overlay > ON
    Overlay Preset...
      > Navigate to /RetroArch/overlays/720p-square and select mastersystem.cfg
    Overlay Opacity > 1.00
```

#### 2. Configure video scaling

```text
Main Menu > Settings > Video > Scaling
    Integer Scale > OFF
    Integer Scale Axis > Any (ignored when Integer Scale is OFF)
    Integer Scale Scaling > Any (ignored when Integer Scale is OFF)
    Aspect Ratio > Custom
        Custom Aspect Ratio (X Position) > 0
        Custom Aspect Ratio (Y Position) > 70
        Custom Aspect Ratio (Width) > 720
        Custom Aspect Ratio (Height) > 540
    Viewport Anchor Bias X > 0.00
    Viewport Anchor Bias Y > 0.00
    Bilinear Filtering > OFF
    Crop Overscan > ON
```

#### 3. Save an override

```text
Quick Menu > Overrides > Save Content Directory Overrides
```

</details>

#### Notes

**Shader used:** `~/RetroArch/shaders/shaders_glsl/crt/zfast_crt.glslp`

## [Sega - Mega Drive](https://github.com/Atodarack/720p-square-overlays/tree/main/overlays/megadrive)

![SMD overlay](https://github.com/user-attachments/assets/2f00d66e-acd9-40f9-bd20-407c7b816468)

<details>
  <summary>Show RetroArch configuration</summary>

#### 1. Apply the overlay

```text
Quick Menu > On-Screen Overlay
    Display Overlay > ON
    Overlay Preset...
      > Navigate to /RetroArch/overlays/720p-square and select megadrive.cfg
    Overlay Opacity > 1.00
```

#### 2. Configure video scaling

```text
Main Menu > Settings > Video > Scaling
    Integer Scale > OFF
    Integer Scale Axis > Any (ignored when Integer Scale is OFF)
    Integer Scale Scaling > Any (ignored when Integer Scale is OFF)
    Aspect Ratio > Custom
        Custom Aspect Ratio (X Position) > 0
        Custom Aspect Ratio (Y Position) > 70
        Custom Aspect Ratio (Width) > 720
        Custom Aspect Ratio (Height) > 540
    Viewport Anchor Bias X > 0.00
    Viewport Anchor Bias Y > 0.00
    Bilinear Filtering > OFF
    Crop Overscan > ON
```

#### 3. Save an override

```text
Quick Menu > Overrides > Save Content Directory Overrides
```

</details>

#### Notes

**Shader used:** `~/RetroArch/shaders/shaders_glsl/crt/zfast_crt.glslp`

## [Sega - Saturn](https://github.com/Atodarack/720p-square-overlays/tree/main/overlays/saturn)

![SS overlay](https://github.com/user-attachments/assets/e8e497f9-6f04-439b-83c0-f8b70328c3a2)

<details>
  <summary>Show RetroArch configuration</summary>

#### 1. Apply the overlay

```text
Quick Menu > On-Screen Overlay
    Display Overlay > ON
    Overlay Preset...
      > Navigate to /RetroArch/overlays/720p-square and select saturn.cfg
    Overlay Opacity > 1.00
```

#### 2. Configure video scaling

```text
Main Menu > Settings > Video > Scaling
    Integer Scale > OFF
    Integer Scale Axis > Any (ignored when Integer Scale is OFF)
    Integer Scale Scaling > Any (ignored when Integer Scale is OFF)
    Aspect Ratio > Custom
        Custom Aspect Ratio (X Position) > 0
        Custom Aspect Ratio (Y Position) > 70
        Custom Aspect Ratio (Width) > 720
        Custom Aspect Ratio (Height) > 540
    Viewport Anchor Bias X > 0.00
    Viewport Anchor Bias Y > 0.00
    Bilinear Filtering > OFF
    Crop Overscan > ON
```

#### 3. Save an override

```text
Quick Menu > Overrides > Save Content Directory Overrides
```

</details>

## [Sega - Dreamcast](https://github.com/Atodarack/720p-square-overlays/tree/main/overlays/dreamcast)

![SD overlay](https://github.com/user-attachments/assets/3fd6c08f-1404-448d-a2fe-74435be6694f)

<details>
  <summary>Show RetroArch configuration</summary>

#### 1. Apply the overlay

```text
Quick Menu > On-Screen Overlay
    Display Overlay > ON
    Overlay Preset...
      > Navigate to /RetroArch/overlays/720p-square and select dreamcast.cfg
    Overlay Opacity > 1.00
```

#### 2. Configure video scaling

```text
Main Menu > Settings > Video > Scaling
    Integer Scale > OFF
    Integer Scale Axis > Any (ignored when Integer Scale is OFF)
    Integer Scale Scaling > Any (ignored when Integer Scale is OFF)
    Aspect Ratio > Custom
        Custom Aspect Ratio (X Position) > 0
        Custom Aspect Ratio (Y Position) > 70
        Custom Aspect Ratio (Width) > 720
        Custom Aspect Ratio (Height) > 540
    Viewport Anchor Bias X > 0.00
    Viewport Anchor Bias Y > 0.00
    Bilinear Filtering > OFF
    Crop Overscan > ON
```

#### 3. Save an override

```text
Quick Menu > Overrides > Save Content Directory Overrides
```

</details>

## [SNK - Neo Geo Pocket](https://github.com/Atodarack/720p-square-overlays/tree/main/overlays/ngp)

![NGP overlay](https://github.com/user-attachments/assets/58d520d5-0065-4398-b1af-da564431eded)

<details>
  <summary>Show RetroArch configuration</summary>

#### 1. Apply the overlay

```text
Quick Menu > On-Screen Overlay
    Display Overlay > ON
    Overlay Preset...
      > Navigate to /RetroArch/overlays/720p-square and select ngp.cfg
    Overlay Opacity > 1.00
```

#### 2. Configure video scaling

```text
Main Menu > Settings > Video > Scaling
    Integer Scale > OFF
    Integer Scale Axis > Any (ignored when Integer Scale is OFF)
    Integer Scale Scaling > Any (ignored when Integer Scale is OFF)
    Aspect Ratio > Custom
        Custom Aspect Ratio (X Position) > 0
        Custom Aspect Ratio (Y Position) > 0
        Custom Aspect Ratio (Width) > 720
        Custom Aspect Ratio (Height) > 684
    Viewport Anchor Bias X > 0.00
    Viewport Anchor Bias Y > 0.00
    Bilinear Filtering > OFF
    Crop Overscan > ON
```

#### 3. Save an override

```text
Quick Menu > Overrides > Save Content Directory Overrides
```

</details>

#### Notes

**Original overlay by:** [mugwomp93](https://github.com/mugwomp93/720x720_overlays/tree/main/720x720%20overlays/NGPC).

**Shader used:** `~/RetroArch/shaders/shaders_glsl/handheld/lcd3x.glslp`

## [SNK - Neo Geo Pocket Color](https://github.com/Atodarack/720p-square-overlays/tree/main/overlays/ngpc)

![NGPC overlay](https://github.com/user-attachments/assets/a371bd15-6fcc-4e0c-a80f-65a516c9dddf)

<details>
  <summary>Show RetroArch configuration</summary>

#### 1. Apply the overlay

```text
Quick Menu > On-Screen Overlay
    Display Overlay > ON
    Overlay Preset...
      > Navigate to /RetroArch/overlays/720p-square and select ngpc.cfg
    Overlay Opacity > 1.00
```

#### 2. Configure video scaling

```text
Main Menu > Settings > Video > Scaling
    Integer Scale > OFF
    Integer Scale Axis > Any (ignored when Integer Scale is OFF)
    Integer Scale Scaling > Any (ignored when Integer Scale is OFF)
    Aspect Ratio > Custom
        Custom Aspect Ratio (X Position) > 0
        Custom Aspect Ratio (Y Position) > 0
        Custom Aspect Ratio (Width) > 720
        Custom Aspect Ratio (Height) > 684
    Viewport Anchor Bias X > 0.00
    Viewport Anchor Bias Y > 0.00
    Bilinear Filtering > OFF
    Crop Overscan > ON
```

#### 3. Save an override

```text
Quick Menu > Overrides > Save Content Directory Overrides
```

</details>

#### Notes

**Original overlay by:** [mugwomp93](https://github.com/mugwomp93/720x720_overlays/tree/main/720x720%20overlays/NGPC).

**Shader used:** `~/RetroArch/shaders/shaders_glsl/handheld/lcd3x.glslp`

## [SNK - Neo Geo](https://github.com/Atodarack/720p-square-overlays/tree/main/overlays/neogeo)

![NEOGEO overlay](https://github.com/user-attachments/assets/028c9042-659f-4131-9c40-636b46fe48cd)

<details>
  <summary>Show RetroArch configuration</summary>

#### 1. Apply the overlay

```text
Quick Menu > On-Screen Overlay
    Display Overlay > ON
    Overlay Preset...
      > Navigate to /RetroArch/overlays/720p-square and select neogeo.cfg
    Overlay Opacity > 1.00
```

#### 2. Configure video scaling

```text
Main Menu > Settings > Video > Scaling
    Integer Scale > OFF
    Integer Scale Axis > Any (ignored when Integer Scale is OFF)
    Integer Scale Scaling > Any (ignored when Integer Scale is OFF)
    Aspect Ratio > Custom
        Custom Aspect Ratio (X Position) > 0
        Custom Aspect Ratio (Y Position) > 70
        Custom Aspect Ratio (Width) > 720
        Custom Aspect Ratio (Height) > 540
    Viewport Anchor Bias X > 0.00
    Viewport Anchor Bias Y > 0.00
    Bilinear Filtering > OFF
    Crop Overscan > ON
```

#### 3. Save an override

```text
Quick Menu > Overrides > Save Content Directory Overrides
```

</details>

#### Notes

**Shader used:** `~/RetroArch/shaders/shaders_glsl/crt/zfast_crt.glslp`

## [Sony - PlayStation Portable](https://github.com/Atodarack/720p-square-overlays/tree/main/overlays/psp)

![PSP overlay](https://github.com/user-attachments/assets/c261ec5f-ee7a-44c3-93cc-95574d385067)

<details>
  <summary>Show RetroArch configuration</summary>

#### 1. Apply the overlay

```text
Quick Menu > On-Screen Overlay
    Display Overlay > ON
    Overlay Preset...
      > Navigate to /RetroArch/overlays/720p-square and select psp.cfg
    Overlay Opacity > 1.00
```

#### 2. Configure video scaling

```text
Main Menu > Settings > Video > Scaling
    Integer Scale > OFF
    Integer Scale Axis > Any (ignored when Integer Scale is OFF)
    Integer Scale Scaling > Any (ignored when Integer Scale is OFF)
    Aspect Ratio > Custom
        Custom Aspect Ratio (X Position) > 0
        Custom Aspect Ratio (Y Position) > 156
        Custom Aspect Ratio (Width) > 720
        Custom Aspect Ratio (Height) > 408
    Viewport Anchor Bias X > 0.00
    Viewport Anchor Bias Y > 0.00
    Bilinear Filtering > OFF
    Crop Overscan > ON
```

#### 3. Save an override

```text
Quick Menu > Overrides > Save Content Directory Overrides
```

</details>

## [Sony - PlayStation](https://github.com/Atodarack/720p-square-overlays/tree/main/overlays/psx)

![PSX overlay](https://github.com/user-attachments/assets/75f0706d-5d13-462c-a469-73dc047a6657)

<details>
  <summary>Show RetroArch configuration</summary>

#### 1. Apply the overlay

```text
Quick Menu > On-Screen Overlay
    Display Overlay > ON
    Overlay Preset...
      > Navigate to /RetroArch/overlays/720p-square and select psx.cfg
    Overlay Opacity > 1.00
```

#### 2. Configure video scaling

```text
Main Menu > Settings > Video > Scaling
    Integer Scale > OFF
    Integer Scale Axis > Any (ignored when Integer Scale is OFF)
    Integer Scale Scaling > Any (ignored when Integer Scale is OFF)
    Aspect Ratio > Custom
        Custom Aspect Ratio (X Position) > 0
        Custom Aspect Ratio (Y Position) > 70
        Custom Aspect Ratio (Width) > 720
        Custom Aspect Ratio (Height) > 540
    Viewport Anchor Bias X > 0.00
    Viewport Anchor Bias Y > 0.00
    Bilinear Filtering > OFF
    Crop Overscan > ON
```

#### 3. Save an override

```text
Quick Menu > Overrides > Save Content Directory Overrides
```

</details>
