<h3 align="center">Cute Kuma</h3>

<p align="center">
  Cute CSS for  <a href="https://github.com/louislam/uptime-kuma">Uptime Kuma</a> status page with a simple and modern look
  <br>
  <a href="https://status.denisromanov.ru"><strong>Live demo »</strong></a>
  <br>
  <br>
  <a href="https://github.com/dermv/cute-kuma/tree/main#features">Features</a>
  ·
  <a href="https://github.com/dermv/cute-kuma/tree/main#installation">Installation</a>
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

# Features

- Simple and modern design, inspired by the pages of major monitoring services.
- Light and dark themes support.
- Removed the refresh timer (easily restored if needed).
- Clean and understandable code, easily customizable to fit your needs.

# Installation

1. In your Uptime Kuma dashboard, navigate to status page.
2. Click `Edit Status Page`.
3. Scroll down to `Custom CSS`.
4. Copy the contents of `main.css` and paste it into the Custom CSS field.
5. Click `Save` at the bottom.

# Personalization

You can modify the values inside `:root {}` to fit your needs.

By default, the refresh timer is removed. To restore it, simply comment `display: none;` in `.refresh-info` as shown here:
```
.refresh-info {
  /* display: none; */
  opacity: 1 !important;
  color: var(--secondary-color);
}
```
