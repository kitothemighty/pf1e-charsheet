# Personal Disclaimer

I want to first and foremost want to state that I am a complete novice at coding and web development. I am utilizing ChatGPT and its Codex app to create this, simply stated, I am not smart enough to do this myself therefore I cheat! I intended to keep content private until it was done but due to the images needing to be in a public repo, I guess the world will see my work after all.

# PF1E Character Sheet for Roll20

A custom Pathfinder 1st Edition character sheet for Roll20 designed specifically to work with Hero Lab Classic exports.

## Project Goal

Creating Pathfinder 1E characters in Hero Lab Classic is fast and convenient, but transferring those characters into Roll20 normally requires significant manual data entry.

This project aims to bridge that gap by providing:

* A custom Roll20 character sheet
* A Hero Lab statblock importer
* Automatic population of character statistics
* Roll20-compatible roll buttons and automation

The ultimate goal is to allow a character created in Hero Lab Classic to be imported into Roll20 with minimal manual work while still supporting Roll20's built-in rolling and character management features.

## Current Features

### Character Management

* Character information header
* Ability scores
* Initiative tracking
* Saving throws
* Skills
* Feats
* Languages
* Notes

### Hero Lab Importer

* Custom statblock payload importer
* Automatic parsing of Hero Lab exports
* Population of supported character attributes

### Roll20 Integration

* Ability score roll buttons
* Saving throw roll buttons
* Initiative roll button
* Roll20-compatible sheet workers

### Interface Improvements

* Pathfinder-themed styling
* Pathfinder logo integration
* Main / Gear / Spells tab structure
* Custom AC shield interface (work in progress)

## Installation

1. Create a Roll20 game using a Custom Character Sheet.
2. Copy the contents of:

* `pf1echarsheet.html`
* `pf1echarsheet.css`

into the appropriate Roll20 Custom Sheet editor sections.

3. Save and refresh the game.

## Project Status

This project is currently under active development.

The sheet is functional but not yet feature complete.

## Planned Features

### Combat

* Enhanced attack entries
* Damage rolls
* Critical confirmation rolls
* Combat maneuver support
* AC shield display

### Gear

* Equipment tracking
* Encumbrance calculations
* Magic item support

### Spellcasting

* Spellbook management
* Spell slot tracking
* Prepared spells
* Spells known
* Spell-like abilities

### Hero Lab Import Improvements

* Automatic attack creation
* Automatic feat creation
* Automatic gear creation
* Automatic spell creation
* Automatic special ability creation

## Contributing

Suggestions, bug reports, and feature requests are welcome. Keep in mind, I am {ahem} 'coding' at a novice level so any feature requests are more suggestions than any promise of inclusion!

## Disclaimer

Pathfinder is a trademark of Paizo Inc.

This project is a fan-made tool intended to improve Pathfinder 1st Edition play on Roll20 and is not affiliated with or endorsed by Paizo Inc., Hero Lab, Lone Wolf Development, or Roll20.
