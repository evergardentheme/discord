<h3 align="center">
  <img src="https://codeberg.org/evergarden/.profile/raw/branch/main/assets/logo-circle.png" width="100" alt="Logo"/><br/>
  Evergarden for <a href="https://discord.app">Discord</a>
</h3>

<p align="center">
  <a href="https://codeberg.org/evergarden/discord/stars">
    <img src="https://img.shields.io/gitea/stars/evergarden/discord?gitea_url=https%3A%2F%2Fcodeberg.org&style=for-the-badge&colorA=2B3337&colorB=F5D098">
  </a>
  <a href="https://codeberg.org/evergarden/discord/issues">
    <img src="https://img.shields.io/gitea/issues/open/evergarden/discord?gitea_url=https%3A%2F%2Fcodeberg.org&style=for-the-badge&colorA=2B3337&colorB=F7A182">
  </a>
  <a href="https://codeberg.org/evergarden/discord/activity/contributors">
    <img src="https://img.shields.io/github/contributors/evergardentheme/discord?style=for-the-badge&colorA=2B3337&colorB=B3E6DB">
  </a>
</p>

<p align="center">
	<img src="assets/previews/preview.webp"/>
</p>

### Previews

<details>
  <summary>Winter</summary>
  <img src="assets/previews/winter.webp"/>
</details>
<details>
  <summary>Fall</summary>
  <img src="assets/previews/fall.webp"/>
</details>
<details>
  <summary>Spring</summary>
  <img src="assets/previews/spring.webp"/>
</details>
<details>
  <summary>Summer</summary>
  <img src="assets/previews/summer.webp"/>
</details>

### Usage

#### [BetterDiscord](https://betterdiscord.app)

1. Download your preferred variant:

- [Summer](themes/summer.theme.css)
- [Spring](themes/spring.theme.css)
- [Fall](themes/fall.theme.css)
- [Winter](themes/winter.theme.css)

2. Copy the downloaded file to your BetterDiscord themes folder.
3. Enable the theme in BetterDiscord settings.

#### Clients/Mods with custom CSS support

1. Simply add your preferred variant into your discord clients CustomCSS file/editor.

```css
/* summer */
@import url("https://evergardentheme.github.io/discord/themes/evergarden-summer.theme.css");
/* spring */
@import url("https://evergardentheme.github.io/discord/themes/evergarden-spring.theme.css");
/* fall */
@import url("https://evergardentheme.github.io/discord/themes/evergarden-fall.theme.css");
/* winter */
@import url("https://evergardentheme.github.io/discord/themes/evergarden-winter.theme.css");

/* You can also append colors to customize the accent, e.g. */
/* winter (pink accent)*/
@import url("https://evergardentheme.github.io/discord/themes/evergarden-winter-pink.theme.css");
/* spring (orange accent) */
@import url("https://evergardentheme.github.io/discord/themes/evergarden-spring-orange.theme.css");
```

#### [Stylus](https://github.com/openstyles/stylus)

1. Enable CSP Patching from Stylus Settings > Advanced.
2. [Click here to install](discord.user.css).
3. Choose your preferred variant and accent color from the Stylus preference dropdown.

### FAQ

- Q: **_"Can this get my account banned?"_**
- A: Using third party clients and injecting custom css is against the ToS. While nobody has ever been banned for simply using discord client mods, We are not responsible for anything that might happen to your account by using third party clients. Use at your own discretion!

- Q: **_"Can I automatically switch variants between light and dark mode?"_**
- A: The following snippet showcases a configuration that switches between
  `summer` in light mode and `winter` in dark mode by adding an inline
  [`prefers-color-scheme` media
  feature](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-color-scheme),
  `(prefers-color-scheme: <light-or-dark>)`, after each `@import` statement
  (see ["Importing CSS rules conditional on media queries" -
  MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/@import#importing_css_rules_conditional_on_media_queries)).

  ```css
  @import url("https://evergardentheme.github.io/discord/themes/evergarden-winter.theme.css")
  (prefers-color-scheme: dark);
  @import url("https://evergardentheme.github.io/discord/themes/evergarden-summer.theme.css")
  (prefers-color-scheme: light);
  ```

- Q: **_"Can I disable Rainbow Threads"_**
- A: Yes, by placing the following in your QuickCSS threads will be the same colour as typical channels. *note: please respect the `space` between the colon and semi-colon*
  ```css
  :root {
    --ctp-rainbow-thread-disabled: ;
  }
  ```

### Thanks to <3

- [GlowingUmbreon](https://github.com/glowingumbreon)
- [Isabelinc](https://github.com/Isabelincorp)
- [Ren](https://github.com/watatomo)
- [winston](https://github.com/nekowinston)
- [rubyowo](https://github.com/rubyowo)
- [Aven](https://github.com/ToxicAven)
- [comfysage](https://github.com/comfysage)

<hr>

<p align="center">
  <a href="https://codeberg.org/evergarden/discord/src/LICENSE">
    <img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=LICENSE&message=Apache-2.0&colorA=2B3337&colorB=AFD9E6"/>
  </a>
</p>
