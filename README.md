# CharCards — English localization patch

A KOReader user patch that switches [CharCards](https://github.com/poostoon/charcards) to English.

[CharCards](https://github.com/poostoon/charcards) is a manual, AI-assisted character tracker for KOReader. Its interface and Gemini prompts are Ukrainian by default. With this patch installed, the whole interface **and** the prompts sent to Gemini are in English, so character cards for English books are written in English.

## Requirements

* KOReader
* [CharCards](https://github.com/poostoon/charcards) **1.2.0 or newer** (1.3.0 or newer recommended — the patch covers every interface string of those versions, including *Undo last action*)

## Installation

1. Download [`1-charcards-en.lua`](https://github.com/poostoon/charcards-en-patch/blob/main/1-charcards-en.lua) ([raw file](https://raw.githubusercontent.com/poostoon/charcards-en-patch/main/1-charcards-en.lua)).
2. Copy it to:

   ```text
   /koreader/patches/
   ```

3. Restart KOReader.

You can also install it from **Storefront → Patches** once it is listed there.

The interface and the Gemini prompts are now in English.

## Going back to Ukrainian

Delete `1-charcards-en.lua` from `/koreader/patches/` and restart KOReader. Nothing in the plugin itself was changed, so nothing else needs to be undone.

## Good to know

* The patch does not modify the plugin's files. It only replaces the plugin's interface texts and its two Gemini prompts while KOReader is running.
* If a future version of CharCards adds new interface texts, they stay Ukrainian until this patch is updated. Update the patch from this repository when you update the plugin.
* Using a different language? Copy the file, rename it (for example `1-charcards-de.lua`) and replace the texts on the right-hand side. Keep the names on the left unchanged.

## License

MIT — see [LICENSE](LICENSE).

---

## Українською

Патч для KOReader, який перемикає плагін [CharCards](https://github.com/poostoon/charcards) на англійську: і інтерфейс, і запити до Gemini.

**Потрібно:** CharCards 1.2.0 або новіший (рекомендовано 1.3.0 і новіший).

**Встановлення:** завантаж [`1-charcards-en.lua`](https://github.com/poostoon/charcards-en-patch/blob/main/1-charcards-en.lua), скопіюй у `/koreader/patches/` і перезапусти KOReader.

**Повернутися до української:** видали цей файл із `/koreader/patches/` і перезапусти KOReader.
