# War Sans

War Sans, font packs for _World of Warcraft_ and _WoW Classic_ that support all client languages. War Sans is subsetted [Nowar Sans](https://github.com/nowar-fonts/Nowar-Sans).

## Character Set

War Sans introduced some character sets:
* WoWE (WoW European)
  + union set of [Adobe Latin 3](https://adobe-type-tools.github.io/adobe-latin-charsets/adobe-latin-3.html), [Adobe Cyrillic 1](https://adobe-type-tools.github.io/adobe-cyrillic-charsets/adobe-cyrillic-1.html) and [Adobe Greek 1](https://adobe-type-tools.github.io/adobe-greek-charsets/adobe-greek-1.html) character sets;
  + contains more than 500 characters;
  + supports all characters allowed in Latin and Cyrillic character names.
* WoWC (WoW Chinese)
  + roughly “WoWE with common Chinese Character”;
  + superset of GBK, Big 5, JIS X character sets;
  + supports all characters allowed in Latin and Cyrillic character names, and almost all characters in Chinese character names (except non-radical characters in URO+, 龦, 龧, 龨, 龩, 龩, 龫, 龬, 龭, 龮, 龯, 龲, 龳, 龼, 龽, 龾, 龿, 鿀, 鿁, 鿂, 鿃, 鿄, 鿅, 鿆, 鿇, 鿈, 鿉, 鿊, 鿋, 鿌, 鿍, 鿎, 鿏, 䲤, 鿑, 鿒, 鿓, 鿔, 鿕, 鿖, 鿗, 鿘, 鿙, 鿚, 鿛, 鿜, 鿝, 鿞, 鿟, 鿠, 鿡, 鿢, 鿣, 鿤, 鿥, 鿦, 鿧, 鿨, 鿩, 鿪, 鿫, 鿬, 鿭, 鿮, 鿯).
* WoWG (WoW Global)
  + roughly “WoWC with Hangul jamo and syllable”;
  + superset of GBK, Big 5, JIS X, KS X character sets;
  + supports all characters allowed in WoW character names;
  + good for general chat in all WoW client languages.

## Download the Fonts

[Latest release at GitHub](https://github.com/nowar-fonts/War-Sans/releases)

Mirrors: [Gitee (Release Repo)](https://gitee.com/nowar-fonts/War-Sans)

Nowar Sans is shipped in 4 weights and 7 regional variants.

### Weights

* 300: Light
* 400: Regular
* 500: Medium
* 700: Bold
* [Morpheus (European display font) may be bolder or lighter.]

### Regional Variants

CN, TW, HK, JP and KR are “standard variants”, which support WoWG character set with regional Chinese character orthographies.

|    | European            | 简体中文       | 繁體中文  | 한국어        |
| -- | ------------------- | -------------- | --------- | ------------- |
| CN | Mainland China (UI) | Mainland China | Taiwan    | S. Korea (UI) |
| TW | Taiwan (UI)         | Mainland China | Taiwan    | S. Korea (UI) |
| HK | Hong Kong (UI)      | Mainland China | Hong Kong | S. Korea (UI) |
| JP | Japan (UI)          | Mainland China | Taiwan    | S. Korea (UI) |
| KR | S. Korea (UI)       | Mainland China | Taiwan    | S. Korea (UI) |

CL, the “classical variant”, supports WoWG character set with classical Chinese character orthography (aka Kāngxī Dictionary forms).

|     | European       | 中文      | 한국어         |
| --- | -------------- | --------- | -------------- |
| CL  | Classical (UI) | Classical | Classical (UI) |

GBK is a variant that supports the WoWC character set. It has smaller archive sizes.

|     | European            | 中文           | 한국어 |
| --- | ------------------- | -------------- | ------ |
| GBK | Mainland China (UI) | Mainland China | N/A    |

* European: English, Español (AL), Português, Deutsch, Español (EU), Français, Italiano, and Русский.
* UI: Ambiguous punctations are treated as Western; CJK puctations are half-width.

### Features

| Tag | Name        | Description                                                            |
| --- | ----------- | ---------------------------------------------------------------------- |
| OSF | Oldstyle    | Oldstyle (non-lining), propotional figure.                             |
| SC  | Smallcaps   | Small capitals for Latin.                          |
| RP  | Roleplaying | `丶` (U+4E36) is mapped to the same glyph as `·` (U+00B7, MIDDLE DOT). |

Pre-built feature variant: `CL,OSF`. More feature variants can be built in minutes.

## How to Build

Same as [Nowar Sans](https://github.com/nowar-fonts/Nowar-Sans#how-to-build). Note that you don’t need Source Han Sans files (they are already included in the repo).

## Credit

Latin, Greek and Cyrillic characters are from [Noto Sans](https://github.com/googlei18n/noto-fonts) by Google.

CJK Ideographs, Kana and Hangul are from [Source Han Sans](https://github.com/adobe-fonts/source-han-sans) by Adobe.
