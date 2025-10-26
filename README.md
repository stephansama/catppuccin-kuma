<h3 align="center">
    <img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
    <img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
  Catppuccin for <a href="https://github.com/louislam/uptime-kuma">Uptime Kuma</a>
    <img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
  Give your <a href="https://github.com/louislam/uptime-kuma">Uptime Kuma</a> status page a cute and modern look with custom CSS
  <br>
  <a href="https://kuma.denisromanov.ru"><strong>Live demo »</strong></a>
  <br>
  <br>
  <a href="#features">Features</a>
  ·
  <a href="#installation">Installation</a>
  ·
  <a href="#personalization">Personalization</a>
</p>

<p>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./.github/assets/2-col/dark.png">
    <source media="(prefers-color-scheme: light)" srcset="./.github/assets/2-col/light.png">
    <img alt="Cute Kuma" src="./.github/assets/2-col/dark.png">
  </picture>
</p>

## Features

- Modern design inspired by top monitoring services
- Support for Uptime Kuma v2
- Support for light and dark themes
- Hidden refresh timer for a cleaner look (can be easily restored)
- Clean, easily customizable and extendable code

## Installation

1. In your Uptime Kuma dashboard, navigate to status page.
2. Click `Edit Status Page`.
3. Scroll down to `Custom CSS` field.
4. Copy the contents of `main.css` and paste it into the `Custom CSS` field.
5. Click `Save` at the bottom.

## Personalization

You can easily customize the theme by modifying the variables inside the `:root {}` block.

### Columns layout

<details>
  <summary>Preview</summary>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./.github/assets/1-col/dark.png">
    <source media="(prefers-color-scheme: light)" srcset="./.github/assets/1-col/light.png">
    <img alt="Cute Kuma: 2 columns" src="./.github/assets/1-col/dark.png">
  </picture>
</details>

By default, 2 columns are shown on wide screens. If you prefer a single column everywhere, disable the 2‑column rule.

> [!IMPORTANT]
> If you enable tag display (monitor tags), it is strongly recommended to use a 1‑column layout.

1. Search for this comment:
`/* Enable 2 columns on wider screens; comment out to disable */`
2. Comment out the block immediately below it.

### Restoring the Refresh Timer

The refresh timer is hidden by default. To make it visible again, find the `.refresh-info` rule and remove or comment out the `display: none;` line.

