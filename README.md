# Twofell's Homebrew in 5e.tools
[![Format](https://img.shields.io/badge/format-5e.tools%20homebrew-5b3a70?style=for-the-badge)](https://5e.tools/)
[![Rules](https://img.shields.io/badge/rules-D%26D%205e%20%282014%29-8b2635?style=for-the-badge)](https://2014.5e.tools/)
[![Support](https://img.shields.io/badge/support-Twofell-f96854?style=for-the-badge)](https://ko-fi.com/twofell)

There are plenty of ways to share homebrew, but not all of them make it easy to bring that content into play. This repository gathers my publicly released homebrew and converts it into books that can be loaded directly into the 2014 version of 5e.tools.

Each compendium is kept in its own file, with its subclasses, feats, backgrounds, equipment, magic items and any rules needed to use them gathered together. New books will be added as more of my work is finished and given a proper 5e.tools conversion.

## Available Books

| Book | Contents | 5e.tools JSON | Original Version |
| --- | --- | --- | --- |
| **The Idol Compendium** | The Idol Agency patron, Pact of the Song, Pact Songs, Eldritch Invocations, performer backgrounds, feats, equipment, magic items and tools for creating an Agency. | [Load the 5e.tools book](https://raw.githubusercontent.com/twofelled/twofell-5etools-homebrew/refs/heads/main/book/Twofell%3B%20The%20Idol%20Compendium.json) | [Read on The Homebrewery](https://homebrewery.naturalcrit.com/share/Caw0m3qu1aRS) |
| **The Travel Agent Ranger Archetype** | A ranger archetype built around recording visited environments in a Travelogue and turning them into Featured Destinations, each with its own Amenity, Excursion and Local Specialty. | [Load the 5e.tools book](https://raw.githubusercontent.com/twofelled/twofell-5etools-homebrew/refs/heads/main/book/Twofell%3B%20The%20Travel%20Agent%20Ranger%20Archetype.json) | [Read on The Homebrewery](https://homebrewery.naturalcrit.com/share/_guXdHBsJuVf) |
| **The Professor Arcane Tradition** | A wizard tradition that turns one familiar spell into a personal Thesis Spell, gathering Insight from others and spending it on Revisions that change how the spell is cast. | [Load the 5e.tools book](https://raw.githubusercontent.com/twofelled/twofell-5etools-homebrew/refs/heads/main/book/Twofell%3B%20The%20Professor%20Arcane%20Tradition.json) | [Read on The Homebrewery](https://homebrewery.naturalcrit.com/share/T1HoPZbj1NfZ) |

## Installation

### Install from a URL

1. Open [5e.tools (2014)](https://2014.5e.tools/).
2. Open **Manage Homebrew** from the site menu.
3. Choose the option to **load homebrew from a URL**.
4. Copy the URL for the book you want and paste it into the box.
5. Refresh the site if the newly added content does not appear immediately.

#### The Idol Compendium

```text
https://raw.githubusercontent.com/twofelled/twofell-5etools-homebrew/refs/heads/main/book/Twofell%3B%20The%20Idol%20Compendium.json
```

#### The Travel Agent Ranger Archetype

```text
https://raw.githubusercontent.com/twofelled/twofell-5etools-homebrew/refs/heads/main/book/Twofell%3B%20The%20Travel%20Agent%20Ranger%20Archetype.json
```

#### The Professor Arcane Tradition

```text
https://raw.githubusercontent.com/twofelled/twofell-5etools-homebrew/refs/heads/main/book/Twofell%3B%20The%20Professor%20Arcane%20Tradition.json
```

### Install from a downloaded file

If loading from a URL is unavailable:

1. Open the raw JSON link for the book you want.
2. Save the file with the `.json` extension.
3. Open **Manage Homebrew** in [5e.tools (2014)](https://2014.5e.tools/).
4. Upload the downloaded file.
5. Refresh the site if the book does not appear immediately.

## Troubleshooting

### Updated content does not appear

5e.tools stores homebrew in your browser. Remove the previous version of the book, load the current raw URL again and refresh the page. If the old version still appears, perform a hard refresh.

A different browser or browser profile keeps its own homebrew collection, so a book loaded in one will not automatically appear in another.

### A feature, item or section fails to load

First, make sure you are using the 2014 version of 5e.tools and the current raw URL from this README. If the problem remains, [open an issue](https://github.com/twofelled/twofell-5etools-homebrew/issues) and include the book, the affected entry and any error shown by 5e.tools.

### The book appears more than once

Remove every installed copy through **Manage Homebrew**, refresh the page and load only the current version from this repository.

## Repository Conventions

- Each finished compendium is stored as its own book under `book/`.
- The JSON keeps the wording and structure of the public release unless a change is needed for 5e.tools to render it correctly.
- Renderer tags are used for spells, conditions, items, rolls and other references where appropriate.
- Shared rules will only be separated into another file if more than one book comes to depend on them.
- Files are written for D&D 5e using the 2014 rules unless the book says otherwise.
- Books do not need to be installed together unless a future entry is explicitly marked as a dependency.

## Feedback and Corrections

If something is missing, refuses to render or links to the wrong entry, report it through the repository's [Issues](https://github.com/twofelled/twofell-5etools-homebrew/issues) page.

Rules feedback is also welcome, but the formatted public release remains the main version of each brew. Any mechanical revision will be made there before the corresponding 5e.tools book is updated.

## Useful References

- [5e.tools Homebrew Repository](https://github.com/TheGiddyLimit/homebrew) — examples, naming conventions and contribution guidance.
- [5e.tools Data Repository](https://github.com/5etools-mirror-3/5etools-src/tree/main/data) — official data structures used as references.
- [5e.tools Renderer Demo](https://5e.tools/renderdemo.html) — examples of renderer entries and inline tags.
- [5e.tools Text Converter](https://5e.tools/converter.html) — a starting point for supported conversions.
- [5etools Language Server for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=revilowaldow.5etools-language-server) — live validation and editing assistance.

## Support

Everything in this repository is free to load and use at your table. If you enjoyed the work and want to help me keep making more of it, you can support me through [Ko-fi](https://ko-fi.com/twofell).

## Fan Content Notice

This is an independent homebrew project. It is not affiliated with, endorsed by, sponsored by or officially associated with 5e.tools or Wizards of the Coast.

The repository provides 5e.tools conversions of my own publicly released homebrew for personal tabletop use. Unless a book says otherwise, the writing and original material remain mine; references to third-party games, settings or properties remain the property of their respective owners.
