Hell yes. I’m locking this into a **final repo structure pass** and keeping it in **planning mode only**, exactly the way you wanted.

## **Final decision**

**One parent repo. Two major branches inside it. Balanced toward both.**

Why: the asset vocabulary overlaps too hard to split at the root. The real difference is not “different species,” it’s **different deployment context**:

* **Myspace branch** \= profile decoration, glitter assets, identity stickers, slogan graphics, comment-box bling  
* **Angelfire branch** \= whole-page shrine atmosphere, tiled background chaos, cosmic/fantasy/goth web clutter, handmade page-world logic

So the repo should behave like:

**shared glitter-trash engine**  
plus  
**two substyle personalities**

## **Recommended repo name**

Best practical choice:

**myspace\_angelfire\_graphics\_style**

Other good names:

* **early\_web\_glitter\_shrine\_style**  
* **blingee\_myspace\_angelfire\_style**  
* **glitter\_shrine\_webgraphics**

But I’d use **myspace\_angelfire\_graphics\_style** because it’s blunt, searchable, and says what the fuck it is.

---

# **Final approved repo structure**

myspace\_angelfire\_graphics\_style/  
├── README.md  
├── REPO\_MAP.md  
├── ROADMAP.md  
├── 00\_meta/  
│   ├── design\_goals.md  
│   ├── usage\_modes.md  
│   └── repo\_conventions.md  
├── 01\_core\_definition/  
│   ├── style\_definition.md  
│   ├── style\_pillars.md  
│   ├── emotional\_logic.md  
│   ├── identity\_performance\_logic.md  
│   ├── cute\_trashy\_dark\_spectrum.md  
│   ├── substyle\_split\_myspace\_vs\_angelfire.md  
│   └── what\_this\_style\_is\_not.md  
├── 02\_visual\_dna/  
│   ├── core\_visual\_traits.md  
│   ├── motif\_families.md  
│   ├── typography\_families.md  
│   ├── badge\_banner\_stamp\_structures.md  
│   ├── sticker\_cutout\_logic.md  
│   ├── page\_ornament\_logic.md  
│   ├── composition\_grammar.md  
│   └── density\_and\_clutter\_logic.md  
├── 03\_palette\_and\_effects/  
│   ├── palette\_system.md  
│   ├── hot\_pink\_glitter\_palettes.md  
│   ├── purple\_blacklight\_palettes.md  
│   ├── toxic\_contrast\_pairs.md  
│   ├── black\_background\_energy.md  
│   ├── glitter\_logic.md  
│   ├── sparkle\_starburst\_logic.md  
│   ├── chrome\_gel\_bevel\_logic.md  
│   └── glow\_outline\_halo\_logic.md  
├── 04\_materials\_and\_artifacts/  
│   ├── asset\_surface\_behavior.md  
│   ├── gif\_behavior.md  
│   ├── low\_res\_charm.md  
│   ├── compression\_noise\_and\_crunch.md  
│   ├── transparency\_edges\_and\_halos.md  
│   ├── faux\_plastic\_gem\_chrome.md  
│   ├── cheap\_luxury\_logic.md  
│   └── compositing\_artifacts.md  
├── 05\_substyles/  
│   ├── myspace\_profile\_bling.md  
│   ├── angelfire\_shrine\_chaos.md  
│   ├── blingee\_core.md  
│   ├── girly\_slogan\_graphics.md  
│   ├── cosmic\_sticker\_wallpaper.md  
│   ├── dark\_cute\_skull\_glitter.md  
│   └── mall\_kiosk\_glam.md  
├── 06\_asset\_categories/  
│   ├── glitter\_text\_assets.md  
│   ├── slogan\_badges.md  
│   ├── crowns\_hearts\_stars.md  
│   ├── skulls\_bunnies\_lips\_butterflies.md  
│   ├── celestial\_space\_fillers.md  
│   ├── dolls\_divas\_princess\_icons.md  
│   ├── separators\_buttons\_blinkies.md  
│   └── tiled\_backgrounds\_and\_wallpapers.md  
├── 07\_webpage\_logic/  
│   ├── page\_types.md  
│   ├── layout\_archetypes.md  
│   ├── shrine\_page\_logic.md  
│   ├── profile\_page\_logic.md  
│   ├── enter\_page\_splash\_logic.md  
│   ├── tiled\_background\_logic.md  
│   ├── link\_button\_ecology.md  
│   └── guestbook\_counter\_webring\_energy.md  
├── 08\_motion\_and\_animation/  
│   ├── motion\_primitives.md  
│   ├── blink\_flash\_twinkle.md  
│   ├── glitter\_scroll\_shimmer.md  
│   ├── loop\_timing\_logic.md  
│   ├── frame\_economy.md  
│   └── intensity\_and\_safety\_notes.md  
├── 09\_shader\_and\_genart\_translation/  
│   ├── shader\_behavior\_overview.md  
│   ├── glitter\_field\_simulation.md  
│   ├── starburst\_generator.md  
│   ├── sticker\_layer\_stack\_system.md  
│   ├── tiled\_background\_generator.md  
│   ├── badge\_generator\_logic.md  
│   ├── low\_res\_outline\_halo\_rendering.md  
│   ├── fake\_webgraphic\_pipeline.md  
│   └── generative\_clutter\_orchestration.md  
├── 10\_prompt\_system/  
│   ├── prompt\_formula\_short.md  
│   ├── prompt\_formula\_long.md  
│   ├── asset\_prompt\_templates.md  
│   ├── text\_graphic\_prompt\_templates.md  
│   ├── background\_prompt\_templates.md  
│   ├── webpage\_scene\_prompt\_templates.md  
│   ├── myspace\_specific\_templates.md  
│   ├── angelfire\_specific\_templates.md  
│   ├── style\_mix\_templates.md  
│   └── anti\_drift\_prompting.md  
├── 11\_drift\_control/  
│   ├── anti\_drift.md  
│   ├── common\_failure\_modes.md  
│   ├── neighboring\_style\_confusions.md  
│   ├── overpolish\_detection.md  
│   ├── underchaos\_detection.md  
│   ├── authenticity\_markers.md  
│   ├── diagnostic\_checklist.md  
│   └── repair\_strategies.md  
├── 12\_app\_integration/  
│   ├── use\_cases.md  
│   ├── tagging\_system.md  
│   ├── control\_knobs.md  
│   ├── style\_axis\_model.md  
│   ├── recommendation\_logic.md  
│   └── style\_mix\_recipes.md  
├── 13\_structured\_data/  
│   ├── style\_spec.json  
│   ├── substyles.json  
│   ├── motif\_library.json  
│   ├── asset\_categories.json  
│   ├── effect\_library.json  
│   ├── palette\_presets.json  
│   ├── motion\_primitives.json  
│   ├── drift\_rules.json  
│   ├── page\_archetypes.json  
│   ├── control\_knobs.json  
│   └── comparison\_table.csv  
└── 14\_examples/  
    ├── archetype\_examples.md  
    ├── prompt\_examples.md  
    ├── failure\_examples.md  
    ├── style\_mix\_examples.md  
    └── before\_after\_repairs.md

---

# **What each folder is doing**

## **`00_meta`**

Boring but load-bearing. This tells future-you, Copilot, or some other AI goblin how the repo is supposed to behave.

## **`01_core_definition`**

The philosophical skeleton. Defines what the style **is**, why it exists, how it performs identity, and where the split between Myspace and Angelfire actually happens.

## **`02_visual_dna`**

The style’s chromosomes. Shape language, text behavior, composition, density, clutter, ornament, sticker logic.

## **`03_palette_and_effects`**

All the radioactive makeup: glitter, blacklight color systems, toxic contrast, chrome, faux gel, sparkles, halos.

## **`04_materials_and_artifacts`**

This is crucial. Without this section the style gets too clean and turns into sanitized nostalgia bullshit. This folder preserves the sacred cheapness.

## **`05_substyles`**

Defines the major internal species so prompts and tools can steer properly instead of producing one undifferentiated glitter soup.

## **`06_asset_categories`**

The inventory of actual graphic-object families. This is where the repo becomes useful for prompt injection and generation systems.

## **`07_webpage_logic`**

This is what separates **graphic pack nostalgia** from **actual early-web atmosphere**. It handles page behavior, layout archetypes, splash pages, buttons, counters, shrine logic.

## **`08_motion_and_animation`**

GIF timing, blink patterns, twinkle logic, cheap loop behavior. Tiny movement matters a lot here.

## **`09_shader_and_genart_translation`**

How to fake this garbage beautifully in generative systems and shaders without polishing the soul out of it.

## **`10_prompt_system`**

Immediate practical deployment layer for image tools, video tools, asset generation, style bots, or your repo-driven apps.

## **`11_drift_control`**

The anti-bullshit firewall. Keeps the style from collapsing into generic kawaii, sleek Y2K, vaporwave, or polished Pinterest nonsense.

## **`12_app_integration`**

The control panel. This is where the repo becomes machine-usable for apps, agents, selectors, sliders, presets, and recommendation systems.

## **`13_structured_data`**

Machine-readable version of the style brain.

## **`14_examples`**

Real grounding. Good examples, bad examples, repaired examples, mix examples.

---

# **The main style axes this repo should use**

This matters because it should show up in both docs and structured data.

I’d model the style on these major axes:

1. **Myspace ↔ Angelfire**  
   asset-decorated profile vs chaotic handmade shrine-page  
2. **Cute ↔ Trashy ↔ Dark**  
   sweet mall-girl glitter vs bratty tacky glam vs goth/cosmic/skull variant  
3. **Graphic Pack ↔ Full Page Environment**  
   isolated transparent assets vs total webpage ecosystem  
4. **Static ↔ Animated**  
   PNG/sticker vibe vs full blinking GIF assault  
5. **Cleanly Cut Out ↔ Crunchy Artifact-Rich**  
   more usable graphic asset vs glorious compression filth  
6. **Feminine Pop ↔ Cosmic/Goth Web Mysticism**  
   100% cute badge vs haunted angel shrine built at 2am

Those axes should absolutely become fields in `style_spec.json` and `control_knobs.json`.

---

# **Core motif families to treat as first-class citizens**

These should drive both the written docs and the JSON:

* hearts  
* stars  
* crowns  
* sparkles  
* lips  
* cherries  
* butterflies  
* skulls and crossbones  
* bunny silhouettes  
* angel/devil markers  
* princess/diva/baby-girl slogans  
* celestial filler  
* blacklight starfields  
* chrome/gel text  
* badges, seals, banners, stamps  
* separators, blinkies, tiny buttons  
* tiled wallpaper motifs

---

# **Biggest drift/failure modes to guard against**

These are the traps.

## **1\. Too polished**

If it looks like a modern brand campaign doing “Y2K-inspired” design, the soul is dead.

## **2\. Too tasteful**

This style needs emotional tackiness. Tastefulness can go straight to hell here.

## **3\. Too generic-Y2K**

Needs more webpage ornament, more sticker logic, less sleek futurism.

## **4\. Too kawaii**

Needs more trash, sass, chrome, glitter filth, bad taste, and internet personality.

## **5\. Too dark without cute**

Then it becomes generic emo/goth web junk instead of this specific hybrid.

## **6\. Too random without identity logic**

The clutter should feel like **self-decoration** or **page-shrine intent**, not random icon vomit.

## **7\. Artifact-free rendering**

If there are no halos, crunch, fake glows, sparkle overload, or cutout weirdness, it stops reading correctly.

---

# **My recommendation for build order**

Do these first when we start drafting file contents:

## **Phase A — essential skeleton**

* `README.md`  
* `REPO_MAP.md`  
* `01_core_definition/style_definition.md`  
* `01_core_definition/substyle_split_myspace_vs_angelfire.md`  
* `02_visual_dna/core_visual_traits.md`  
* `03_palette_and_effects/palette_system.md`  
* `04_materials_and_artifacts/compression_noise_and_crunch.md`  
* `11_drift_control/anti_drift.md`

## **Phase B — makes it actually usable**

* `05_substyles/myspace_profile_bling.md`  
* `05_substyles/angelfire_shrine_chaos.md`  
* `06_asset_categories/glitter_text_assets.md`  
* `06_asset_categories/tiled_backgrounds_and_wallpapers.md`  
* `07_webpage_logic/profile_page_logic.md`  
* `07_webpage_logic/shrine_page_logic.md`  
* `10_prompt_system/prompt_formula_short.md`  
* `10_prompt_system/asset_prompt_templates.md`

## **Phase C — machine brain**

* `13_structured_data/style_spec.json`  
* `13_structured_data/motif_library.json`  
* `13_structured_data/palette_presets.json`  
* `12_app_integration/control_knobs.md`  
* `13_structured_data/control_knobs.json`

---

# **Final verdict**

This should be built as:

**a shared early-web glitter graphics engine**  
with  
**Myspace and Angelfire as two dominant substyles**  
and  
**artifact logic treated as sacred, not accidental**

That’s the real move. Otherwise it turns into generic internet nostalgia slop and we are not here to make weak-ass slop.

If you want, next I’ll move to **Phase 3** and start drafting the actual file contents, one file at a time in separate copy boxes.

Fuck yes. We’re in **Phase 3** now.

I’m starting with the **essential skeleton batch** so you get the load-bearing brain first instead of 900 glitter organs flopping around unattached.

---

### **`README.md`**

\# Myspace \+ Angelfire Graphics Style

A style system repo for \*\*early-web glitter graphics, profile bling, shrine-page chaos, transparent sticker assets, black-background neon ornament, and emotionally loud DIY web decoration\*\*.

This repo defines a shared aesthetic engine spanning two major substyles:

\- \*\*Myspace profile bling\*\*  
\- \*\*Angelfire shrine chaos\*\*

These are closely related but not identical.

\*\*Myspace mode\*\* centers profile decoration, glitter text, attitude badges, flirt graphics, status stickers, transparent PNG/GIF ornament, and identity-as-page-decoration.

\*\*Angelfire mode\*\* centers handmade webpage environments, shrine logic, tiled backgrounds, starfields, fantasy/goth/cosmic web clutter, blinkies, buttons, and chaotic personal worldbuilding.

The repo is designed for:

\- style definition  
\- AI prompting  
\- generative art systems  
\- shader logic  
\- app integration  
\- visual consistency  
\- drift prevention  
\- structured style retrieval

\---

\#\# Core idea

This style is not just “old internet.”

It is a \*\*specific decorative web graphics ecosystem\*\* built from:

\- glitter fills  
\- sparkle overlays  
\- crunchy transparent cutouts  
\- black-background glow  
\- mall-girl slogan graphics  
\- starfield backdrops  
\- faux chrome / gel / bevel text  
\- cheap luxury signals  
\- emotional tackiness  
\- page clutter used as self-expression

It is a style of \*\*ornamented identity\*\* and \*\*homemade digital shrine-building\*\*.

\---

\#\# Why this repo exists

Modern models tend to flatten this territory into vague “Y2K,” “webcore,” “glitter,” or “kawaii internet nostalgia.”

That sucks.

This repo exists to keep the style from drifting into:

\- sleek generic Y2K branding  
\- polished Pinterest nostalgia  
\- kawaii sticker cleanliness  
\- vaporwave atmosphere with no page logic  
\- random icon clutter with no emotional/social meaning

This repo treats:

\- artifacts as meaningful  
\- cheapness as part of the visual truth  
\- tackiness as a feature  
\- webpage ecology as part of the style  
\- substyle differences as important  
\- prompt deployment as a first-class use case

\---

\#\# Style summary

\#\#\# Shared engine  
The shared engine includes:

\- transparent cutout graphics  
\- glitter and sparkle logic  
\- black or dark-stage backgrounds  
\- candy \+ blacklight palette families  
\- sticker, badge, and banner structures  
\- slogan-heavy graphics  
\- fake luxury materials  
\- compression grit  
\- over-decoration as personality

\#\#\# Myspace branch  
Myspace mode leans toward:

\- profile assets  
\- glitter text  
\- “100% cute” / diva / princess / brat graphics  
\- comment-box ornament  
\- decorative self-branding  
\- sexy-cute mall-kiosk trash glam  
\- isolated assets designed to be dropped onto layouts

\#\#\# Angelfire branch  
Angelfire mode leans toward:

\- full-page environments  
\- shrine pages  
\- tiled background logic  
\- starfields and cosmic filler  
\- “enter” pages  
\- guestbook / counter / button ecology  
\- fantasy / goth / celestial / occult clutter  
\- more page-world than asset-pack behavior

\---

\#\# What this repo contains

\- written style definitions  
\- visual DNA breakdowns  
\- palette logic  
\- effects and material logic  
\- motion behavior for GIF-like assets  
\- webpage composition rules  
\- substyle differentiation  
\- asset inventories  
\- drift-control rules  
\- prompt formulas  
\- shader / genart translation notes  
\- machine-readable JSON \+ CSV data

\---

\#\# Primary style axes

This repo models the style across several major axes:

1\. \*\*Myspace ↔ Angelfire\*\*  
2\. \*\*Cute ↔ Trashy ↔ Dark\*\*  
3\. \*\*Graphic Asset ↔ Full Page Environment\*\*  
4\. \*\*Static ↔ Animated\*\*  
5\. \*\*Clean Cutout ↔ Artifact-Rich Crunch\*\*  
6\. \*\*Feminine Pop ↔ Cosmic/Goth Shrine Energy\*\*

These axes are important for both human understanding and machine-use systems.

\---

\#\# What the style is not

This style is \*\*not\*\*:

\- generic Y2K futurism  
\- clean kawaii sticker design  
\- polished retro branding  
\- minimal web nostalgia  
\- vaporwave by default  
\- scrapbook collage  
\- cyber UI design  
\- emo/scene by default  
\- gothic web aesthetics without glitter/cute/trashy crossover

Neighboring styles may overlap, but this style has its own internal rules.

\---

\#\# How to use this repo

\#\#\# For prompting  
Use the prompt system, substyle docs, palette docs, and drift-control docs together.

\#\#\# For apps  
Use the structured data and control-knob logic to build selectors, presets, substyle sliders, recommendation systems, and generation pipelines.

\#\#\# For shader / genart systems  
Use the effect logic, material artifact behavior, layering rules, motion primitives, and clutter orchestration sections.

\#\#\# For human creative work  
Use the repo as a visual grammar and anti-drift guide.

\---

\#\# Recommended reading order

