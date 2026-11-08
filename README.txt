# WordMaster phone version

This is a phone-friendly Progressive Web App (PWA).

## Publish it from your phone
A PWA must be served from an HTTPS website before Chrome can install it. The ZIP cannot install itself directly.

One phone-only route:
1. Download and extract this ZIP with your Android file manager.
2. Create a free GitHub account or sign in at github.com.
3. Create a public repository named `wordmaster`.
4. In the repository choose **Add file → Upload files** and upload `index.html`, `manifest.webmanifest`, and `sw.js` from the extracted folder.
5. Open **Settings → Pages**. Under Build and deployment choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
6. Wait for GitHub Pages to publish. Open the Pages URL it provides in Chrome.
7. In Chrome, tap ⋮ → **Add to Home screen** or **Install app**.

## Features
- English dictionary definitions and part-of-speech labels
- Nepali and Hindi translations
- Synonyms and antonyms where supplied by the dictionary
- Example sentences where supplied, with translations
- Pronunciation using Android text-to-speech
- Saved vocabulary stored on the phone

## Services
Definitions: dictionaryapi.dev
Translations: MyMemory Translation API
Internet required for fresh lookups and translations. Saved words are stored locally. Machine translations may miss nuance.
