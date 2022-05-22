# Polybar DSH theme
![dsh-theme-demo](https://user-images.githubusercontent.com/47615360/169708336-93c9dc9c-32ed-45e2-8a23-f7203bc9024c.gif)
<br><br>

## Run each of these command lines to install the theme:
```
git clone https://github.com/D-Freitas/polybar-dsh-theme.git dsh
mv dsh ~/.config/polybar
sed -i "59 a elif [[ \"$\1\" == \"--dsh\" ]]; then\n	style=\"dsh\"\n	launch_bar\n" ~/.config/polybar/launch.sh
sed -i "83 a\	--dsh" ~/.config/polybar/launch.sh
```

## Modules:

### modules-left
- Workspaces visualizer
- CPU meter
- Current memory used
- Free disk space meter

### modules-center
- Day, month and time

### modules-right
- Internet connection checker
- Volume adjuster
- Current user
