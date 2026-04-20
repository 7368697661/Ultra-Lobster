<img width="1920" height="1080" alt="preview_thumb" src="https://github.com/user-attachments/assets/58147806-bd64-4fbb-9d19-5ce72457770d" />

# hi
this is ultra lobster.. idk what this theme is anymore 😭

<img width="1920" height="597" alt="ul5" src="https://github.com/user-attachments/assets/eaf973d4-9f94-4450-90c4-d19db82d48b7" />

<img width="1710" height="1067" alt="image" src="https://github.com/user-attachments/assets/43be71ba-0d60-4a6b-905b-25c0ec73b9b9" />

‘ultra lobster’ is the culmination of all the css i have written for obsidian. i wanted a theme that pushed obsidian's UI as far as possible (via card layouts, glassmorphism, and deep customization) without losing the core utility of a note-taking app.

the result is a rather large theme that offers plenty of options without being too overwhelming. because at the end of the day, i simply want to make a theme that makes taking notes more pleasant.

```
/*
╭── . ݁₊ ✶ ──────────── ✶ ₊ ݁ . ──╮
  section: flagship features
╰──────────────────────────────╯
*/
```

### ✨ standout features
ultra lobster comes packed with massive visual overhauls, most notably through way to many colorschemes/subthemes, two of which make massive mechanical changes to the ui:

### 🌋 flagship subthemes
while there are dozens of subthemes available, two stand out as the definitive ultra lobster experience:

🪟 abaddon glass: a dark, moody theme that applies heavy frosted glass (backdrop-filter) to the main reading view and floating headers. it allows custom backgrounds to shine through :3
<img width="1710" height="1070" alt="image" src="https://github.com/user-attachments/assets/ce7541bb-5415-450c-bd3d-3441a5fd7e18" />

🦎 chameleon: an adaptive subtheme that dynamically shifts its entire color palette based on your chosen accent color.
<img width="1920" height="1205" alt="ul-cham-light" src="https://github.com/user-attachments/assets/7b661a32-d63a-402f-b5c4-c892715661fc" />
<img width="1920" height="1202" alt="ul-cham-dark" src="https://github.com/user-attachments/assets/c3e959de-69e5-41f4-aa84-a1feb7c75241" />

### 🖼️ custom workspace backgrounds
when using the abaddon glass subtheme, you can paste a direct image url into Style Settings to set a custom wallpaper that displays behind your notes, visible through the frosted glass UI.
<img width="1920" height="1205" alt="ul-ab-glass" src="https://github.com/user-attachments/assets/e7045f40-107a-4391-9ee5-a4ed2b13aa87" />
(**!! image url MUST be surrounded by url("url-here")**)

### 💫 halo gradient animation
a toggleable, infinite-expanding accent ring background feature. it creates a slow, rhythmic, pulsating gradient behind your workspace that is both visually stunning and unobtrusive.

### 🎨 massive subtheme library
not into glass? no worries. there are dozens of finely-tuned subthemes for both light and dark mode, including:
Demon Queen, Succubus, Sorcery, Megalodon, Timberwolf, Shadow, Blahaj, Gruvbox, Solarized, and many more!
<img width="1920" height="1203" alt="ul-light" src="https://github.com/user-attachments/assets/95ac60e4-4586-4cd8-8d2c-ac7ae18bee45" />
<img width="1920" height="1204" alt="ul-dark" src="https://github.com/user-attachments/assets/7be27104-db21-45c6-9dc7-0c74a6235057" />

**color schemes:**
:sunny: **light themes:**
- :lizard: chameleon: automatically adapts to your accent color
- :heart: sorcery: warm, blush-toned theme with soft reds and creamy backgrounds
- :green_heart: eidolon: soothing and botanical with muted sage greens
- :blue_heart: shadow: cool and airy with soft icy blues and crisp whites
- :purple_heart: umbra: a gentle floral theme with light lavender undertones
- :sunrise: creation: parchment-inspired with warm ivory, cream, and beige
- :classical_building: architect: structured and concrete-inspired with cool neutral greys
- :transgender_flag: blahaj: bright and playful with vivid candy-pink gradients
- :sunny: solarized: a classic low-contrast warm yellow-beige for reading comfort
- :package: gruvbox: retro-inspired with warm earthy sand and tan colors
- :lobster: lobster-time: vibrant and aquatic with bright sky blues
- :wolf: timberwolf: high-contrast with a sharp greyscale palette
- :shark: megalodon: deep-sea inspired with slate greys and washed-out blues

