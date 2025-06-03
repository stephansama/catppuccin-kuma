<h3 align="center">Cute Kuma</h3>

<p align="center">
  Cute CSS for  <a href="https://github.com/louislam/uptime-kuma">Uptime Kuma</a> status page with a simple and modern look
  <br>
  <a href="https://kuma.denisromanov.ru"><strong>Live demo »</strong></a>
  <br>
  <br>
  <a href="https://github.com/dermv/cute-kuma/tree/main#features">Features</a>
  ·
  <a href="https://github.com/dermv/cute-kuma/tree/main#install">Install</a>
  ·
  <a href="https://github.com/dermv/cute-kuma/tree/main#personalization">Personalization</a>
</p>

<p>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./.github/assets/dark.png">
    <source media="(prefers-color-scheme: light)" srcset="./.github/assets/light.png">
    <img alt="Cute Kuma" src="./.github/assets/dark.png">
  </picture>
</p>

## Features

- Modern design: Inspired by top monitoring services
- Light and dark themes
- No refresh timer: Removed by default (optional restoration)
- Clean code: Easy to customize and extend

## Install

1. In your Uptime Kuma dashboard, navigate to status page.
2. Click `Edit Status Page`.
3. Scroll down to `Custom CSS`.
4. Copy the contents of `main.css` and paste it into the `Custom CSS` field.
5. Click `Save` at the bottom.

## Personalization

You can modify the values inside `:root {}` to fit your needs.

By default, the refresh timer is removed. Remove/comment `display: none;` in `.refresh-info` to restore visibility as shown here:
```
.refresh-info[data-v-b8247e57] {
  /* display: none; */
  opacity: 1;
  margin-bottom: 0 !important;
}
```
