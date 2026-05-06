# The Fields of Normandy 2 VASSAL Module

VASSAL module for **The Fields of Normandy 2: A Solitaire Wargame** by Mike Lambo.

BoardGameGeek page: https://boardgamegeek.com/boardgame/380356/the-fields-of-normandy-2-a-solitaire-wargame

This module has been released with the written permission of the author.

## Requirements

- VASSAL 3.7.21 or later

## Repository Layout

- `src/` contains the unpacked VASSAL module source, including `buildFile.xml`, `moduledata`, module help, and images.
- `src/module_info.md` is the Readme shown from inside VASSAL.
- `src/images/` contains images used by the module.
- `src/original_images/` contains source images used while preparing module assets.

## Module Features

- Mission boards 1 through 12.
- Standard and alternate counter sets.
- Toolbar dice buttons for `1d6`, `2d6`, `US Activation`, `German Unit`, and `Fire`.
- Colored dice icons in chat reports for the main game rolls.
- Unit activation tracking with a cyan border.
- `Reset Activations` toolbar command.
- `New Turn` command on the Turn counter, which resets activations and removes Smoke markers.
- US morale flipping and cover placement helpers.
- German facing rotation for units that need it.
- Map zoom controls, map image export, and hide/show pieces control.

## Using the Module

Open the module in VASSAL and start a new game. Choose one of the mission boards when prompted.

Use the `Counters` toolbar button to open the counter palette. The palette includes Standard Counters and Alternate Counters.

Activated units are marked with a cyan border. Right-click a unit and choose `Activate/Deactivate` to toggle its activation state.

To clear activation markers, use either `Reset Activations` from the toolbar or `New Turn` from a Turn counter. `New Turn` also removes Smoke markers from the map.

## Packaging

The module source is stored unpacked in `src/`. To create a distributable VASSAL module, package the contents of `src/` as a `.vmod` archive using your usual VASSAL module workflow.

## Credits

- Mike Lambo, author of *The Fields of Normandy 2: A Solitaire Wargame*.
- WeeBeasties at BoardGameGeek, for permission to use the alternate counter set.
- Nicola Marangon, module author.

## Notes

This module is intended to support play of the physical game. It does not enforce the full game rules automatically; players should follow the published rulebook.
