# Urdu Quran Audio

A free Islamic audio library: the complete Holy Quran — all 114 surahs in order — with
**Urdu translation only** (no Arabic recitation mixed in), provided as MP3 files plus a
machine-readable JSON index for apps.

This library powers the upcoming **Urdu Quran Audio** app, so that Urdu-speaking Muslims
everywhere can listen to the meaning of the Quran in their own language, free of charge.

## Credits

- **Urdu translation:** Fateh Muhammad Jalandhari (رحمه الله)
- **Audio source:** YouTube channel **"True Islam"** — playlist
  "QURAN JUST URDU TRANSLATION WITH TEXT (FATEH MUHAMMAD JALANDRI)":
  https://youtube.com/playlist?list=PLjMdlvowxr_0XqrqKSvbvcKd4562mnonS

All credit for the translation and the recordings belongs to their original creators.
This repository simply organises the audio into a clean, app-ready library so the
translation can reach more listeners. May Allah reward everyone involved. If you are a
rights holder and have any concern, please open an issue and it will be addressed promptly.

## The API (JSON index)

`index.json` in this repository lists every surah with its number, English and Arabic
names, MP3 file name, direct download/stream URL, duration and file size:

- Raw: https://raw.githubusercontent.com/haiderreminds/urdu-quran-audio/main/index.json
- CDN mirror: https://cdn.jsdelivr.net/gh/haiderreminds/urdu-quran-audio@main/index.json

## Audio files

All 114 MP3 files (96 kbps, ~773 MB total, ~17.9 hours) are attached to
[release v1.0](https://github.com/haiderreminds/urdu-quran-audio/releases/tag/v1.0),
named `001-al-fatiha.mp3` … `114-an-naas.mp3` in surah order.

Direct URL pattern:
`https://github.com/haiderreminds/urdu-quran-audio/releases/download/v1.0/<filename>`
