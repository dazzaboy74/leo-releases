# Leo releases

Downloads for **Leo**, a personal Android app for reading books in Spanish, French, Italian and German:
tap any word for its meaning, hold for the whole sentence, and review saved words with spaced repetition.

This repository holds only release files; the app's source lives elsewhere.

- **App:** the latest release has the APK. Leo checks here for updates (Profile → App update).
- **Dictionaries:** the `dictionaries` release has one offline dictionary per language (`<code>_en.db.gz`)
  and `manifest.json` with each file's version, size and SHA-256. Leo downloads the ones you choose.

## Credits and licences

- Dictionary content comes from [Wiktionary](https://en.wiktionary.org/), extracted by
  [kaikki.org](https://kaikki.org/) (Tatu Ylonen, *Wiktextract*). It is licensed under
  [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) and the GFDL; the dictionary files
  are adapted versions and are shared under the same licence.
- Word frequencies: [FrequencyWords](https://github.com/hermitdave/FrequencyWords) by Hermit Dave,
  CC BY-SA 4.0.
- The app bundles Inter and Literata (SIL Open Font License) and Lucide icons (ISC).
