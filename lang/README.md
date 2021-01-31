if you want to add a new language;

  Create a `<language_you_added.sh>` file, at that dir.

Its name will be such as english.sh

and run **tetori.sh** as:
```sh
sh /tetori.sh -l english
```

The main script will automatically identify the local variables you added.


EXAMPLE `language_you_added.sh` file:
```bash
i18n_lines_completed="Lines completed: "
i18n_level="Level:           "
i18n_score="Score:           "
i18n_use_cursor_keys="  Use cursor keys"
i18n_or="       or"
i18n_rotate="    s: rotate"
i18n_left_right="a: left,  d: right"
i18n_drop="    space: drop"
i18n_quit="      q: quit"
i18n_toggle_color="  c: toggle color"
i18n_toggle_show_next="n: toggle show next"
i18n_toggle_this_help="h: toggle this help"
i18n_game_over="Game over!"
```
