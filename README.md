## WindowsAPI
You don't have to do anything for this. This option should work flawlessly with Spotify, without any setup.
See a list of supported players [here](https://github.com/ModernFlyouts-Community/ModernFlyouts/blob/main/docs/GSMTC-Support-And-Popular-Apps.md).

## AIMP

**Step 1**: Set the Rainmeter skin to use AIMP.

**Step 2**: Done!

## foobar2000

**Step 1**: Download and install the [foo_cad_plus](https://github.com/RangerCD/foo-cad-plus/releases/latest) plugin for foobar2000.

**Step 2**: Set the Rainmeter skin to use foobar2000 as the music player. It's most often referred to as 'CAD'.

**Step 3**: Done!

## iTunes

**Step 1**: Set the Rainmeter skin to use iTunes.

**Step 2**: Done!

**Step 3**: Uninstall iTunes because it's just awful.

## MusicBee

**Step 1**: Go the MusicBee menu (top left corner) > Edit Preferences > Plugins (at the bottom)

**Step 2**: Enable the cd art display plugin. Enable 'launch on startup' as well.

**Step 3**: Set the Rainmeter skin to use MusicBee, most commonly referred to as 'CAD'.

**Step 4**: Done!

## Spotify

**Step 1**: Make sure you have the desktop version of Spotify installed, NOT the Microsoft Store app!

**Step 2**: Open PowerShell and run the following commands one by one:

```
Invoke-WebRequest -UseBasicParsing "https://raw.githubusercontent.com/khanhas/spicetify-cli/master/install.ps1" | Invoke-Expression
```

```
Spicetify
```

```
spicetify config extensions webnowplaying.js
```

```
spicetify config inject_css 0 replace_colors 0
```

```
spicetify backup apply
```

If you're having any issues, it's probably best to ask for help on the [Rainmeter](http://discord.gg/rainmeter) or [Spicetify](https://discord.com/invite/VnevqPp2Rr) Discord servers.

**Step 3**: Set the Rainmeter skin to use Spotify, most commonly referred to as WebNowPlaying (it uses the same plugin).

**Step 4**: Done!

## WebNowPlaying
**Step 1**: Download and install the browser extension for [Chrome](https://chrome.google.com/webstore/detail/webnowplaying-companion/jfakgfcdgpghbbefmdfjkbdlibjgnbli) or [Firefox](https://addons.mozilla.org/en-US/firefox/addon/webnowplaying-companion/). The Chrome extension should work with most Chromium-based browsers, such as Edge, Brave or Opera.

**Step 2**: Set the Rainmeter skin to use WebNowPlaying.

**Step 3**: Done!
