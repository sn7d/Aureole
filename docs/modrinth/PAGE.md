# Modrinth page kit — Angelic Halo

Everything below is ready to paste into your Modrinth project. Images in the description load straight from the GitHub repo, so you don't need to upload them; the gallery images are optional extras.

---

## 1. Summary (the short line under the title)

```
A cosmetic ring of light around your player: scans with fading trails, crowns, glow, custom text, emblems and nametags. 100% client-side.
```

## 2. Side settings

| Field | Value |
|---|---|
| Icon | `docs/modrinth/icon.png` (512×512) |
| Client side | **Required** |
| Server side | **Unsupported** |
| Categories | **Decoration**, **Utility** |
| Additional tags | Fabric |
| License | **MIT** |
| Source code | `https://github.com/sn7d/Angelic-halo` |
| Issue tracker | `https://github.com/sn7d/Angelic-halo/issues` |

## 3. Description (paste into the Description tab, Markdown)

Copy everything between the two lines.

---8<--- copy from here ---8<---

![Angelic Halo](https://raw.githubusercontent.com/sn7d/Angelic-halo/main/docs/images/hero.png)

## A ring of light that follows you

**Angelic Halo** draws a fully customisable ring of light around your player: sweeping scans with fading trails, crowns of light, orbiting text, projected emblems and your own styled nametag. You tune it all live in an animated menu with a 3D preview.

It is **purely cosmetic and entirely client-side**. It sends nothing to the server, changes no gameplay and uses no mixins. Only you see it.

| | |
|---|---|
| ![Classic ring](https://raw.githubusercontent.com/sn7d/Angelic-halo/main/docs/images/classic.png) | ![Scan with trail](https://raw.githubusercontent.com/sn7d/Angelic-halo/main/docs/images/scan.png) |
| **Classic**: a thin soft-red ring at your feet, drawn through walls. | **Scan**: sweeps from feet to head and leaves a fading, recolourable trail. |

### ✦ Features

- **10 ring styles**: Line, Glow Line, Aura, Disc, Dashed, Orbs, Sonar, Crown, Galaxy and Lightning.
- **8 motions**: Static, Scan, Breathe, Halo (floats above your head), Ripple, Wave, Gyro and Heartbeat.
- **Scan trail**: a smooth fading smear or echo rings that follow the scan, with their own colours.
- **11 colour effects** for every layer: Solid, Gradient, Rainbow, Chroma, Pulse, Height, Comet, Health, Sparkle, Aurora and Fire.
- **Glow**: soft bloom on everything, adjustable per layer.
- **Custom text**: your words orbiting the ring, engraved in the floor or floating as a banner.
- **Emblems**: project an image under you, above your head or on your back. Six built-ins, or **drop in your own PNGs**.
- **Nametags**: your own styled name tag with formatting codes, a title line, colour effects, icons and a symbols picker.
- **Extras**: rising embers, helix orbs, jump rings, speed-reactive glow and an optional damage flash.
- **15 presets**, **share codes** and a **saved-looks library**.

![Text and emblems](https://raw.githubusercontent.com/sn7d/Angelic-halo/main/docs/images/text.png)

![Floor emblem](https://raw.githubusercontent.com/sn7d/Angelic-halo/main/docs/images/emblem.png)

### ✦ A menu you'll actually enjoy

A custom, animated settings window with smooth sliders, switches and colour pickers. A **live 3D projector** on the right shows your exact settings on a mannequin as you change them (drag to orbit, scroll to zoom).

Open it with **H**, from the **halo button next to Friends** on the Esc menu, with `/angelichalo`, or from Mod Menu.

![Settings menu](https://raw.githubusercontent.com/sn7d/Angelic-halo/main/docs/images/menu.png)

### ✦ Nametags

Rename yourself (only in your own view) with colours, `&` formatting codes, a title line, icons and over 100 symbols such as ★ ♛ ⚔ ❤ ☾ ⚡ ✦. Everything is previewed live in the menu.

![Nametag](https://raw.githubusercontent.com/sn7d/Angelic-halo/main/docs/images/gallery/feature_nametag.jpg)

### ✦ Works with shaders

Angelic Halo registers its rendering with **Iris** through Iris's official API, so it stays visible and keeps its colours with shaderpacks. It is tested with Complementary (Reimagined & Unbound), BSL, Photon, Solas, Bliss, MakeUp Ultra Fast, Sildur's Vibrant and Rethinking Voxels.

![Shader comparison](https://raw.githubusercontent.com/sn7d/Angelic-halo/main/docs/images/shaders.png)

### ✦ Tested alongside

Sodium, Iris, Lithium, ImmediatelyFast, EntityCulling, FerriteCore, Skyblocker, Mod Menu, Zoomify and Essential. Every release is tested automatically inside a real game.

### ✦ Safe on servers

- Client-side only: it does nothing on a server.
- No packets, no chat or commands sent. `/angelichalo` runs locally.
- No mixins and no game changes, just extra drawing on your screen.

It's a cosmetic, like a resource pack, that only you can see. As always, each server's own rules have the final word.

### ✦ Requirements

- Minecraft **26.2** with **Fabric Loader 0.20.1+**
- [Fabric API](https://modrinth.com/mod/fabric-api) (required)
- [Mod Menu](https://modrinth.com/mod/modmenu) (optional)

---

Source code and full documentation: [GitHub](https://github.com/sn7d/Angelic-halo)

---8<--- copy to here ---8<---

## 4. Gallery (optional, Gallery tab → Upload)

Upload these files from the repo (`docs/images/`). Mark the first one as **Featured**.

| File | Title | Description |
|---|---|---|
| `hero.png` | Seraph | A golden crown of light floating above your head, with drifting motes. |
| `classic.png` | Classic | The default thin red ring, drawn right through the walls. |
| `scan.png` | Scan + trail | The ring sweeps up your body and leaves a rainbow trail. |
| `text.png` | Orbiting text | Your own words wrapping around the ring. |
| `emblem.png` | Floor emblem | A golden sigil projected on the ground around you. |
| `menu.png` | The menu | Animated settings window with a live 3D preview. |
| `menu_colours.png` | Colour studio | Hue and shade pickers, palette and effects for every layer. |
| `shaders.png` | With shaders | The same effect without shaders and with nine popular shaderpacks. |
| `gallery/feature_nametag.jpg` | Nametags | Your own styled nametag with title, icons and symbols. |
| `gallery/preset_inferno.jpg` | Inferno | A flickering fire curtain with rising embers. |
| `gallery/style_galaxy.jpg` | Galaxy | Spiral arms of stars turning at your feet. |
| `gallery/style_crown.jpg` | Crown | Shimmering spikes of light with glowing tips. |

## 5. First version changelog (used by the "Publish to Modrinth" workflow)

```
First public release.

- 10 ring styles, 8 motions and 11 colour effects, with a scan trail
- Glow on every layer, custom text, emblems (plus your own PNGs)
- Nametags: your own styled name with codes, title, icons and symbols
- Animated menu with a live 3D preview, presets, share codes and saved looks
- Shader support (Iris) and tested with popular Skyblock and performance mods
```
