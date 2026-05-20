# Female Character Prompt Skill

[English Version](./README.en.md)    [中文版](./README.md)

A structured Skill for generating high-quality prompts for adult female character images, including 3D CG, anime-style, fantasy, game-character, and vertical poster prompts.

This Skill breaks female character image prompts into a stable and reusable framework:

> Subject Positioning → Composition & Camera → Pose & State → Face & Skin → Hairstyle & Hair Color → Outfit & Materials → Environment & Scene → Lighting & Color → Render Style → Negative Constraints

It is suitable for prompt generation and rewriting workflows in tools such as Jimeng AI, Seedream / Seedance, Midjourney, Stable Diffusion, Kling, Runway, ComfyUI, and other text-to-image or image-to-video systems.

---

## Install

Install with `npx skills`:

```bash
npx skills@latest add hry1729/female-character-prompt-skill
```

Install from a local directory:

```bash
npx skills@latest add ./female-character-prompt-skill
```

List installed Skills:

```bash
npx skills@latest list
```

> If your GitHub username or repository name is different, replace `hry1729/female-character-prompt-skill` with your own repository path.

---

## Features

- Generate high-quality female character prompts with a structured framework
- Suitable for 9:16 vertical character posters, portrait cards, fantasy character visuals, and promotional character images
- Includes field libraries for subject, temperament, composition, camera, pose, hairstyle, outfit, materials, scene, lighting, and style
- Emphasizes adult characters, refined aesthetics, restrained expression, and non-vulgar visual language
- Automatically includes negative prompt constraints to reduce hand errors, limb distortion, face collapse, text artifacts, watermarks, and other common image issues
- Supports expanding a simple theme into a complete high-quality prompt

---

## Framework

This Skill uses the following fixed framework:

```text
Subject Positioning
→ Composition & Camera
→ Pose & State
→ Face & Skin
→ Hairstyle & Hair Color
→ Outfit & Materials
→ Environment & Scene
→ Lighting & Color
→ Render Style
→ Negative Constraints
```

### 1. Subject Positioning

Define the character's identity, theme, age impression, temperament, and overall aesthetic direction.

Example:

```text
An adult Eastern fantasy female character with a gentle, cool, and dreamy temperament, featuring refined anime-inspired beauty and a premium 3D CG character-rendering quality.
```

### 2. Composition & Camera

Define the aspect ratio, character placement, shot range, and camera angle.

Example:

```text
9:16 vertical composition, the character is placed slightly left of center, framed from upper body to thighs, shot from a slightly high-angle perspective, with the subject in sharp focus and the background softly blurred.
```

### 3. Pose & State

Define the character's pose, body direction, emotional state, and overall body language.

Example:

```text
The character leans slightly forward, with relaxed shoulders and neck, a naturally defined waistline, and a calm, soft, elegant posture, conveying a mature, healthy, and restrained feminine presence.
```

### 4. Face & Skin

Define facial features, eyes, skin quality, makeup, and expression details.

Example:

```text
She has refined and soft Eastern fantasy facial features, fair translucent skin, a smooth and delicate skin texture, soft subsurface scattering, natural highlights, and a subtle blush.
```

### 5. Hairstyle & Hair Color

Define hair color, hairstyle structure, hair movement, and highlight details.

Example:

```text
Her hairstyle is medium-length silver-blue hair, soft, lightweight, and layered, with cool blue highlights and translucent rim light. Some strands naturally fall along the sides of her face.
```

### 6. Outfit & Materials

Define the outfit type, fabric material, structural details, accessories, and overall design completeness.

Example:

```text
She wears an off-shoulder light gray-white knitted sweater with visible soft knit texture and a naturally loose neckline. Accessories include a black satin choker, blue crystal earrings, and a butterfly gemstone pendant.
```

### 7. Environment & Scene

Define the location, background elements, and thematic atmosphere.

Example:

