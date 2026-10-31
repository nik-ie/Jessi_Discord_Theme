# Jessi Discord Theme
#### A purple fork of [Spotify Discord](https://github.com/CapnKitten/BetterDiscord/tree/master/Themes/Spotify-Discord) by CapnKitten
<hr>

This fork keeps the original Spotify Discord theme and swaps the green accent for a soft purple:

```css
--accent-hue: 300;
--accent-saturation: 25.68%;
--accent-lightness: 70.98%;
/* hsl(300, 25.68%, 70.98%) */
```

## Install

#### Vencord / Vesktop
Open **Settings → Themes → Online Themes** and add this link:
```
https://git.nik.ie/nik/Jessi_Discord_Theme/raw/branch/master/Spotify-Discord.theme.css
```

#### BetterDiscord
Download [Spotify-Discord.theme.css](https://git.nik.ie/nik/Jessi_Discord_Theme/raw/branch/master/Spotify-Discord.theme.css) and put it in your BetterDiscord themes folder.

The theme file only holds the color settings. It imports the main styles from the original theme, so updates to upstream come through automatically.

<hr>

This theme works best with the plugin called [SpotifyControls](https://github.com/mwittrien/BetterDiscordAddons/tree/master/Plugins/SpotifyControls) by DevilBro. To get it up and working, make sure your Spotify account is linked to your Discord account then download the plugin [here](https://github.com/mwittrien/BetterDiscordAddons/tree/master/Plugins/SpotifyControls) or from the plugin repo.

## Previews

(Previews are from the original theme and show its green accent.)

#### Main chat area

![discord_201](https://github.com/CapnKitten/Spotify-Discord/assets/4013216/b182452c-785d-42b2-9115-361faace562e)

#### User info popout

![discord_202](https://github.com/CapnKitten/Spotify-Discord/assets/4013216/c67b6d2d-71ea-47fd-a972-68ca620c5c08)

#### User settings

![discord_203](https://github.com/CapnKitten/Spotify-Discord/assets/4013216/19c44b12-1bc7-45b8-b333-2fd7843999cd)

![discord_204](https://github.com/CapnKitten/Spotify-Discord/assets/4013216/99f6d683-6837-456b-9a1a-7fa5e9a17b1a)

## Custom server title bar colors
To change the title bar color for specific servers, use the code template below and place it in your custom CSS and change the server name and HSL color code to your liking.
```css
.container-1NXEtd[aria-label*="SERVER_NAME"] {
  --header-bar-color: hsl(212,70%,31%);
}
```

## Credits
All of the theme's design and source styles are by [CapnKitten](https://github.com/CapnKitten). If you like the theme, support the original author:

- [Donate on PayPal](https://paypal.me/capnkitten)
- [Sponsor on GitHub](https://github.com/sponsors/CapnKitten)
- [Join the Discord server](https://discord.gg/jzJkA6Z)
