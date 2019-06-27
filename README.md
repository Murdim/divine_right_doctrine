# Divine Right: Coronation and Priest Nomination

A game mod for Crusader Kings II. Only includes text files; the full version must be downloaded on the [Steam Workshop][Steam]. Feel free to [contribute](#modding)!

[Steam]: https://steamcommunity.com/sharedfiles/filedetails/?id=1780291286


## Features

This mod adds a new religious doctrine, Divine Right, as an option for Pagan reformation and Random World starts.

Divine Right is incompatible with Temporal leadership, and adds up to three features to the religion:

- Catholic-style coronation ceremonies.
- Priest nomination, similar to Catholic bishop nomination with Papal investiture.
- Vassal Dukes and Kings pay homage to their liege. Disabled by default.

Each feature can be enabled individually for religions with the Divine Right doctrine, all Christians, or both.

For more info, check the mod description on [Steam], which can also be found in the file [workshop.md](workshop.md).


## Compatibility

This mod was developed for Crusader Kings 2 v3.1 with Holy Fury DLC, and should remain compatible with future versions.

It should also be compatible with most other mods.

### CK2 Overrides

* `localisation/HolyFury.csv` (partial): "Crowned by" trait names and descriptions, 1 event description.

### Notable Dependencies

* `events/HF_coronation_events.txt`: homage event chain, also contains important on-actions.
* `common/on_actions/00_on_actions.txt`
* `common/scripted_triggers/00_scripted_triggers.txt`


## Modding

The source code of this mod is publicly available for anyone to fork, reuse, or take inspiration from it. Bug reports, suggestions and pull requests are all very much welcome.

The playable version also includes image files, some of which have been derived from artwork found in the base game. In order to run the mod from this repository, you will need to extract the "gfx" directory from the Steam version, or else use some kind of placeholder.

Finally, do not forget to copy the .mod file to the root of your "mod" directory.