```text
The scene is a bright indoor window-side setting with pale curtains, a soft interior background, and a cup of coffee. The background is clean and minimal, creating a warm, quiet, and healing atmosphere.
```

### 8. Lighting & Color

Define the light source direction, light-shadow structure, main color palette, and visual mood.

Example:

```text
Morning sunlight enters from the side and rear, creating soft natural light, rim lighting, and shallow depth-of-field bokeh. The overall palette is light blue, creamy white, and pale lavender.
```

### 9. Render Style

Define the overall rendering quality and visual art style.

Example:

```text
High-quality 3D CG character rendering, semi-realistic anime beauty aesthetics, PBR materials, cinematic lighting, soft subsurface scattering, high-precision hair rendering, realistic fabric texture, shallow depth of field, and ultra-clear details.
```

### 10. Negative Constraints

Exclude low-quality output, visual collapse, vulgarization, and image contamination.

Example:

```text
No watermark, no text, no logo, no low resolution, no face collapse, no asymmetrical eyes, no deformed hands, no extra fingers, no extra limbs, no wrong body proportions, no messy background, no excessive exposure, no vulgar sexualization, no infantilization.
```

---

## Usage

You can call it like this:

```text
Use the female-character-prompt skill to generate a vertical poster prompt for an adult female character with silver-blue hair, a cool temperament, morning light by a window, and a white knitted sweater.
```

You can also provide a shorter theme:

```text
Use the female-character-prompt skill to generate a pink urban night female character.
```

Or ask it to rewrite an existing prompt:

```text
Use the female-character-prompt skill to rewrite the following prompt into a more structured and stable 9:16 female character 3D CG prompt.
```

---

## Example Prompt

```text
Generate a high-precision 3D CG illustration of an adult female character, 9:16 vertical composition, with a premium anime-style 3D CG character-rendering aesthetic. The image should feel clean, soft, dreamy, and refined.

The character is an adult Eastern fantasy female character with a cool, gentle, and dreamy temperament. She is positioned slightly left of center, framed from upper body to thighs, using a three-quarter face angle. The subject is in sharp focus while the background is softly blurred.

She stands in a slight side-facing pose with relaxed shoulders and neck, a naturally defined waistline, and a quiet, elegant posture. The overall impression is mature, healthy, soft, and restrained.

She has refined and soft Eastern fantasy facial features, fair translucent skin, a smooth and delicate skin texture, soft subsurface scattering, natural highlights, and a subtle blush. Her eyes have a blue-purple gradient, with a gentle, cool, and dreamy gaze.

Her hair is long silver-blue hair, soft, lightweight, and layered, with cool blue highlights and translucent rim light. Some strands naturally fall along the sides of her face, and the ends of the hair move slightly in the air.

She wears a white off-shoulder knitted sweater with a soft knit texture and a naturally loose neckline. Accessories include blue crystal earrings, a black satin choker, and a refined gemstone pendant. The overall styling is premium, delicate, and restrained.

The scene is a bright indoor window-side setting with pale curtains, a soft interior background, and a cup of coffee. The background is clean and minimal, creating a warm, quiet, and healing atmosphere.

Morning sunlight enters from the side and rear, creating soft natural light, rim lighting, and shallow depth-of-field bokeh. The overall palette is light blue, creamy white, and pale lavender, with a clear, delicate, and bright visual mood.

High-quality 3D CG character rendering, refined character modeling, PBR materials, delicate skin shading, soft subsurface scattering, high-precision hair rendering, realistic fabric texture, cinematic lighting, shallow depth of field, soft-focus atmosphere, ultra-clear details, premium 3D CG render, cinematic lighting, ultra detailed, masterpiece, best quality.

Negative prompt: no watermark, no text, no logo, no low resolution, no face collapse, no asymmetrical eyes, no deformed hands, no extra fingers, no extra limbs, no wrong body proportions, no stiff pose, no broken outfit, no plastic-like material, no clumped hair, no messy background, no overexposure, no muddy gray colors, no vulgar sexualization, no infantilization.
```

