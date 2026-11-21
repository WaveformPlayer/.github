<a href="https://waveformplayer.com"><img src="https://raw.githubusercontent.com/WaveformPlayer/assets/main/banner/banner-wide.png" alt="WaveformPlayer — beautiful, zero-dependency audio visualization for the web" width="100%"></a>

<div align="center">

**[Website](https://waveformplayer.com)** · **[Docs](https://docs.waveformplayer.com)** · [Examples](https://waveformplayer.com/examples/) · [Builder](https://waveformplayer.com/builder/) · [npm](https://www.npmjs.com/package/@arraypress/waveform-player)

[![npm](https://img.shields.io/npm/v/@arraypress/waveform-player?style=flat-square&labelColor=09090b&color=3f3f46)](https://www.npmjs.com/package/@arraypress/waveform-player)
[![downloads](https://img.shields.io/npm/dm/@arraypress/waveform-player?style=flat-square&labelColor=09090b&color=3f3f46)](https://www.npmjs.com/package/@arraypress/waveform-player)
[![gzip](https://img.shields.io/bundlephobia/minzip/@arraypress/waveform-player?style=flat-square&label=gzip&labelColor=09090b&color=3f3f46)](https://bundlephobia.com/package/@arraypress/waveform-player)
[![license](https://img.shields.io/badge/license-MIT-3f3f46?style=flat-square&labelColor=09090b)](https://github.com/WaveformPlayer/waveform-player/blob/main/LICENSE)

</div>

<br>

**Zero-config audio waveforms for the web.** Add a `data-` attribute to any `<div>` and get a real, interactive waveform player.

- **No build step, no dependencies.** Vanilla JS, about 15 KB gzipped.
- **Six waveform styles,** themeable with CSS.
- **Keyboard control and Media Session** out of the box.
- **Extensions** for a site-wide bar, playlists, sample-pack browsing and listen analytics.
- **Components** for Astro, React, Svelte and Vue.

## Quick start

```html
<link rel="stylesheet" href="https://unpkg.com/@arraypress/waveform-player/dist/waveform-player.css">
<script src="https://unpkg.com/@arraypress/waveform-player/dist/waveform-player.min.js"></script>

<div data-waveform-player data-url="track.mp3" data-title="My Song" data-artist="The Artist"></div>
```

Or from npm:

```bash
npm install @arraypress/waveform-player
```

```js
import WaveformPlayer from '@arraypress/waveform-player';

new WaveformPlayer('#player', { url: 'track.mp3', title: 'My Song', artist: 'The Artist' });
```

## Packages

<table>
<tr>
<td width="33%" valign="top">

**[WaveformPlayer](https://github.com/WaveformPlayer/waveform-player)**<br>
<sub>CORE · <a href="https://www.npmjs.com/package/@arraypress/waveform-player">npm</a></sub>

Canvas waveform player with six styles, keyboard control and Media Session.

</td>
<td width="33%" valign="top">

**[WaveformBar](https://github.com/WaveformPlayer/waveform-bar)**<br>
<sub>EXTENSION · <a href="https://www.npmjs.com/package/@arraypress/waveform-bar">npm</a></sub>

A persistent bottom bar: queue, volume, repeat, favourites, cart and cross-page sessions.

</td>
<td width="33%" valign="top">

**[WaveformPlaylist](https://github.com/WaveformPlayer/waveform-playlist)**<br>
<sub>EXTENSION · <a href="https://www.npmjs.com/package/@arraypress/waveform-playlist">npm</a></sub>

Playlists and chapters for podcasts, courses, albums and audiobooks.

</td>
</tr>
<tr>
<td width="33%" valign="top">

**[WaveformSounds](https://github.com/WaveformPlayer/waveform-sounds)**<br>
<sub>EXTENSION · <a href="https://www.npmjs.com/package/@arraypress/waveform-sounds">npm</a></sub>

A searchable, filterable sound list for sample packs, with a mini waveform per row.

</td>
<td width="33%" valign="top">

**[WaveformTracker](https://github.com/WaveformPlayer/waveform-tracker)**<br>
<sub>EXTENSION · <a href="https://www.npmjs.com/package/@arraypress/waveform-tracker">npm</a></sub>

Privacy-first listen analytics that count real listening time. No cookies.

</td>
<td width="33%" valign="top">

**[WaveformGen](https://github.com/WaveformPlayer/waveform-gen)**<br>
<sub>TOOLING · <a href="https://www.npmjs.com/package/@arraypress/waveform-gen">npm</a></sub>

A Node CLI and library that pre-generates waveform peaks and BPM from audio files.

</td>
</tr>
</table>

## Framework components

<table>
<tr>
<th></th>
<th><img src="https://cdn.simpleicons.org/astro/BC52EE" width="20" alt=""><br>Astro</th>
<th><img src="https://cdn.simpleicons.org/react/61DAFB" width="20" alt=""><br>React</th>
<th><img src="https://cdn.simpleicons.org/svelte/FF3E00" width="20" alt=""><br>Svelte</th>
<th><img src="https://cdn.simpleicons.org/vuedotjs/4FC08D" width="20" alt=""><br>Vue</th>
</tr>
<tr>
<td><b>Player</b></td>
<td><a href="https://github.com/WaveformPlayer/waveform-player-astro">player-astro</a></td>
<td><a href="https://github.com/WaveformPlayer/waveform-player-react">player-react</a></td>
<td><a href="https://github.com/WaveformPlayer/waveform-player-svelte">player-svelte</a></td>
<td><a href="https://github.com/WaveformPlayer/waveform-player-vue">player-vue</a></td>
</tr>
<tr>
<td><b>Bar</b></td>
<td><a href="https://github.com/WaveformPlayer/waveform-bar-astro">bar-astro</a></td>
<td><a href="https://github.com/WaveformPlayer/waveform-bar-react">bar-react</a></td>
<td><a href="https://github.com/WaveformPlayer/waveform-bar-svelte">bar-svelte</a></td>
<td><a href="https://github.com/WaveformPlayer/waveform-bar-vue">bar-vue</a></td>
</tr>
<tr>
<td><b>Playlist</b></td>
<td><a href="https://github.com/WaveformPlayer/waveform-playlist-astro">playlist-astro</a></td>
<td><a href="https://github.com/WaveformPlayer/waveform-playlist-react">playlist-react</a></td>
<td><a href="https://github.com/WaveformPlayer/waveform-playlist-svelte">playlist-svelte</a></td>
<td><a href="https://github.com/WaveformPlayer/waveform-playlist-vue">playlist-vue</a></td>
</tr>
<tr>
<td><b>Sounds</b></td>
<td><a href="https://github.com/WaveformPlayer/waveform-sounds-astro">sounds-astro</a></td>
<td><a href="https://github.com/WaveformPlayer/waveform-sounds-react">sounds-react</a></td>
<td><a href="https://github.com/WaveformPlayer/waveform-sounds-svelte">sounds-svelte</a></td>
<td><a href="https://github.com/WaveformPlayer/waveform-sounds-vue">sounds-vue</a></td>
</tr>
</table>

Each is on npm as `@arraypress/waveform-<name>`, for example `@arraypress/waveform-bar-react`.

<br>

<div align="center">
<sub>MIT © <a href="https://github.com/arraypress">ArrayPress Limited</a> · <a href="https://github.com/WaveformPlayer/waveform-docs">Docs source</a> · <a href="https://github.com/WaveformPlayer/assets">Brand assets</a></sub>
</div>