:crescent_moon: **dark themes:**
- :lizard: chameleon: automatically adapts to your accent color
- :heart: sorcery: deep and rich with blood red and burgundy gradients
- :green_heart: eidolon: calm and forest-inspired with deep emerald greens
- :blue_heart: shadow: moody and midnight-blue with cool indigo tones
- :purple_heart: umbra: mystical with deep plum, amethyst, and violet gradients
- :coat: soft: comfortable and low-contrast using smooth charcoal greys
- :rotating_light: control: brutalist and high-tech with sharp concrete greys
- :construction: blueprint: technical and deep grid-blue, like drafting paper
- :classical_building: architect: structured and stone-inspired with dark slate greys
- :transgender_flag: blahaj: deep soft blues contrasted with vivid neon pinks
- :sunny: solarized: classic teal-toned deep grey designed to lower eye strain
- :package: gruvbox: warm and retro with rich espresso browns and earthy accents
- :lobster: lobster-time: deep-sea vibes with very dark, rich ocean blues
- :bat: dracula: high-contrast and vibrant with a deep purple-grey background
- :thought_balloon: linking your thinking: a focused theme collab with deep navy and warm accents
- :volcano: abaddon: ultra-dark with near-black backgrounds and intense borders
- :window: abaddon glass: a variant of abaddon that lets you put a custom image behind frosted glass
- :wine_glass: succubus: sensual and velvety with rich burgundy and deep wine reds
- :crown: demon queen: regal and intense with dark violet and deep crimson tones
- :rabbit: bunny: cozy and soft with warm chocolate browns and gentle earthy tones

```
/*
╭── . ݁₊ ✶ ──────────── ✶ ₊ ݁ . ──╮
  section: workspace ui
╰──────────────────────────────╯
*/
```

### 🪟 workspace ui
<img width="1710" height="1075" alt="image" src="https://github.com/user-attachments/assets/ee779372-a378-47a0-aeb8-acb7213eafaf" />

### 🃏 floating card ui
with base ultra lobster ui i ditch rigid panels for a floating card layout. the tab bars, breadcrumbs, and window controls have been consolidated into sleek "pill" designs with subtle outer shadows. i did heavy and intense ui resets so i could rebuild the ui the way i want it. because of the approach i took with this theme, it remains extremely performant despite its size.

###📁 refined file explorer
the file explorer has gradients for open folders, cleaner highlights for active files that don't overlap indentation lines, and a highlight feature that shows which folders the open file sit in.

### Ⓜ glass menus & modals
command palettes, settings menus, tooltips, and context menus have all been redone with altered borders, custom shadows, and heavy blurred glass effects (that can be toggled).

### 🫓 flat mode
with the move towards blur and (complex) borders (loosely inspired by glassmorphism) i understand some might miss the old ultra lobster with its abstract 'flat' ui. because of that, i spent way too much time making a 'flat' mode that strips the intricate borders and shadows in favor of a level ui. milage may very, open an issue if you find something please :)

```
/*
╭── . ݁₊ ✶ ──────────── ✶ ₊ ݁ . ──╮
  section: markdown elements
╰──────────────────────────────╯
*/
```

### 📝 note elements
<img width="1710" height="1077" alt="image" src="https://github.com/user-attachments/assets/c97bcaa2-b77b-487a-88cd-2fe6c73848d8" />
<img width="1710" height="1073" alt="image" src="https://github.com/user-attachments/assets/507fb4fd-d439-4ec3-a5a0-8880b5e570b9" />

### 🗣 blockquotes
blockquotes have been stripped of bulky styling in live view, and feature a clean shadow and outer-border system in reading view without rendering artifacts. they also support the citation syntax from eleanor konik’s wonderful palatinate theme.
<img width="727" height="440" alt="image" src="https://github.com/user-attachments/assets/9e69fa58-4537-4ea6-9da8-d76fb115be4c" />
(use `<cite>text</cite>`)

❗ callouts
<img width="732" height="399" alt="image" src="https://github.com/user-attachments/assets/25646ef9-bfdb-46ce-b876-25941c3e4bfe" />
(default callouts)
for callouts, i kept it simple for defaults. however, with style settings, i offer a few different versions:
- gummy: callouts from my gummy theme
- notyoutube: callouts inspired/color matched to youtube's cards
- brutal: heavy border, drop shadow creates paper effect
- soft: no border, darker tone on top to give depth (currently broken)
- working edits mk3: glowing callouts from my working edits (we) tweaks
- line: minimal side-line styling

### 🖥 codeblocks
code blocks by default are very minimal. they have slight animations, and a small gradient. additionally, with style settings, there are alternative options:
- gummy: codeblocks from my gummy theme with accent colors and dynamic glow.
- notosx: terminal mac style blocks by zamsyt#4459 💖.

### ❓ custom checkboxes
with ultra lobster, i added several custom checkboxes that can be used with the following operators:
```
- [!] (important)
- [?] (question)
- [i] (info)
- [*] (star)
- [+] (plus/add)
- [-] (minus/remove)
- [b] (bookmark)
- ["] (quote)
- [l] (location)
```