---

## Field Library

### Subject Fields

```text
adult Eastern fantasy female character
adult anime-style fantasy female character
adult fantasy beautiful-girl-style female character
adult high-end game-character-style female character
adult modern fantasy fashion female character
adult dreamy fairy-style female character
```

### Temperament Fields

```text
gentle, cool, dreamy, sweet, elegant, lazy, mysterious, romantic, healing, intellectual, premium, ethereal, confident, light luxury, soft and cute, distant
```

### Composition Fields

```text
9:16 vertical composition
upper-body close-up portrait
upper-body-to-thigh framing
close-up half-body portrait
full-body vertical poster
centered character composition
character slightly left of center
character slightly right of center
subject in sharp focus
softly blurred background
```

### Camera Fields

```text
front-facing eye-level camera
slightly high-angle shot
close portrait lens
low-angle perspective
side-back over-the-shoulder gaze
three-quarter face angle
soft-focus lens
shallow depth of field
cinematic close-up
```

### Pose Fields

```text
quiet sitting pose
slightly leaning forward
slight side-facing standing pose
elegant side-sitting pose
looking back at the camera
kneeling sitting pose
sitting on the edge of a bed
standing by a window
both hands gently resting on a counter
looking down at piano keys
natural body twist
dynamic S-curve standing pose
```

### Face and Skin Fields

```text
refined and soft Eastern fantasy facial features
fair translucent skin
smooth and delicate skin texture
soft subsurface scattering
natural highlights
subtle blush
large clear eyes
blue-purple gradient pupils
pink-purple pupils
ice-blue eyes
cyan-green pupils
gentle bright gaze
cool dreamy gaze
```

### Hair Fields

```text
silver-white long hair
blue-purple gradient long hair
light pink long hair
high-saturation red long hair
light silver-blue medium-length hair
black short hair
twin tails
high ponytail
double bun hairstyle
loose thick braid
short bob haircut
hair moving in the wind
hair ends naturally spread out
hair with translucent rim light
```

### Outfit Fields

```text
white off-shoulder dress
black satin slip dress
light gray-white off-shoulder knitted sweater
pink maid outfit
light blue-purple fantasy gown
dreamy galaxy gown
white satin dress
white high-neck knitted sweater
glossy black leather bodysuit
deep blue swimsuit
high-end fantasy gown
```

### Material Fields

```text
satin reflection
soft knit texture
translucent chiffon
lace trim
ruffled edges
leather highlights
latex reflection
pearl-like stardust
metal ornament reflection
transparent gemstone quality
realistic fabric wrinkles
high-precision hair rendering
delicate skin material
```

### Scene Fields

```text
bright empty indoor space
soft bed
bright window-side scene
pink bedroom
classical music room
dreamy cosmic galaxy space
summer seaside
high-rise urban night view
white European-style room
indoor sofa space
```

### Lighting Fields

```text
soft natural light
window-side lighting
cool blue and warm white mixed lighting
cinematic soft light
backlit rim light
edge highlights
volumetric light
warm golden window light
soft-focus glow
shallow depth-of-field bokeh
```

### Style Fields

```text
premium anime-style 3D CG character rendering
high-quality 3D CG anime character promotional image
semi-realistic anime beauty aesthetics
high-end game character CG
premium fantasy movie poster quality
commercial-grade character illustration quality
PBR materials
cinematic lighting
Octane render quality
Unreal Engine quality
ultra detailed
masterpiece
best quality
```

---

## Safety and Style Notes

This Skill is designed for creating adult female character prompts with a refined, high-quality visual style.

Recommended constraints:

- The character should be clearly adult.
- The visual expression should remain elegant, premium, and restrained.
- Avoid infantilization.
- Avoid explicit or vulgar sexualization.
- Avoid excessive exposure.
- Avoid prompts that focus only on body parts.
- Prefer fashion, character design, portrait, fantasy, editorial, or game-character language.

---

## License

MIT License.
