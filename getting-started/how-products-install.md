---
icon: file-moved
label: How Products Install
order: 97
---

# How KH Products Install

Kyler Holland packs use different file types depending on the product. Use this guide to find the right install path — then open your product's help page for pack-specific details.

!!!tip Just downloaded?
If you haven't extracted your order yet, start with [How to download your products](index.md#how-to-download-your-products).
!!!

## Quick picker

| If your download includes… | Install method | Common products |
|----------------------------|----------------|-----------------|
| `.prfpset` | Import Presets in Premiere | Transitions, text effects, audio presets, many LUT packs |
| `.prproj` | Drag project into Project panel | Ultimate Effects Pack, Seamless Flow |
| `.mogrt` | Essential Graphics panel | Motion graphics, overlays, auto-resize templates |
| `.cube` | Lumetri Color or any LUT browser | Film LUTs, free LUTs, cinematic LUT packs |
| Video / audio files | Import into Project panel | Light leaks, sound effects |
| `.xmp` / `.dng` | Lightroom import | BLACK 2.0 preset pack |
| Extension / app | Partner install flow | Brevidy |

---

## `.prfpset` — Premiere preset packs

Most KH **transition**, **text**, **subtitle**, and **audio** packs use a `.prfpset` preset file.

### Steps

1. **Extract** the `.zip` from your order (do not import the zip itself).
2. Open **Adobe Premiere Pro** and your project.
3. Open the **Effects** panel.
4. Right-click **Presets** → **Import Presets**.
5. Select the `.prfpset` file from the extracted folder.
6. Expand **Presets** — your pack appears as a new bin. Drag presets onto clips or edit points.

### Example products

- [Speed Zoom Transitions](../products/speed-zoom-transitions/index.md)
- [Shake Transitions](../products/shake-transitions-preset-pack/index.md)
- [200+ Text Effects](../products/200-text-effects/index.md)
- [Seamless Subtitles](../products/seamless-subtitles-v2/index.md)
- [Audio Effects](../products/audio-effects/index.md)

!!!tip Preset bin missing?
Restart Premiere after import. See [Troubleshooting — preset bin not showing](../support/troubleshooting.md#installation--import).
!!!

---

## `.prproj` — Premiere project imports

Large transition libraries ship as a **Premiere Pro project** with bins of ready-made transitions — not a preset file.

### Steps

1. **Extract** the full `.zip` and keep all folders together (especially any **Do not delete** folder).
2. Open Premiere Pro and your editing project.
3. From Finder/Explorer, **drag the `.prproj` file** into your **Project** panel.
4. When prompted, confirm import and browse transition bins inside the imported project.
5. Drag transitions from those bins onto your timeline.

### Pick the right version folder

Many packs include separate projects for different Premiere versions:

- **CC 2020 Update 2** (and newer) — use this folder on current Premiere builds.
- **CC 2018–2019** — use if you're on an older Premiere version.

### Example products

- [The Ultimate Effects Pack](../products/the-ultimate-effects-pack/index.md)
- [Seamless Flow Transition Pack](../products/seamless-flow-transition-pack/index.md)

!!!warning Keep linked media intact
Do not move or delete the **Do not delete** folder (or other linked asset folders) separately from the project file. That causes **media offline** errors. Move the **entire extracted pack** if you need to relocate it.
!!!

---

## MOGRT — Motion Graphics templates

**MOGRT** files install through the **Essential Graphics** panel. Used for motion graphics, overlays, and customizable templates.

### Steps

1. **Extract** the `.zip`.
2. In Premiere, open **Window → Essential Graphics**.
3. Either:
   - **Drag** the `.mogrt` file into the Essential Graphics panel, or
   - Click **Install Motion Graphics Template** (plus icon) and select the file.
4. Find the template under **Local Templates**.
5. Drag it onto your timeline and edit text, colors, and controls in the **Edit** tab.

### Example products

- [Auto Resize Text Motion Graphic](../products/auto-resize-text-motion-graphic/index.md)
- [100 FREE Textures](../products/100-free-textures/index.md)
- [10 Glitch Overlays](../products/10-glitch-overlays/index.md)
- [10 Texture Overlays](../products/10-texture-overlays/index.md)
- [Dynamic Slide Text Motion Graphic](../products/dynamic-slide-text-motion-graphic/index.md)
- [48 Text Slide Transitions](../products/48-text-slide-transitions/index.md)

---

## `.cube` LUTs — Color grading

LUT packs include **`.cube`** files. Many also include a `.prfpset` for one-click use in Premiere.

### Option A — Import preset (Premiere)

1. Extract the `.zip`.
2. **Effects → Presets** → right-click → **Import Presets** → select the `.prfpset`.
3. Drag a LUT preset onto your clip.

### Option B — Lumetri Color (Premiere)

1. Select your clip → open **Lumetri Color**.
2. **Creative** tab → **Look** → **Browse**.
3. Choose a `.cube` file and adjust **Intensity**.

### Option C — Other apps

Import `.cube` files into **DaVinci Resolve**, **Final Cut Pro**, **Photoshop**, or any app with a standard LUT workflow — no Premiere required.

### Example products

- [10 FREE Luts](../products/10-free-luts/index.md)
- [10 Cinematic Luts](../products/10-cinematic-luts/index.md)
- [Film Luts](../products/film-luts/index.md)
- [Sam Kolder Lut Pack](../products/sam-kolder-lut-pack/index.md)
- [Dark Green Lut](../products/dark-green-lut/index.md)

---

## Video & audio files — Media libraries

Some products are folders of **video overlays** or **sound effects** — no preset import step.

### Steps

1. **Extract** the `.zip` to a permanent location (large libraries need plenty of disk space).
2. Keep the **folder structure** — categories stay organized that way.
3. In Premiere: **File → Import** or use the **Media Browser** to add files to a bin.
4. Drag clips to video or audio tracks on the timeline.

Works in any editor that supports the file format (`.wav`, `.mp3`, `.mov`, `.mp4`, etc.).

### Example products

- [1,300 Cinematic Sound Effects](../products/1300-cinematic-sound-effects/index.md)
- [14 FREE 4K Light Leaks](../products/14-free-4k-light-leaks/index.md)

---

## Lightroom — `.xmp` and `.dng` presets

[Lightroom Preset: BLACK 2.0](../products/lightroom-preset-black-2-0/index.md) uses different files per platform:

| Format | Platform |
|--------|----------|
| **`.xmp`** | Lightroom desktop and **Android** |
| **`.dng`** | **iPhone/iPad** (import into Lightroom mobile, then save as preset) |

See the BLACK 2.0 help page for step-by-step install on [iPhone](https://www.youtube.com/watch?v=5X3lyo-XgCc), [Android](https://www.youtube.com/watch?v=GGvcSqN_oxM), and [desktop](https://www.youtube.com/watch?v=04pj4V1CRws).

---

## Extensions & partner products

### Brevidy

[Brevidy](../products/brevidy/index.md) is a Premiere Pro **extension** (captions, AutoCut, Brevidy Media). Install and update through Brevidy's extension workflow after purchase — not via Import Presets or `.zip` drag-in.

---

## Mixed packs

Some downloads include **more than one file type** (for example `.prfpset` plus shape assets, or LUT cubes plus a preset file). Always read the **What's included** section on your product's help page before deleting anything from the extracted folder.

---

## Need help?

- [Troubleshooting & FAQ](../support/troubleshooting.md)
- [Tutorial index](../support/tutorial-index.md) — video walkthroughs for most packs
- [Contact support](../support/contact.md)
