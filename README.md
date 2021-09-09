# My i3 configuration

This is my configuration of the tiling window manager i3.

<img src="https://github.com/Manuel0516/i3/blob/master/Screenshots/i3.jpg">

## Dependencies 🚀 :

Install the most important package, i3:

```
The tiling window manager i3 (pacman -S i3) and all of his packages.
```

Terminal:

  ```
  -alacritty (pacman -S alacritty).
  ```
  
Menu:

  ```
  -rofi (pacman -S rofi).
  ```

Fonts: 

  ```
  -Nerd fonts (yay nerd-fonts-complete).
  -Noto-fonts-emoji (pacman -S noto-fonts-emoji).
  ```

Wallpaper:

  ```
  -feh (pacman -S feh).
  -picom (pacman -S picom) for the applications' transparencies.
  ```

Resolution:

  ```
  -xrandr (pacman -S xorg-xrandr) for change the resolution.
  ```

## Instalation 🔧:

replace your i3 folder in /home/(your user name)/.config/i3

```
Pres sift + mod (for default the key "win") + r
```

And the configuration file will be reloaded with the new configuration

## How to use ✏️:

(key mod = key win in the default configuration)

Open a new terminal:

```
mod + enter = new terminal
```

Close one window:

```
mod + q = close the window focus
```

Open aplications:

```
mod + d = rofi launcher
```

Move between windows:

```
mod + (arrows) = focuse the window
```

Move the windows:

```
mod + sift + (arrows) = move the focuse window
```

Rezice the window:

```
mod + r = enter en mode resize (to exit press esc)

use the arrows to rezise the focuse window
```

## The screen.sh:

This is a script to change the resolution, for default it is comment but you can add your configuration in there.

```
nano screen.sh
```

## Credits:

Manuel0516 is the coder of this files.
