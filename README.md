# Gruvbox Theme - AwesomeWM

This is an adaptation of the default theme for AwesomeWM following the Gruvbox colorscheme. The main branch is basically a colorswap of the default theme while the 'opinioated' branch will contain a slightly more tailored version.

## Screenshots

### Main
![Screenshot of the main](https://i.imgur.com/E84ngOh.png)

### Opinionated
![Screenshot of the opinionated](https://i.imgur.com/14jbcR1.png)

## Installation (in .config)

You can put the directory anywhere and fetch the theme in your rc.lua by changing the beautiful.init line appropriately.
(I would recommend putting it in ~/.config/awesome/themes)

``` sh
cd ~/.config/awesome/themes
git clone https://github.com/lnus/awesome-wm-gruvbox-theme.git gruvbox
```

And the update your rc.lua accordingly

``` lua
local theme_path = gears.filesystem.get_configuration_dir() .. "themes/"
beautiful.init(theme_path .. "gruvbox/theme.lua")
```

## Installation (in /usr/share)

Clone the repo into your AwesomeWM themes directory (by default /usr/share/awesome/themes) and rename it to "gruvbox".

``` sh
cd /usr/share/awesome/themes
git clone https://github.com/lnus/awesome-wm-gruvbox-theme.git gruvbox
```

After that, put this line in your rc.lua file

``` lua
beautiful.init(gears.filesystem.get_themes_dir() .. "gruvbox/theme.lua")
```

## Contributing
Pull requests are welcome for the main branch version, please open an issue before creating a pull request.
