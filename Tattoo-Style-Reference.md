# Tattoo Style Reference - Skull & Snake Engraving Style

This file defines the reusable artistic style DNA from the reference image `image_8c2630.png` (skull with coiled snake). Use this as a style anchor for generating completely different subjects with identical tattoo styling.

---

## 1. Core Style DNA (Copy/Paste Suffix)

Use this block at the end of any prompt to force the same aesthetic:

```
STYLE: traditional bold tattoo flash engraving, high contrast black and white line art, thick bold outer contour lines with thinner crisp inner detail lines, pure black ink on stark white background, no gray wash, no color, no gradients, shading done only with cross-hatching and stippling dot-work, vector-like clean closed outlines, intricate detailed patterning, highly detailed but flat graphic illustration, print-ready tattoo stencil
```

### Technical Breakdown

- **Medium & Color:** Pure monochrome. 100% black ink on stark white background. High contrast, no color, no gray wash.
- **Line Style & Stroke:** Bold, clean, confident outlines. Thick outer contour (weight: 3-4px equivalent), thin inner detail lines (1px). No sketchy, broken, or fuzzy lines. Closed, vector-like contours.
- **Shading:** NO soft shading, airbrush, or gradients. Only traditional engraving techniques: cross-hatching in cavities, stipple dot-work texture, dense parallel lines, solid black fill only for deep mouth interiors.
- **Texture:** Hyper-detailed but flat graphic. Individual scales drawn as distinct U-shapes with inner highlight lines. Bone texture suggested with short crack lines and fine hatching.
- **Composition:** Centered, front-facing, symmetrical but dynamic, isolated subject, tattoo flash stencil ready.
- **Vibe:** Old-school biker / metal / traditional American flash, illustrative, not photorealistic.

---

## 2. Midjourney v6 / v7 - Style Reference Method (Most Accurate)

Upload `image_8c2630.png` to Midjourney and copy its URL.

### Master Formula

```
[YOUR SUBJECT HERE] --sref [URL_OF_YOUR_SKULL_IMAGE] --sw 800 --style raw --ar 1:1 --stylize 200

black and white bold tattoo flash, thick outer lines, intricate engraving shading, pure ink on white background
```

### Parameters Explained

- `--sref [URL]`: Uses the skull/snake as a visual style anchor
- `--sw 800` to `1000`: Very tight style match. Use 300-500 for looser interpretation
- `--style raw`: Prevents Midjourney from adding soft shading
- `--no grayscale, color, watercolor, photorealistic, 3d render, soft shading, blurry lines, sketch`: Add to force monochrome

### Example Prompts - Same Style, Different Subjects

```md
# Lion
fierce lion head roaring, mane flowing --sref [URL] --sw 800 --style raw --ar 1:1
black and white bold tattoo flash, thick outer lines, intricate engraving shading, pure ink on white background

# Dagger & Rose
traditional dagger piercing a rose with thorns --sref [URL] --sw 800 --style raw --ar 1:1
black and white tattoo linework, bold outlines, detailed cross-hatching, monochrome stencil

# Eagle
bald eagle with wings spread, talons out --sref [URL] --sw 800 --style raw --ar 1:1 --stylize 200
same style: bold tattoo flash engraving, crisp line art, high contrast black and white, dotwork shading

# Wolf
howling wolf head with forest --sref [URL] --sw 800 --style raw
black and white bold tattoo flash engraving, thick outer contour, thin inner detail

# Panther Crawling
crawling panther --sref [URL] --sw 900 --style raw --ar 3:2
traditional tattoo flash, high contrast black and white line art, vector-like clean lines, cross-hatching

# Dragon
coiled dragon, traditional japanese inspired but in western engraving style --sref [URL] --sw 800
monochrome tattoo stencil, bold outlines, detailed scale pattern, pure black on white
```

---

## 3. For Flux / SDXL / Leonardo / Firefly (Text-Only, No sref)

### Positive Prompt

```
bold traditional tattoo flash, black and white line art illustration, thick bold outline, thin detailed inner lines, engraving style, cross-hatching and stippling shading, pure black ink on white background, vector stencil, high contrast, intricate detailed, print-ready tattoo pattern, isolated on white
```

### Negative Prompt

```
color, colour, gray wash, grayscale gradient, watercolor, photorealistic, 3d, blurry, soft shading, airbrush, sketchy lines, painting, faded, low contrast
```

### Combined Prompt Template

```
[YOUR SUBJECT], bold traditional tattoo flash, black and white line art illustration, thick bold outline, thin detailed inner lines, engraving style, cross-hatching and stippling shading, pure black ink on white background, vector stencil, high contrast, intricate detailed
```

---

## 4. Importable JSON Style Preset

```json
{
  "style_name": "Skull Snake Bold Engraving",
  "style_prompt": "traditional bold tattoo flash engraving, high contrast black and white line art, thick bold outer contour lines with thinner crisp inner detail lines, pure black ink on stark white background, no gray wash, no color, no gradients, shading done only with cross-hatching and stippling dot-work, vector-like clean closed outlines, intricate detailed patterning, highly detailed but flat graphic illustration, print-ready tattoo stencil",
  "negative_prompt": "color, gray wash, gradient, watercolor, photorealistic, 3d render, soft shading, blurry lines, sketch, painting",
  "midjourney_params": "--style raw --ar 1:1 --stylize 200 --sw 800 --no color, watercolor, photorealistic, soft shading",
  "reference_image": "image_8c2630.png"
}
```
