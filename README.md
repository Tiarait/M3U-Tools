[![Stand With Ukraine](https://raw.githubusercontent.com/vshymanskyy/StandWithUkraine/main/banner2-direct.svg)](https://vshymanskyy.github.io/StandWithUkraine/)

[![Issues][issues-shield]][issues-url] [![Android][android-shield]][gp-url] [![LinkedIn][linkedin-shield]][linkedin-url]

# **M3U Tools: IPTV Playlist Editor**

[<img src="/screenshots/play_store_512.png" align="left"
width="25%" hspace="10" vspace="10">](#)

M3U Tools is an Android app for importing, editing, organizing, and exporting IPTV playlists in M3U/M3U8 format. 

It is built for people who manage live TV channel lists: fix metadata, clean duplicates, check stream URLs, refresh from a remote source, and export a clean file for your player.

All playlist data stays on your device. The app does not require an account.

<p align="left">
<a href="https://play.google.com/store/apps/details?id=ua.tiar.m3utools">
    <img alt="Get it on Google Play"
        height="73"
        src="https://play.google.com/intl/en_us/badges/images/generic/en_badge_web_generic.png" />
</a>  
</p>
<br>

### User Help (soon)

[Information about available settings in the application](https://tiarait.github.io/M3U-Tools-Intro/help.html)

## Why use M3U Editor?

| Advantage | What it means for you |
|-----------|------------------------|
| **Preserves your source file** | Original M3U formatting, unknown tags, and lines like `#KODIPROP` are kept where possible. Edits patch the existing block instead of rewriting everything from scratch. |
| **Fields + Raw editing** | Edit channels and playlist headers in structured forms, or switch to raw M3U text when you need full control. |
| **Large playlists** | Channel lists load quickly because the UI does not load full raw text for every row. |
| **URL-based playlists** | Import from a URL, refresh when the provider updates the list, and review changes before applying. |
| **Stream URL checker** | Run background checks (HEAD/GET) and filter channels by OK / Error / Unchecked. |
| **Power tools** | Merge playlists, find duplicates, bulk edit, reorder, hide groups, move/copy between playlists. |
| **Export anywhere** | Save to a file, share via another app, or copy generated text. |


## Tips and limitations

- **Player app** — M3U Editor edits playlists; it does not play streams itself (except launching URLs in another app).
- **Parse warnings** — if some lines fail to import, a global dialog lists line numbers; valid channels are still saved.
- **Undo** — deleting channels or playlists may offer an undo snackbar at the bottom of the screen.
- **Private data** — playlists may contain credentials in URLs. Database and M3U files are excluded from cloud backup by default; device-to-device transfer can include them if you use Android’s transfer flow.
- **Very large playlists** — browse mode is optimized; reorder mode loads the full list once. Paging for 10k+ channels is planned for a future update.
- **Network** — import, refresh, URL check, and logo preview require internet for remote URLs. Only use sources you trust.


### Planned Features:

- **Cloud sync** | Opt-in backup/sync (Google Drive, WebDAV, etc.) 
- **Export profiles** | Presets: TiviMate, Kodi, minimal metadata, full metadata
- **Compare two playlists** | Diff report without merge — added/removed/changed channels
- **Regex bulk rename** | Find/replace across name, URL, group, tvg-id for selection or whole playlist

## Screenshots
[<img src="/screenshots/01_screenshot.png" align="center"
width="20%" hspace="10" vspace="10">](/screenshots/01_screenshot.png)
[<img src="/screenshots/02_screenshot.png" align="center"
width="20%" hspace="10" vspace="10">](/screenshots/02_screenshot.png)
[<img src="/screenshots/03_screenshot.png" align="center"
width="20%" hspace="10" vspace="10">](/screenshots/03_screenshot.png)
[<img src="/screenshots/04_screenshot.png" align="center"
width="20%" hspace="10" vspace="10">](/screenshots/04_screenshot.png)
[<img src="/screenshots/05_screenshot.png" align="center"
width="20%" hspace="10" vspace="10">](/screenshots/05_screenshot.png)
[<img src="/screenshots/06_screenshot.png" align="center"
width="20%" hspace="10" vspace="10">](/screenshots/06_screenshot.png)
[<img src="/screenshots/07_screenshot.png" align="center"
width="20%" hspace="10" vspace="10">](/screenshots/07_screenshot.png)
[<img src="/screenshots/08_screenshot.png" align="center"
width="20%" hspace="10" vspace="10">](/screenshots/08_screenshot.png)
    

## License

M3U Tools is released under the [Apache-2.0](LICENSE).

[linkedin-url]: https://linkedin.com/in/tiarait
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[issues-shield]: https://img.shields.io/github/issues/Tiarait/M3U-Tools.svg?style=for-the-badge
[issues-url]: https://github.com/Tiarait/M3U-Tools/issues
[version-shield]: https://img.shields.io/badge/Version-1.0.1-blue?style=for-the-badge
[gp-url]: https://play.google.com/store/apps/details?id=ua.tiar.m3utools

[coffee-shield]: https://img.shields.io/badge/-Bye_me_a_coffee-red.svg?style=for-the-badge&logo=buymeacoffee&colorB=grey
[coffee-url]: https://www.buymeacoffee.com/tiarapps

[android-shield]: https://img.shields.io/badge/Android-8.0+-green?style=for-the-badge
[stand-with-ukraine]: https://img.shields.io/badge/Stand_With-Ukraine-yellow?style=for-the-badge&labelColor=blue
[stand-with-ukraine-url]: https://vshymanskyy.github.io/StandWithUkraine
