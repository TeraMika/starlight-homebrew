# starlight-homebrew
Homebrew JSONs for 5etools.

All of the JSONs are kept in source_jsons.

Templates.json is simply a blank slate for each of the main entries, like items, spells, or conditions. Eventually classes and subclasses will be added here too.

JSON Source tags take the following format:
- `Starlight: Z` is core rules additions that I would use in any campaign of mine. These are typically abbreviated to `S: Z` in the actual source, for readability.
- They are labelled separately so that they can be used separately, and together while being in separate files.
- \-> e.g.: `S: Items` and `S: Weapons` are similar, but one is for weapons/armour and the other is for all other magic items.
- \-> It's easier to edit these when they are in individual files, but if they share a source name it will break 5etools, hence the distinction.

- Anything in the 'campaign' folder will have its own source, such as `SToD` for Shifting Tides of Delamir.
- These are things that are specific to one campaign, and are not included in the main Starlight collection for that reason.
