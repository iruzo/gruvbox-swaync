<h3 align="center">
    Gruvbox theme for <a href="https://github.com/ErikReider/SwayNotificationCenter">swaync</a>
</h3>

<p align="center">
  <img alt="gruvbox-dark" src="https://camo.githubusercontent.com/410b3ab80570bcd5b470a08d84f93caa5b4962ccd994ebceeb3d1f78364c2120/687474703a2f2f692e696d6775722e636f6d2f776136363678672e706e67" width="45%">
&nbsp; &nbsp; &nbsp; &nbsp;
  <img alt="gruvbox-light" src="https://camo.githubusercontent.com/d080d9c204408ef06b862b76bc795f930b3a9b1be4c5d2de149f1d8eb765b660/687474703a2f2f692e696d6775722e636f6d2f3439714b7959572e706e67" width="45%">
</p>

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
