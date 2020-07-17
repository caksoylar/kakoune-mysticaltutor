# kakoune-mysticaltutor 📚🔮

A port of the [Mystical Tutor colorscheme](https://github.com/caksoylar/vim-mysticaltutor) to [Kakoune](https://kakoune.org).

![screenshot](https://caksoylar.github.io/mysticaltutor/images/mystical-kak.png)

There are small differences to the Vim version, such fewer background changes for highlighting selected items in menus. Themes for some terminals and [tmux](https://tmux.github.io) are also available in the [main Mystical Tutor repo](https://github.com/caksoylar/vim-mysticaltutor/tree/master/terminal).

A major feature of this colorscheme is its use of alpha-blending for selections, thus being able to preserve syntax highlighting in selected text as in the screenshot above. However this is only available in the development versions of Kakoune after commit [ccecd5b](https://github.com/mawww/kakoune/commit/ccecd5bd8e871b7aa89568609fd4ba7c50fd52ad) that support `rgba` color definitions.

Another version of the colorscheme `mysticaltutor-plain.kak` is included for use with older versions such as the [v2020.01.16 release](https://github.com/mawww/kakoune/releases/tag/v2020.01.16).

## Installation

Using [plug.kak](https://gitlab.com/andreyorst/plug.kak):
```
plug "caksoylar/kakoune-mysticaltutor" theme %{ colorscheme mysticaltutor }
```

Or you can download `mysticaltutor.kak` to your `~/.config/kak/colors/` folder and call `colorscheme mysticaltutor` in your `kakrc`.

## See also

### powerline.kak theme

A port of this colorscheme for [powerline.kak](https://gitlab.com/andreyorst/powerline.kak) is available at [jordan-yee/kakoune-mysticaltutor-powerline](https://github.com/jordan-yee/kakoune-mysticaltutor-powerline).

### Other Kakoune colorschemes

- [ayu-kak](https://github.com/Icantjuddle/ayu-kak)

- [base16-gruvbox](https://github.com/andreyorst/base16-gruvbox.kak)

- [base16-kakoune](https://github.com/leira/base16-kakoune)

- [beryl.kak](https://github.com/ftonneau/beryl.kak)

- [cosy-gruvbox.kak](https://github.com/Anfid/cosy-gruvbox.kak)

- [darkokai.kak](https://github.com/markolenik/darkokai.kak)

- [dracula](https://github.com/dracula/kakoune)

- [garbo](https://github.com/gustavo-hms/garbo)

- [kakoune-colors](https://github.com/Delapouite/kakoune-colors)

- [kakoune-material-theme](https://github.com/valerdi/kakoune-material-theme)

- [kakoune-selenized](https://github.com/TeddyDD/kakoune-selenized)

- [nord-kakoune](https://github.com/rubberydub/nord-kakoune)

- [primer.kak](https://github.com/evanrelf/primer.kak)

- [shirotelin-kakoune](https://github.com/esessoms/shirotelin-kakoune)

- [torchwood](https://github.com/codymlewis/torchwood)

- [ultrasonic](https://github.com/Jackojc/ultrasonic)

## License

MIT
