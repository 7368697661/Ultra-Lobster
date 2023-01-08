# 🦞 Ultra Lobster
A theme for [Obsidian](https://obsidian.md/).

![UltraLobster](https://user-images.githubusercontent.com/87339163/211223767-62ad037a-b837-41e2-a553-5b450544fbfe.png)

Ultra Lobster is a living interface theme for Obsidian, heavily inspired by modern design and focused on color and type. It offers a visually pleasing and comfortable experience, with an emphasis on rounded UI elements and soft design choices. While Ultra Lobster currently does not offer many customization options, they are planned for future updates. In the meantime, Ultra Lobster serves as a codebase for easily extending and creating new themes. It also supports many popular community plugins.

## 🎨 Color Choices 
![Screenshots](https://user-images.githubusercontent.com/87339163/211225385-7b0b4b32-945c-4957-9095-cf396451c686.png)
Ultra Lobster boasts a carefully crafted color palette that balances aesthetics with readability. The light mode is reminiscent of manilla envelopes, while the dark mode breaks from the common red and blue hues of many dark UI themes, instead opting for a green accent and coloring. Both modes offer high contrast for easy reading, while still maintaining an aesthetically pleasing look.

## ⌨️ Type Choices 
![canvas](https://user-images.githubusercontent.com/87339163/211224408-5890432a-ae00-486f-bc56-9a9cf666dcca.png)
Ultra Lobster places a strong emphasis on typography, with a focus on increasing readability and reducing strain on the eyes. To achieve this, I spent hours researching and fine-tuning font pairs and CSS settings based on factors such as contrast, legibility, and spacing. I chose to use a serif font for titles and a sans serif font for UI and text elements, as this follows centuries of design tradition and has been shown to have benefits for readability in older populations. 

![handgloves](https://user-images.githubusercontent.com/87339163/211224406-d3d75abb-29b6-4420-8c4a-8aeccee127cc.png)
The specific fonts used are DT Nightingale for titles, Syne for header 2, Aspekta for UI and editor text, and Heming for monospace. In order to save on file size, I primarily used variable fonts and only included as many as were necessary.

## ⬇️ Installation

Ultra Lobster can be found within the Obsidian community theme hub! Navigate to: 

Settings ⇨ Appearance ⇨ Themes and click “**Manage**” and search for `Ultra Lobster`

## ⚙️ Configuration

Ultra Lobster is designed to be an extensible theme, and I plan to offer a variety of customization options in the future. Currently, the Style Settings menu allows users to choose from a range of color accents that will be applied to various elements throughout the theme, such as canvas cards. Users can also enable a WIP border around the first item in lists to help visually distinguish blocks of text while bullet journaling. These options have been carefully chosen to enhance the aesthetics of both light and dark modes. 

In addition to these current options, I plan to expose variables for customization in the Style Settings menu, such as text settings, various colors, and other optional features. This will allow users to further personalize the appearance and functionality of Ultra Lobster to their preferences. 

One upcoming feature will be "type palettes" in the Style Settings menu. These palettes will allow users to choose from pre-selected font combinations that have been carefully designed to enhance the aesthetic and usability of the theme. With these options, users will be able to personalize the appearance of Ultra Lobster to their own preferences and style.

### 🔌 Plugin Support
- [Kanban](https://github.com/mgmeyers/obsidian-kanban)
- [Influx](https://github.com/jensmtg/influx)
- [Memo](https://github.com/quorafind/obsidian-memos)
- [Better Command Palette](https://github.com/AlexBieg/obsidian-better-command-palette)
- [Omnisearch](https://github.com/scambier/obsidian-omnisearch)
- [Reminder](https://github.com/uphy/obsidian-reminder)
- [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) (🚧HEAVY WIP🚧)

#### ❔ Is this theme missing something?
Open a ticket! I can't promise I will always be the fastest, but I'll try to add support and push fixes as quickly as I can.

## 🏗️ TODO
- [ ] Refactor codebase:
	- [ ] Finish commenting the `wasteland` sections of the theme
	- [ ] Add back Style Settings options
- [ ] Add Style Settings for:
	- [ ] Typography 
		- [ ] Type Palettes
			1. Serif Dominant
				- Title: DT Nightingale (*actually no clue where this font came from… Pixel Surplus?*)
				- Headers: Syne (_Google Fonts_)
				- UI, Text: [Aspekta](https://github.com/ivodolenc/aspekta?ref=uncut.wtf)
				- Monospace: [Heming](https://www.behance.net/gallery/142001915/Heming-Free-Variable-Font?locale=en_US)
			2. Sans-Serif Dominant 
				- Title: TBD (*Aspekta*?)
				- Headers: TBD
				- UI, Text: TBD
				- Monospace: TBD
			3. Support for loading font packs? idk.
		- [ ] Type Settings
			- [ ] Size, maybe; might be redundant since you can change size in settings and I am using clamp values for responsive type
	- [ ] Color
		- [ ] Additional Sub-themes
		- [ ] (*small design trick that goes a long way*) Add chosen color accent to:
			- [ ] `background-primary`
			- [ ] `background-secondary`
			- [ ] Add to shadows
		- [ ] Potentially switch current color scheme to "Ultra Lobster" sub-theme, and use a neutral base theme palette
	- [ ] UI
		- [ ] Finish Callout theming
		- [ ] Finish plugin support
		- [ ] Clean up card UI code
		- [ ] Codeblocks
		- [ ] Embeds
		- [ ] Asides? (_maybe footers would be nice_)

## 💖 Credits

-  🖥️ **Lukemt** for their smooth live headers and continued help!
-  🐕**Anubis** for their rainbow folders
-  💎 **Obsidian**, for the amazing program to theme
-  ⌨️ The amazing **plugin** developers, for their time
-  🎨 The gifted **theme** community, for their inspiration
-  📌 **Pinterest** for offering far too many designs to look at
-  👯 Countless members of **the community**, for helping me test things
-  😈 Myself, for writing all of this
-  🎡 John Wheeler, for still having a really cool name
-  💖 **You**, for reading this & trying my theme

## ⚖️ Licensing

Ultra Lobster is licensed under the [MIT License](https://opensource.org/licenses/MIT), which means that it is free to use, modify, and distribute for personal or commercial use. I encourage users to customize and edit the theme to create their own unique versions. Please keep in mind that any modifications or distributions of the theme must retain the original MIT License and credit to the original author (*me*) and anyone else who’s code is used in those snippets :)

I hope that this theme serves as a helpful and flexible starting point for your own customization and development. If you have any questions or need further information, please don't hesitate to ask.
