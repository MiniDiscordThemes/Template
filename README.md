[light]: https://user-images.githubusercontent.com/29710355/231909647-72871e7f-8763-4174-9c71-5f1bb7d401bc.png
[dark]: https://user-images.githubusercontent.com/29710355/231909520-b24c4301-2d90-4c6c-9e5d-ca9ce20e3ba6.png

[screenshot]: https://user-images.githubusercontent.com/29710355/235375875-9faeffdb-0bbb-47aa-a1ba-6ab3d8045ecc.png

[css-color]:        https://developer.mozilla.org/en-US/docs/Web/CSS/color_value
[discord]:          https://discord.gg/uy8nKQVatp

[BetterDiscord]:    https://betterdiscord.app/
[Replugged]:        https://replugged.dev/
[Vencord]:          https://github.com/Vendicated/Vencord

[shield-donate]:    https://img.shields.io/badge/Donate-ko--fi-orange?style=flat-square&logo=kofi&logoColor=orange
[ko-fi]:            https://ko-fi.com/saltssaumure "Buy me a coffee!"

[shield-total-dl]:  https://img.shields.io/github/downloads/MiniDiscordThemes/Template/Template.theme.css?color=purple&label=BD%20GitHub%20downloads&style=flat-square
[shield-asar-dl]:   https://img.shields.io/github/downloads/MiniDiscordThemes/Template/net.saltssaumure.Template.asar?color=purple&label=Replugged%20downloads&style=flat-square
[shield-repo-size]: https://img.shields.io/github/repo-size/MiniDiscordThemes/Template?style=flat-square "Total size"

[license]:          https://github.com/MiniDiscordThemes/Template/blob/main/LICENSE
[issues]:           https://github.com/MiniDiscordThemes/Template/issues
[.theme.css]:       https://github.com/MiniDiscordThemes/Template/blob/main/Template.theme.css

[release-gh]:       https://github.com/MiniDiscordThemes/Template/releases/latest "Latest GitHub release"
[release-bd]:       https://betterdiscord.app/theme/?id=000 "BetterDiscord store page"
[release-rp-store]: https://replugged.dev/install?identifier=MiniDiscordThemes/Template&source=github "Replugged store installer"
[release-rp-gh]:    https://replugged.dev/install?identifier=net.saltssaumure.Template "Replugged GitHub installer"


# Template Discord Theme
[![Buy me a coffee on ko-fi][shield-donate]][ko-fi]
[![BetterDiscord GitHub downloads][shield-total-dl]][release-gh]
[![Replugged downloads][shield-asar-dl]][release-rp-store]
![Total size][shield-repo-size]

***A template Discord theme.***

![Screenshot of Template applied to Discord][screenshot]

| Light mode                                                     | Dark mode                                                    |
| -------------------------------------------------------------- | ------------------------------------------------------------ |
| ![Screenshot of Template light mode applied to Discord][light] | ![Screenshot of Template dark mode applied to Discord][dark] |

## Installation

### BetterDiscord
1. Install [BetterDiscord][BetterDiscord].
2. Download the `Template.theme.css` file:
    - [GitHub][release-gh]
3. Place theme file in the `themes` folder:
    - Windows: `%AppData%/BetterDiscord/themes`
    - Mac: `~/Library/Application Support/betterdiscord/themes`
    - Linux: `~/.config/BetterDiscord/themes`

### Replugged
1. Install [Replugged][Replugged].
2. Install the theme:
    - [Replugged store][release-rp-store]
    - [GitHub (auto)][release-rp-gh]
    - [GitHub (manual)][release-gh]

### Vencord
1. Install [Vencord][Vencord].
2. Paste the following in `Settings` > `Vencord` > `Themes`:
    - `https://minidiscordthemes.github.io/Template/Template.theme.css`

## Customisation

| Description                    | Variable name     | Valid values                            | Default value |
| ------------------------------ | ----------------- | --------------------------------------- | ------------- |
| Background colour              | `--temp-bg-color` | Any [CSS-recognised][css-color] colour. | #000          |
| &#9936; Moving scanline on/off | `--temp-scanline` | `block` (on) or `none` (off).           | `block`       |
| &#9888; Screen flicker on/off  | `--temp-flicker`  | `flicker` (on) or `none` (off).         | `none`        |

- &#9936; This effect is performance-intensive.
- &#9888; This is a fast flickering effect and may not be suitable for those with photosensitive epilepsy.

### BetterDiscord
1. Open `Settings` > `BetterDiscord` > `Themes`.
2. Click the pencil icon on this theme.
3. Edit the variable values and save changes.

### Replugged
1. Open `Settings` > `Replugged` > `Quick CSS`.
2. Copy and paste lines 30-36 of [`Template.theme.css`][.theme.css].
3. Edit the variable values and apply changes.

### Vencord
#### Standard method
1. Follow the instructions in `Settings` > `Vencord` > `Themes`.
#### Recommended method
1. Open `Settings` > `Vencord` > `Vencord`.
2. Toggle on `Enable Custom CSS` and click `Open QuickCSS File`.
3. Copy and paste lines 30-36 of [`Template.theme.css`][.theme.css].
4. Edit the variable values.

## License
[MIT License][license]
- <span title="Too long; didn't read; not a lawyer">TL;DR;NAL</span>: Do whatever you want with this theme, just include the original license.

## Questions or suggestions?
- Post [an issue][issues] on GitHub.
- Post in `#theme-support` on [my support server][discord].