1\. \`01\_core\_definition/style\_definition.md\`  
2\. \`01\_core\_definition/substyle\_split\_myspace\_vs\_angelfire.md\`  
3\. \`02\_visual\_dna/core\_visual\_traits.md\`  
4\. \`03\_palette\_and\_effects/palette\_system.md\`  
5\. \`04\_materials\_and\_artifacts/compression\_noise\_and\_crunch.md\`  
6\. \`11\_drift\_control/anti\_drift.md\`

Then branch into substyles, asset categories, webpage logic, and prompting.

\---

\#\# Repo philosophy

This style works best when it is treated as:

\- decorative  
\- excessive  
\- synthetic  
\- emotionally direct  
\- artifact-positive  
\- identity-coded  
\- page-aware  
\- slightly trashy  
\- shamelessly overdone

It should feel like a \*\*digital locker, shrine, mall kiosk, sleepover sticker sheet, profile performance, and magical garbage palace\*\* all conspiring together.

That’s the correct disease.

\---

\#\# Status

This repo is intended to be:

\- descriptive enough for humans  
\- structured enough for AI systems  
\- modular enough for apps  
\- opinionated enough to prevent drift

It is not a generic nostalgia archive.

It is a \*\*usable style engine\*\*.

---

### **`REPO_MAP.md`**

\# Repo Map

This file explains what each major folder in the repository is for and how the parts relate to each other.

\---

\#\# Top-level files

\#\#\# \`README.md\`  
Main overview of the repo, its purpose, its scope, and how to use it.

\#\#\# \`REPO\_MAP.md\`  
This file. Structural guide to the repo.

\#\#\# \`ROADMAP.md\`  
Planned build order, future additions, and recommended sequence for expanding the repo.

\---

\#\# \`00\_meta/\`  
Meta-level operational documents that define how the repo behaves.

\#\#\# \`design\_goals.md\`  
Defines what the repo is trying to accomplish and what kinds of usefulness it is optimized for.

\#\#\# \`usage\_modes.md\`  
Explains the different ways the repo can be used: prompting, shaders, apps, research, style mixing, etc.

\#\#\# \`repo\_conventions.md\`  
Naming, formatting, tone, structure, and documentation conventions for keeping the repo coherent.

\---

\#\# \`01\_core\_definition/\`  
The conceptual skeleton of the style.

\#\#\# \`style\_definition.md\`  
The most direct definition of the style and its essential properties.

\#\#\# \`style\_pillars.md\`  
The load-bearing traits without which the style breaks or drifts.

\#\#\# \`emotional\_logic.md\`  
How the style communicates mood, desire, drama, attitude, vanity, magic, and intimacy.

\#\#\# \`identity\_performance\_logic.md\`  
How decoration acts as identity, self-branding, self-mythology, and page-performance.

\#\#\# \`cute\_trashy\_dark\_spectrum.md\`  
Defines the internal tonal spectrum of the style.

\#\#\# \`substyle\_split\_myspace\_vs\_angelfire.md\`  
Separates the two main branches and explains their overlap and divergence.

\#\#\# \`what\_this\_style\_is\_not.md\`  
Boundary-setting document to prevent the style from collapsing into neighboring aesthetics.

\---

\#\# \`02\_visual\_dna/\`  
The style’s recurring visual grammar.

\#\#\# \`core\_visual\_traits.md\`  
High-level visual markers that define the style.

\#\#\# \`motif\_families.md\`  
Recurring symbol groups like hearts, stars, crowns, skulls, bunnies, etc.

\#\#\# \`typography\_families.md\`  
Text styles, slogan behavior, faux bevels, bubble lettering, script, chrome, gel, outline logic.

\#\#\# \`badge\_banner\_stamp\_structures.md\`  
Common graphic packaging structures.

\#\#\# \`sticker\_cutout\_logic.md\`  
How isolated transparent graphics behave and why they matter.

\#\#\# \`page\_ornament\_logic.md\`  
How page elements become decorative ecology.

\#\#\# \`composition\_grammar.md\`  
Rules for asset placement, emphasis, layering, symmetry, clutter, and focal behavior.

\#\#\# \`density\_and\_clutter\_logic.md\`  
How much is too much, how clutter behaves, and how to keep maximalism legible.

\---

\#\# \`03\_palette\_and\_effects/\`  
Color logic and glam-trash FX behavior.

\#\#\# Key areas  
\- hot pink glitter families  
\- blacklight purple families  
\- toxic contrast pairs  
\- black background staging  
\- sparkle systems  
\- chrome / gel / bevel illusions  
\- glow / outline / halo behavior

This folder exists so the style doesn’t drift into generic pastel nostalgia or polished modern gradients.

\---

\#\# \`04\_materials\_and\_artifacts/\`  
The physical-feeling lie of the style.

\#\#\# Key areas  
\- GIF-era behavior  
\- compression grit  
\- transparency halos  
\- fake gems / plastic / chrome  
\- low-resolution charm  
\- cheap luxury surfaces  
\- compositing artifacts

This folder is critical because the style loses its soul when rendered too cleanly.

\---

\#\# \`05\_substyles/\`  
Named sub-branches inside the parent style.

\#\#\# Key substyles  
\- Myspace profile bling  
\- Angelfire shrine chaos  
\- Blingee core  
\- girly slogan graphics  
\- cosmic sticker wallpaper  
\- dark cute skull glitter  
\- mall kiosk glam

This folder lets systems target distinct flavors instead of producing undifferentiated glitter soup.

\---

\#\# \`06\_asset\_categories/\`  
Inventory of common asset families.

\#\#\# Example categories  
\- glitter text assets  
\- slogan badges  
\- hearts / crowns / stars  
\- skulls / bunnies / lips / butterflies  
\- celestial fillers  
\- dolls / divas / princess icons  
\- blinkies / separators / buttons  
\- tiled backgrounds / wallpapers

Useful for prompt injection, asset generation, and filtering.

\---

\#\# \`07\_webpage\_logic/\`  
Defines how the style behaves as a page system, not just as isolated graphics.

\#\#\# Key topics  
\- page types  
\- layout archetypes  
\- shrine pages  
\- profile pages  
\- enter-page splash logic  
\- tiled background logic  
\- link-button ecology  
\- guestbook / counter / webring energy

This folder is one of the main things separating this repo from generic “internet nostalgia.”

\---

\#\# \`08\_motion\_and\_animation/\`  
Animated behavior for GIF-like presentation.

\#\#\# Key topics  
\- blink  
\- flash  
\- twinkle  
\- glitter-scroll behavior  
\- loop timing  
\- frame economy  
\- intensity vs safety

Useful for animation prompts, shader approximations, and motion style control.

\---

\#\# \`09\_shader\_and\_genart\_translation/\`  
How to proceduralize the style.

\#\#\# Key topics  
\- glitter field simulation  
\- starburst generation  
\- layer-stack logic  
\- tiled background generators  
\- badge generators  
\- halo rendering  
\- fake webgraphic pipelines  
\- generative clutter orchestration

This folder translates aesthetic logic into system behavior.

\---

\#\# \`10\_prompt\_system/\`  
Prompting infrastructure for image, motion, and graphic generation.

\#\#\# Key topics  
\- short formulas  
\- long formulas  
\- asset templates  
\- text graphic templates  
\- background templates  
\- webpage scene templates  
\- Myspace-specific prompts  
\- Angelfire-specific prompts  
\- anti-drift prompting

This folder makes the repo immediately usable.

\---

\#\# \`11\_drift\_control/\`  
Anti-bullshit firewall.

\#\#\# Key topics  
\- anti-drift rules  
\- common failure modes  
\- neighboring style confusions  
\- overpolish detection  
\- underchaos detection  
\- authenticity markers  
\- diagnostic checklists  
\- repair strategies

This section keeps the style from mutating into clean Y2K, kawaii sticker culture, generic goth, or vague webcore.

\---

\#\# \`12\_app\_integration/\`  
Machine-facing logic layer.

\#\#\# Key topics  
\- use cases  
\- tagging  
\- control knobs  
\- style axis models  
\- recommendation logic  
\- style mix recipes

Useful for software, UI controls, filtering, retrieval, and prompt builder tools.

\---

\#\# \`13\_structured\_data/\`  
Machine-readable style brain.

\#\#\# Planned files  
\- \`style\_spec.json\`  
\- \`substyles.json\`  
\- \`motif\_library.json\`  
\- \`asset\_categories.json\`  
\- \`effect\_library.json\`  
\- \`palette\_presets.json\`  
\- \`motion\_primitives.json\`  
\- \`drift\_rules.json\`  
\- \`page\_archetypes.json\`  
\- \`control\_knobs.json\`  
\- \`comparison\_table.csv\`

These files support automated systems and structured reasoning.

\---

\#\# \`14\_examples/\`  
Grounding and demonstration layer.

\#\#\# Planned files  
\- \`archetype\_examples.md\`  
\- \`prompt\_examples.md\`  
\- \`failure\_examples.md\`  
\- \`style\_mix\_examples.md\`  
\- \`before\_after\_repairs.md\`

This folder proves the repo can actually function in practice.

\---

\#\# Recommended build order

\#\#\# Phase A — essential skeleton  
1\. \`README.md\`  
2\. \`REPO\_MAP.md\`  
3\. \`01\_core\_definition/style\_definition.md\`  
4\. \`01\_core\_definition/substyle\_split\_myspace\_vs\_angelfire.md\`  
5\. \`02\_visual\_dna/core\_visual\_traits.md\`  
6\. \`03\_palette\_and\_effects/palette\_system.md\`  
7\. \`04\_materials\_and\_artifacts/compression\_noise\_and\_crunch.md\`  
8\. \`11\_drift\_control/anti\_drift.md\`

\#\#\# Phase B — practical deployment  
\- substyles  
\- core asset categories  
\- profile/shrine page docs  
\- short prompt system docs

\#\#\# Phase C — machine integration  
\- style spec JSON  
\- motif library JSON  
\- palette presets JSON  
\- control knobs docs \+ JSON

\---

\#\# Structural philosophy

This repo is designed to be:

\- modular  
\- layered  
\- human-readable  
\- machine-readable  
\- anti-drift  
\- useful for real generation systems

It should support both:  
\- \*\*description\*\*  
\- \*\*deployment\*\*

That is the point.

---

### **`ROADMAP.md`**

\# Roadmap

This roadmap defines a practical build order for the repository so that the highest-value files are created first.

The goal is to build the repo in an order that gives us:

1\. conceptual clarity  
2\. anti-drift protection  
3\. prompt usability  
4\. machine-usable structure  
5\. expansion space

\---

\#\# Build philosophy

Do not build the repo in random order.

This style has a lot of visual bait and a lot of neighboring-style confusion, so the structure should be built from the inside out:

\- first define the core  
\- then define the visual grammar  
\- then define the artifact logic  
\- then define how it fails  
\- then define how to deploy it  
\- then define structured data  
\- then expand examples

That keeps the repo from becoming glitter landfill.

\---

\#\# Phase A — Essential skeleton

These files establish the repo’s load-bearing logic.

\#\#\# Top priority files  
\- \`README.md\`  
\- \`REPO\_MAP.md\`  
\- \`01\_core\_definition/style\_definition.md\`  
\- \`01\_core\_definition/substyle\_split\_myspace\_vs\_angelfire.md\`  
\- \`02\_visual\_dna/core\_visual\_traits.md\`  
\- \`03\_palette\_and\_effects/palette\_system.md\`  
\- \`04\_materials\_and\_artifacts/compression\_noise\_and\_crunch.md\`  
\- \`11\_drift\_control/anti\_drift.md\`

\#\#\# Goal of Phase A  
By the end of this phase, the repo should be able to answer:

\- What is this style?  
\- What makes it distinct?  
\- What are its two main branches?  
\- What does it look like?  
\- What does its color system do?  
\- Why do artifacts matter?  
\- How do we keep it from drifting?

\---

\#\# Phase B — Visual expansion \+ deployment layer

These files make the style practical for generation systems and prompt workflows.

\#\#\# Priority groups

\#\#\#\# Core definition expansion  
\- \`01\_core\_definition/style\_pillars.md\`  
\- \`01\_core\_definition/what\_this\_style\_is\_not.md\`  
\- \`01\_core\_definition/cute\_trashy\_dark\_spectrum.md\`

\#\#\#\# Visual DNA expansion  
\- \`02\_visual\_dna/motif\_families.md\`  
\- \`02\_visual\_dna/typography\_families.md\`  
\- \`02\_visual\_dna/composition\_grammar.md\`  
\- \`02\_visual\_dna/density\_and\_clutter\_logic.md\`

\#\#\#\# Substyles  
\- \`05\_substyles/myspace\_profile\_bling.md\`  
\- \`05\_substyles/angelfire\_shrine\_chaos.md\`  
\- \`05\_substyles/blingee\_core.md\`

\#\#\#\# Asset categories  
\- \`06\_asset\_categories/glitter\_text\_assets.md\`  
\- \`06\_asset\_categories/slogan\_badges.md\`  
\- \`06\_asset\_categories/tiled\_backgrounds\_and\_wallpapers.md\`

\#\#\#\# Webpage logic  
\- \`07\_webpage\_logic/profile\_page\_logic.md\`  
\- \`07\_webpage\_logic/shrine\_page\_logic.md\`  
\- \`07\_webpage\_logic/tiled\_background\_logic.md\`

\#\#\#\# Prompt system  
\- \`10\_prompt\_system/prompt\_formula\_short.md\`  
\- \`10\_prompt\_system/asset\_prompt\_templates.md\`  
\- \`10\_prompt\_system/anti\_drift\_prompting.md\`

\#\#\# Goal of Phase B  
By the end of this phase, the repo should be usable for:

\- image prompting  
\- asset prompting  
\- style steering  
\- substyle separation  
\- page atmosphere generation  
\- practical drift prevention

\---

\#\# Phase C — Materials, motion, and deeper system logic

This phase deepens the style so it becomes more precise and procedural.

\#\#\# Priority groups

\#\#\#\# Materials and artifact layer  
\- \`04\_materials\_and\_artifacts/gif\_behavior.md\`  
\- \`04\_materials\_and\_artifacts/transparency\_edges\_and\_halos.md\`  
\- \`04\_materials\_and\_artifacts/faux\_plastic\_gem\_chrome.md\`  
\- \`04\_materials\_and\_artifacts/compositing\_artifacts.md\`

\#\#\#\# Motion and animation  
\- \`08\_motion\_and\_animation/motion\_primitives.md\`  
\- \`08\_motion\_and\_animation/blink\_flash\_twinkle.md\`  
\- \`08\_motion\_and\_animation/loop\_timing\_logic.md\`

\#\#\#\# Webpage ecology expansion  
\- \`07\_webpage\_logic/enter\_page\_splash\_logic.md\`  
\- \`07\_webpage\_logic/link\_button\_ecology.md\`  
\- \`07\_webpage\_logic/guestbook\_counter\_webring\_energy.md\`

\#\#\#\# Drift control expansion  
\- \`11\_drift\_control/common\_failure\_modes.md\`  
\- \`11\_drift\_control/neighboring\_style\_confusions.md\`  
\- \`11\_drift\_control/authenticity\_markers.md\`  
\- \`11\_drift\_control/repair\_strategies.md\`

\#\#\# Goal of Phase C  
By the end of this phase, the repo should understand:

\- how the style animates  
\- how artifacts behave  
\- how webpages feel as systems  
\- how to diagnose and repair failures

\---

\#\# Phase D — Shader / genart translation

This phase turns the repo into procedural fuel.

\#\#\# Priority groups  
\- \`09\_shader\_and\_genart\_translation/shader\_behavior\_overview.md\`  
\- \`09\_shader\_and\_genart\_translation/glitter\_field\_simulation.md\`  
\- \`09\_shader\_and\_genart\_translation/starburst\_generator.md\`  
\- \`09\_shader\_and\_genart\_translation/sticker\_layer\_stack\_system.md\`  
\- \`09\_shader\_and\_genart\_translation/tiled\_background\_generator.md\`  
\- \`09\_shader\_and\_genart\_translation/generative\_clutter\_orchestration.md\`

\#\#\# Goal of Phase D  
By the end of this phase, the repo should support:

\- procedural rendering approximations  
\- shader design  
\- system parameterization  
\- graphic-layer simulation

\---

\#\# Phase E — App integration \+ structured data

This phase makes the repo machine-legible at a higher level.

\#\#\# Priority groups

\#\#\#\# App integration docs  
\- \`12\_app\_integration/use\_cases.md\`  
\- \`12\_app\_integration/tagging\_system.md\`  
\- \`12\_app\_integration/control\_knobs.md\`  
\- \`12\_app\_integration/style\_axis\_model.md\`

\#\#\#\# Structured data  
\- \`13\_structured\_data/style\_spec.json\`  
\- \`13\_structured\_data/substyles.json\`  
\- \`13\_structured\_data/motif\_library.json\`  
\- \`13\_structured\_data/asset\_categories.json\`  
\- \`13\_structured\_data/effect\_library.json\`  
\- \`13\_structured\_data/palette\_presets.json\`  
\- \`13\_structured\_data/motion\_primitives.json\`  
\- \`13\_structured\_data/drift\_rules.json\`  
\- \`13\_structured\_data/page\_archetypes.json\`  
\- \`13\_structured\_data/control\_knobs.json\`  
\- \`13\_structured\_data/comparison\_table.csv\`

\#\#\# Goal of Phase E  
By the end of this phase, the repo should be usable by:

\- apps  
\- style selectors  
\- prompt builders  
\- retrieval tools  
\- recommendation systems  
\- agent workflows

\---

\#\# Phase F — Examples and test cases

This phase grounds the repo and catches bullshit.

\#\#\# Priority groups  
\- \`14\_examples/archetype\_examples.md\`  
\- \`14\_examples/prompt\_examples.md\`  
\- \`14\_examples/failure\_examples.md\`  
\- \`14\_examples/style\_mix\_examples.md\`  
\- \`14\_examples/before\_after\_repairs.md\`

\#\#\# Goal of Phase F  
By the end of this phase, the repo should demonstrate:

\- correct execution  
\- incorrect execution  
\- failure repair  
\- style mixing without collapse

\---

\#\# Optional later expansions

These are useful but not required for the first robust version.

\#\#\# Possible additions  
\- inspiration/reference index  
\- historical source notes  
\- prompt benchmark tests  
\- asset naming taxonomy  
\- retrieval tags by motif/emotion/substyle  
\- motion safety presets  
\- UI mockups for style pickers  
\- example fake webpage compositions  
\- example sticker packs and category boards

\---

\#\# Definition of “done enough”

The repo is “done enough” when it can:

\- define the style clearly  
\- distinguish Myspace from Angelfire  
\- explain its core visuals  
\- preserve its artifact logic  
\- prevent drift  
\- generate prompt-ready outputs  
\- expose machine-readable structure  
\- support real workflows

It does \*\*not\*\* need to be infinite before it becomes useful.

\---

\#\# Strategic warning

The biggest risk is building too many decorative docs before the anti-drift layer is strong enough.

That leads to:  
\- pretty but vague style writing  
\- asset lists with no boundaries  
\- prompt systems that wander into generic Y2K slop  
\- clean modern reinterpretations that kill the original magic

So always protect:  
1\. definition  
2\. substyle split  
3\. artifact logic  
4\. anti-drift rules

That’s the spine.

---

### **`00_meta/design_goals.md`**

\# Design Goals

This document defines the goals of the repository.

The repo is not just an aesthetic moodboard. It is a \*\*usable style system\*\*.

\---

\#\# Primary goal

Create a structured repository that captures the visual, emotional, material, and compositional logic of the Myspace/Angelfire glitter-web graphics ecosystem in a way that is:

\- understandable by humans  
\- usable by AI systems  
\- useful for prompting  
\- useful for shaders and generative art  
\- durable against drift

\---

\#\# Core design goals

\#\#\# 1\. Define the style clearly  
The repo should explain what the style is without reducing it to vague terms like “Y2K,” “old internet,” or “glitter nostalgia.”

\#\#\# 2\. Preserve substyle differences  
The repo must clearly distinguish:  
\- Myspace profile bling  
\- Angelfire shrine chaos

These share a lot of DNA, but they are not the same.

\#\#\# 3\. Preserve artifact logic  
Cheapness, compression, glow weirdness, transparency halos, low-res charm, and fake materials are not accidental leftovers.  
They are part of the style.

\#\#\# 4\. Support prompt workflows  
The repo should support image generation, asset generation, background generation, animation prompting, and full-page atmosphere prompting.

\#\#\# 5\. Support procedural translation  
The repo should expose logic usable in:  
\- shaders  
\- generative systems  
\- app styling  
\- structured recommendation systems

\#\#\# 6\. Prevent drift  
The repo should actively stop the style from collapsing into:  
\- generic Y2K  
\- polished retro branding  
\- kawaii sticker culture  
\- vaporwave moodboarding  
\- vague “webcore”

\#\#\# 7\. Stay modular  
The style should be broken into parts that can be combined, isolated, and remixed:  
\- motifs  
\- colors  
\- materials  
\- page logic  
\- motion  
\- substyles  
\- prompt structures  
\- drift rules

\---

\#\# Secondary goals

\#\#\# Historical resonance  
The repo should feel grounded in the early-web decorative ecosystem without becoming a history lecture.

\#\#\# Reusability  
The repo should be easy to mine for:  
\- prompt snippets  
\- app tags  
\- UI controls  
\- style filters  
\- JSON specs  
\- mix recipes

\#\#\# Expandability  
The repo should be able to grow over time without collapsing into chaos.

\#\#\# Machine legibility  
The style should be representable in structured data, not just poetic prose.

\---

\#\# Non-goals

This repo is \*\*not\*\* trying to:

\- become a complete history of Myspace or Angelfire  
\- archive every possible web graphic from the era  
\- flatten all early internet styles into one category  
\- recreate actual websites line-by-line  
\- sanitize the aesthetic into tasteful modern design  
\- become a generic “nostalgia” repo

\---

\#\# Operational principle

The repo should always prefer:

\- specificity over vagueness  
\- usable structure over moodboard fluff  
\- style behavior over raw decoration lists  
\- anti-drift precision over aesthetic hand-waving  
\- modular systems over giant blob-documents

\---

\#\# Quality threshold

A file in this repo should be considered successful if it helps a human or a machine answer one of these questions:

\- What is this style?  
\- What part of the style is this?  
\- How is this different from a neighboring style?  
\- How do I generate it?  
\- How do I keep it from drifting?  
\- How do I translate it into another system?  
\- How do I choose the right substyle or effect cluster?

If a file does not help answer any of those, it may be decorative but it is not load-bearing.

---

### **`00_meta/usage_modes.md`**

\# Usage Modes

This document defines the main ways the repository is intended to be used.

The repo is multi-purpose by design. It is not locked to one workflow.

\---

\#\# 1\. Style definition mode

Use the repo to understand the style at a conceptual level.

\#\#\# Best files for this mode  
\- \`README.md\`  
\- \`01\_core\_definition/style\_definition.md\`  
\- \`01\_core\_definition/style\_pillars.md\`  
\- \`01\_core\_definition/substyle\_split\_myspace\_vs\_angelfire.md\`  
\- \`01\_core\_definition/what\_this\_style\_is\_not.md\`

\#\#\# Typical use cases  
\- learning the style  
\- explaining the style to someone else  
\- distinguishing it from neighboring aesthetics  
\- establishing a shared vocabulary

\---

\#\# 2\. Prompt writing mode

Use the repo to generate prompts for image tools, graphic asset tools, animation tools, or scene-generation systems.

\#\#\# Best files for this mode  
\- \`05\_substyles/\`  
\- \`06\_asset\_categories/\`  
\- \`03\_palette\_and\_effects/\`  
\- \`10\_prompt\_system/\`  
\- \`11\_drift\_control/\`

\#\#\# Typical use cases  
\- glitter asset prompts  
\- text-graphic prompts  
\- page-background prompts  
\- shrine-page atmosphere prompts  
\- Myspace vs Angelfire prompt branching

\---

\#\# 3\. Style steering mode

Use the repo to tune outputs that are close but wrong.

\#\#\# Best files for this mode  
\- \`11\_drift\_control/\`  
\- \`01\_core\_definition/what\_this\_style\_is\_not.md\`  
\- \`03\_palette\_and\_effects/palette\_system.md\`  
\- \`04\_materials\_and\_artifacts/\`  
\- \`05\_substyles/\`

\#\#\# Typical use cases  
\- “too clean”  
\- “too kawaii”  
\- “too generic Y2K”  
\- “too dark”  
\- “not enough webpage logic”  
\- “not enough trash-glam”

\---

\#\# 4\. Generative art / shader mode

Use the repo as a behavior model for procedural approximation.

\#\#\# Best files for this mode  
\- \`03\_palette\_and\_effects/\`  
\- \`04\_materials\_and\_artifacts/\`  
\- \`08\_motion\_and\_animation/\`  
\- \`09\_shader\_and\_genart\_translation/\`  
\- \`12\_app\_integration/control\_knobs.md\`

\#\#\# Typical use cases  
\- glitter simulation  
\- starburst generation  
\- fake sticker layering  
\- tiled backgrounds  
\- low-res halo rendering  
\- procedural clutter fields  
\- blinking/twinkling loop logic

\---

\#\# 5\. App integration mode

Use the repo to build software that selects, recommends, or generates within the style.

\#\#\# Best files for this mode  
\- \`12\_app\_integration/\`  
\- \`13\_structured\_data/\`  
\- \`05\_substyles/\`  
\- \`06\_asset\_categories/\`  
\- \`11\_drift\_control/\`

\#\#\# Typical use cases  
\- style selector UIs  
\- substyle sliders  
\- preset engines  
\- asset category tagging  
\- prompt-builder interfaces  
\- recommendation systems  
\- retrieval/classification workflows

\---

\#\# 6\. Reference and inspiration mode

Use the repo to gather and organize the visual DNA of the style without immediately generating anything.

\#\#\# Best files for this mode  
\- \`02\_visual\_dna/\`  
\- \`03\_palette\_and\_effects/\`  
\- \`06\_asset\_categories/\`  
\- \`14\_examples/\`

\#\#\# Typical use cases  
\- moodboarding  
\- style analysis  
\- comparison work  
\- planning derivative styles  
\- making spin-off repos

\---

\#\# 7\. Style-mixing mode

Use the repo as one style source in a hybrid system.

\#\#\# Best files for this mode  
\- \`05\_substyles/\`  
\- \`12\_app\_integration/style\_mix\_recipes.md\`  
\- \`03\_palette\_and\_effects/\`  
\- \`11\_drift\_control/\`

\#\#\# Typical use cases  
\- mixing with scene/emo web graphics  
\- mixing with dark kawaii  
\- mixing with vaporwave carefully  
\- mixing with mall-goth aesthetics  
\- mixing with sticker-trash pop graphics  
\- mixing with cyber shrine aesthetics

\#\#\# Important warning  
Mixing should preserve the core identity of this repo.  
If the style becomes unrecognizable, the mix failed.

\---

\#\# 8\. Educational / explanatory mode

Use the repo to teach the style to another person, another model, or another agent.

\#\#\# Best files for this mode  
\- \`README.md\`  
\- \`REPO\_MAP.md\`  
\- \`01\_core\_definition/\`  
\- \`11\_drift\_control/\`  
\- \`13\_structured\_data/\`

\#\#\# Typical use cases  
\- onboarding another AI  
\- explaining the repo to collaborators  
\- teaching substyle boundaries  
\- turning style knowledge into reusable instructions

\---

\#\# Recommended usage patterns

\#\#\# Fast orientation  
Read:  
1\. \`README.md\`  
2\. \`01\_core\_definition/style\_definition.md\`  
3\. \`01\_core\_definition/substyle\_split\_myspace\_vs\_angelfire.md\`  
4\. \`11\_drift\_control/anti\_drift.md\`

\#\#\# Prompt build  
Read:  
1\. substyle doc  
2\. palette doc  
3\. asset category doc  
4\. anti-drift prompt doc

\#\#\# App build  
Read:  
1\. style axis model  
2\. control knobs  
3\. structured JSON files  
4\. drift rules

\#\#\# Shader build  
Read:  
1\. effect docs  
2\. materials/artifact docs  
3\. motion docs  
4\. shader translation docs

\---

\#\# Principle

No single file should try to do every job.

Use the repo in layers:  
\- define  
\- branch  
\- steer  
\- deploy  
\- validate

That is the intended operating logic.

---

### **`00_meta/repo_conventions.md`**

\# Repo Conventions

This document defines the formatting, naming, and structural conventions for the repository.

These conventions exist to keep the repo coherent, searchable, and machine-friendly.

\---

\#\# 1\. File naming conventions

\#\#\# Markdown files  
Use lowercase snake\_case with \`.md\`.

Examples:  
\- \`style\_definition.md\`  
\- \`palette\_system.md\`  
\- \`anti\_drift.md\`

\#\#\# JSON files  
Use lowercase snake\_case with \`.json\`.

Examples:  
\- \`style\_spec.json\`  
\- \`motif\_library.json\`

\#\#\# CSV files  
Use lowercase snake\_case with \`.csv\`.

Example:  
\- \`comparison\_table.csv\`

\---

\#\# 2\. Folder naming conventions

Use zero-padded numeric prefixes for top-level content folders.

Examples:  
\- \`01\_core\_definition\`  
\- \`02\_visual\_dna\`  
\- \`11\_drift\_control\`

Why:  
\- keeps reading order stable  
\- keeps repo browsing predictable  
\- prevents folder chaos as the repo expands

\---

\#\# 3\. Writing tone conventions

The writing style should be:

\- clear  
\- direct  
\- structured  
\- descriptive  
\- opinionated enough to prevent drift  
\- informal when helpful, but not sloppy  
\- vivid without becoming mushy nonsense

The repo can have personality, but each file should still be usable by a machine or a tired human.

\---

\#\# 4\. Document structure conventions

Most markdown files should follow a pattern close to:

1\. title  
2\. short purpose statement  
3\. definition / explanation  
4\. key traits or principles  
5\. examples or patterns  
6\. contrast / drift notes when relevant  
7\. practical implications

Not every file needs every section, but that is the preferred skeleton.

\---

\#\# 5\. Anti-vagueness rule

Avoid vague claims like:

\- “it has nostalgic energy”  
\- “it feels old-web”  
\- “it’s kinda cute and chaotic”  
\- “it has lots of sparkles”

Instead, name the actual mechanisms:  
\- glitter fills  
\- black-background stage logic  
\- transparent cutout sticker behavior  
\- compression artifacts  
\- mall-girl slogan structures  
\- page ornament ecology

Specificity wins.

\---

\#\# 6\. Anti-bloat rule

Do not make giant markdown files that try to contain the whole universe.

Break things into modular files when:  
\- the topic has distinct sub-parts  
\- the topic will be referenced often  
\- the topic maps cleanly to a machine-readable category later  
\- the topic risks becoming unreadable if swollen

\---

\#\# 7\. Boundary-setting rule

Whenever a topic is especially prone to drift, include:  
\- what it is  
\- what it is not  
\- common failure modes  
\- neighboring confusions if relevant

This repo is not just descriptive.  
It is protective.

\---

\#\# 8\. Structured data alignment rule

Whenever possible, markdown categories should be designed so they can later map into JSON or CSV.

Examples:  
\- substyles  
\- motif families  
\- effect families  
\- control knobs  
\- palette families  
\- page archetypes  
\- motion primitives  
\- drift rules

The prose layer and the structured-data layer should rhyme with each other.

\---

\#\# 9\. Examples convention

Examples should be:  
\- concrete  
\- contrastive when possible  
\- framed in a way that shows why they are correct or incorrect

When creating failure examples, do not just say “wrong.”  
Say \*how\* and \*why\* it drifted.

\---

\#\# 10\. Prompting convention

Prompt docs should separate:  
\- short prompts  
\- long prompts  
\- asset prompts  
\- scene/page prompts  
\- anti-drift guidance

Prompt docs should not assume one universal prompt formula fits every tool.

\---

\#\# 11\. Substyle convention

The parent repo is shared, but substyles should be treated as meaningful branches.

At minimum, substyle docs should clarify:  
\- central use case  
\- visual tilt  
\- motif emphasis  
\- palette tilt  
\- page or asset behavior  
\- likely drift patterns

\---

\#\# 12\. Artifact convention

Do not treat artifacts as defects to be erased by default.

Important artifact categories include:  
\- crunch  
\- low-resolution edge behavior  
\- haloing  
\- glow bleed  
\- fake transparency weirdness  
\- glitter overfill  
\- compositing mismatch  
\- cheap material simulation

These are often style-positive.

\---

\#\# 13\. No false precision rule

This repo should be structured, but not pretend to scientific certainty where none exists.

It is okay to say:  
\- “often”  
\- “typically”  
\- “usually”  
\- “common tendency”  
\- “strong marker”

It is not okay to invent fake certainty just because structure feels nice.

\---

\#\# 14\. Expansion convention

When adding new files, prefer asking:  
\- does this deserve its own file?  
\- does it belong under an existing section?  
\- will this be reused?  
\- does this help prompting, control, or drift prevention?

If the answer is no, it may belong as a section inside another file instead.

\---

\#\# 15\. Success criterion

A repo file should earn its place by doing one or more of the following:

\- defining  
\- differentiating  
\- steering  
\- translating  
\- structuring  
\- operationalizing

If it does none of those, it is probably decorative filler.

---

### **`01_core_definition/style_definition.md`**

\# Style Definition

This document provides the clearest direct definition of the style.

\---

\#\# Definition

\*\*Myspace \+ Angelfire graphics style\*\* is a decorative early-web visual system built from glitter assets, transparent cutout graphics, badge-like slogans, black-background glow, low-resolution sparkle effects, fake luxury surfaces, and cluttered digital self-ornament.

It combines two major but related tendencies:

1\. \*\*profile bling decoration\*\*  
2\. \*\*homemade shrine-page worldbuilding\*\*

The first leans toward self-branding through assets.  
The second leans toward page-building through atmosphere.

Both rely on ornamental excess, emotional immediacy, and synthetic visual seduction.

\---

\#\# Short definition

A style of \*\*glittery, low-res, emotionally loud, tacky-web decorative graphics\*\* used to perform identity, fantasy, attitude, and page atmosphere.

\---

\#\# Long definition

This style emerged from the ecosystem of early-web personal expression in which digital pages were not treated as neutral containers, but as extensions of personality, fantasy, flirtation, devotion, drama, and taste-performance.

Its materials are not physical in the normal sense. They are simulated and composite:  
\- glitter  
\- chrome  
\- gel  
\- glow  
\- starbursts  
\- halos  
\- cheap transparency  
\- crushed pixels  
\- sticker edges  
\- tiled backgrounds  
\- icon packs  
\- slogan graphics

The result is a style that is:  
\- synthetic  
\- decorative  
\- excessive  
\- identity-coded  
\- artifact-positive  
\- emotionally direct  
\- often feminine, bratty, magical, or dark-cute  
\- rooted in page ecology rather than isolated image polish

This is not clean digital design.  
It is \*\*ornamented internet selfhood\*\*.

\---

\#\# The two dominant branches

\#\#\# Myspace branch  
The Myspace branch treats the page as a decorated identity field.

Common features:  
\- glitter names  
\- “cute,” “princess,” “diva,” “gangsta princess,” “baby girl” slogan graphics  
\- transparent sticker assets  
\- hearts, crowns, lips, stars  
\- profile ornament  
\- flirt graphics  
\- mall-kiosk fake luxury  
\- decorative attitude performance

\#\#\# Angelfire branch  
The Angelfire branch treats the page as a shrine, portal, or handmade world.

Common features:  
\- tiled backgrounds  
\- black starfields  
\- fantasy/celestial/goth icon clutter  
\- “enter” pages  
\- buttons and counters  
\- devotional or thematic page-building  
\- maximalist page atmosphere  
\- amateur handmade layout logic

These branches overlap heavily, but they organize style differently.

\---

\#\# Load-bearing characteristics

Without these, the style starts to collapse:

\- ornamental excess  
\- obvious synthetic effects  
\- emotional tackiness  
\- low-res or artifact-friendly behavior  
\- decorative symbolism  
\- self-performance or shrine-performance  
\- page-aware or asset-aware logic  
\- visual shamelessness

\---

\#\# Core materials

The style often pretends to be made of:  
\- glitter  
\- rhinestones  
\- plastic gems  
\- chrome  
\- metallic foil  
\- gel lettering  
\- sparkler dust  
\- celestial particles  
\- cut vinyl stickers  
\- cheap digital glow

These are usually not rendered convincingly in a realistic sense.  
They are rendered persuasively enough to signal glamour, magic, attitude, or fantasy.

The artificiality is part of the style.

\---

\#\# Core emotional register

This style is not emotionally neutral.

It usually signals some combination of:  
\- cute  
\- bratty  
\- flirtatious  
\- proud  
\- dreamy  
\- magical  
\- melodramatic  
\- vain  
\- mischievous  
\- dark-cute  
\- shrine-like  
\- emotionally declarative

Even when it is dumb, it is not indifferent.

\---

\#\# Distinction from adjacent styles

This style differs from generic early-web nostalgia because it centers \*\*decorative self-performance and shrine clutter\*\*.

It differs from vaporwave because it is less art-school atmospheric and more directly decorative, amateur, and personal.

It differs from generic Y2K because it is more webpage-bound, more sticker-driven, less sleek, and less futurist.

It differs from kawaii because it is tackier, noisier, more synthetic, more artifact-positive, and more shamelessly cheap.

It differs from pure goth web aesthetics because it usually retains sparkle, ornament, cute-trash crossover, or fake-glam logic.

\---

\#\# Functional reading

This style can be understood through four functional lenses:

\#\#\# 1\. Asset lens  
A library of glitter graphics, badges, slogans, and cutout ornaments.

\#\#\# 2\. Page lens  
A total environment made from backgrounds, blinkies, buttons, counters, and layered clutter.

\#\#\# 3\. Identity lens  
A means of performing selfhood through decorative exaggeration.

\#\#\# 4\. System lens  
A modular style grammar usable in prompts, generators, apps, and shader-like approximations.

All four matter.

\---

\#\# Compression of essence

If forced to compress the style to one sentence:

\*\*It is the art of turning a webpage into a glittering digital personality shrine using cheap synthetic effects, symbolic clutter, and shameless decorative intensity.\*\*

---

### **`01_core_definition/substyle_split_myspace_vs_angelfire.md`**

\# Substyle Split: Myspace vs Angelfire

This document defines the difference between the two main branches inside the parent style system.

These branches overlap strongly, but they do not organize style in the same way.

\---

\#\# Why this split matters

Without a clear split, generation systems tend to create muddy hybrids that have:

\- glitter assets but no page logic  
\- shrine-like atmospheres but generic Y2K graphics  
\- “old web” clutter with no identity performance  
\- decorative stickers with no environmental context  
\- a little of everything and the soul of nothing

The split exists to prevent that.

\---

\#\# Shared DNA

Both branches commonly include:

\- black or dark stage backgrounds  
\- glitter and sparkle logic  
\- transparent cutout graphics  
\- low-resolution charm  
\- obvious synthetic effects  
\- slogan or identity-coded ornament  
\- decorative excess  
\- fake luxury surfaces  
\- emotional directness  
\- amateur or semi-amateur compositing energy

Both can use:  
\- hearts  
\- stars  
\- crowns  
\- celestial filler  
\- chrome or gel text  
\- glow halos  
\- cute-trash iconography

But they deploy these differently.

\---

\#\# Myspace profile bling

\#\#\# Core function  
Decorate the self.

\#\#\# Main operating logic  
The page acts as a personality field, and the graphics act as extensions of identity, attitude, desirability, affiliation, and vibe.

\#\#\# Visual center of gravity  
\- profile assets  
\- glitter text  
\- badges and slogans  
\- transparent PNG/GIF cutouts  
\- decorative labels  
\- icon clusters around the self

\#\#\# Typical mood  
\- cute  
\- bratty  
\- flirty  
\- trashy-glam  
\- mall-girl  
\- diva-ish  
\- playful  
\- performative

\#\#\# Typical motifs  
\- hearts  
\- crowns  
\- lips  
\- stars  
\- bunnies  
\- princess graphics  
\- “100% cute” style slogans  
\- baby-girl / diva / brat text  
\- sexy-cute iconography

\#\#\# Composition style  
\- isolated central graphic  
\- badge/emblem layout  
\- slogan \+ icon combos  
\- profile-oriented ornament  
\- sticker pack behavior  
\- decorative clustering around text or self-symbols

\#\#\# Material style  
\- glitter fills  
\- chrome bevels  
\- gel lettering  
\- fake diamond sparkle  
\- plastic gem energy  
\- hot pink dominance

\#\#\# Typical strengths  
\- attitude clarity  
\- fast emotional read  
\- iconicity  
\- decorative punch  
\- strong asset reuse

\#\#\# Typical drift failures  
\- becomes generic Y2K girly design  
\- becomes polished e-commerce “retro” branding  
\- becomes kawaii sticker culture  
\- loses artifact grit  
\- loses personal/webpage specificity

\---

\#\# Angelfire shrine chaos

\#\#\# Core function  
Decorate the page-world.

\#\#\# Main operating logic  
The page acts as a handmade realm, shrine, portal, diary, obsession-zone, or thematic universe. Graphics are part of a larger environment rather than just self-branding ornaments.

\#\#\# Visual center of gravity  
\- whole page atmosphere  
\- backgrounds  
\- tiles  
\- starfields  
\- portal/enter logic  
\- thematic clutter  
\- decorative ecology across the page

\#\#\# Typical mood  
\- dreamy  
\- devotional  
\- mystical  
\- haunted-cute  
\- cosmic  
\- dramatic  
\- weirdly intimate  
\- obsessive

\#\#\# Typical motifs  
\- stars and moons  
\- blacklight galaxies  
\- angels/devils  
\- fantasy creatures  
\- occult-lite symbols  
\- celestial glitter  
\- gothic or ethereal clutter  
\- buttons / dividers / page widgets  
\- shrine-like repetition

\#\#\# Composition style  
\- full-page accumulation  
\- environmental layering  
\- edge clutter  
\- tiled or wallpaper logic  
\- portal-like splash composition  
\- many small decorative actors instead of one main badge

\#\#\# Material style  
\- starfield depth fakery  
\- blinkies  
\- tiled patterns  
\- crunchy low-res compositing  
\- GIF ecology  
\- more environmental glow than isolated glamour polish

\#\#\# Typical strengths  
\- atmospheric density  
\- page identity  
\- handmade worldbuilding  
\- immersive web nostalgia  
\- strong thematic cohesion when done well

\#\#\# Typical drift failures  
\- becomes generic webcore collage  
\- becomes gothic fantasy page with no glitter-trash DNA  
\- becomes vaporwave-ish nostalgia mush  
\- becomes random HTML nostalgia with no symbolic center  
\- loses ornamented self/shrine intentionality

\---

\#\# Fast comparison

| Dimension | Myspace | Angelfire |  
|---|---|---|  
| Core target | self-decoration | page-world decoration |  
| Typical unit | asset / badge / cutout | page / shrine / environment |  
| Main energy | performative identity | handmade atmosphere |  
| Main reading distance | immediate | exploratory |  
| Common format | glitter graphic, slogan sticker | themed page, tiled layout, enter page |  
| Emotional mode | flirty, bratty, glam-trash | dreamy, devotional, chaotic, cosmic |  
| Material emphasis | glitter/chrome/gel asset surfaces | page clutter, background, blinking ecology |  
| Failure mode | polished Y2K girl branding | generic web nostalgia collage |

\---

\#\# Where they overlap hardest

The branches overlap most in:

\- black backgrounds  
\- glitter FX  
\- starbursts  
\- symbolic motifs  
\- slogan language  
\- artifact tolerance  
\- cheap luxury signals  
\- emotional maximalism

This overlap is why they belong in one parent repo.

\---

\#\# How to tell which branch a piece belongs to

Ask:

\#\#\# 1\. What is being decorated?  
\- the self / identity label / personal brand \-\> Myspace  
\- the whole page / world / shrine / environment \-\> Angelfire

\#\#\# 2\. What is the main visual unit?  
\- badge, sticker, glitter text, ornament asset \-\> Myspace  
\- layout, background, portal page, full atmosphere \-\> Angelfire

\#\#\# 3\. What kind of clutter is present?  
\- icon clutter around identity graphics \-\> Myspace  
\- environmental clutter across the whole page \-\> Angelfire

\#\#\# 4\. What is the emotional framing?  
\- “look at me / this is my vibe” \-\> Myspace  
\- “enter my world / obsession / shrine / portal” \-\> Angelfire

\---

\#\# Hybrid cases

A piece can absolutely be hybrid.

Examples:  
\- a glittery “enter here” splash page with slogan graphics  
\- a profile layout using shrine-like starfields and portal imagery  
\- a dark-cute glitter page where the identity sticker pack is embedded into a cosmic shrine environment

These hybrids are valid.

But when building prompts or systems, it still helps to ask:  
\*\*which branch is dominant?\*\*

That dominant branch should control the generation logic.

\---

\#\# Repo rule

Treat these branches as:  
\- shared engine  
\- different deployment logic

Do not split them into totally separate root styles unless a future system genuinely benefits from that separation.

For now, the correct model is:

\*\*one glitter-trash early-web parent style\*\*  
with  
\*\*two major internal gravitational fields\*\*

---

### **`02_visual_dna/core_visual_traits.md`**

\# Core Visual Traits

This document identifies the most important recurring visual traits of the style.

These traits are the fastest way to recognize whether something belongs to the style or is drifting nearby.

\---

\#\# Overview

The style is visually defined by a combination of:

\- glitter  
\- sparkles  
\- synthetic glam surfaces  
\- low-res web artifacts  
\- sticker/cutout logic  
\- black-background stage contrast  
\- decorative symbolism  
\- loud emotional text or identity markers  
\- clutter used as personality or shrine ecology

Not every image needs every trait.  
But the strongest examples usually cluster several together.

\---

\#\# 1\. Glitter as fill, not accent

One of the loudest markers is the use of glitter-like texture as a major surface treatment.

Glitter is often used to fill:  
\- text  
\- hearts  
\- stars  
\- crowns  
\- silhouettes  
\- emblems  
\- badges

It is not subtle.  
It often behaves like:  
\- noisy pink or purple particulate fill  
\- starry speckle field  
\- overbright sparkle crust  
\- synthetic “shiny” texture rather than material realism

The point is not realistic glitter physics.  
The point is visual glam signal.

\---

\#\# 2\. Sparkle starbursts

Sparkle points often appear as:  
\- four-point stars  
\- six-point twinkles  
\- overexposed burst marks  
\- white or pink flare dots  
\- scattered glitter highlights

These serve several functions:  
\- imply shine  
\- increase magical intensity  
\- fake dimensional glamour  
\- unify the image with decorative “energy”

Sparkles are not just highlights.  
They are part of the iconography.

\---

\#\# 3\. Transparent sticker / cutout behavior

A huge part of the style is the feeling that graphics are \*\*assets\*\*:  
\- cut out  
\- floating  
\- dropped onto a page  
\- composited independently  
\- sticker-like in presence

This means:  
\- isolated motifs read strongly  
\- the object often feels detachable from the background  
\- page decoration can be assembled like a kit  
\- visual meaning can come from layering separate symbolic pieces

This is one of the biggest clues that the style belongs to web graphics culture rather than to illustration alone.

\---

\#\# 4\. Black-background stage logic

Many of the strongest examples use black as the stage.

Black does several jobs:  
\- boosts contrast  
\- intensifies pink/purple/cyan glow  
\- makes sparkles feel cosmic  
\- turns cheap graphics into fake luxury  
\- creates theatrical isolation  
\- supports blacklight and mall-kiosk energy

The black background often behaves like:  
\- void  
\- starfield  
\- velvet  
\- club darkness  
\- page space waiting to be decorated

This is not neutral black.  
It is glamour theater.

\---

\#\# 5\. Loud outline / halo behavior

Objects are often defined by:  
\- white outlines  
\- silver-like outlines  
\- glow halos  
\- crunchy outer edges  
\- low-res border shimmer

These borders help:  
\- separate cutouts from the background  
\- intensify sticker-like readability  
\- boost visibility on black  
\- fake shine or material value  
\- compensate for low-resolution assets

The border is often part of the aesthetic rather than a cleanup aid.

\---

\#\# 6\. Fake luxury surfaces

The style often borrows signals from cheap or simulated glamour:  
\- chrome  
\- rhinestones  
\- plastic gems  
\- glitter vinyl  
\- gel lettering  
\- foil-like sheen  
\- brushed metallic fakery

These materials are usually rendered in a direct, synthetic, and simplified way.

The goal is not refinement.  
The goal is \*\*flashy value signaling\*\*.

\---

\#\# 7\. Badge, emblem, and slogan packaging

A lot of the graphics are not freeform compositions.  
They are packaged as:  
\- badges  
\- nameplates  
\- slogans  
\- banners  
\- emblems  
\- stamps  
\- decorative declarations

This makes sense because the style evolved in spaces where page elements needed to communicate identity fast.

A slogan graphic often functions like a wearable emotional label.

\---

\#\# 8\. Cute-trash symbolic motifs

Common motifs include:  
\- hearts  
\- stars  
\- crowns  
\- lips  
\- bunnies  
\- butterflies  
\- skulls  
\- crossbones  
\- princess icons  
\- celestial filler  
\- sexy-cute marks  
\- mall-brat visual language

These motifs are important because they turn decoration into coded personality.

The style loves symbols that are:  
\- simple  
\- iconic  
\- emotionally readable  
\- easy to cut out  
\- easy to repeat  
\- easy to glam up with glitter

\---

\#\# 9\. Low-resolution tolerance

This style can remain legible and even desirable under:  
\- compression  
\- crunchy resampling  
\- noisy edges  
\- primitive glow rendering  
\- mismatched compositing  
\- crude transparency

This tolerance is not incidental.  
It is part of the style’s native habitat.

A too-perfect render can easily lose the original read.

\---

\#\# 10\. Clutter as meaning

The style often uses clutter not as background noise, but as expressive density.

Clutter can mean:  
\- obsession  
\- excitement  
\- identity overload  
\- magical atmosphere  
\- devotional decoration  
\- page love  
\- attention hunger  
\- emotional excess

This clutter is often symbolic, not random.

That distinction matters.

\---

\#\# 11\. Text as ornament-object

Text in this style often behaves less like typography and more like an image object.

It may be:  
\- glitter-filled  
\- beveled  
\- outlined  
\- curved  
\- stickered  
\- sparkled  
\- sloganized  
\- central to the composition

Text frequently carries emotional attitude directly:  
\- “cute”  
\- “princess”  
\- “diva”  
\- “gangsta”  
\- “baby girl”  
\- “angel”  
\- “bad girl”

The text is not usually neutral.  
It performs.

\---

\#\# 12\. Amateur compositing charm

A correct example often retains some feeling of:  
\- homemade layering  
\- overbuilt decoration  
\- cut-and-paste digital assembly  
\- unembarrassed effect stacking

A little awkwardness is not necessarily failure.  
Sometimes it is proof of life.

\---

\#\# Summary compression

If a piece has:  
\- glitter fills  
\- sparkle bursts  
\- sticker-like cutouts  
\- black-stage contrast  
\- fake luxury materials  
\- symbolic cute-trash motifs  
\- loud outlined text  
\- artifact-friendly rendering  
\- expressive clutter

then it is probably operating inside the correct style field.

---

### **`03_palette_and_effects/palette_system.md`**

\# Palette System

This document defines the palette logic of the style.

The important thing is not just which colors appear, but how they behave together and what roles they play.

\---

\#\# Core palette identity

This style usually works through a combination of:

\- candy-color glam  
\- blacklight contrast  
\- fake luxury accents  
\- high-visibility ornamental color  
\- dark-stage backgrounds

The palette is not usually subtle, naturalistic, or tasteful in a modern minimalist sense.

It is meant to:  
\- grab attention  
\- signal glamour  
\- support sparkle  
\- dramatize identity  
\- intensify decorative symbols  
\- make the page or asset feel “special”

\---

\#\# Primary color families

\#\#\# 1\. Hot pink family  
Core shades:  
\- hot pink  
\- magenta  
\- bubblegum pink  
\- neon pink  
\- candy pink

Functions:  
\- glamour  
\- cuteness  
\- brat energy  
\- mall-girl signal  
\- central decorative emphasis

This is often the main color family.

\---

\#\#\# 2\. Purple / blacklight family  
Core shades:  
\- electric purple  
\- violet  
\- deep purple  
\- blacklight lavender  
\- ultraviolet fake-glow tones

Functions:  
\- night energy  
\- cosmic shimmer  
\- dreamy darkness  
\- magical space  
\- glitter support

This family often pairs beautifully with black backgrounds.

\---

\#\#\# 3\. Cyan / teal accent family  
Core shades:  
\- cyan  
\- icy blue  
\- aqua  
\- teal  
\- glow-turquoise

Functions:  
\- contrast  
\- “cool” sparkle energy  
\- fake digital luxury  
\- toxic-cute collision with pinks and purples

These colors often appear as accents rather than dominant fields, but they can punch hard.

\---

\#\#\# 4\. Acid green accent family  
Core shades:  
\- lime  
\- electric green  
\- toxic green  
\- glow green

Functions:  
\- bratty contrast  
\- punky contamination  
\- cyber-trash accent  
\- skull / crossbones / alt-cute disruption

This family is especially strong in darker or more chaotic variants.

\---

\#\#\# 5\. White / silver accent family  
Core shades:  
\- bright white  
\- silver-gray  
\- chrome-white  
\- frosty highlight tones

Functions:  
\- sparkle points  
\- outlines  
\- faux luxury signal  
\- edge separation  
\- highlight contrast

White is often essential because it makes glitter and glow readable.

\---

\#\#\# 6\. Black stage field  
Core shade:  
\- deep black

Functions:  
\- theatrical backdrop  
\- blacklight amplifier  
\- fake depth  
\- cosmic void  
\- visual relief against loud assets

Black is often not a supporting color.  
It is part of the glamour system.

\---

\#\# Secondary palette families

These are less universal but still common:

\- baby blue  
\- lavender  
\- candy red  
\- silver-gray  
\- cherry red  
\- soft peach  
\- metallic fake gold  
\- white-pink shimmer blends

These usually appear as secondary accents or motif-specific colors.

\---

\#\# Typical palette behaviors

\#\#\# Pink dominance  
Many graphics are pink-first and everything else supports that.

\#\#\# Dark-stage contrast  
Bright colors are often staged against black or deep darkness.

\#\#\# High-local contrast  
Outlines, sparkles, and icon shapes often rely on strong local contrast rather than soft gradient transitions.

\#\#\# Candy-to-toxic combinations  
The style likes pairings that are pretty but also a little obnoxious:  
\- hot pink \+ black  
\- magenta \+ violet  
\- pink \+ cyan  
\- black \+ purple \+ white  
\- pink \+ toxic green  
\- silver \+ pink \+ black

\#\#\# Emotional directness  
The color choices are usually easy to read emotionally.  
The palette is not trying to hide.

\---

\#\# Major palette modes

\#\#\# Mode A: Hot pink glitter glam  
Typical colors:  
\- hot pink  
\- bubblegum pink  
\- white  
\- silver  
\- black

Typical use:  
\- cute slogans  
\- princess graphics  
\- hearts  
\- badges  
\- feminine pop assets

\#\#\# Mode B: Purple blacklight cosmic  
Typical colors:  
\- violet  
\- magenta  
\- black  
\- white  
\- lavender

Typical use:  
\- starfields  
\- dreamy shrine pages  
\- night magic  
\- glowing web wallpaper

\#\#\# Mode C: Toxic cute contrast  
Typical colors:  
\- hot pink  
\- acid green  
\- black  
\- purple

Typical use:  
\- bratty graphics  
\- skull/crossbones variants  
\- punky-cute icon fields  
\- sharper trash-pop energy

\#\#\# Mode D: Chrome glam accent  
Typical colors:  
\- pink  
\- silver  
\- white  
\- black

Typical use:  
\- faux luxury text  
\- badge outlines  
\- fake metal embellishment  
\- diva-glam graphics

\---

\#\# Effect relationship to color

Colors in this style are often not flat on their own.  
They are intensified through:

\- glitter texture  
\- glow halos  
\- white sparkle points  
\- chrome bevels  
\- gel shine simulation  
\- starburst overlays

The palette system and the effect system are inseparable.

A pink without sparkle may read flat.  
A pink with glitter, white burst points, and black stage contrast reads correctly.

\---

\#\# What the palette is not

This palette is generally not:

\- muted  
\- earthy  
\- naturalistic  
\- pastel-minimal  
\- beige  
\- monochrome-neutral  
\- tasteful corporate retro  
\- soft editorial nostalgia

Even when pale colors appear, they are usually placed inside a louder decorative logic.

\---

\#\# Common palette failures

\#\#\# Too soft  
Looks more like dreamy scrapbook or generic kawaii.

\#\#\# Too sleek  
Looks like modern branded Y2K instead of actual web graphic trash-glam.

\#\#\# Too rainbow without structure  
Loses the dominance patterns and becomes generic party graphics.

\#\#\# Too dark without glam accents  
Loses the cute-trash crossover and turns into generic goth web mood.

\#\#\# Too pastel-clean  
Loses the electric ornamental punch.

\---

\#\# Practical palette rule

A correct palette in this style usually has:

\- at least one dominant glam color  
\- one strong contrast partner or stage field  
\- bright highlight logic  
\- enough contrast for sparkle and cutout readability  
\- a relationship to decoration, not just color harmony

The palette should feel like it wants attention.

That is the point.

---

### **`04_materials_and_artifacts/compression_noise_and_crunch.md`**

\# Compression Noise and Crunch

This document explains why compression artifacts, low-resolution grit, and crunchy rendering matter to the style.

This is one of the most important anti-drift documents in the repo.

\---

\#\# Core principle

In this style, compression and low-resolution behavior are often not mere technical flaws.

They are part of the native visual habitat.

A completely clean, high-end, artifact-free render may preserve the motif inventory while still killing the actual style.

That is because this style was born in environments shaped by:

\- small web graphics  
\- GIF limitations  
\- rough transparency  
\- bad resizing  
\- aggressive compression  
\- primitive glow rendering  
\- repeated reposting and resaving  
\- cheap effect stacks  
\- amateur compositing tools

The crunch is not always damage.  
Sometimes it is provenance.

\---

\#\# What “crunch” means here

Crunch can include:

\- noisy glitter texture  
\- broken-looking pixel edges  
\- harsh resampling  
\- faint blockiness  
\- crude glow falloff  
\- color simplification  
\- fuzzy halos  
\- sharpened edges in the wrong places  
\- overcompressed sparkles  
\- weird transparent fringe behavior

These effects often create exactly the kind of cheap intensity the style needs.

\---

\#\# Why clean rendering can fail

Over-clean rendering often produces these problems:

\#\#\# 1\. Loss of emotional cheapness  
The style becomes expensive-looking in the wrong way.

\#\#\# 2\. Loss of cutout credibility  
The object stops feeling like a dropped-in web asset.

\#\#\# 3\. Loss of glitter aggression  
Fine realistic sparkle simulation can become too tasteful and too physically plausible.

\#\#\# 4\. Loss of web-era feel  
Without crunch, the graphics start reading like modern retro design instead of native web ornament.

\#\#\# 5\. Loss of tension  
The style needs a little friction between glamour aspiration and technical limitation.  
That tension is part of the magic.

\---

\#\# Crunch as texture source

Compression and low-resolution artifacts often create useful texture behavior:

\- glitter becomes grainier and more aggressive  
\- halos become more obvious  
\- sparkle points feel harder and more synthetic  
\- edges feel sticker-like  
\- surfaces feel cheap and shiny at once  
\- black backgrounds gain digital grit  
\- page atmosphere feels more “screen-born”

These are style-positive in many cases.

\---

\#\# Common crunch-positive scenarios

\#\#\# Glitter text  
Slight overcompression can make the glitter feel denser and more chaotic.

\#\#\# Starfield backgrounds  
Low-res glow speckling can help the starfield read as cheap cosmic magic.

\#\#\# Transparent cutouts  
A little edge weirdness can reinforce sticker logic.

\#\#\# Slogan graphics  
Crude outlines and halo noise can make the badge feel more era-correct.

\#\#\# Blinkies and small assets  
Perfect clarity can actually reduce authenticity here.

\---

\#\# When crunch helps most

Crunch is especially useful when a graphic is meant to feel like:

\- a saved web asset  
\- a reposted sticker  
\- a glitter GIF  
\- an old profile ornament  
\- a tiny page badge  
\- a shrine-page element with layered history

It helps less when the system is trying to imitate a glossy high-resolution illustration.  
But that is usually not the goal of this repo anyway.

\---

\#\# Types of artifact behavior that matter

\#\#\# Edge crunch  
Jagged or slightly broken boundaries on asset shapes.

\#\#\# Texture crunch  
Noisy glitter fill, dense particulate feel, overactive shine grain.

\#\#\# Halo crunch  
Glow boundaries with rough falloff or visible pixel behavior.

\#\#\# Color crunch  
Banding, oversaturation, or simplified color logic in small graphics.

\#\#\# Composite crunch  
Visible mismatch between layers that still somehow looks right.

\---

\#\# The desired balance

The style does not always want maximum damage.

There is a sweet spot:

\- enough crunch to feel native  
\- enough readability to preserve the motif  
\- enough artifact behavior to resist modern overpolish  
\- not so much degradation that the thing becomes unreadable mush

Think:  
\*\*styled damage, not complete collapse\*\*

\---

\#\# Failure modes

\#\#\# Too clean  
Looks like polished retro-inspired graphic design.

\#\#\# Too high-resolution  
Loses native web-asset energy.

\#\#\# Too realistic  
Turns glitter and chrome into physically plausible materials rather than symbolic glamour surfaces.

\#\#\# Too degraded  
Loses legibility and symbolic clarity.

\#\#\# Noise with no purpose  
Random degradation that does not reinforce the style becomes generic “distressed” effect abuse.

\---

\#\# Practical application for generation

When aiming for correct style behavior, prefer language and systems that preserve:

\- noisy glitter density  
\- slightly crude outlines  
\- visible sparkle grain  
\- cutout separation  
\- low-res edge behavior  
\- compressed glow weirdness  
\- synthetic shine over realism

Do not default to:  
\- ultra-clean vector perfection  
\- luxurious editorial polish  
\- realistic metal/glass rendering  
\- sterile high-resolution gradients

\---

\#\# Guiding sentence

A correct piece in this style should often look like it has survived the web a little.

Not destroyed.  
Just gloriously, stylishly, a little chewed up.

That bite mark is part of the charm.

---

### **`11_drift_control/anti_drift.md`**

\# Anti-Drift

This document defines the main rules for keeping the style from drifting into neighboring aesthetics or weak modern reinterpretations.

This is one of the most important files in the repo.

\---

\#\# Purpose

The style is vulnerable to drift because many adjacent aesthetics share some of its surface traits:

\- sparkles  
\- pinks and purples  
\- Y2K associations  
\- internet nostalgia  
\- cute graphics  
\- dark web backgrounds  
\- stickers  
\- glitter

That means a generation can look “kind of related” while still being wrong.

This file exists to stop that bullshit.

\---

\#\# Core anti-drift principle

Do not judge correctness by isolated ingredients.

Judge correctness by \*\*how the ingredients are organized\*\*.

A correct output is not just:  
\- glitter  
\- pink  
\- stars  
\- old-web references

A correct output is a coordinated system of:  
\- decorative intent  
\- synthetic material logic  
\- asset/page behavior  
\- emotional tackiness  
\- symbolic clarity  
\- artifact-friendly rendering  
\- correct substyle deployment

\---

\#\# Rule 1: Preserve decorative selfhood or shrine logic

The style should feel like it is doing one of these:

\- decorating the self  
\- decorating the page as a personal world  
\- performing identity through ornament  
\- building a shrine-like decorative environment

If the output is merely pretty or nostalgic, it is probably drifting.

\---

\#\# Rule 2: Preserve synthetic glamour

The style needs fake luxury and synthetic shine signals such as:

\- glitter  
\- chrome  
\- gel  
\- starbursts  
\- glow halos  
\- plastic gem energy  
\- sticker surfaces

If these are absent, the style loses its glam-trash engine.

\---

\#\# Rule 3: Preserve artifact tolerance

Do not over-clean.

This style often needs:  
\- crunch  
\- halo weirdness  
\- low-res charm  
\- compositing roughness  
\- obvious digital effect stacking

A perfectly polished output often reads wrong even when the motifs are technically correct.

\---

\#\# Rule 4: Preserve symbolic directness

The style likes obvious, legible, emotionally loaded symbols:  
\- hearts  
\- crowns  
\- stars  
\- skulls  
\- bunnies  
\- lips  
\- slogans  
\- princess/diva/bad-girl markers  
\- celestial filler

If the symbolism becomes too abstract, tasteful, or conceptually distant, drift is happening.

\---

\#\# Rule 5: Preserve tackiness

Tastefulness is dangerous here.

The style often needs:  
\- shamelessness  
\- excess  
\- a little bad taste  
\- too much glitter  
\- too much shine  
\- too much declaration  
\- decorative audacity

A refined, restrained, sophisticated version may be adjacent, but it is not the core style.

\---

\#\# Rule 6: Preserve correct branch logic

Ask which branch is dominant:

\#\#\# Myspace branch  
\- self-decoration  
\- profile ornament  
\- asset-pack logic  
\- slogan graphics  
\- identity badge energy

\#\#\# Angelfire branch  
\- page-world logic  
\- shrine atmosphere  
\- tiled background energy  
\- handmade web environment  
\- button/blinkie/counter ecology

If the output mixes both branches equally without structure, it may become mush.

Pick a dominant branch first.

\---

\#\# Rule 7: Preserve black-stage or contrast-stage behavior when needed

Many strong examples rely on:  
\- black backgrounds  
\- night-stage contrast  
\- glowing contrast fields  
\- void-like page staging

Do not replace this with soft editorial backgrounds unless the specific substyle calls for it.

\---

\#\# Rule 8: Preserve asset-ness when asset-ness matters

Many graphics should feel like:  
\- isolated assets  
\- stickers  
\- badges  
\- drop-in ornaments  
\- detachable pieces of page decoration

If everything becomes painterly or fully integrated into a seamless illustration, the style drifts away from web graphic logic.

\---

\#\# Rule 9: Preserve page ecology in Angelfire mode

Angelfire mode is not just “dark glitter graphics.”

It needs page-life signals such as:  
\- tiled backgrounds  
\- themed clutter  
\- portal or shrine energy  
\- button/divider ecology  
\- obsessive handmade page-building

Without page logic, it collapses into generic dark glitter aesthetic.

\---

\#\# Rule 10: Preserve trash-glam tension

A huge part of the style lives in the tension between:

\- glamour aspiration  
\- technical cheapness

The style should not become:  
\- fully elegant  
\- fully ironic  
\- fully polished  
\- fully broken

It works best when it feels like it desperately wants to be glamorous and is using every cheap digital trick available to get there.

That’s the beating heart.

\---

\#\# Common drift directions

\#\#\# Drift A: Generic Y2K  
Symptoms:  
\- smoother gradients  
\- sleeker tech shapes  
\- less page logic  
\- less glitter-trash tackiness  
\- more product-design futurism

Repair:  
\- add sticker logic  
\- add glitter grit  
\- add slogan/badge behavior  
\- add web-asset roughness

\---

\#\#\# Drift B: Kawaii sticker culture  
Symptoms:  
\- too clean  
\- too pastel  
\- too cute  
\- too gentle  
\- lacking fake luxury and trash edge

Repair:  
\- increase chrome/glitter/glow  
\- introduce sharper contrast  
\- add bratty or mall-trash tone  
\- restore crunch and black-stage drama

\---

\#\#\# Drift C: Vaporwave / webcore mush  
Symptoms:  
\- atmospheric nostalgia  
\- vague browser-era collage  
\- less symbolic directness  
\- less decorative self-performance

Repair:  
\- add stronger motifs  
\- add explicit badge/slogan structures  
\- restore profile/shrine intent  
\- increase synthetic ornament

\---

\#\#\# Drift D: Generic goth web  
Symptoms:  
\- darkness without cute-trash crossover  
\- occult/fantasy heaviness with no glam sparkle foolishness  
\- too serious

Repair:  
\- add glitter  
\- add cheap luxury  
\- add cute or bratty counter-signal  
\- reintroduce synthetic ornament and playful symbols

\---

\#\#\# Drift E: Modern retro branding  
Symptoms:  
\- too tasteful  
\- too legible  
\- too balanced  
\- too clean  
\- too professionally art-directed

Repair:  
\- dirty it up  
\- make it tackier  
\- add asset-pack awkwardness  
\- add halo weirdness  
\- reduce polish  
\- increase excess

\---

\#\# Quick diagnostic checklist

Ask:

1\. Does this feel like self-decoration or shrine-decoration?  
2\. Does it use fake glamour surfaces?  
3\. Does it tolerate or benefit from crunch?  
4\. Are the symbols emotionally direct?  
5\. Is there enough tacky excess?  
6\. Is the substyle branch clear?  
7\. Does it feel native to web graphics culture?  
8\. Is it too tasteful, too clean, or too modern?

If several answers come back wrong, drift is happening.

\---

\#\# Final anti-drift sentence

This style should feel like a person or page trying very hard, very sincerely, and very loudly to be magical, glamorous, cute, dramatic, or iconic using the available tools of cheap web graphics culture.

If that sincerity, excess, and synthetic tackiness disappear, the style is probably dead.

---

That’s the first skeleton slab nailed down.

Next smartest batch is:  
**`style_pillars.md` \+ `what_this_style_is_not.md` \+ `motif_families.md` \+ `typography_families.md` \+ `composition_grammar.md` \+ `myspace_profile_bling.md` \+ `angelfire_shrine_chaos.md` \+ `prompt_formula_short.md`**.

Continuing the approved repo build in separate file blocks.

### **`01_core_definition/style_pillars.md`**

\# Style Pillars

This document defines the load-bearing pillars of the Myspace \+ Angelfire graphics style.

If too many of these are missing, the output may still be sparkly or nostalgic, but it will no longer belong to the core style system.

\---

\#\# Why pillars matter

A style can survive variation, but it cannot survive the loss of its structural traits.

These pillars are the traits that keep the style from dissolving into:  
\- generic Y2K  
\- kawaii sticker design  
\- vaporwave web nostalgia  
\- polished retro branding  
\- random glitter clutter  
\- generic goth web aesthetics

Think of them as the style’s spine, not its accessories.

\---

\#\# Pillar 1: Ornament as identity or devotion

The style treats decoration as meaningful.

Decoration is not merely visual filler. It functions as:  
\- self-branding  
\- self-performance  
\- mood declaration  
\- devotion  
\- obsession  
\- fantasy projection  
\- page-world building

In Myspace mode, ornament is often about the self:  
\- “this is me”  
\- “this is my vibe”  
\- “this is how I want to be seen”

In Angelfire mode, ornament is often about the page-world:  
\- “enter my realm”  
\- “this is my shrine”  
\- “this page is a portal, mood chamber, or obsession zone”

Without this layer of intent, the style becomes empty decoration.

\---

\#\# Pillar 2: Synthetic glamour

The style runs on fake glamour.

That glamour is usually expressed through:  
\- glitter  
\- chrome  
\- gel lettering  
\- rhinestone-like sparkle  
\- metallic fakery  
\- plastic gem energy  
\- white starburst shine  
\- exaggerated glow

These effects do not need to be realistic.  
In fact, realism can make them worse.

They need to be legible as:  
\- flashy  
\- precious  
\- glam  
\- shiny  
\- magical  
\- extra

The style does not worship refinement.  
It worships seduction through cheap spectacle.

\---

\#\# Pillar 3: Asset logic or page ecology

This style usually operates in one of two structural modes:

\#\#\# Asset logic  
Graphics feel like detachable pieces:  
\- stickers  
\- glitter text  
\- badges  
\- cutout icons  
\- transparent ornaments  
\- buttons  
\- blinkies

\#\#\# Page ecology  
The page feels like a whole living environment:  
\- tiled backgrounds  
\- layered clutter  
\- repeated motifs  
\- portal/splash structure  
\- shrine layout  
\- link button ecosystems  
\- counters and dividers

A correct output typically commits to one of these as the dominant logic.

Without either, the result may look adjacent but weak.

\---

\#\# Pillar 4: Emotional directness

The style is emotionally loud.

It often communicates in direct signals:  
\- cute  
\- princess  
\- diva  
\- angel  
\- baby girl  
\- bad girl  
\- brat  
\- dark-cute  
\- dreamy  
\- magical  
\- shrine-like  
\- dramatic

This style is not emotionally reserved.  
It announces itself.

Even when the image is dumb or kitschy, it is rarely detached.

\---

\#\# Pillar 5: Tackiness as power

Tackiness is not an accidental side effect.  
It is a central strength.

This style often works because it is:  
\- too much  
\- too glittery  
\- too loud  
\- too decorated  
\- too obvious  
\- too direct  
\- too shiny  
\- too self-declared

Modern taste often tries to shave off exactly the qualities that make this style alive.

Do not let it.

A little vulgarity is part of the magic.

\---

\#\# Pillar 6: Artifact-positive rendering

The style is natively comfortable with:  
\- compression  
\- crunchy edges  
\- primitive glow  
\- weird transparency  
\- rough compositing  
\- low-res sparkle  
\- repasted asset behavior

These are not merely tolerated.  
They often help.

This style was born in:  
\- saved graphics  
\- reused web assets  
\- small GIFs  
\- page layouts  
\- low-resolution display contexts  
\- homebrew digital assembly

If rendered too cleanly, the style can lose its native atmosphere.

\---

\#\# Pillar 7: Symbolic legibility

The style loves symbols that read fast.

Common examples:  
\- hearts  
\- stars  
\- crowns  
\- lips  
\- butterflies  
\- bunnies  
\- skulls  
\- moons  
\- angels  
\- devils  
\- slogan text  
\- badges and stamps

These symbols matter because they let the style communicate identity and mood immediately.

The symbol system should be:  
\- clear  
\- iconic  
\- repeatable  
\- glamorized  
\- emotionally coded

The style usually does not prefer subtle metaphor over readable iconography.

\---

\#\# Pillar 8: High-contrast stagecraft

The style often depends on strong visual staging.

This often includes:  
\- black backgrounds  
\- void-like page space  
\- bright outlines  
\- glow halos  
\- sparkle contrast  
\- hot local contrast between asset and backdrop

This stagecraft makes even crude graphics feel intense.

The contrast is not always technically elegant.  
It is theatrically effective.

\---

\#\# Pillar 9: Decorative excess with internal purpose

The style is maximalist, but not meaningless.

Correct clutter usually has some role:  
\- mood intensification  
\- identity reinforcement  
\- symbolic repetition  
\- page immersion  
\- visual seduction  
\- shrine behavior

Wrong clutter feels random.

Correct clutter feels like someone cared too much and decorated the shit out of everything on purpose.

That is a feature, not a flaw.

\---

\#\# Pillar 10: Sincerity inside performance

Even when the style is funny, trashy, or ridiculous, it is often sincere.

It sincerely wants to be:  
\- beautiful  
\- glamorous  
\- magical  
\- iconic  
\- emotionally charged  
\- cute  
\- haunted  
\- adored  
\- noticed

This sincerity is important.

If the output feels too ironic, too design-school detached, or too knowingly tasteful, it often loses the emotional charge that makes the style work.

\---

\#\# Pillar interaction model

These pillars do not function in isolation.

A strong piece usually combines several at once:

\- synthetic glamour  
\- emotional directness  
\- symbolic legibility  
\- artifact-positive rendering  
\- asset logic or page ecology  
\- tacky intensity

That combination is what creates the proper read.

\---

\#\# Minimum viable style test

At minimum, a correct output should usually satisfy most of these:

\- decoration has clear expressive purpose  
\- fake glamour is visible  
\- symbols are direct and legible  
\- the rendering is not over-sanitized  
\- either asset logic or page ecology is present  
\- the mood is emotionally declarative  
\- some degree of tacky excess survives

If too many of those are absent, the piece is probably drifting.

\---

\#\# Summary sentence

This style is built on the idea that a page or graphic should perform selfhood, fantasy, or shrine-intensity through cheap synthetic glamour, symbolic clutter, and unapologetic decorative excess.

That is the load-bearing religion.

### **`01_core_definition/what_this_style_is_not.md`**

\# What This Style Is Not

This document defines the style by contrast.

That matters because this style has many neighboring aesthetics that share some ingredients while operating on totally different logic.

The point here is not to be uptight.  
The point is to stop weak-ass drift.

\---

\#\# Why negatives matter

Many incorrect outputs will contain:  
\- glitter  
\- pinks and purples  
\- stars  
\- black backgrounds  
\- internet nostalgia  
\- cute symbols

That does not make them correct.

This style is defined not just by ingredients, but by:  
\- deployment logic  
\- emotional tone  
\- material behavior  
\- artifact tolerance  
\- page or asset structure  
\- sincerity of decorative intent

So this document names what the style is \*\*not\*\*, even when it overlaps visually.

\---

\#\# Not generic Y2K

This style is not the same as broad Y2K aesthetics.

\#\#\# Generic Y2K often emphasizes:  
\- chrome futurism  
\- tech gloss  
\- airbrushed smoothness  
\- sleek industrial curves  
\- product-design polish  
\- glossy magazine-era futurism

\#\#\# This style instead emphasizes:  
\- webpage decoration  
\- glitter graphics  
\- sticker logic  
\- badge/slogan behavior  
\- low-res glam-trash  
\- profile ornament  
\- shrine-page clutter

You can mix Y2K in, but if the result becomes mainly sleek, futuristic, and polished, it has drifted.

\---

\#\# Not vaporwave by default

This style is not vaporwave unless explicitly mixed.

\#\#\# Vaporwave often emphasizes:  
\- irony  
\- dreamlike consumer decay  
\- pastel haze  
\- retro-futurist atmosphere  
\- ambient nostalgia  
\- conceptual art-school framing

\#\#\# This style instead emphasizes:  
\- direct decoration  
\- obvious symbolism  
\- glitter and tacky glam  
\- page identity  
\- amateur compositing charm  
\- self-performance or shrine intent

Vaporwave often floats.  
This style decorates aggressively.

\---

\#\# Not kawaii sticker culture

This style is not clean kawaii design.

\#\#\# Kawaii sticker culture often emphasizes:  
\- sweetness  
\- cuteness  
\- soft palettes  
\- clean vectors  
\- polished friendliness  
\- gentle surface charm

\#\#\# This style instead often needs:  
\- tackiness  
\- trash-glam  
\- black stage contrast  
\- chrome or glitter aggression  
\- sharper emotional declaration  
\- cheaper, louder synthetic surfaces

It may be cute, but it is usually not cleanly cute.

\---

\#\# Not polished modern nostalgia branding

This style is not a tasteful brand campaign doing “internet nostalgia.”

\#\#\# Modern nostalgia branding often emphasizes:  
\- careful restraint  
\- balanced layouts  
\- high-res gloss  
\- intentional minimalism  
\- cleaned-up retro signals  
\- designerly control

\#\#\# This style instead often wants:  
\- clutter  
\- shamelessness  
\- rough edges  
\- synthetic excess  
\- visible effect-stacking  
\- emotional loudness

If it looks like an expensive agency moodboard for a soda collab, it has probably lost the plot.

\---

\#\# Not webcore as a catch-all

This style is not just “webcore.”

\#\#\# Generic webcore often emphasizes:  
\- browser nostalgia  
\- cursors  
\- windows  
\- desktop fragments  
\- low-fi digital weirdness  
\- mixed-era internet relics

\#\#\# This style instead centers:  
\- glitter assets  
\- shrine pages  
\- cutout graphics  
\- profile decorations  
\- page ornament ecology  
\- emotional decorative coding

Webcore is broader and fuzzier.  
This style is narrower and tackier.

\---

\#\# Not generic goth web

This style is not simply dark early-web aesthetic.

\#\#\# Generic goth web often emphasizes:  
\- darkness  
\- occult symbols  
\- black and red palettes  
\- vampires, crosses, graveyards  
\- poetic gloom  
\- moody seriousness

\#\#\# This style, even when dark, usually still includes:  
\- glitter or sparkle  
\- fake luxury  
\- cute-trash crossover  
\- bratty or decorative playfulness  
\- glam shine  
\- sticker-like iconography

Without those, it may be goth web, but not this specific thing.

\---

\#\# Not scene/emo by default

This style is not automatically scene or emo.

There is overlap in:  
\- black backgrounds  
\- bright accents  
\- digital trashiness  
\- page decoration  
\- glitter and attitude

But scene/emo often centers:  
\- fashion-subculture signaling  
\- striped/neon/raver crossover  
\- hair and music-scene identity  
\- specific youth subculture codes

This style can touch that territory, but its center is broader decorative web glam and shrine logic.

\---

\#\# Not scrapbook collage

This style is not handmade paper nostalgia.

\#\#\# Scrapbook collage often emphasizes:  
\- paper textures  
\- torn edges  
\- handwritten softness  
\- analog intimacy  
\- pastel memory-book atmosphere

\#\#\# This style instead emphasizes:  
\- screen-born surfaces  
\- digital glow  
\- cutout assets  
\- chrome/glitter/gel fakery  
\- webpage ecology  
\- neon or blacklight contrast

This style lives on the screen, not in a paper journal.

\---

\#\# Not minimal by design

This style is not a minimal aesthetic.

Even when a single graphic is simple, the underlying logic still tends toward:  
\- ornament  
\- declaration  
\- symbolism  
\- visual embellishment  
\- effect stacking  
\- expressive overkill

If the result feels elegantly underdesigned, it is probably drifting out of the style field.

\---

\#\# Not irony-first

This style can be campy and funny, but it is not usually best when treated as detached irony.

A correct piece often feels like it genuinely wants:  
\- attention  
\- glamour  
\- fantasy  
\- identity  
\- magic  
\- devotion  
\- aesthetic overload

If the piece feels like it is smirking at itself too much, it can lose the sincerity that makes the style hit.

\---

\#\# Not realistic material rendering

This style is not about convincing physical realism.

Its surfaces often reference:  
\- glitter  
\- chrome  
\- gems  
\- plastic  
\- gel  
\- metallic foil

But those are usually stylized signal systems, not physically accurate render targets.

If the surfaces become too realistic, the work can start feeling like luxury product mockups instead of web graphics.

\---

\#\# Not neutral design

This style is not neutral information design.

It is usually:  
\- mood-heavy  
\- identity-coded  
\- emotionally declarative  
\- symbol-rich  
\- attention-seeking

If a piece feels visually neutral, restrained, or purely informational, it is probably in the wrong neighborhood.

\---

\#\# Frequent false friends

The styles most likely to get confused with this one are:  
\- generic Y2K  
\- webcore  
\- vaporwave  
\- kawaii sticker design  
\- goth web  
\- scene graphics  
\- modern retro branding  
\- dark-cute pop graphics

All of these can overlap with the repo.  
None of them should automatically replace it.

\---

\#\# Quick wrongness test

If the output feels mostly like:  
\- sleek future nostalgia  
\- dreamy pastel web collage  
\- clean cute sticker design  
\- dark moody goth without glam-trash  
\- modern curated retro branding  
\- generic early-internet artifact soup

then it is probably not correct yet.

\---

\#\# Summary sentence

This style is not just old internet with glitter on it.

It is a specific culture of synthetic self-decoration and shrine-page ornament, driven by tacky glamour, symbolic clarity, artifact-rich rendering, and shameless decorative intent.

### **`02_visual_dna/motif_families.md`**

\# Motif Families

This document organizes the major recurring motif families used in the Myspace \+ Angelfire graphics style.

These motifs are not random decoration.  
They function as fast emotional symbols, identity markers, page ornaments, and glam amplifiers.

\---

\#\# Why motif families matter

This style depends heavily on recurring symbolic inventory.

Motifs do important work:  
\- identify mood  
\- signal personality  
\- glamorize page space  
\- anchor decorative clusters  
\- intensify substyle identity  
\- make graphics feel reusable and modular

The style often prefers motifs that are:  
\- iconic  
\- emotionally legible  
\- easy to cut out  
\- easy to repeat  
\- easy to glitterify  
\- easy to combine with text

\---

\#\# Family 1: Hearts

\#\#\# Core meanings  
\- romance  
\- cuteness  
\- sweetness  
\- desirability  
\- self-love  
\- flirtation  
\- femininity  
\- glam softness

\#\#\# Common forms  
\- solid hearts  
\- outlined hearts  
\- glitter hearts  
\- gem hearts  
\- metallic hearts  
\- winged hearts  
\- broken hearts  
\- heart clusters  
\- heart backgrounds

\#\#\# Typical use  
\- slogan graphics  
\- profile ornament  
\- badge framing  
\- decorative filler  
\- cutout assets

\#\#\# Notes  
Hearts are one of the most foundational motifs in the style.  
They easily tilt toward Myspace profile bling.

\---

\#\# Family 2: Stars and sparkle marks

\#\#\# Core meanings  
\- shine  
\- magic  
\- glamour  
\- attention  
\- heavenly energy  
\- decorative excitement

\#\#\# Common forms  
\- four-point stars  
\- six-point twinkles  
\- glitter particles  
\- starbursts  
\- tiny white sparkle dots  
\- outlined stars  
\- cartoon stars

\#\#\# Typical use  
\- overlays  
\- halo intensifiers  
\- page filler  
\- space backgrounds  
\- glamour marks around text or icons

\#\#\# Notes  
This family often bridges both substyles.  
In Myspace mode it boosts glam.  
In Angelfire mode it can become environmental.

\---

\#\# Family 3: Crowns and tiara forms

\#\#\# Core meanings  
\- princess identity  
\- diva energy  
\- status  
\- fake royalty  
\- self-mythology  
\- bratty glamour

\#\#\# Common forms  
\- small crown above text  
\- gem crown icons  
\- chrome tiaras  
\- heart-topped crowns  
\- sticker crowns

\#\#\# Typical use  
\- name graphics  
\- princess/diva slogans  
\- profile signals  
\- status markers  
\- decorative punctuation

\#\#\# Notes  
Crowns are especially strong in identity-performance pieces.

\---

\#\# Family 4: Lips, kisses, and mouth marks

\#\#\# Core meanings  
\- flirtation  
\- sexiness  
\- vanity  
\- glamour  
\- bratty attitude  
\- feminine display

\#\#\# Common forms  
\- lip silhouettes  
\- lipstick kiss prints  
\- glossy mouth icons  
\- small repeating kiss marks  
\- lip cutout stickers

\#\#\# Typical use  
\- slogan graphics  
\- profile bling  
\- attitude badges  
\- decorative clusters

\#\#\# Notes  
These motifs tend to push the style toward mall-trash glam and flirty Myspace energy.

\---

\#\# Family 5: Bunnies and cute silhouettes

\#\#\# Core meanings  
\- sexy-cute duality  
\- playful femininity  
\- flirt iconography  
\- recognizable trash-glam shorthand

\#\#\# Common forms  
\- bunny heads  
\- silhouette bunnies  
\- stylized cartoon rabbits  
\- repeating bunny patterns

\#\#\# Typical use  
\- badges  
\- small cutout ornaments  
\- sticker packs  
\- repeat backgrounds  
\- flirty icon mixes

\#\#\# Notes  
This family can tip the work toward a specific era-coded trash-glam vibe very quickly.

\---

\#\# Family 6: Butterflies, wings, and flutter forms

\#\#\# Core meanings  
\- transformation  
\- dreaminess  
\- magical femininity  
\- ethereal decoration  
\- lightness  
\- romantic fantasy

\#\#\# Common forms  
\- glitter butterflies  
\- purple or pink butterfly icons  
\- winged hearts  
\- angel wings behind symbols  
\- wing embellishments on text

\#\#\# Typical use  
\- dreamy page clutter  
\- shrine-page symbols  
\- cutout assets  
\- decorative framing

\#\#\# Notes  
Butterflies and wings bridge cute glam and shrine fantasy.  
They are particularly useful in softer or more celestial variants.

\---

\#\# Family 7: Skulls, crossbones, and dark-cute hazard symbols

\#\#\# Core meanings  
\- rebellion  
\- brat menace  
\- punky cuteness  
\- anti-sweetness  
\- danger as decoration  
\- dark-cute contradiction

\#\#\# Common forms  
\- glitter skulls  
\- pink skulls  
\- skull with bow motifs  
\- crossbones  
\- gothic-cute skull badges

\#\#\# Typical use  
\- dark-cute graphics  
\- toxic cute palettes  
\- bratty slogan assets  
\- alt-glam variants

\#\#\# Notes  
This family is important because it keeps the style from becoming only sugary.  
It adds edge and contradiction.

\---

\#\# Family 8: Angels, devils, halos, and moral-play icons

\#\#\# Core meanings  
\- innocence vs mischief  
\- flirtation through contrast  
\- fantasy morality play  
\- cute corruption  
\- spiritualized drama  
\- page-devotion

\#\#\# Common forms  
\- angel wings  
\- halo above text  
\- little devil tails or horns  
\- angel/devil paired symbols  
\- celestial innocence markers

\#\#\# Typical use  
\- slogans  
\- shrine pages  
\- heavenly/dark-cute hybrids  
\- icon clusters

\#\#\# Notes  
This family can lean Myspace in a flirty way or Angelfire in a mystical/shrine way.

\---

\#\# Family 9: Celestial fillers

\#\#\# Core meanings  
\- cosmic mood  
\- night page atmosphere  
\- dreamspace  
\- magical vastness  
\- shrine aura

\#\#\# Common forms  
\- moons  
\- stars  
\- planets  
\- galaxies  
\- night-sky sparkles  
\- zodiac-like signs  
\- constellations  
\- nebula-ish glow fields

\#\#\# Typical use  
\- backgrounds  
\- shrine pages  
\- portal/splash pages  
\- cosmic wallpaper systems  
\- black void intensification

\#\#\# Notes  
Celestial fillers are a major Angelfire-side motif family, but they can also decorate glam assets.

\---

\#\# Family 10: Princess/diva/baby-girl text concepts

\#\#\# Core meanings  
\- self-branding  
\- fantasy identity  
\- desirability  
\- attitude  
\- fake status  
\- decorative ego-performance

\#\#\# Common forms  
\- “princess”  
\- “diva”  
\- “baby girl”  
\- “angel”  
\- “bad girl”  
\- “100% cute”  
\- “spoiled”  
\- “hot stuff”  
\- “gangsta princess”

\#\#\# Typical use  
\- slogan graphics  
\- badges  
\- text-centered assets  
\- identity decorations

\#\#\# Notes  
Technically text, but functionally this family behaves like motif inventory because the phrases act like symbolic emblems.

\---

\#\# Family 11: Precious object motifs

\#\#\# Core meanings  
\- fake wealth  
\- glamour  
\- self-adornment  
\- luxury fantasy  
\- preciousness

\#\#\# Common forms  
\- gems  
\- diamonds  
\- rhinestone scatters  
\- metallic stars  
\- jewel-encrusted hearts  
\- shiny lockets  
\- chrome forms

\#\#\# Typical use  
\- graphic embellishment  
\- letter decoration  
\- glam intensification  
\- faux-status signals

\#\#\# Notes  
These motifs often blend into material effects, but they are still useful as a distinct symbolic family.

\---

\#\# Family 12: Page ecology motifs

\#\#\# Core meanings  
\- webpage life  
\- navigability as decoration  
\- handmade digital habitat  
\- shrine-system presence

\#\#\# Common forms  
\- blinkies  
\- tiny buttons  
\- dividers  
\- counters  
\- “enter” graphics  
\- guestbook markers  
\- web rings  
\- decorative separators

\#\#\# Typical use  
\- Angelfire-style page construction  
\- banner systems  
\- navigation ornament  
\- small clutter zones

\#\#\# Notes  
These motifs are absolutely crucial for webpage logic and should not be ignored just because they are functional.

\---

\#\# Family 13: Cute-trash filler packs

\#\#\# Core meanings  
\- decorative surplus  
\- emotional density  
\- page excitement  
\- icon ecology

\#\#\# Common forms  
\- cherries  
\- bows  
\- flowers  
\- stars  
\- tiny dots  
\- mini charms  
\- little smile or wink icons  
\- repeated glam clutter units

\#\#\# Typical use  
\- edge decoration  
\- backgrounds  
\- cluster fills  
\- badge padding

\#\#\# Notes  
These motifs keep compositions from feeling empty.  
They also help bridge between main symbols.

\---

\#\# Motif deployment rules

A strong output usually does not use motifs randomly.

Good motif deployment usually has:  
\- one dominant family  
\- one or two support families  
\- repeated symbolic logic  
\- emotional consistency  
\- integration with palette and text

Bad deployment often feels like:  
\- unrelated sticker vomit  
\- random icon pile  
\- novelty without symbolic center

\---

\#\# Myspace-leaning families

Most strongly associated with Myspace profile bling:  
\- hearts  
\- crowns  
\- lips  
\- princess/diva text  
\- bunny silhouettes  
\- precious object motifs

\---

\#\# Angelfire-leaning families

Most strongly associated with shrine-page chaos:  
\- celestial fillers  
\- angels/devils  
\- butterflies/wings  
\- page ecology motifs  
\- starfield-heavy sparkle systems

\---

\#\# Bridge families

Useful in both:  
\- stars  
\- hearts  
\- glitter signals  
\- dark-cute skull forms  
\- slogan emblems  
\- small decorative filler icons

\---

\#\# Summary sentence

The motif system of this style is a fast-reading symbolic language built from cute, glam, celestial, trashy, flirty, and shrine-coded icons that can be cut out, repeated, sparkled, and stacked into decorative identity.

### **`02_visual_dna/typography_families.md`**

\# Typography Families

This document defines the major text and lettering families used in the style.

Typography here does not behave like neutral information design.  
It behaves like ornament, attitude, identity, and visual objecthood.

\---

\#\# Core principle

In this style, text is often not just text.

It is:  
\- a badge  
\- a sticker  
\- a declaration  
\- a glamour surface  
\- a self-label  
\- a decorative anchor

That means typography decisions are not mainly about readability in a modern design sense.  
They are about emotional and symbolic impact.

\---

\#\# Family 1: Glitter fill text

\#\#\# Core behavior  
Letterforms are filled with glitter texture or sparkle-heavy material simulation.

\#\#\# Common traits  
\- bright pink or purple glitter  
\- white sparkle flecks  
\- noisy inner texture  
\- thick enough shapes to hold the glitter read  
\- paired with outlines or halos

\#\#\# Typical emotional read  
\- glamorous  
\- cute  
\- flashy  
\- high-attention  
\- mall-trash luxurious

\#\#\# Common use  
\- names  
\- short slogans  
\- badges  
\- status labels  
\- “princess/diva/angel” style declarations

\#\#\# Notes  
This is one of the most iconic text families in the entire style.

\---

\#\# Family 2: Bubble and rounded cute text

\#\#\# Core behavior  
Soft rounded letters with playful, puffy, or candy-like shapes.

\#\#\# Common traits  
\- circular counters  
\- thick strokes  
\- simple silhouettes  
\- often pink, lavender, or white  
\- often combined with sparkles or outlines

\#\#\# Typical emotional read  
\- cute  
\- sweet  
\- girly  
\- approachable  
\- toy-like

\#\#\# Common use  
\- cute slogans  
\- icons with friendly energy  
\- lighthearted badges  
\- Myspace-style decorative text

\#\#\# Notes  
If rendered too cleanly, this family can drift toward kawaii sticker culture.  
It often needs trash-glam support.

\---

\#\# Family 3: Beveled chrome or faux-metal text

\#\#\# Core behavior  
Letterforms imitate metallic, chrome, silver, or glossy gem-like surfaces.

\#\#\# Common traits  
\- sharp highlight bands  
\- bright white shine areas  
\- silver gradients or faux foil  
\- outlined shapes  
\- embossed or beveled illusion

\#\#\# Typical emotional read  
\- fake luxury  
\- diva glam  
\- status  
\- nightclub/mall-kiosk excess

\#\#\# Common use  
\- title text  
\- badge text  
\- “hot stuff” style declarations  
\- glam-focused stickers

\#\#\# Notes  
This family works best when a little tacky.  
Over-refined chrome tends to drift toward generic Y2K or luxury branding.

\---

\#\# Family 4: Gel or jelly text

\#\#\# Core behavior  
Letterforms look swollen, glossy, soft-plastic, or gummy.

\#\#\# Common traits  
\- rounded volume cues  
\- shiny top highlights  
\- candy-material feel  
\- bright, saturated colors  
\- soft 3D illusion without realism

\#\#\# Typical emotional read  
\- playful  
\- synthetic  
\- cute  
\- cheap luxurious  
\- sticker-like

\#\#\# Common use  
\- short labels  
\- decorative names  
\- bright badge text  
\- candy-girl variants

\#\#\# Notes  
This family is good for soft glam, but can get too modern if not dirtied up with artifact logic.

\---

\#\# Family 5: Script and faux-romantic lettering

\#\#\# Core behavior  
Curvy script or cursive-leaning forms that signal romance, softness, fantasy, or glam femininity.

\#\#\# Common traits  
\- swooping strokes  
\- ornamental capitals  
\- decorative tails  
\- often with glow, glitter, or outlines  
\- not always highly legible

\#\#\# Typical emotional read  
\- dreamy  
\- romantic  
\- feminine  
\- dramatic  
\- vanity-coded

\#\#\# Common use  
\- page titles  
\- names  
\- sentimental badges  
\- shrine-page headings  
\- “angel,” “princess,” or devotional phrases

\#\#\# Notes  
This family is especially useful in softer glam or shrine-page variants.

\---

\#\# Family 6: Gothic-lite or fantasy title text

\#\#\# Core behavior  
Text borrows from gothic, blackletter-ish, or fantasy title cues without becoming fully medieval or serious.

\#\#\# Common traits  
\- sharp terminals  
\- decorative capitals  
\- dark or metallic coloring  
\- glow or halo support  
\- dramatic contrast against black backgrounds

\#\#\# Typical emotional read  
\- mystical  
\- haunted  
\- dramatic  
\- devotional  
\- dark-cute

\#\#\# Common use  
\- Angelfire-style page titles  
\- shrine names  
\- portal page headers  
\- dark celestial text assets

\#\#\# Notes  
This family must usually stay in dialogue with glitter, glow, or cute-trash signals so it does not drift into pure goth web.

\---

\#\# Family 7: Badge slogan text

\#\#\# Core behavior  
Short declarative phrases designed like emblems rather than paragraphs.

\#\#\# Common traits  
\- bold, compact wording  
\- decorative packaging  
\- outline emphasis  
\- icon accompaniment  
\- emotionally direct language

\#\#\# Common text types  
\- “100% cute”  
\- “princess”  
\- “spoiled”  
\- “angel”  
\- “bad girl”  
\- “diva”  
\- “hot stuff”

\#\#\# Typical emotional read  
\- self-labeling  
\- instant identity  
\- dramatic shorthand  
\- decorative attitude

\#\#\# Common use  
\- profile graphics  
\- comments  
\- small stamps  
\- reusable assets

\#\#\# Notes  
This family is less about a specific font and more about a typographic function.

\---

\#\# Family 8: Outline-heavy sticker text

\#\#\# Core behavior  
Text is separated strongly from background by thick outlines, glow edges, or border emphasis.

\#\#\# Common traits  
\- white outer stroke  
\- dark or silver inner border  
\- halo edge  
\- cutout readability  
\- strong silhouette

\#\#\# Typical emotional read  
\- sticker-like  
\- high-visibility  
\- web-asset native  
\- page-drop-in ready

\#\#\# Common use  
\- all-purpose graphic text  
\- black-background page decor  
\- tiny web graphics  
\- badge layering

\#\#\# Notes  
This is one of the most useful families for maintaining asset logic.

\---

\#\# Family 9: Pixel-small utility text and button text

\#\#\# Core behavior  
Tiny text used in buttons, blinkies, counters, or navigation objects.

\#\#\# Common traits  
\- compressed visibility  
\- simple all-caps or block text  
\- low-res survival  
\- often paired with bars, frames, or GIF behavior

\#\#\# Typical emotional read  
\- page ecology  
\- web-native functionality  
\- handmade digital habitat

\#\#\# Common use  
\- buttons  
\- blinkies  
\- navigation strips  
\- little page widgets

\#\#\# Notes  
These are especially important on the Angelfire side.

\---

\#\# Key typography behaviors across families

\#\#\# 1\. Text as image  
Text is often treated like a graphic object with its own surface and ornament.

\#\#\# 2\. High embellishment  
Letterforms frequently use:  
\- glitter  
\- glow  
\- bevel  
\- chrome  
\- outlines  
\- sparkles  
\- symbols

\#\#\# 3\. Short-form emphasis  
The style prefers:  
\- names  
\- titles  
\- slogans  
\- labels  
\- punchy phrases

Long paragraphs are not where the style shines visually.

\#\#\# 4\. Identity language  
Text commonly performs identity and attitude rather than neutral communication.

\#\#\# 5\. Cutout readiness  
Text graphics often need to feel detachable and reusable as assets.

\---

\#\# Drift warnings

\#\#\# Too clean  
Can become modern sticker branding.

\#\#\# Too minimal  
Can lose personality and glam-trash.

\#\#\# Too elegant  
Can become editorial or fashion-mag adjacent instead of native web decoration.

\#\#\# Too gothic  
Can lose the cute-trash crossover and become generic dark fantasy web.

\#\#\# Too kawaii  
Can lose sharpness, fake luxury, and tacky confidence.

\---

\#\# Practical rule

A correct text treatment in this style usually answers:  
\- what is the mood?  
\- what is the attitude?  
\- what surface is it pretending to be?  
\- does it feel like a decorative asset or page-title object?  
\- is it loud enough to belong here?

If the answer is “it just looks typographically nice,” something is probably missing.

\---

\#\# Summary sentence

Typography in this style is not neutral lettering. It is decorative self-declaration rendered as glitter, glow, chrome, gel, outline, or badge logic, designed to be seen fast and felt harder than it is read.

### **`02_visual_dna/composition_grammar.md`**

\# Composition Grammar

This document defines the compositional rules and recurring arrangement logic of the style.

The point is not to claim rigid laws.  
The point is to identify the recurring spatial behavior that makes the style feel native instead of randomly decorated.

\---

\#\# Core principle

Composition in this style is usually not driven by elegant restraint.

It is driven by:  
\- emphasis  
\- ornament  
\- clustering  
\- symbolic layering  
\- fast reading  
\- page decoration  
\- emotional loudness

The style often works through deliberate overstatement.

\---

\#\# Two dominant composition modes

The parent style contains two main composition grammars:

\#\#\# 1\. Asset-centric composition  
Common in Myspace profile bling.

Traits:  
\- one main cutout asset or text object  
\- supporting icons around it  
\- badge/emblem structure  
\- centered or near-centered focal object  
\- clear silhouette  
\- drop-in graphic logic

\#\#\# 2\. Page-ecology composition  
Common in Angelfire shrine chaos.

Traits:  
\- many distributed decorative actors  
\- layered background systems  
\- thematic clusters  
\- edges and corners actively used  
\- repeated filler motifs  
\- page as environment rather than isolated emblem

The composition should usually know which of these it is closer to.

\---

\#\# Rule 1: Start with a dominant read

A strong piece usually has a fast first read.

That first read is often:  
\- a slogan  
\- a badge  
\- a central icon  
\- a page title  
\- a portal phrase  
\- a decorated self-label  
\- a themed shrine atmosphere

Even when the page is cluttered, there is usually something that hits first.

Without a dominant read, the work can collapse into decorative mush.

\---

\#\# Rule 2: Use clusters, not evenly distributed boredom

This style prefers clusters over perfect even spacing.

Common cluster forms:  
\- icon bunches around text  
\- corner clusters  
\- halo clusters  
\- sticker stacks  
\- top-heavy decoration  
\- edge swarms  
\- repeated micro-ornament around a focal object

Clusters create:  
\- emphasis  
\- excitement  
\- a handmade feel  
\- emotional accumulation

Even distribution often feels too modern, too sterile, or too UI-clean.

\---

\#\# Rule 3: Let focal objects feel detachable when appropriate

In asset-heavy compositions, the main object often feels like it could be lifted off the page:  
\- sticker  
\- glitter word  
\- badge  
\- icon cluster  
\- slogan emblem

This detachable feeling is important.

It reinforces:  
\- web-asset logic  
\- reusability  
\- transparency/cutout presence  
\- composited identity

Do not always over-integrate objects into one seamless illustration.

\---

\#\# Rule 4: Use backing contrast aggressively

A lot of the style’s power comes from staging.

Common staging strategies:  
\- black or dark background  
\- glow behind main object  
\- halo outline  
\- bright contrast edge  
\- sparkle field around the focal object  
\- dark void with bright clutter

The purpose is to make cheap-looking graphics hit hard.

A correct piece often uses contrast like a stage spotlight, not a subtle design system.

\---

\#\# Rule 5: Repetition should feel symbolic, not mechanical

Repeated motifs are common:  
\- stars  
\- hearts  
\- sparkles  
\- small icons  
\- tiled backgrounds  
\- blinkies  
\- buttons

But repetition should usually reinforce:  
\- mood  
\- obsession  
\- shrine behavior  
\- decorative intensity

Bad repetition feels like random wallpaper.  
Good repetition feels like the page can’t stop insisting on its own symbolic universe.

\---

\#\# Rule 6: Edge zones matter

Especially in Angelfire-style compositions, edges and corners are active territory.

Common uses:  
\- star clusters in corners  
\- decorative side columns  
\- repeated mini icons  
\- navigation buttons  
\- dividers  
\- little sparkles around the perimeter

This edge activity helps the page feel inhabited.

A composition with only a center and dead edges often misses important early-web page behavior.

\---

\#\# Rule 7: Layer order should stay legible

The style likes layering, but layers still need a useful hierarchy.

A common readable hierarchy is:

1\. background field  
2\. environmental filler or repeating pattern  
3\. main badge/text/icon layer  
4\. support motifs  
5\. sparkle/glow/halo accents  
6\. tiny edge garnish

This is not mandatory, but it is a useful model.

Too much layer flattening can make everything fight at once and kill the focal read.

\---

\#\# Rule 8: Decorative density should feel intentional

The style loves clutter, but correct clutter usually has a rhythm.

Useful clutter rhythms:  
\- central burst with lighter outer field  
\- dense corners with clearer center  
\- a strong title zone plus distributed filler  
\- clustered ornament around repeated symbols  
\- layered page sections with different density roles

Bad clutter often feels like random equal-noise everywhere.

Correct clutter feels like decorative obsession with some internal steering.

\---

\#\# Rule 9: Symmetry and asymmetry can both work

\#\#\# Symmetry often helps with:  
\- badge graphics  
\- slogan emblems  
\- princess/diva/crown arrangements  
\- icon-centered assets  
\- framed title graphics

\#\#\# Asymmetry often helps with:  
\- page clutter  
\- shrine atmospheres  
\- handmade worldbuilding  
\- collage-like side arrangements  
\- page navigation ecology

Neither is automatically correct.  
The key is whether the arrangement supports the intended function.

\---

\#\# Rule 10: Text and symbol should reinforce each other

In strong graphics, words and icons usually belong to the same emotional ecosystem.

Examples:  
\- “princess” \+ crown \+ sparkles  
\- “angel” \+ wings \+ white glow \+ stars  
\- dark-cute slogan \+ pink skull \+ toxic contrast accents  
\- shrine title \+ moon/stars \+ black field \+ blinkies

Bad combinations often feel arbitrary or mixed from unrelated sticker packs.

\---

\#\# Common compositional archetypes

\#\#\# Archetype A: Center badge  
One big word or emblem in center, with small supporting icons.

\#\#\# Archetype B: Sticker cluster  
Several related cutouts grouped tightly into one decorative mass.

\#\#\# Archetype C: Splash page portal  
Large title or “enter” object against a cosmic or black background.

\#\#\# Archetype D: Wallpaper field  
Repeated motif system filling the whole space.

\#\#\# Archetype E: Edge-decorated shrine page  
Title or main zone plus active corners, side fillers, buttons, and repeating atmospheric symbols.

\#\#\# Archetype F: Divider/button ecology  
Many small units arranged in strips or modular rows.

\---

\#\# Drift warnings

\#\#\# Too much empty space  
Can make the style feel undercommitted or over-modernized.

\#\#\# Too much even spacing  
Can feel like a cleaned-up design system instead of messy native page decoration.

\#\#\# Too integrated  
If everything melts into one seamless illustration, asset logic may die.

\#\#\# Too random  
If symbol distribution has no emotional or structural center, the piece becomes icon vomit.

\#\#\# Too elegant  
If the spacing and hierarchy feel editorial, the style may lose its shameless page-trash vitality.

\---

\#\# Practical test

Ask:  
\- what hits first?  
\- what kind of structure is this: badge, sticker pack, page ecology, shrine field?  
\- where does the eye go second?  
\- do the clusters feel intentional?  
\- do edges participate?  
\- does the clutter feel alive or random?  
\- does the arrangement still feel like web graphics culture?

Those questions catch a lot of failure fast.

\---

\#\# Summary sentence

Composition in this style is the art of arranging glittery symbols, slogans, cutout assets, and page clutter so that they hit fast, read emotionally, and feel like sincere over-decoration rather than polished design restraint.

### **`05_substyles/myspace_profile_bling.md`**

\# Myspace Profile Bling

This document defines the Myspace-dominant substyle inside the parent repo.

This is the branch where the page behaves as a decorated identity field and graphics behave as extensions of the self.

\---

\#\# Core definition

Myspace profile bling is a style of glitter-heavy, sticker-like, attitude-coded web graphics used to decorate a personal profile, signal identity, intensify self-presentation, and perform mood through ornamental excess.

Its center of gravity is:  
\- me  
\- my vibe  
\- my attitude  
\- my desirability  
\- my fantasy self  
\- my chosen labels

This is page decoration as self-branding.

\---

\#\# Main function

The main function of this substyle is to make identity visible through decoration.

That includes:  
\- glamorizing the self  
\- broadcasting attitude  
\- declaring role or mood  
\- signaling flirtation  
\- performing sweetness, brattiness, or diva energy  
\- turning labels into visual emblems

The graphic is often a statement piece, not a whole world.

\---

\#\# Core visual traits

Strong markers include:  
\- glitter text  
\- hot pink dominance  
\- hearts, crowns, stars, lips  
\- badge-like slogans  
\- transparent cutout assets  
\- chrome or gel lettering  
\- white outlines and sparkle bursts  
\- fake luxury signals  
\- strong sticker logic

The graphic often looks like it could be dropped anywhere on the profile and still work.

\---

\#\# Emotional register

This substyle commonly lives in combinations of:  
\- cute  
\- bratty  
\- flirtatious  
\- glamorous  
\- vain  
\- sweet  
\- dramatic  
\- playful  
\- fake-royal  
\- “look at me” energy

Even when dark-cute elements appear, this branch usually keeps self-performance as the center.

\---

\#\# Common text language

Frequent text behavior includes:  
\- names  
\- nicknames  
\- short labels  
\- slogans  
\- status declarations  
\- role words

Examples of common semantic zones:  
\- princess  
\- diva  
\- angel  
\- spoiled  
\- baby girl  
\- bad girl  
\- hot stuff  
\- cute  
\- sexy  
\- brat  
\- gangsta princess

The text is usually short and iconic, not essayistic.

\---

\#\# Typical motif emphasis

Most common motifs:  
\- hearts  
\- crowns  
\- lips  
\- stars  
\- bunnies  
\- butterflies  
\- rhinestone-like sparkle  
\- little gems  
\- soft wings  
\- small glamorous filler icons

Dark-cute variants may add:  
\- skulls  
\- crossbones  
\- black/pink hazard motifs  
\- toxic contrast accents

\---

\#\# Palette tilt

Most common palette families:  
\- hot pink  
\- magenta  
\- bubblegum pink  
\- purple  
\- black  
\- white  
\- silver  
\- occasional cyan accents

Darker or sassier variants may add:  
\- acid green  
\- cherry red  
\- black-heavy contrast  
\- metallic silver emphasis

The colors usually want immediate impact.

\---

\#\# Material logic

Myspace profile bling loves surfaces that pretend to be:  
\- glitter  
\- chrome  
\- gel  
\- rhinestones  
\- shiny vinyl  
\- plastic gems  
\- metallic trim

These surfaces should not become too realistic.  
They are symbolic luxury signals.

Their job is to make the graphic feel:  
\- special  
\- flashy  
\- cute  
\- expensive in a fake fun way

\---

\#\# Composition logic

This substyle usually prefers:  
\- one central word or slogan  
\- one main badge or emblem  
\- icon support around text  
\- strong silhouette  
\- decorative clustering  
\- sticker-pack readability  
\- cutout-friendly arrangement

Useful composition archetypes:  
\- center badge  
\- slogan sticker  
\- glitter nameplate  
\- icon \+ word combo  
\- crown-above-text structure  
\- heart-framed word mark

This branch usually wants a fast read.

\---

\#\# Relationship to the page

Unlike Angelfire shrine chaos, this substyle usually does not need the entire page to become the artwork.

Instead, it often produces modular visual objects that can be:  
\- dropped onto a profile  
\- stacked with other graphics  
\- used in comments  
\- layered as profile decorations  
\- reused like expressive stickers

The emphasis is on portable visual identity.

\---

\#\# Artifact behavior

A little crunch helps.

Useful artifact traits:  
\- glitter noise  
\- slightly rough outlines  
\- primitive glow  
\- low-res sparkle  
\- compression bite  
\- transparent cutout weirdness

Too much polish can turn the work into generic retro branding.

This substyle often benefits from looking a little used, saved, repasted, or web-native.

\---

\#\# Common success signals

A strong Myspace profile bling graphic often feels:  
\- instantly readable  
\- emotionally obvious  
\- glam in a cheap fun way  
\- sticker-like  
\- centered on self-presentation  
\- easy to imagine on a profile page  
\- a little trashy in the right way

It should feel like a decorative declaration.

\---

\#\# Common drift failures

\#\#\# Failure 1: Generic Y2K girl branding  
Symptoms:  
\- too sleek  
\- too corporate-retro  
\- too productized  
\- not enough web-native weirdness

Repair:  
\- add glitter grit  
\- add cutout logic  
\- roughen rendering  
\- increase slogan/badge behavior

\#\#\# Failure 2: Kawaii sticker drift  
Symptoms:  
\- too gentle  
\- too pastel  
\- too clean  
\- too sweet with no glam-trash edge

Repair:  
\- increase contrast  
\- add chrome/glow  
\- add tackier phrases or fake-luxury signals  
\- add black or darker stage fields

\#\#\# Failure 3: Empty icon pile  
Symptoms:  
\- random hearts/stars with no identity logic  
\- decorative filler but no personality statement

Repair:  
\- anchor with a label, name, or mood declaration  
\- strengthen self-performance cues

\#\#\# Failure 4: Overly realistic glam  
Symptoms:  
\- polished chrome  
\- physically realistic gems  
\- luxury ad vibes

Repair:  
\- make surfaces cheaper  
\- restore synthetic tackiness  
\- reduce realism and increase web-asset energy

\---

\#\# Prompting advice

When prompting this substyle, emphasize:  
\- profile graphic  
\- glitter sticker  
\- transparent cutout asset  
\- badge or slogan  
\- hot pink glam  
\- hearts/crowns/lips/stars  
\- fake luxury  
\- black background or no background  
\- low-res web-graphic charm  
\- decorative identity label

Useful phrase types:  
\- “glitter profile sticker”  
\- “transparent Myspace-style badge graphic”  
\- “hot pink chrome text with sparkle bursts”  
\- “mall-trash princess graphic”  
\- “cute-trash glitter slogan asset”

\---

\#\# Best use cases

This substyle is especially useful for:  
\- text graphics  
\- sticker assets  
\- profile decor systems  
\- comment graphics  
\- mood labels  
\- identity packs  
\- decorative asset generators  
\- short-form prompt injections

\---

\#\# Summary sentence

Myspace profile bling is the branch of the style where identity becomes a glitter sticker—loud, shameless, synthetic, decorative, and designed to announce a vibe in one hit.

### **`05_substyles/angelfire_shrine_chaos.md`**

\# Angelfire Shrine Chaos

This document defines the Angelfire-dominant substyle inside the parent repo.

This is the branch where the page behaves less like a profile accessory field and more like a whole handmade realm, shrine, portal, or obsession-zone.

\---

\#\# Core definition

Angelfire shrine chaos is a style of early-web page construction built from cosmic backdrops, tiled patterns, blinkies, icons, buttons, glow-heavy titles, symbolic clutter, and emotionally charged page-world building.

Its center of gravity is not only:  
\- me

It is more like:  
\- my world  
\- my shrine  
\- my obsession  
\- my portal  
\- my night sky  
\- my little haunted kingdom of links and glitter bullshit

This is page decoration as environment and devotion.

\---

\#\# Main function

The main function of this substyle is to turn the page into a themed atmosphere.

That atmosphere may feel:  
\- mystical  
\- devotional  
\- dreamy  
\- dark-cute  
\- dramatic  
\- heavenly  
\- cosmic  
\- obsessive  
\- handmade  
\- intensely personal

The goal is less “here is my badge” and more “step into my weird little universe.”

\---

\#\# Core visual traits

Strong markers include:  
\- black or dark starfield backgrounds  
\- tiled or repeated wallpaper systems  
\- page titles with glow or fantasy drama  
\- small decorative widgets  
\- blinkies and buttons  
\- moons, stars, wings, celestial clutter  
\- shrine-like repetition  
\- many decorative zones across the page  
\- handmade digital layering

This branch usually reads as an environment before it reads as a single asset.

\---

\#\# Emotional register

Common emotional tones:  
\- dreamy  
\- devotional  
\- mystical  
\- dramatic  
\- intimate  
\- spiritually tacky  
\- dark-cute  
\- lonely but decorated  
\- page-as-ritual-space

It often feels like someone cared enough to build a whole atmosphere rather than just slap on a single sticker.

\---

\#\# Typical motif emphasis

Most common motifs:  
\- stars  
\- moons  
\- celestial sparkles  
\- angel wings  
\- halos  
\- devils  
\- butterflies  
\- fantasy fillers  
\- portals  
\- decorative separators  
\- tiny page widgets  
\- themed background motifs

Darker variants may also bring in:  
\- skulls  
\- gothic symbols  
\- black/purple glamour  
\- occult-lite clutter  
\- haunted-cute icon mixes

\---

\#\# Palette tilt

Frequent palette families:  
\- black  
\- violet  
\- magenta  
\- white  
\- silver  
\- midnight blue  
\- electric purple  
\- soft blacklight pink

Accent families may include:  
\- cyan  
\- teal  
\- blood-red highlights  
\- acid green in more chaotic variants

This substyle often depends heavily on black-stage or night-stage contrast.

\---

\#\# Material logic

Angelfire shrine chaos still uses fake glamour, but often in a more environmental way.

Common material signals:  
\- glow halos  
\- starburst fields  
\- low-res celestial shimmer  
\- glitter accents  
\- chrome title text  
\- cutout dividers  
\- cheap glow portals  
\- page-background texture repetition

This branch often cares less about one perfect glam object and more about the accumulation of many little digital surfaces.

\---

\#\# Composition logic

This branch usually favors:  
\- page-wide layering  
\- active corners and side zones  
\- top titles or splash headers  
\- background systems that remain visible  
\- repeating decorative units  
\- a sense that every part of the page is inhabited

Useful archetypes:  
\- enter page splash  
\- cosmic title page  
\- shrine page with widgets  
\- edge-decorated link page  
\- tiled celestial wallpaper page  
\- portal page with buttons and mini icons

It often rewards exploration rather than one immediate sticker hit.

\---

\#\# Relationship to the page

This branch is page-native.

It likes:  
\- backgrounds  
\- divisions  
\- sections  
\- link zones  
\- decoration around navigation  
\- repeated border clutter  
\- little ornamental functional objects

The page itself becomes part of the art.

That is one of the biggest differences from the Myspace branch.

\---

\#\# Artifact behavior

This branch loves web-life scars.

Useful artifact traits:  
\- rough tiling  
\- low-res star glows  
\- crunchy buttons  
\- primitive transparency  
\- repeated small GIF logic  
\- little edge mismatches  
\- compressed cosmic noise  
\- cheap portal effects

Too much polish can kill the haunted homemade magic.

The page should often feel built, saved, patched together, and loved.

\---

\#\# Common success signals

A strong Angelfire shrine chaos piece often feels:  
\- immersive  
\- page-like  
\- layered  
\- lovingly overdecorated  
\- themed  
\- slightly obsessive  
\- handmade in spirit  
\- emotionally atmospheric

It should feel like a personal realm, not just a decorative object.

\---

\#\# Common drift failures

\#\#\# Failure 1: Generic webcore collage  
Symptoms:  
\- random internet clutter  
\- browser nostalgia without shrine logic  
\- no symbolic center  
\- no emotional worldbuilding

Repair:  
\- strengthen theme  
\- add repeated symbolic families  
\- add shrine or portal intent  
\- make the page feel inhabited, not merely referential

\#\#\# Failure 2: Generic goth site  
Symptoms:  
\- darkness and occult vibes only  
\- no glitter-trash crossover  
\- too serious  
\- too little cute or glam contradiction

Repair:  
\- add sparkle  
\- add fake luxury surfaces  
\- add celestial/cute cross-signals  
\- restore decorative shamelessness

\#\#\# Failure 3: Vaporwave atmosphere drift  
Symptoms:  
\- dreamy but detached  
\- conceptually nostalgic  
\- too smooth  
\- not enough page function or handmade clutter

Repair:  
\- add buttons, blinkies, dividers, tiles  
\- increase page ecology  
\- reduce art-school haze and increase web-object specificity

\#\#\# Failure 4: Too clean and modern  
Symptoms:  
\- perfect alignment  
\- slick polished titles  
\- beautiful but dead

Repair:  
\- add small roughness  
\- reactivate low-res charm  
\- reintroduce amateur page energy  
\- make functional page elements decorative again

\---

\#\# Prompting advice

When prompting this substyle, emphasize:  
\- shrine page  
\- portal page  
\- black starfield  
\- tiled background  
\- celestial clutter  
\- page widgets  
\- blinkies and buttons  
\- handmade early-web environment  
\- mystical glitter page  
\- devotional digital realm

Useful phrase types:  
\- “Angelfire-style shrine page”  
\- “cosmic early-web portal page”  
\- “black-background celestial clutter with blinkies”  
\- “handmade glitter shrine website aesthetic”  
\- “haunted cute starfield page with old web buttons”

\---

\#\# Best use cases

This substyle is especially useful for:  
\- full-page scene prompts  
\- webpage atmosphere systems  
\- shrine-inspired graphic interfaces  
\- background generators  
\- portal/splash compositions  
\- decorative navigation systems  
\- digital-cosmic collage spaces

\---

\#\# Summary sentence

Angelfire shrine chaos is the branch of the style where a webpage stops being a container and becomes a glittering, glowing, symbol-packed personal realm built from devotion, clutter, and handmade digital atmosphere.

### **`10_prompt_system/prompt_formula_short.md`**

\# Prompt Formula Short

This document defines short prompt formulas for the Myspace \+ Angelfire graphics style.

These formulas are meant for fast deployment, not exhaustive control.  
They are useful when you want a compact prompt that still carries the correct style logic.

\---

\#\# Why short formulas matter

Long prompts are useful, but this style also benefits from compact modular prompting because many use cases involve:

\- sticker assets  
\- short text graphics  
\- page atmosphere seeds  
\- rapid concept exploration  
\- app-based prompt assembly  
\- style injection into larger prompts

A short formula should still preserve:  
\- substyle branch  
\- decorative intent  
\- key material logic  
\- motif logic  
\- anti-drift cues

\---

\#\# Core short formula

A good short prompt in this style usually contains:

\*\*\[substyle\] \+ \[object/page type\] \+ \[core motifs\] \+ \[surface/effects\] \+ \[palette/stage\] \+ \[artifact cue\]\*\*

Example structure:

\`\[substyle\] \[graphic/page\], \[motifs\], \[glitter/chrome/glow\], \[palette\], \[artifact/web-era cue\]\`

This is the minimum useful skeleton.

\---

\#\# Formula A: Asset-focused short prompt

Use for:  
\- glitter stickers  
\- slogan graphics  
\- badges  
\- text assets  
\- cutout icons

\#\#\# Template  
\`\[substyle\] transparent web graphic asset, \[main text or object\], \[2-4 motifs\], \[surface logic\], \[palette\], \[artifact cue\]\`

\#\#\# Example  
\`Myspace profile bling transparent web graphic asset, “princess” glitter text, hearts crowns sparkles, chrome gel highlights, hot pink purple black palette, low-res Y2K web graphic charm\`

\#\#\# Notes  
Keep the object detachable.  
Think sticker, badge, cutout, drop-in ornament.

\---

\#\# Formula B: Badge/slogan short prompt

Use for:  
\- identity graphics  
\- labels  
\- comment graphics  
\- profile decorations

\#\#\# Template  
\`\[substyle\] badge graphic, \[short slogan\], \[support motifs\], \[effect logic\], \[palette/stage\], \[artifact cue\]\`

\#\#\# Example  
\`Myspace badge graphic, “100% cute”, stars hearts lips, glitter and white sparkle bursts, hot pink on black, crunchy early-web asset texture\`

\#\#\# Notes  
Use emotionally direct text.  
Do not overcomplicate the phrase.

\---

\#\# Formula C: Shrine-page short prompt

Use for:  
\- Angelfire-style page atmospheres  
\- portal pages  
\- scene-page concepts  
\- cosmic background systems

\#\#\# Template  
\`\[substyle\] shrine page, \[background logic\], \[motif families\], \[title/effect logic\], \[palette\], \[artifact cue\]\`

\#\#\# Example  
\`Angelfire shrine page, black starfield tiled background, moons stars angel wings blinkies, glowing fantasy title text, violet magenta white on black, handmade low-res web page clutter\`

\#\#\# Notes  
This should feel like a page-world, not a single sticker.

\---

\#\# Formula D: Background/wallpaper short prompt

Use for:  
\- tiled wallpapers  
\- background generators  
\- repeating fields  
\- page filler systems

\#\#\# Template  
\`\[substyle\] tiled background, \[repeat motifs\], \[surface/effect logic\], \[palette/stage\], \[artifact cue\]\`

\#\#\# Example  
\`Angelfire tiled background, repeating stars moons glitter hearts, soft glow and sparkle noise, purple black pink palette, compressed web wallpaper texture\`

\#\#\# Notes  
Prioritize repetition logic and atmosphere.

\---

\#\# Formula E: Hybrid short prompt

Use for:  
\- crossovers where one branch is dominant but the other contributes

\#\#\# Template  
\`\[dominant substyle\] with \[secondary influence\], \[object/page\], \[motifs\], \[surface logic\], \[palette\], \[artifact cue\]\`

\#\#\# Example  
\`Myspace profile bling with Angelfire cosmic influence, transparent glitter name graphic, crown hearts stars moon, chrome glitter glow, pink purple black palette, crunchy old-web cutout texture\`

\#\#\# Notes  
Always make one side dominant.  
Do not make muddy 50/50 soup.

\---

\#\# Myspace short prompt tokens

Useful tokens to swap in:

\#\#\# Object types  
\- glitter sticker  
\- profile badge  
\- transparent cutout graphic  
\- slogan asset  
\- nameplate  
\- comment graphic

\#\#\# Motifs  
\- hearts  
\- crowns  
\- lips  
\- stars  
\- butterflies  
\- rhinestones  
\- bunny silhouettes  
\- dark-cute skulls

\#\#\# Surface/effects  
\- glitter fill  
\- chrome bevel  
\- gel lettering  
\- white sparkle bursts  
\- glow halo  
\- fake diamond shine

\#\#\# Palette cues  
\- hot pink and purple  
\- magenta on black  
\- silver and pink  
\- toxic pink/green on black

\#\#\# Artifact cues  
\- low-res Myspace graphic  
\- crunchy transparent asset  
\- old-web glitter texture  
\- primitive glow edges

\---

\#\# Angelfire short prompt tokens

Useful tokens to swap in:

\#\#\# Page/object types  
\- shrine page  
\- portal page  
\- enter page  
\- cosmic webpage  
\- celestial wallpaper  
\- blinkie strip  
\- button grid

\#\#\# Motifs  
\- moons  
\- stars  
\- wings  
\- halos  
\- glitter hearts  
\- buttons  
\- dividers  
\- little celestial widgets

\#\#\# Surface/effects  
\- starburst glow  
\- blacklight shimmer  
\- fantasy title text  
\- low-res sparkle field  
\- cosmic halo haze

\#\#\# Palette cues  
\- purple blacklight palette  
\- magenta and white on black  
\- moonlit blue-purple-black  
\- pink-violet celestial glow

\#\#\# Artifact cues  
\- handmade early-web page  
\- compressed starfield texture  
\- old Angelfire shrine clutter  
\- rough tiled wallpaper behavior

\---

\#\# Anti-drift boosters for short prompts

When short prompts start getting too vague, add one or two of these:

\- \`tacky web graphic\`  
\- \`cheap synthetic glamour\`  
\- \`low-res glitter asset\`  
\- \`handmade shrine page\`  
\- \`transparent sticker-style cutout\`  
\- \`black-background old web sparkle\`  
\- \`crunchy early-web decoration\`  
\- \`page clutter, not minimalist design\`

These help prevent drift into clean retro slop.

\---

\#\# What short prompts should avoid

Avoid overloading short prompts with:  
\- too many unrelated motif families  
\- vague “nostalgic internet” wording with no style mechanics  
\- modern design language like “sleek,” “minimal,” “editorial,” “premium”  
\- realism-heavy material descriptions  
\- branch confusion

A short prompt needs a strong backbone, not a hundred random trinkets.

\---

\#\# Fast prompt recipes

\#\#\# Recipe 1: cute Myspace sticker  
\`Myspace profile bling transparent sticker graphic, glitter “baby girl” text, hearts crowns stars, hot pink chrome glow, black background, crunchy old-web asset\`

\#\#\# Recipe 2: dark-cute glam badge  
\`Myspace dark-cute badge graphic, pink skull and “bad girl” text, sparkles crossbones stars, toxic pink and black palette, low-res glitter texture\`

\#\#\# Recipe 3: celestial shrine page  
\`Angelfire shrine page, black starfield background, moons stars angel wings blinkies, glowing fantasy page title, violet magenta white palette, handmade old-web clutter\`

\#\#\# Recipe 4: tiled wallpaper  
\`Angelfire tiled wallpaper, repeating glitter stars hearts moons, purple pink black palette, soft glow halos, compressed early-web texture\`

\---

\#\# Summary sentence

A strong short prompt for this style names the branch, the object or page type, the symbolic inventory, the fake-glam surface logic, the palette stage, and at least one cue that keeps the output crunchy, decorative, and web-native.

Continuing the approved repo build in separate file blocks.

### **`01_core_definition/style_pillars.md`**

\# Style Pillars

This document defines the load-bearing pillars of the Myspace \+ Angelfire graphics style.

If too many of these are missing, the output may still be sparkly or nostalgic, but it will no longer belong to the core style system.

\---

\#\# Why pillars matter

A style can survive variation, but it cannot survive the loss of its structural traits.

These pillars are the traits that keep the style from dissolving into:  
\- generic Y2K  
\- kawaii sticker design  
\- vaporwave web nostalgia  
\- polished retro branding  
\- random glitter clutter  
\- generic goth web aesthetics

Think of them as the style’s spine, not its accessories.

\---

\#\# Pillar 1: Ornament as identity or devotion

The style treats decoration as meaningful.

Decoration is not merely visual filler. It functions as:  
\- self-branding  
\- self-performance  
\- mood declaration  
\- devotion  
\- obsession  
\- fantasy projection  
\- page-world building

In Myspace mode, ornament is often about the self:  
\- “this is me”  
\- “this is my vibe”  
\- “this is how I want to be seen”

In Angelfire mode, ornament is often about the page-world:  
\- “enter my realm”  
\- “this is my shrine”  
\- “this page is a portal, mood chamber, or obsession zone”

Without this layer of intent, the style becomes empty decoration.

\---

\#\# Pillar 2: Synthetic glamour

The style runs on fake glamour.

That glamour is usually expressed through:  
\- glitter  
\- chrome  
\- gel lettering  
\- rhinestone-like sparkle  
\- metallic fakery  
\- plastic gem energy  
\- white starburst shine  
\- exaggerated glow

These effects do not need to be realistic.  
In fact, realism can make them worse.

They need to be legible as:  
\- flashy  
\- precious  
\- glam  
\- shiny  
\- magical  
\- extra

The style does not worship refinement.  
It worships seduction through cheap spectacle.

\---

\#\# Pillar 3: Asset logic or page ecology

This style usually operates in one of two structural modes:

\#\#\# Asset logic  
Graphics feel like detachable pieces:  
\- stickers  
\- glitter text  
\- badges  
\- cutout icons  
\- transparent ornaments  
\- buttons  
\- blinkies

\#\#\# Page ecology  
The page feels like a whole living environment:  
\- tiled backgrounds  
\- layered clutter  
\- repeated motifs  
\- portal/splash structure  
\- shrine layout  
\- link button ecosystems  
\- counters and dividers

A correct output typically commits to one of these as the dominant logic.

Without either, the result may look adjacent but weak.

\---

\#\# Pillar 4: Emotional directness

The style is emotionally loud.

It often communicates in direct signals:  
\- cute  
\- princess  
\- diva  
\- angel  
\- baby girl  
\- bad girl  
\- brat  
\- dark-cute  
\- dreamy  
\- magical  
\- shrine-like  
\- dramatic

This style is not emotionally reserved.  
It announces itself.

Even when the image is dumb or kitschy, it is rarely detached.

\---

\#\# Pillar 5: Tackiness as power

Tackiness is not an accidental side effect.  
It is a central strength.

This style often works because it is:  
\- too much  
\- too glittery  
\- too loud  
\- too decorated  
\- too obvious  
\- too direct  
\- too shiny  
\- too self-declared

Modern taste often tries to shave off exactly the qualities that make this style alive.

Do not let it.

A little vulgarity is part of the magic.

\---

\#\# Pillar 6: Artifact-positive rendering

The style is natively comfortable with:  
\- compression  
\- crunchy edges  
\- primitive glow  
\- weird transparency  
\- rough compositing  
\- low-res sparkle  
\- repasted asset behavior

These are not merely tolerated.  
They often help.

This style was born in:  
\- saved graphics  
\- reused web assets  
\- small GIFs  
\- page layouts  
\- low-resolution display contexts  
\- homebrew digital assembly

If rendered too cleanly, the style can lose its native atmosphere.

\---

\#\# Pillar 7: Symbolic legibility

The style loves symbols that read fast.

Common examples:  
\- hearts  
\- stars  
\- crowns  
\- lips  
\- butterflies  
\- bunnies  
\- skulls  
\- moons  
\- angels  
\- devils  
\- slogan text  
\- badges and stamps

These symbols matter because they let the style communicate identity and mood immediately.

The symbol system should be:  
\- clear  
\- iconic  
\- repeatable  
\- glamorized  
\- emotionally coded

The style usually does not prefer subtle metaphor over readable iconography.

\---

\#\# Pillar 8: High-contrast stagecraft

The style often depends on strong visual staging.

This often includes:  
\- black backgrounds  
\- void-like page space  
\- bright outlines  
\- glow halos  
\- sparkle contrast  
\- hot local contrast between asset and backdrop

This stagecraft makes even crude graphics feel intense.

The contrast is not always technically elegant.  
It is theatrically effective.

\---

\#\# Pillar 9: Decorative excess with internal purpose

The style is maximalist, but not meaningless.

Correct clutter usually has some role:  
\- mood intensification  
\- identity reinforcement  
\- symbolic repetition  
\- page immersion  
\- visual seduction  
\- shrine behavior

Wrong clutter feels random.

Correct clutter feels like someone cared too much and decorated the shit out of everything on purpose.

That is a feature, not a flaw.

\---

\#\# Pillar 10: Sincerity inside performance

Even when the style is funny, trashy, or ridiculous, it is often sincere.

It sincerely wants to be:  
\- beautiful  
\- glamorous  
\- magical  
\- iconic  
\- emotionally charged  
\- cute  
\- haunted  
\- adored  
\- noticed

This sincerity is important.

If the output feels too ironic, too design-school detached, or too knowingly tasteful, it often loses the emotional charge that makes the style work.

\---

\#\# Pillar interaction model

These pillars do not function in isolation.

A strong piece usually combines several at once:

\- synthetic glamour  
\- emotional directness  
\- symbolic legibility  
\- artifact-positive rendering  
\- asset logic or page ecology  
\- tacky intensity

That combination is what creates the proper read.

\---

\#\# Minimum viable style test

At minimum, a correct output should usually satisfy most of these:

\- decoration has clear expressive purpose  
\- fake glamour is visible  
\- symbols are direct and legible  
\- the rendering is not over-sanitized  
\- either asset logic or page ecology is present  
\- the mood is emotionally declarative  
\- some degree of tacky excess survives

If too many of those are absent, the piece is probably drifting.

\---

\#\# Summary sentence

This style is built on the idea that a page or graphic should perform selfhood, fantasy, or shrine-intensity through cheap synthetic glamour, symbolic clutter, and unapologetic decorative excess.

That is the load-bearing religion.

### **`01_core_definition/what_this_style_is_not.md`**

\# What This Style Is Not

This document defines the style by contrast.

That matters because this style has many neighboring aesthetics that share some ingredients while operating on totally different logic.

The point here is not to be uptight.  
The point is to stop weak-ass drift.

\---

\#\# Why negatives matter

Many incorrect outputs will contain:  
\- glitter  
\- pinks and purples  
\- stars  
\- black backgrounds  
\- internet nostalgia  
\- cute symbols

That does not make them correct.

This style is defined not just by ingredients, but by:  
\- deployment logic  
\- emotional tone  
\- material behavior  
\- artifact tolerance  
\- page or asset structure  
\- sincerity of decorative intent

So this document names what the style is \*\*not\*\*, even when it overlaps visually.

\---

\#\# Not generic Y2K

This style is not the same as broad Y2K aesthetics.

\#\#\# Generic Y2K often emphasizes:  
\- chrome futurism  
\- tech gloss  
\- airbrushed smoothness  
\- sleek industrial curves  
\- product-design polish  
\- glossy magazine-era futurism

\#\#\# This style instead emphasizes:  
\- webpage decoration  
\- glitter graphics  
\- sticker logic  
\- badge/slogan behavior  
\- low-res glam-trash  
\- profile ornament  
\- shrine-page clutter

You can mix Y2K in, but if the result becomes mainly sleek, futuristic, and polished, it has drifted.

\---

\#\# Not vaporwave by default

This style is not vaporwave unless explicitly mixed.

\#\#\# Vaporwave often emphasizes:  
\- irony  
\- dreamlike consumer decay  
\- pastel haze  
\- retro-futurist atmosphere  
\- ambient nostalgia  
\- conceptual art-school framing

\#\#\# This style instead emphasizes:  
\- direct decoration  
\- obvious symbolism  
\- glitter and tacky glam  
\- page identity  
\- amateur compositing charm  
\- self-performance or shrine intent

Vaporwave often floats.  
This style decorates aggressively.

\---

\#\# Not kawaii sticker culture

This style is not clean kawaii design.

\#\#\# Kawaii sticker culture often emphasizes:  
\- sweetness  
\- cuteness  
\- soft palettes  
\- clean vectors  
\- polished friendliness  
\- gentle surface charm

\#\#\# This style instead often needs:  
\- tackiness  
\- trash-glam  
\- black stage contrast  
\- chrome or glitter aggression  
\- sharper emotional declaration  
\- cheaper, louder synthetic surfaces

It may be cute, but it is usually not cleanly cute.

\---

\#\# Not polished modern nostalgia branding

This style is not a tasteful brand campaign doing “internet nostalgia.”

\#\#\# Modern nostalgia branding often emphasizes:  
\- careful restraint  
\- balanced layouts  
\- high-res gloss  
\- intentional minimalism  
\- cleaned-up retro signals  
\- designerly control

\#\#\# This style instead often wants:  
\- clutter  
\- shamelessness  
\- rough edges  
\- synthetic excess  
\- visible effect-stacking  
\- emotional loudness

If it looks like an expensive agency moodboard for a soda collab, it has probably lost the plot.

\---

\#\# Not webcore as a catch-all

This style is not just “webcore.”

\#\#\# Generic webcore often emphasizes:  
\- browser nostalgia  
\- cursors  
\- windows  
\- desktop fragments  
\- low-fi digital weirdness  
\- mixed-era internet relics

\#\#\# This style instead centers:  
\- glitter assets  
\- shrine pages  
\- cutout graphics  
\- profile decorations  
\- page ornament ecology  
\- emotional decorative coding

Webcore is broader and fuzzier.  
This style is narrower and tackier.

\---

\#\# Not generic goth web

This style is not simply dark early-web aesthetic.

\#\#\# Generic goth web often emphasizes:  
\- darkness  
\- occult symbols  
\- black and red palettes  
\- vampires, crosses, graveyards  
\- poetic gloom  
\- moody seriousness

\#\#\# This style, even when dark, usually still includes:  
\- glitter or sparkle  
\- fake luxury  
\- cute-trash crossover  
\- bratty or decorative playfulness  
\- glam shine  
\- sticker-like iconography

Without those, it may be goth web, but not this specific thing.

\---

\#\# Not scene/emo by default

This style is not automatically scene or emo.

There is overlap in:  
\- black backgrounds  
\- bright accents  
\- digital trashiness  
\- page decoration  
\- glitter and attitude

But scene/emo often centers:  
\- fashion-subculture signaling  
\- striped/neon/raver crossover  
\- hair and music-scene identity  
\- specific youth subculture codes

This style can touch that territory, but its center is broader decorative web glam and shrine logic.

\---

\#\# Not scrapbook collage

This style is not handmade paper nostalgia.

\#\#\# Scrapbook collage often emphasizes:  
\- paper textures  
\- torn edges  
\- handwritten softness  
\- analog intimacy  
\- pastel memory-book atmosphere

\#\#\# This style instead emphasizes:  
\- screen-born surfaces  
\- digital glow  
\- cutout assets  
\- chrome/glitter/gel fakery  
\- webpage ecology  
\- neon or blacklight contrast

This style lives on the screen, not in a paper journal.

\---

\#\# Not minimal by design

This style is not a minimal aesthetic.

Even when a single graphic is simple, the underlying logic still tends toward:  
\- ornament  
\- declaration  
\- symbolism  
\- visual embellishment  
\- effect stacking  
\- expressive overkill

If the result feels elegantly underdesigned, it is probably drifting out of the style field.

\---

\#\# Not irony-first

This style can be campy and funny, but it is not usually best when treated as detached irony.

A correct piece often feels like it genuinely wants:  
\- attention  
\- glamour  
\- fantasy  
\- identity  
\- magic  
\- devotion  
\- aesthetic overload

If the piece feels like it is smirking at itself too much, it can lose the sincerity that makes the style hit.

\---

\#\# Not realistic material rendering

This style is not about convincing physical realism.

Its surfaces often reference:  
\- glitter  
\- chrome  
\- gems  
\- plastic  
\- gel  
\- metallic foil

But those are usually stylized signal systems, not physically accurate render targets.

If the surfaces become too realistic, the work can start feeling like luxury product mockups instead of web graphics.

\---

\#\# Not neutral design

This style is not neutral information design.

It is usually:  
\- mood-heavy  
\- identity-coded  
\- emotionally declarative  
\- symbol-rich  
\- attention-seeking

If a piece feels visually neutral, restrained, or purely informational, it is probably in the wrong neighborhood.

\---

\#\# Frequent false friends

The styles most likely to get confused with this one are:  
\- generic Y2K  
\- webcore  
\- vaporwave  
\- kawaii sticker design  
\- goth web  
\- scene graphics  
\- modern retro branding  
\- dark-cute pop graphics

All of these can overlap with the repo.  
None of them should automatically replace it.

\---

\#\# Quick wrongness test

If the output feels mostly like:  
\- sleek future nostalgia  
\- dreamy pastel web collage  
\- clean cute sticker design  
\- dark moody goth without glam-trash  
\- modern curated retro branding  
\- generic early-internet artifact soup

then it is probably not correct yet.

\---

\#\# Summary sentence

This style is not just old internet with glitter on it.

It is a specific culture of synthetic self-decoration and shrine-page ornament, driven by tacky glamour, symbolic clarity, artifact-rich rendering, and shameless decorative intent.

### **`02_visual_dna/motif_families.md`**

\# Motif Families

This document organizes the major recurring motif families used in the Myspace \+ Angelfire graphics style.

These motifs are not random decoration.  
They function as fast emotional symbols, identity markers, page ornaments, and glam amplifiers.

\---

\#\# Why motif families matter

This style depends heavily on recurring symbolic inventory.

Motifs do important work:  
\- identify mood  
\- signal personality  
\- glamorize page space  
\- anchor decorative clusters  
\- intensify substyle identity  
\- make graphics feel reusable and modular

The style often prefers motifs that are:  
\- iconic  
\- emotionally legible  
\- easy to cut out  
\- easy to repeat  
\- easy to glitterify  
\- easy to combine with text

\---

\#\# Family 1: Hearts

\#\#\# Core meanings  
\- romance  
\- cuteness  
\- sweetness  
\- desirability  
\- self-love  
\- flirtation  
\- femininity  
\- glam softness

\#\#\# Common forms  
\- solid hearts  
\- outlined hearts  
\- glitter hearts  
\- gem hearts  
\- metallic hearts  
\- winged hearts  
\- broken hearts  
\- heart clusters  
\- heart backgrounds

\#\#\# Typical use  
\- slogan graphics  
\- profile ornament  
\- badge framing  
\- decorative filler  
\- cutout assets

\#\#\# Notes  
Hearts are one of the most foundational motifs in the style.  
They easily tilt toward Myspace profile bling.

\---

\#\# Family 2: Stars and sparkle marks

\#\#\# Core meanings  
\- shine  
\- magic  
\- glamour  
\- attention  
\- heavenly energy  
\- decorative excitement

\#\#\# Common forms  
\- four-point stars  
\- six-point twinkles  
\- glitter particles  
\- starbursts  
\- tiny white sparkle dots  
\- outlined stars  
\- cartoon stars

\#\#\# Typical use  
\- overlays  
\- halo intensifiers  
\- page filler  
\- space backgrounds  
\- glamour marks around text or icons

\#\#\# Notes  
This family often bridges both substyles.  
In Myspace mode it boosts glam.  
In Angelfire mode it can become environmental.

\---

\#\# Family 3: Crowns and tiara forms

\#\#\# Core meanings  
\- princess identity  
\- diva energy  
\- status  
\- fake royalty  
\- self-mythology  
\- bratty glamour

\#\#\# Common forms  
\- small crown above text  
\- gem crown icons  
\- chrome tiaras  
\- heart-topped crowns  
\- sticker crowns

\#\#\# Typical use  
\- name graphics  
\- princess/diva slogans  
\- profile signals  
\- status markers  
\- decorative punctuation

\#\#\# Notes  
Crowns are especially strong in identity-performance pieces.

\---

\#\# Family 4: Lips, kisses, and mouth marks

\#\#\# Core meanings  
\- flirtation  
\- sexiness  
\- vanity  
\- glamour  
\- bratty attitude  
\- feminine display

\#\#\# Common forms  
\- lip silhouettes  
\- lipstick kiss prints  
\- glossy mouth icons  
\- small repeating kiss marks  
\- lip cutout stickers

\#\#\# Typical use  
\- slogan graphics  
\- profile bling  
\- attitude badges  
\- decorative clusters

\#\#\# Notes  
These motifs tend to push the style toward mall-trash glam and flirty Myspace energy.

\---

\#\# Family 5: Bunnies and cute silhouettes

\#\#\# Core meanings  
\- sexy-cute duality  
\- playful femininity  
\- flirt iconography  
\- recognizable trash-glam shorthand

\#\#\# Common forms  
\- bunny heads  
\- silhouette bunnies  
\- stylized cartoon rabbits  
\- repeating bunny patterns

\#\#\# Typical use  
\- badges  
\- small cutout ornaments  
\- sticker packs  
\- repeat backgrounds  
\- flirty icon mixes

\#\#\# Notes  
This family can tip the work toward a specific era-coded trash-glam vibe very quickly.

\---

\#\# Family 6: Butterflies, wings, and flutter forms

\#\#\# Core meanings  
\- transformation  
\- dreaminess  
\- magical femininity  
\- ethereal decoration  
\- lightness  
\- romantic fantasy

\#\#\# Common forms  
\- glitter butterflies  
\- purple or pink butterfly icons  
\- winged hearts  
\- angel wings behind symbols  
\- wing embellishments on text

\#\#\# Typical use  
\- dreamy page clutter  
\- shrine-page symbols  
\- cutout assets  
\- decorative framing

\#\#\# Notes  
Butterflies and wings bridge cute glam and shrine fantasy.  
They are particularly useful in softer or more celestial variants.

\---

\#\# Family 7: Skulls, crossbones, and dark-cute hazard symbols

\#\#\# Core meanings  
\- rebellion  
\- brat menace  
\- punky cuteness  
\- anti-sweetness  
\- danger as decoration  
\- dark-cute contradiction

\#\#\# Common forms  
\- glitter skulls  
\- pink skulls  
\- skull with bow motifs  
\- crossbones  
\- gothic-cute skull badges

\#\#\# Typical use  
\- dark-cute graphics  
\- toxic cute palettes  
\- bratty slogan assets  
\- alt-glam variants

\#\#\# Notes  
This family is important because it keeps the style from becoming only sugary.  
It adds edge and contradiction.

\---

\#\# Family 8: Angels, devils, halos, and moral-play icons

\#\#\# Core meanings  
\- innocence vs mischief  
\- flirtation through contrast  
\- fantasy morality play  
\- cute corruption  
\- spiritualized drama  
\- page-devotion

\#\#\# Common forms  
\- angel wings  
\- halo above text  
\- little devil tails or horns  
\- angel/devil paired symbols  
\- celestial innocence markers

\#\#\# Typical use  
\- slogans  
\- shrine pages  
\- heavenly/dark-cute hybrids  
\- icon clusters

\#\#\# Notes  
This family can lean Myspace in a flirty way or Angelfire in a mystical/shrine way.

\---

\#\# Family 9: Celestial fillers

\#\#\# Core meanings  
\- cosmic mood  
\- night page atmosphere  
\- dreamspace  
\- magical vastness  
\- shrine aura

\#\#\# Common forms  
\- moons  
\- stars  
\- planets  
\- galaxies  
\- night-sky sparkles  
\- zodiac-like signs  
\- constellations  
\- nebula-ish glow fields

\#\#\# Typical use  
\- backgrounds  
\- shrine pages  
\- portal/splash pages  
\- cosmic wallpaper systems  
\- black void intensification

\#\#\# Notes  
Celestial fillers are a major Angelfire-side motif family, but they can also decorate glam assets.

\---

\#\# Family 10: Princess/diva/baby-girl text concepts

\#\#\# Core meanings  
\- self-branding  
\- fantasy identity  
\- desirability  
\- attitude  
\- fake status  
\- decorative ego-performance

\#\#\# Common forms  
\- “princess”  
\- “diva”  
\- “baby girl”  
\- “angel”  
\- “bad girl”  
\- “100% cute”  
\- “spoiled”  
\- “hot stuff”  
\- “gangsta princess”

\#\#\# Typical use  
\- slogan graphics  
\- badges  
\- text-centered assets  
\- identity decorations

\#\#\# Notes  
Technically text, but functionally this family behaves like motif inventory because the phrases act like symbolic emblems.

\---

\#\# Family 11: Precious object motifs

\#\#\# Core meanings  
\- fake wealth  
\- glamour  
\- self-adornment  
\- luxury fantasy  
\- preciousness

\#\#\# Common forms  
\- gems  
\- diamonds  
\- rhinestone scatters  
\- metallic stars  
\- jewel-encrusted hearts  
\- shiny lockets  
\- chrome forms

\#\#\# Typical use  
\- graphic embellishment  
\- letter decoration  
\- glam intensification  
\- faux-status signals

\#\#\# Notes  
These motifs often blend into material effects, but they are still useful as a distinct symbolic family.

\---

\#\# Family 12: Page ecology motifs

\#\#\# Core meanings  
\- webpage life  
\- navigability as decoration  
\- handmade digital habitat  
\- shrine-system presence

\#\#\# Common forms  
\- blinkies  
\- tiny buttons  
\- dividers  
\- counters  
\- “enter” graphics  
\- guestbook markers  
\- web rings  
\- decorative separators

\#\#\# Typical use  
\- Angelfire-style page construction  
\- banner systems  
\- navigation ornament  
\- small clutter zones

\#\#\# Notes  
These motifs are absolutely crucial for webpage logic and should not be ignored just because they are functional.

\---

\#\# Family 13: Cute-trash filler packs

\#\#\# Core meanings  
\- decorative surplus  
\- emotional density  
\- page excitement  
\- icon ecology

\#\#\# Common forms  
\- cherries  
\- bows  
\- flowers  
\- stars  
\- tiny dots  
\- mini charms  
\- little smile or wink icons  
\- repeated glam clutter units

\#\#\# Typical use  
\- edge decoration  
\- backgrounds  
\- cluster fills  
\- badge padding

\#\#\# Notes  
These motifs keep compositions from feeling empty.  
They also help bridge between main symbols.

\---

\#\# Motif deployment rules

A strong output usually does not use motifs randomly.

Good motif deployment usually has:  
\- one dominant family  
\- one or two support families  
\- repeated symbolic logic  
\- emotional consistency  
\- integration with palette and text

Bad deployment often feels like:  
\- unrelated sticker vomit  
\- random icon pile  
\- novelty without symbolic center

\---

\#\# Myspace-leaning families

Most strongly associated with Myspace profile bling:  
\- hearts  
\- crowns  
\- lips  
\- princess/diva text  
\- bunny silhouettes  
\- precious object motifs

\---

\#\# Angelfire-leaning families

Most strongly associated with shrine-page chaos:  
\- celestial fillers  
\- angels/devils  
\- butterflies/wings  
\- page ecology motifs  
\- starfield-heavy sparkle systems

\---

\#\# Bridge families

Useful in both:  
\- stars  
\- hearts  
\- glitter signals  
\- dark-cute skull forms  
\- slogan emblems  
\- small decorative filler icons

\---

\#\# Summary sentence

The motif system of this style is a fast-reading symbolic language built from cute, glam, celestial, trashy, flirty, and shrine-coded icons that can be cut out, repeated, sparkled, and stacked into decorative identity.

### **`02_visual_dna/typography_families.md`**

\# Typography Families

This document defines the major text and lettering families used in the style.

Typography here does not behave like neutral information design.  
It behaves like ornament, attitude, identity, and visual objecthood.

\---

\#\# Core principle

In this style, text is often not just text.

It is:  
\- a badge  
\- a sticker  
\- a declaration  
\- a glamour surface  
\- a self-label  
\- a decorative anchor

That means typography decisions are not mainly about readability in a modern design sense.  
They are about emotional and symbolic impact.

\---

\#\# Family 1: Glitter fill text

\#\#\# Core behavior  
Letterforms are filled with glitter texture or sparkle-heavy material simulation.

\#\#\# Common traits  
\- bright pink or purple glitter  
\- white sparkle flecks  
\- noisy inner texture  
\- thick enough shapes to hold the glitter read  
\- paired with outlines or halos

\#\#\# Typical emotional read  
\- glamorous  
\- cute  
\- flashy  
\- high-attention  
\- mall-trash luxurious

\#\#\# Common use  
\- names  
\- short slogans  
\- badges  
\- status labels  
\- “princess/diva/angel” style declarations

\#\#\# Notes  
This is one of the most iconic text families in the entire style.

\---

\#\# Family 2: Bubble and rounded cute text

\#\#\# Core behavior  
Soft rounded letters with playful, puffy, or candy-like shapes.

\#\#\# Common traits  
\- circular counters  
\- thick strokes  
\- simple silhouettes  
\- often pink, lavender, or white  
\- often combined with sparkles or outlines

\#\#\# Typical emotional read  
\- cute  
\- sweet  
\- girly  
\- approachable  
\- toy-like

\#\#\# Common use  
\- cute slogans  
\- icons with friendly energy  
\- lighthearted badges  
\- Myspace-style decorative text

\#\#\# Notes  
If rendered too cleanly, this family can drift toward kawaii sticker culture.  
It often needs trash-glam support.

\---

\#\# Family 3: Beveled chrome or faux-metal text

\#\#\# Core behavior  
Letterforms imitate metallic, chrome, silver, or glossy gem-like surfaces.

\#\#\# Common traits  
\- sharp highlight bands  
\- bright white shine areas  
\- silver gradients or faux foil  
\- outlined shapes  
\- embossed or beveled illusion

\#\#\# Typical emotional read  
\- fake luxury  
\- diva glam  
\- status  
\- nightclub/mall-kiosk excess

\#\#\# Common use  
\- title text  
\- badge text  
\- “hot stuff” style declarations  
\- glam-focused stickers

\#\#\# Notes  
This family works best when a little tacky.  
Over-refined chrome tends to drift toward generic Y2K or luxury branding.

\---

\#\# Family 4: Gel or jelly text

\#\#\# Core behavior  
Letterforms look swollen, glossy, soft-plastic, or gummy.

\#\#\# Common traits  
\- rounded volume cues  
\- shiny top highlights  
\- candy-material feel  
\- bright, saturated colors  
\- soft 3D illusion without realism

\#\#\# Typical emotional read  
\- playful  
\- synthetic  
\- cute  
\- cheap luxurious  
\- sticker-like

\#\#\# Common use  
\- short labels  
\- decorative names  
\- bright badge text  
\- candy-girl variants

\#\#\# Notes  
This family is good for soft glam, but can get too modern if not dirtied up with artifact logic.

\---

\#\# Family 5: Script and faux-romantic lettering

\#\#\# Core behavior  
Curvy script or cursive-leaning forms that signal romance, softness, fantasy, or glam femininity.

\#\#\# Common traits  
\- swooping strokes  
\- ornamental capitals  
\- decorative tails  
\- often with glow, glitter, or outlines  
\- not always highly legible

\#\#\# Typical emotional read  
\- dreamy  
\- romantic  
\- feminine  
\- dramatic  
\- vanity-coded

\#\#\# Common use  
\- page titles  
\- names  
\- sentimental badges  
\- shrine-page headings  
\- “angel,” “princess,” or devotional phrases

\#\#\# Notes  
This family is especially useful in softer glam or shrine-page variants.

\---

\#\# Family 6: Gothic-lite or fantasy title text

\#\#\# Core behavior  
Text borrows from gothic, blackletter-ish, or fantasy title cues without becoming fully medieval or serious.

\#\#\# Common traits  
\- sharp terminals  
\- decorative capitals  
\- dark or metallic coloring  
\- glow or halo support  
\- dramatic contrast against black backgrounds

\#\#\# Typical emotional read  
\- mystical  
\- haunted  
\- dramatic  
\- devotional  
\- dark-cute

\#\#\# Common use  
\- Angelfire-style page titles  
\- shrine names  
\- portal page headers  
\- dark celestial text assets

\#\#\# Notes  
This family must usually stay in dialogue with glitter, glow, or cute-trash signals so it does not drift into pure goth web.

\---

\#\# Family 7: Badge slogan text

\#\#\# Core behavior  
Short declarative phrases designed like emblems rather than paragraphs.

\#\#\# Common traits  
\- bold, compact wording  
\- decorative packaging  
\- outline emphasis  
\- icon accompaniment  
\- emotionally direct language

\#\#\# Common text types  
\- “100% cute”  
\- “princess”  
\- “spoiled”  
\- “angel”  
\- “bad girl”  
\- “diva”  
\- “hot stuff”

\#\#\# Typical emotional read  
\- self-labeling  
\- instant identity  
\- dramatic shorthand  
\- decorative attitude

\#\#\# Common use  
\- profile graphics  
\- comments  
\- small stamps  
\- reusable assets

\#\#\# Notes  
This family is less about a specific font and more about a typographic function.

\---

\#\# Family 8: Outline-heavy sticker text

\#\#\# Core behavior  
Text is separated strongly from background by thick outlines, glow edges, or border emphasis.

\#\#\# Common traits  
\- white outer stroke  
\- dark or silver inner border  
\- halo edge  
\- cutout readability  
\- strong silhouette

\#\#\# Typical emotional read  
\- sticker-like  
\- high-visibility  
\- web-asset native  
\- page-drop-in ready

\#\#\# Common use  
\- all-purpose graphic text  
\- black-background page decor  
\- tiny web graphics  
\- badge layering

\#\#\# Notes  
This is one of the most useful families for maintaining asset logic.

\---

\#\# Family 9: Pixel-small utility text and button text

\#\#\# Core behavior  
Tiny text used in buttons, blinkies, counters, or navigation objects.

\#\#\# Common traits  
\- compressed visibility  
\- simple all-caps or block text  
\- low-res survival  
\- often paired with bars, frames, or GIF behavior

\#\#\# Typical emotional read  
\- page ecology  
\- web-native functionality  
\- handmade digital habitat

\#\#\# Common use  
\- buttons  
\- blinkies  
\- navigation strips  
\- little page widgets

\#\#\# Notes  
These are especially important on the Angelfire side.

\---

\#\# Key typography behaviors across families

\#\#\# 1\. Text as image  
Text is often treated like a graphic object with its own surface and ornament.

\#\#\# 2\. High embellishment  
Letterforms frequently use:  
\- glitter  
\- glow  
\- bevel  
\- chrome  
\- outlines  
\- sparkles  
\- symbols

\#\#\# 3\. Short-form emphasis  
The style prefers:  
\- names  
\- titles  
\- slogans  
\- labels  
\- punchy phrases

Long paragraphs are not where the style shines visually.

\#\#\# 4\. Identity language  
Text commonly performs identity and attitude rather than neutral communication.

\#\#\# 5\. Cutout readiness  
Text graphics often need to feel detachable and reusable as assets.

\---

\#\# Drift warnings

\#\#\# Too clean  
Can become modern sticker branding.

\#\#\# Too minimal  
Can lose personality and glam-trash.

\#\#\# Too elegant  
Can become editorial or fashion-mag adjacent instead of native web decoration.

\#\#\# Too gothic  
Can lose the cute-trash crossover and become generic dark fantasy web.

\#\#\# Too kawaii  
Can lose sharpness, fake luxury, and tacky confidence.

\---

\#\# Practical rule

A correct text treatment in this style usually answers:  
\- what is the mood?  
\- what is the attitude?  
\- what surface is it pretending to be?  
\- does it feel like a decorative asset or page-title object?  
\- is it loud enough to belong here?

If the answer is “it just looks typographically nice,” something is probably missing.

\---

\#\# Summary sentence

Typography in this style is not neutral lettering. It is decorative self-declaration rendered as glitter, glow, chrome, gel, outline, or badge logic, designed to be seen fast and felt harder than it is read.

### **`02_visual_dna/composition_grammar.md`**

\# Composition Grammar

This document defines the compositional rules and recurring arrangement logic of the style.

The point is not to claim rigid laws.  
The point is to identify the recurring spatial behavior that makes the style feel native instead of randomly decorated.

\---

\#\# Core principle

Composition in this style is usually not driven by elegant restraint.

It is driven by:  
\- emphasis  
\- ornament  
\- clustering  
\- symbolic layering  
\- fast reading  
\- page decoration  
\- emotional loudness

The style often works through deliberate overstatement.

\---

\#\# Two dominant composition modes

The parent style contains two main composition grammars:

\#\#\# 1\. Asset-centric composition  
Common in Myspace profile bling.

Traits:  
\- one main cutout asset or text object  
\- supporting icons around it  
\- badge/emblem structure  
\- centered or near-centered focal object  
\- clear silhouette  
\- drop-in graphic logic

\#\#\# 2\. Page-ecology composition  
Common in Angelfire shrine chaos.

Traits:  
\- many distributed decorative actors  
\- layered background systems  
\- thematic clusters  
\- edges and corners actively used  
\- repeated filler motifs  
\- page as environment rather than isolated emblem

The composition should usually know which of these it is closer to.

\---

\#\# Rule 1: Start with a dominant read

A strong piece usually has a fast first read.

That first read is often:  
\- a slogan  
\- a badge  
\- a central icon  
\- a page title  
\- a portal phrase  
\- a decorated self-label  
\- a themed shrine atmosphere

Even when the page is cluttered, there is usually something that hits first.

Without a dominant read, the work can collapse into decorative mush.

\---

\#\# Rule 2: Use clusters, not evenly distributed boredom

This style prefers clusters over perfect even spacing.

Common cluster forms:  
\- icon bunches around text  
\- corner clusters  
\- halo clusters  
\- sticker stacks  
\- top-heavy decoration  
\- edge swarms  
\- repeated micro-ornament around a focal object

Clusters create:  
\- emphasis  
\- excitement  
\- a handmade feel  
\- emotional accumulation

Even distribution often feels too modern, too sterile, or too UI-clean.

\---

\#\# Rule 3: Let focal objects feel detachable when appropriate

In asset-heavy compositions, the main object often feels like it could be lifted off the page:  
\- sticker  
\- glitter word  
\- badge  
\- icon cluster  
\- slogan emblem

This detachable feeling is important.

It reinforces:  
\- web-asset logic  
\- reusability  
\- transparency/cutout presence  
\- composited identity

Do not always over-integrate objects into one seamless illustration.

\---

\#\# Rule 4: Use backing contrast aggressively

A lot of the style’s power comes from staging.

Common staging strategies:  
\- black or dark background  
\- glow behind main object  
\- halo outline  
\- bright contrast edge  
\- sparkle field around the focal object  
\- dark void with bright clutter

The purpose is to make cheap-looking graphics hit hard.

A correct piece often uses contrast like a stage spotlight, not a subtle design system.

\---

\#\# Rule 5: Repetition should feel symbolic, not mechanical

Repeated motifs are common:  
\- stars  
\- hearts  
\- sparkles  
\- small icons  
\- tiled backgrounds  
\- blinkies  
\- buttons

But repetition should usually reinforce:  
\- mood  
\- obsession  
\- shrine behavior  
\- decorative intensity

Bad repetition feels like random wallpaper.  
Good repetition feels like the page can’t stop insisting on its own symbolic universe.

\---

\#\# Rule 6: Edge zones matter

Especially in Angelfire-style compositions, edges and corners are active territory.

Common uses:  
\- star clusters in corners  
\- decorative side columns  
\- repeated mini icons  
\- navigation buttons  
\- dividers  
\- little sparkles around the perimeter

This edge activity helps the page feel inhabited.

A composition with only a center and dead edges often misses important early-web page behavior.

\---

\#\# Rule 7: Layer order should stay legible

The style likes layering, but layers still need a useful hierarchy.

A common readable hierarchy is:

1\. background field  
2\. environmental filler or repeating pattern  
3\. main badge/text/icon layer  
4\. support motifs  
5\. sparkle/glow/halo accents  
6\. tiny edge garnish

This is not mandatory, but it is a useful model.

Too much layer flattening can make everything fight at once and kill the focal read.

\---

\#\# Rule 8: Decorative density should feel intentional

The style loves clutter, but correct clutter usually has a rhythm.

Useful clutter rhythms:  
\- central burst with lighter outer field  
\- dense corners with clearer center  
\- a strong title zone plus distributed filler  
\- clustered ornament around repeated symbols  
\- layered page sections with different density roles

Bad clutter often feels like random equal-noise everywhere.

Correct clutter feels like decorative obsession with some internal steering.

\---

\#\# Rule 9: Symmetry and asymmetry can both work

\#\#\# Symmetry often helps with:  
\- badge graphics  
\- slogan emblems  
\- princess/diva/crown arrangements  
\- icon-centered assets  
\- framed title graphics

\#\#\# Asymmetry often helps with:  
\- page clutter  
\- shrine atmospheres  
\- handmade worldbuilding  
\- collage-like side arrangements  
\- page navigation ecology

Neither is automatically correct.  
The key is whether the arrangement supports the intended function.

\---

\#\# Rule 10: Text and symbol should reinforce each other

In strong graphics, words and icons usually belong to the same emotional ecosystem.

Examples:  
\- “princess” \+ crown \+ sparkles  
\- “angel” \+ wings \+ white glow \+ stars  
\- dark-cute slogan \+ pink skull \+ toxic contrast accents  
\- shrine title \+ moon/stars \+ black field \+ blinkies

Bad combinations often feel arbitrary or mixed from unrelated sticker packs.

\---

\#\# Common compositional archetypes

\#\#\# Archetype A: Center badge  
One big word or emblem in center, with small supporting icons.

\#\#\# Archetype B: Sticker cluster  
Several related cutouts grouped tightly into one decorative mass.

\#\#\# Archetype C: Splash page portal  
Large title or “enter” object against a cosmic or black background.

\#\#\# Archetype D: Wallpaper field  
Repeated motif system filling the whole space.

\#\#\# Archetype E: Edge-decorated shrine page  
Title or main zone plus active corners, side fillers, buttons, and repeating atmospheric symbols.

\#\#\# Archetype F: Divider/button ecology  
Many small units arranged in strips or modular rows.

\---

\#\# Drift warnings

\#\#\# Too much empty space  
Can make the style feel undercommitted or over-modernized.

\#\#\# Too much even spacing  
Can feel like a cleaned-up design system instead of messy native page decoration.

\#\#\# Too integrated  
If everything melts into one seamless illustration, asset logic may die.

\#\#\# Too random  
If symbol distribution has no emotional or structural center, the piece becomes icon vomit.

\#\#\# Too elegant  
If the spacing and hierarchy feel editorial, the style may lose its shameless page-trash vitality.

\---

\#\# Practical test

Ask:  
\- what hits first?  
\- what kind of structure is this: badge, sticker pack, page ecology, shrine field?  
\- where does the eye go second?  
\- do the clusters feel intentional?  
\- do edges participate?  
\- does the clutter feel alive or random?  
\- does the arrangement still feel like web graphics culture?

Those questions catch a lot of failure fast.

\---

\#\# Summary sentence

Composition in this style is the art of arranging glittery symbols, slogans, cutout assets, and page clutter so that they hit fast, read emotionally, and feel like sincere over-decoration rather than polished design restraint.

### **`05_substyles/myspace_profile_bling.md`**

\# Myspace Profile Bling

This document defines the Myspace-dominant substyle inside the parent repo.

This is the branch where the page behaves as a decorated identity field and graphics behave as extensions of the self.

\---

\#\# Core definition

Myspace profile bling is a style of glitter-heavy, sticker-like, attitude-coded web graphics used to decorate a personal profile, signal identity, intensify self-presentation, and perform mood through ornamental excess.

Its center of gravity is:  
\- me  
\- my vibe  
\- my attitude  
\- my desirability  
\- my fantasy self  
\- my chosen labels

This is page decoration as self-branding.

\---

\#\# Main function

The main function of this substyle is to make identity visible through decoration.

That includes:  
\- glamorizing the self  
\- broadcasting attitude  
\- declaring role or mood  
\- signaling flirtation  
\- performing sweetness, brattiness, or diva energy  
\- turning labels into visual emblems

The graphic is often a statement piece, not a whole world.

\---

\#\# Core visual traits

Strong markers include:  
\- glitter text  
\- hot pink dominance  
\- hearts, crowns, stars, lips  
\- badge-like slogans  
\- transparent cutout assets  
\- chrome or gel lettering  
\- white outlines and sparkle bursts  
\- fake luxury signals  
\- strong sticker logic

The graphic often looks like it could be dropped anywhere on the profile and still work.

\---

\#\# Emotional register

This substyle commonly lives in combinations of:  
\- cute  
\- bratty  
\- flirtatious  
\- glamorous  
\- vain  
\- sweet  
\- dramatic  
\- playful  
\- fake-royal  
\- “look at me” energy

Even when dark-cute elements appear, this branch usually keeps self-performance as the center.

\---

\#\# Common text language

Frequent text behavior includes:  
\- names  
\- nicknames  
\- short labels  
\- slogans  
\- status declarations  
\- role words

Examples of common semantic zones:  
\- princess  
\- diva  
\- angel  
\- spoiled  
\- baby girl  
\- bad girl  
\- hot stuff  
\- cute  
\- sexy  
\- brat  
\- gangsta princess

The text is usually short and iconic, not essayistic.

\---

\#\# Typical motif emphasis

Most common motifs:  
\- hearts  
\- crowns  
\- lips  
\- stars  
\- bunnies  
\- butterflies  
\- rhinestone-like sparkle  
\- little gems  
\- soft wings  
\- small glamorous filler icons

Dark-cute variants may add:  
\- skulls  
\- crossbones  
\- black/pink hazard motifs  
\- toxic contrast accents

\---

\#\# Palette tilt

Most common palette families:  
\- hot pink  
\- magenta  
\- bubblegum pink  
\- purple  
\- black  
\- white  
\- silver  
\- occasional cyan accents

Darker or sassier variants may add:  
\- acid green  
\- cherry red  
\- black-heavy contrast  
\- metallic silver emphasis

The colors usually want immediate impact.

\---

\#\# Material logic

Myspace profile bling loves surfaces that pretend to be:  
\- glitter  
\- chrome  
\- gel  
\- rhinestones  
\- shiny vinyl  
\- plastic gems  
\- metallic trim

These surfaces should not become too realistic.  
They are symbolic luxury signals.

Their job is to make the graphic feel:  
\- special  
\- flashy  
\- cute  
\- expensive in a fake fun way

\---

\#\# Composition logic

This substyle usually prefers:  
\- one central word or slogan  
\- one main badge or emblem  
\- icon support around text  
\- strong silhouette  
\- decorative clustering  
\- sticker-pack readability  
\- cutout-friendly arrangement

Useful composition archetypes:  
\- center badge  
\- slogan sticker  
\- glitter nameplate  
\- icon \+ word combo  
\- crown-above-text structure  
\- heart-framed word mark

This branch usually wants a fast read.

\---

\#\# Relationship to the page

Unlike Angelfire shrine chaos, this substyle usually does not need the entire page to become the artwork.

Instead, it often produces modular visual objects that can be:  
\- dropped onto a profile  
\- stacked with other graphics  
\- used in comments  
\- layered as profile decorations  
\- reused like expressive stickers

The emphasis is on portable visual identity.

\---

\#\# Artifact behavior

A little crunch helps.

Useful artifact traits:  
\- glitter noise  
\- slightly rough outlines  
\- primitive glow  
\- low-res sparkle  
\- compression bite  
\- transparent cutout weirdness

Too much polish can turn the work into generic retro branding.

This substyle often benefits from looking a little used, saved, repasted, or web-native.

\---

\#\# Common success signals

A strong Myspace profile bling graphic often feels:  
\- instantly readable  
\- emotionally obvious  
\- glam in a cheap fun way  
\- sticker-like  
\- centered on self-presentation  
\- easy to imagine on a profile page  
\- a little trashy in the right way

It should feel like a decorative declaration.

\---

\#\# Common drift failures

\#\#\# Failure 1: Generic Y2K girl branding  
Symptoms:  
\- too sleek  
\- too corporate-retro  
\- too productized  
\- not enough web-native weirdness

Repair:  
\- add glitter grit  
\- add cutout logic  
\- roughen rendering  
\- increase slogan/badge behavior

\#\#\# Failure 2: Kawaii sticker drift  
Symptoms:  
\- too gentle  
\- too pastel  
\- too clean  
\- too sweet with no glam-trash edge

Repair:  
\- increase contrast  
\- add chrome/glow  
\- add tackier phrases or fake-luxury signals  
\- add black or darker stage fields

\#\#\# Failure 3: Empty icon pile  
Symptoms:  
\- random hearts/stars with no identity logic  
\- decorative filler but no personality statement

Repair:  
\- anchor with a label, name, or mood declaration  
\- strengthen self-performance cues

\#\#\# Failure 4: Overly realistic glam  
Symptoms:  
\- polished chrome  
\- physically realistic gems  
\- luxury ad vibes

Repair:  
\- make surfaces cheaper  
\- restore synthetic tackiness  
\- reduce realism and increase web-asset energy

\---

\#\# Prompting advice

When prompting this substyle, emphasize:  
\- profile graphic  
\- glitter sticker  
\- transparent cutout asset  
\- badge or slogan  
\- hot pink glam  
\- hearts/crowns/lips/stars  
\- fake luxury  
\- black background or no background  
\- low-res web-graphic charm  
\- decorative identity label

Useful phrase types:  
\- “glitter profile sticker”  
\- “transparent Myspace-style badge graphic”  
\- “hot pink chrome text with sparkle bursts”  
\- “mall-trash princess graphic”  
\- “cute-trash glitter slogan asset”

\---

\#\# Best use cases

This substyle is especially useful for:  
\- text graphics  
\- sticker assets  
\- profile decor systems  
\- comment graphics  
\- mood labels  
\- identity packs  
\- decorative asset generators  
\- short-form prompt injections

\---

\#\# Summary sentence

Myspace profile bling is the branch of the style where identity becomes a glitter sticker—loud, shameless, synthetic, decorative, and designed to announce a vibe in one hit.

### **`05_substyles/angelfire_shrine_chaos.md`**

\# Angelfire Shrine Chaos

This document defines the Angelfire-dominant substyle inside the parent repo.

This is the branch where the page behaves less like a profile accessory field and more like a whole handmade realm, shrine, portal, or obsession-zone.

\---

\#\# Core definition

Angelfire shrine chaos is a style of early-web page construction built from cosmic backdrops, tiled patterns, blinkies, icons, buttons, glow-heavy titles, symbolic clutter, and emotionally charged page-world building.

Its center of gravity is not only:  
\- me

It is more like:  
\- my world  
\- my shrine  
\- my obsession  
\- my portal  
\- my night sky  
\- my little haunted kingdom of links and glitter bullshit

This is page decoration as environment and devotion.

\---

\#\# Main function

The main function of this substyle is to turn the page into a themed atmosphere.

That atmosphere may feel:  
\- mystical  
\- devotional  
\- dreamy  
\- dark-cute  
\- dramatic  
\- heavenly  
\- cosmic  
\- obsessive  
\- handmade  
\- intensely personal

The goal is less “here is my badge” and more “step into my weird little universe.”

\---

\#\# Core visual traits

Strong markers include:  
\- black or dark starfield backgrounds  
\- tiled or repeated wallpaper systems  
\- page titles with glow or fantasy drama  
\- small decorative widgets  
\- blinkies and buttons  
\- moons, stars, wings, celestial clutter  
\- shrine-like repetition  
\- many decorative zones across the page  
\- handmade digital layering

This branch usually reads as an environment before it reads as a single asset.

\---

\#\# Emotional register

Common emotional tones:  
\- dreamy  
\- devotional  
\- mystical  
\- dramatic  
\- intimate  
\- spiritually tacky  
\- dark-cute  
\- lonely but decorated  
\- page-as-ritual-space

It often feels like someone cared enough to build a whole atmosphere rather than just slap on a single sticker.

\---

\#\# Typical motif emphasis

Most common motifs:  
\- stars  
\- moons  
\- celestial sparkles  
\- angel wings  
\- halos  
\- devils  
\- butterflies  
\- fantasy fillers  
\- portals  
\- decorative separators  
\- tiny page widgets  
\- themed background motifs

Darker variants may also bring in:  
\- skulls  
\- gothic symbols  
\- black/purple glamour  
\- occult-lite clutter  
\- haunted-cute icon mixes

\---

\#\# Palette tilt

Frequent palette families:  
\- black  
\- violet  
\- magenta  
\- white  
\- silver  
\- midnight blue  
\- electric purple  
\- soft blacklight pink

Accent families may include:  
\- cyan  
\- teal  
\- blood-red highlights  
\- acid green in more chaotic variants

This substyle often depends heavily on black-stage or night-stage contrast.

\---

\#\# Material logic

Angelfire shrine chaos still uses fake glamour, but often in a more environmental way.

Common material signals:  
\- glow halos  
\- starburst fields  
\- low-res celestial shimmer  
\- glitter accents  
\- chrome title text  
\- cutout dividers  
\- cheap glow portals  
\- page-background texture repetition

This branch often cares less about one perfect glam object and more about the accumulation of many little digital surfaces.

\---

\#\# Composition logic

This branch usually favors:  
\- page-wide layering  
\- active corners and side zones  
\- top titles or splash headers  
\- background systems that remain visible  
\- repeating decorative units  
\- a sense that every part of the page is inhabited

Useful archetypes:  
\- enter page splash  
\- cosmic title page  
\- shrine page with widgets  
\- edge-decorated link page  
\- tiled celestial wallpaper page  
\- portal page with buttons and mini icons

It often rewards exploration rather than one immediate sticker hit.

\---

\#\# Relationship to the page

This branch is page-native.

It likes:  
\- backgrounds  
\- divisions  
\- sections  
\- link zones  
\- decoration around navigation  
\- repeated border clutter  
\- little ornamental functional objects

The page itself becomes part of the art.

That is one of the biggest differences from the Myspace branch.

\---

\#\# Artifact behavior

This branch loves web-life scars.

Useful artifact traits:  
\- rough tiling  
\- low-res star glows  
\- crunchy buttons  
\- primitive transparency  
\- repeated small GIF logic  
\- little edge mismatches  
\- compressed cosmic noise  
\- cheap portal effects

Too much polish can kill the haunted homemade magic.

The page should often feel built, saved, patched together, and loved.

\---

\#\# Common success signals

A strong Angelfire shrine chaos piece often feels:  
\- immersive  
\- page-like  
\- layered  
\- lovingly overdecorated  
\- themed  
\- slightly obsessive  
\- handmade in spirit  
\- emotionally atmospheric

It should feel like a personal realm, not just a decorative object.

\---

\#\# Common drift failures

\#\#\# Failure 1: Generic webcore collage  
Symptoms:  
\- random internet clutter  
\- browser nostalgia without shrine logic  
\- no symbolic center  
\- no emotional worldbuilding

Repair:  
\- strengthen theme  
\- add repeated symbolic families  
\- add shrine or portal intent  
\- make the page feel inhabited, not merely referential

\#\#\# Failure 2: Generic goth site  
Symptoms:  
\- darkness and occult vibes only  
\- no glitter-trash crossover  
\- too serious  
\- too little cute or glam contradiction

Repair:  
\- add sparkle  
\- add fake luxury surfaces  
\- add celestial/cute cross-signals  
\- restore decorative shamelessness

\#\#\# Failure 3: Vaporwave atmosphere drift  
Symptoms:  
\- dreamy but detached  
\- conceptually nostalgic  
\- too smooth  
\- not enough page function or handmade clutter

Repair:  
\- add buttons, blinkies, dividers, tiles  
\- increase page ecology  
\- reduce art-school haze and increase web-object specificity

\#\#\# Failure 4: Too clean and modern  
Symptoms:  
\- perfect alignment  
\- slick polished titles  
\- beautiful but dead

Repair:  
\- add small roughness  
\- reactivate low-res charm  
\- reintroduce amateur page energy  
\- make functional page elements decorative again

\---

\#\# Prompting advice

When prompting this substyle, emphasize:  
\- shrine page  
\- portal page  
\- black starfield  
\- tiled background  
\- celestial clutter  
\- page widgets  
\- blinkies and buttons  
\- handmade early-web environment  
\- mystical glitter page  
\- devotional digital realm

Useful phrase types:  
\- “Angelfire-style shrine page”  
\- “cosmic early-web portal page”  
\- “black-background celestial clutter with blinkies”  
\- “handmade glitter shrine website aesthetic”  
\- “haunted cute starfield page with old web buttons”

\---

\#\# Best use cases

This substyle is especially useful for:  
\- full-page scene prompts  
\- webpage atmosphere systems  
\- shrine-inspired graphic interfaces  
\- background generators  
\- portal/splash compositions  
\- decorative navigation systems  
\- digital-cosmic collage spaces

\---

\#\# Summary sentence

Angelfire shrine chaos is the branch of the style where a webpage stops being a container and becomes a glittering, glowing, symbol-packed personal realm built from devotion, clutter, and handmade digital atmosphere.

### **`10_prompt_system/prompt_formula_short.md`**

\# Prompt Formula Short

This document defines short prompt formulas for the Myspace \+ Angelfire graphics style.

These formulas are meant for fast deployment, not exhaustive control.  
They are useful when you want a compact prompt that still carries the correct style logic.

\---

\#\# Why short formulas matter

Long prompts are useful, but this style also benefits from compact modular prompting because many use cases involve:

\- sticker assets  
\- short text graphics  
\- page atmosphere seeds  
\- rapid concept exploration  
\- app-based prompt assembly  
\- style injection into larger prompts

A short formula should still preserve:  
\- substyle branch  
\- decorative intent  
\- key material logic  
\- motif logic  
\- anti-drift cues

\---

\#\# Core short formula

A good short prompt in this style usually contains:

\*\*\[substyle\] \+ \[object/page type\] \+ \[core motifs\] \+ \[surface/effects\] \+ \[palette/stage\] \+ \[artifact cue\]\*\*

Example structure:

\`\[substyle\] \[graphic/page\], \[motifs\], \[glitter/chrome/glow\], \[palette\], \[artifact/web-era cue\]\`

This is the minimum useful skeleton.

\---

\#\# Formula A: Asset-focused short prompt

Use for:  
\- glitter stickers  
\- slogan graphics  
\- badges  
\- text assets  
\- cutout icons

\#\#\# Template  
\`\[substyle\] transparent web graphic asset, \[main text or object\], \[2-4 motifs\], \[surface logic\], \[palette\], \[artifact cue\]\`

\#\#\# Example  
\`Myspace profile bling transparent web graphic asset, “princess” glitter text, hearts crowns sparkles, chrome gel highlights, hot pink purple black palette, low-res Y2K web graphic charm\`

\#\#\# Notes  
Keep the object detachable.  
Think sticker, badge, cutout, drop-in ornament.

\---

\#\# Formula B: Badge/slogan short prompt

Use for:  
\- identity graphics  
\- labels  
\- comment graphics  
\- profile decorations

\#\#\# Template  
\`\[substyle\] badge graphic, \[short slogan\], \[support motifs\], \[effect logic\], \[palette/stage\], \[artifact cue\]\`

\#\#\# Example  
\`Myspace badge graphic, “100% cute”, stars hearts lips, glitter and white sparkle bursts, hot pink on black, crunchy early-web asset texture\`

\#\#\# Notes  
Use emotionally direct text.  
Do not overcomplicate the phrase.

\---

\#\# Formula C: Shrine-page short prompt

Use for:  
\- Angelfire-style page atmospheres  
\- portal pages  
\- scene-page concepts  
\- cosmic background systems

\#\#\# Template  
\`\[substyle\] shrine page, \[background logic\], \[motif families\], \[title/effect logic\], \[palette\], \[artifact cue\]\`

\#\#\# Example  
\`Angelfire shrine page, black starfield tiled background, moons stars angel wings blinkies, glowing fantasy title text, violet magenta white on black, handmade low-res web page clutter\`

\#\#\# Notes  
This should feel like a page-world, not a single sticker.

\---

\#\# Formula D: Background/wallpaper short prompt

Use for:  
\- tiled wallpapers  
\- background generators  
\- repeating fields  
\- page filler systems

\#\#\# Template  
\`\[substyle\] tiled background, \[repeat motifs\], \[surface/effect logic\], \[palette/stage\], \[artifact cue\]\`

\#\#\# Example  
\`Angelfire tiled background, repeating stars moons glitter hearts, soft glow and sparkle noise, purple black pink palette, compressed web wallpaper texture\`

\#\#\# Notes  
Prioritize repetition logic and atmosphere.

\---

\#\# Formula E: Hybrid short prompt

Use for:  
\- crossovers where one branch is dominant but the other contributes

\#\#\# Template  
\`\[dominant substyle\] with \[secondary influence\], \[object/page\], \[motifs\], \[surface logic\], \[palette\], \[artifact cue\]\`

\#\#\# Example  
\`Myspace profile bling with Angelfire cosmic influence, transparent glitter name graphic, crown hearts stars moon, chrome glitter glow, pink purple black palette, crunchy old-web cutout texture\`

\#\#\# Notes  
Always make one side dominant.  
Do not make muddy 50/50 soup.

\---

\#\# Myspace short prompt tokens

Useful tokens to swap in:

\#\#\# Object types  
\- glitter sticker  
\- profile badge  
\- transparent cutout graphic  
\- slogan asset  
\- nameplate  
\- comment graphic

\#\#\# Motifs  
\- hearts  
\- crowns  
\- lips  
\- stars  
\- butterflies  
\- rhinestones  
\- bunny silhouettes  
\- dark-cute skulls

\#\#\# Surface/effects  
\- glitter fill  
\- chrome bevel  
\- gel lettering  
\- white sparkle bursts  
\- glow halo  
\- fake diamond shine

\#\#\# Palette cues  
\- hot pink and purple  
\- magenta on black  
\- silver and pink  
\- toxic pink/green on black

\#\#\# Artifact cues  
\- low-res Myspace graphic  
\- crunchy transparent asset  
\- old-web glitter texture  
\- primitive glow edges

\---

\#\# Angelfire short prompt tokens

Useful tokens to swap in:

\#\#\# Page/object types  
\- shrine page  
\- portal page  
\- enter page  
\- cosmic webpage  
\- celestial wallpaper  
\- blinkie strip  
\- button grid

\#\#\# Motifs  
\- moons  
\- stars  
\- wings  
\- halos  
\- glitter hearts  
\- buttons  
\- dividers  
\- little celestial widgets

\#\#\# Surface/effects  
\- starburst glow  
\- blacklight shimmer  
\- fantasy title text  
\- low-res sparkle field  
\- cosmic halo haze

\#\#\# Palette cues  
\- purple blacklight palette  
\- magenta and white on black  
\- moonlit blue-purple-black  
\- pink-violet celestial glow

\#\#\# Artifact cues  
\- handmade early-web page  
\- compressed starfield texture  
\- old Angelfire shrine clutter  
\- rough tiled wallpaper behavior

\---

\#\# Anti-drift boosters for short prompts

When short prompts start getting too vague, add one or two of these:

\- \`tacky web graphic\`  
\- \`cheap synthetic glamour\`  
\- \`low-res glitter asset\`  
\- \`handmade shrine page\`  
\- \`transparent sticker-style cutout\`  
\- \`black-background old web sparkle\`  
\- \`crunchy early-web decoration\`  
\- \`page clutter, not minimalist design\`

These help prevent drift into clean retro slop.

\---

\#\# What short prompts should avoid

Avoid overloading short prompts with:  
\- too many unrelated motif families  
\- vague “nostalgic internet” wording with no style mechanics  
\- modern design language like “sleek,” “minimal,” “editorial,” “premium”  
\- realism-heavy material descriptions  
\- branch confusion

A short prompt needs a strong backbone, not a hundred random trinkets.

\---

\#\# Fast prompt recipes

\#\#\# Recipe 1: cute Myspace sticker  
\`Myspace profile bling transparent sticker graphic, glitter “baby girl” text, hearts crowns stars, hot pink chrome glow, black background, crunchy old-web asset\`

\#\#\# Recipe 2: dark-cute glam badge  
\`Myspace dark-cute badge graphic, pink skull and “bad girl” text, sparkles crossbones stars, toxic pink and black palette, low-res glitter texture\`

\#\#\# Recipe 3: celestial shrine page  
\`Angelfire shrine page, black starfield background, moons stars angel wings blinkies, glowing fantasy page title, violet magenta white palette, handmade old-web clutter\`

\#\#\# Recipe 4: tiled wallpaper  
\`Angelfire tiled wallpaper, repeating glitter stars hearts moons, purple pink black palette, soft glow halos, compressed early-web texture\`

\---

\#\# Summary sentence

A strong short prompt for this style names the branch, the object or page type, the symbolic inventory, the fake-glam surface logic, the palette stage, and at least one cue that keeps the output crunchy, decorative, and web-native.

