# Setup
Install this Karabiner-elements fork: https://github.com/wwwjfy/Karabiner-Elements

Copy the karabiner config into ~/.config/karabiner/karabiner.json

start karabiner-elements

brew install kwm khd m-cli shiftit

install ubersich http://tracesof.net/uebersicht/

clone nerdbar for ubersich https://github.com/crisidev/nerdbar.widget

launch `$PATH_TO_REPO/kwm-profile laptop`

"it should be working"

Working profiles:
 * `laptop`

# kbd layout changes (through karabiner)
* right ctrl -> hyper (shift + cmd + ctrl + alt)
* right caps -> escape+ctrl, tap (less than 150 ms) sends escape, ctrl otherwise
* right alt -> cmd + ctrl + alt
* escape -> f18

# essential keybindings (through khd)
* cmd + f18: (remapped to escape) terminals
* cmd + f1/2: personal irc/browser
* cmd + f3: various\_float
* cmd + f4: various\_bsp
* cmd + f5: fuze app
* cmd + 1/2: work irc/browser
* cmd + 3: emacs
* cmd + 4: outlook
* cmd + 5: auth
* ctrl + shift + l: enables laptop profile
* ctrl + shift + f12: starts screensaver
* right alt: f1-f5/1-5: moves focused window to space

For more key combos look at the various `*.khd` files
