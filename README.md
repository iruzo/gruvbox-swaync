<h3 align="center">
    Gruvbox theme for <a href="https://github.com/ErikReider/SwayNotificationCenter">swaync</a>
</h3>

<p align="center">
	<img src="https://raw.githubusercontent.com/iruzo/gruvbox-swaync/main/assets/preview.webp"/>
</p>

## Previews

<details>
  <summary>:black_circle: Dark</summary>
  <img src="https://raw.githubusercontent.com/iruzo/gruvbox-swaync/main/assets/swaync-dark.png"/>
</details>
<details>
  <summary>:white_circle: Light</summary>
  <img src="https://raw.githubusercontent.com/iruzo/gruvbox-swaync/main/assets/swaync-light.png"/>
</details>

## Usage

1. Download the corresponding theme into `~/.config/swaync/style.css`
- dark
```sh
curl https://raw.githubusercontent.com/iruzo/gruvbox-swaync/main/gruvbox-dark.css > ~/.config/swaync/style.css
```
- light
```sh
curl https://raw.githubusercontent.com/iruzo/gruvbox-swaync/main/gruvbox-light.css > ~/.config/swaync/style.css
```
- You can let sway manage your swaync theme
```sh
exec_always if [ ! -f ~/.config/swaync/style.css ]; then $(mkdir -p ~/.config/swaync && curl -L https://raw.githubusercontent.com/iruzo/gruvbox-swaync/main/gruvbox-dark.css -o ~/.config/swaync/style.css); fi
```
```sh
exec_always if [ ! -f ~/.config/swaync/style.css ]; then $(mkdir -p ~/.config/swaync && curl -L https://raw.githubusercontent.com/iruzo/gruvbox-swaync/main/gruvbox-light.css -o ~/.config/swaync/style.css); fi
```
2. Restart swaync
