# Obsidian X-Search

## Quick Demo

![x-search](https://user-images.githubusercontent.com/38722307/214887761-342e47ae-e7da-433d-b5bd-dd8e93afcb7a.gif)

## Features

- Use "block" as the minimal search unit (relatively, performance can be terrible)
- Render math block, table block, code block in the search result
- Intuitive filters

	| Example | Description |
	| :- | :- |
	| `# Collocation` | Search "Collocation" in all the heading blocks |
	| `$$ mathbb` | Search "mathbb" in all the math blocks | 
	| `\| type` | Search "type" in all the table blocks |
	| `.md dataview` or `。md dataview` (position of ".md" is not important) | Search "dataview" in all the files and their aliases |
	| `- [x] xxx` | Search "xxx" in all the check lists |
	| `- xxx` or `* xxx` | Search "xxx" in all the unordered lists  |
	| `1. xxx` | Search "xxx" in all the ordered lists |
	| `> linus` or `》 linus` | Search "linux" in all the blockquotes |  

## See Also

- [obsidian-another-quick-switcher](https://github.com/tadashi-aikawa/obsidian-another-quick-switcher)
- [obsidian-omnisearch](https://github.com/scambier/obsidian-omnisearch)
- [flexsearch](https://github.com/nextapps-de/flexsearch)