```
/*
╭── . ݁₊ ✶ ──────────── ✶ ₊ ݁ . ──╮
  section: canvas
╰──────────────────────────────╯
*/
```

### 🖼️ canvas
<img width="1007" height="805" alt="image" src="https://github.com/user-attachments/assets/d034a541-8215-469c-b087-267f464bd528" />

gods… so much here. there are thousands of lines of just canvas stuff. 
- cards feature heavy rounding (28px) to match the ui.
- by default cards have heavy blur. idk, i think its pwetty :p
- control groups and menus have been themed as floating glass pills.
- multiple color options per card from several themes & snippets.
    - canvas cards feature per color style settings options for different gradients or colorways.
- ! performance toggle: a new toggle to disable the heavy canvas blur effects if you prefer solid colors or need better performance.

### .𖥔 ݁ ˖ mobile support ⊹ ࣪ ˖
ultra lobster is fully responsive and tailored for obsidian mobile (ios tested, if there are android issues lmk <3). 
- phone & tablet ready: workspace elements, side docks, and menus scale elegantly to fit your screen.
- feature parity: all custom styles, from canvas edges to custom checkboxes, work just as well on mobile.
- style settings: fully compatible with the style settings plugin on mobile, so you can tweak your theme on the go.
<img width="368" height="733" alt="image" src="https://github.com/user-attachments/assets/3196f4f2-bc1e-43aa-b02f-e0681c548686" />


```
/*
╭── . ݁₊ ✶ ──────────── ✶ ₊ ݁ . ──╮
  section: style settings
╰──────────────────────────────╯
*/
```

### ⚙️ style settings stuff
ultra lobster is built to be tweaked. i highly recommended you install the style settings plugin.
through style settings, you can completely change the vibe of the theme:
- toggles: disable callout blurs, mobile nav blurs, popup menu blurs, header underlines, and canvas blurs.
- custom Backgrounds: input a direct image URL to theme the Abaddon Glass subtheme.
- granular typography: absolute control over editor fonts, title fonts, and inline titles.
- header customization: choose exact hex colors, typefaces, font weights, and underline styles for every individual header level (h1-h6).
- animations: enable the wip halo gradient background:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e37d6aee-c113-49d9-84a5-22cd136080a3" />



```
/*
╭── . ݁₊ ✶ ──────────── ✶ ₊ ݁ . ──╮
  section: plugins & credits
╰──────────────────────────────╯
*/
```

🔌 supported plugins
style Settings: REQUIRED for accessing subthemes, customizing colors, enabling the custom background, and adjusting typography.
there is loose support for the following plugins:
- Better Command Palette
- cMenu Toolbar
- Calendar
- Loomsidian
- Kanban
- Omnisearch
- Tag Navigator
- Style Settings
- Dataview (Tables & Lists)
- Tasks
- Excalidraw

❓ is this theme missing something?
open a ticket! I can't promise I will always be the fastest, but i'll try to add support and push fixes as quickly as I can.

💕 credits
- 🖤 data for their support
- 🖥️ lukemt for their smooth live headers and continued help!
- 💭 the wonderful lyt theme by nick milo!
- 💎 obsidian, for the amazing program to theme
- ⌨️ the amazing plugin developers, for their time
- 🎨 the gifted theme community, for their inspiration
- 📌 pinterest for offering far too many designs to look at
- 👯 countless members of the community, for helping me test things
- 😈 myself, for writing all of this
- 🎡 john wheeler, for still having a really cool name
- 💖 you, for reading this & trying my theme!

⚖️ Licensing
ultra Lobster is licensed under the mit License, which means that it is free to use, modify, and distribute for personal or commercial use. i encourage users to customize and edit the theme to create their own unique versions. please keep in mind that any modifications or distributions of the theme must retain the original mit License and credit to the original author (me) and anyone else who’s code is used in those snippets :)

i hope that this theme serves as a helpful and flexible starting point for your own customization and development. if you have any questions or need further information, please don't hesitate to ask. my discord is moka.bbg :)

```
⠀⠀⠀⠀⠀⠀⠀⠀⣠⣶⣶⣶⣦⠀⠀
⠀⠀⣠⣤⣤⣄⣀⣾⣿⠟⠛⠻⢿⣷⠀
⢰⣿⡿⠛⠙⠻⣿⣿⠁⠀⠀⠀⣶⢿⡇
⢿⣿⣇⠀⠀⠀⠈⠏⠀⠀⠀ ultra lobster
⠀⠻⣿⣷⣦⣤⣀⠀⠀⠀⠀⣾⡿⠃⠀
⠀⠀⠀⠀⠉⠉⠻⣿⣄⣴⣿⠟⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⣿⡿⠟⠁⠀⠀⠀⠀
```
