# Obsidian X-Search

## Quick Demo

  ![x-search1](https://user-images.githubusercontent.com/38722307/216741457-53f51167-2d6f-4457-a99e-21d30987626e.gif)
  ![x-search2](https://user-images.githubusercontent.com/38722307/216741462-b59ee9cb-9195-4f4f-b338-87878c5c7cd6.gif)
  ![x-search3](https://user-images.githubusercontent.com/38722307/216741467-b5ea07d8-f86c-42c9-901a-00746b6483d6.gif)
  ![x-search4](https://user-images.githubusercontent.com/38722307/216742332-acd7848a-193b-4657-99ec-1ffa53c7405c.gif)  


## Features

- Use "section" as the minimal search unit (relatively, performance can be terrible)
- Render search results
- Intuitive filters

	| Example | Description |
	| :- | :- |
	| `# Collocation` | Search "Collocation" in all heading blocks |
	| `$$ mathbb` | Search "mathbb" in all math blocks | 
	| `\| type` | Search "type" in all table blocks |
	| `.md dataview` or `。md dataview` (position of ".md" is not important) | Search "dataview" in all files and their aliases |
	| `-[] xxx` | Search "xxx" in all check lists |
	| `- xxx` or `* xxx` | Search "xxx" in all unordered lists  |
	| `1. xxx` | Search "xxx" in all ordered lists |
	| `> linus` or `》 linus` | Search "linux" in all blockquotes |
	| `!# Collocation`   | Search "Collocation" in all NON-heading blocks   |
	
- Insert file / heading / block link directly from the search result.

## See Also

- [obsidian-another-quick-switcher](https://github.com/tadashi-aikawa/obsidian-another-quick-switcher)
- [obsidian-omnisearch](https://github.com/scambier/obsidian-omnisearch)
- [flexsearch](https://github.com/nextapps-de/flexsearch)
