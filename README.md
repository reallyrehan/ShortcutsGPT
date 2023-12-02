# ShortcutsGPT
Using ChatGPT to supercharge your mobile workflows using iOS Shortcuts. This repo contains a list of automations that combine the power of some OpenAI's APIs like ChatGPT and Whisper, allowing you to do perform tasks like,
- 📱➡🤖 Get text on Screen and summarize it using ChatGPT 
- 🌐➡🤖 Share a URL to directly share text and ask questions from ChatGPT
- 🎙️➡🤖 Share an Audio and get a summary/translation from ChatGPT

## List of Shortcuts

1. ### Ask ChatGPT from Screenshot
**What does it do?**

This shortcut allows you extract text from any screen, translate it, summarize it and ask questions from it using ChatGPT.

**Pre-requisites**
- You need to have ChatGPT installed on your device

Here's how it works,
- Take a screenshot of the text you want to summarize/translate/ask questions from.
- Extracts the text from the screenshot using native iOS shortcut action

Asks what you need to do,
- Translate : Translate the text to the specified language(English by default) and show it in *Quick Look*
- Summarize : Summarize the text using ChatGPT and show it in *Quick Look*
- Ask : Provides the full text to ChatGPT and let you ask questions from it in a continuous chat session. The shortcut will keep asking you for questions until you press *Cancel*.

It is especially useful for apps that don't let you copy/paste the text. You can also configure this shortcut to run when you tap the back of the phone using [BackTap on iPhone](https://support.apple.com/en-us/HT211781).

**How to use?**
- **iCloud Link** : [Ask ChatGPT from Screenshot](https://www.icloud.com/shortcuts/a0da9bb2b9d34759ac4f518f73409f73)
- **Shortcut File** : [Ask ChatGPT from Screenshot](./shortcuts/Ask%20ChatGPT%20from%20Screenshot.shortcut)

2. ### Ask ChatGPT (from ShareSheet by sharing URL)
**What does it do?**

This shortcut allows you to share any URL, from browser or any other app, extracts the text, translate it, summarize it and/or ask questions from it using ChatGPT.

**Pre-requisites**
- You need to have ChatGPT installed on your device

This shortcut is only visible when you press on the "Share" button. Here's how it works,
- Takes the URL as input when you share it.
- Extracts the text from URL using native iOS shortcut action

Asks what you need to do,
- Translate : Translate the text to the specified language(English by default) and show it in *Quick Look*
- Summarize : Summarize the text using ChatGPT and show it in *Quick Look*
- Ask : Provides the full text to ChatGPT and let you ask questions from it in a continuous chat session. The shortcut will keep asking you for questions until you press *Cancel*.

**How to use?**
- **iCloud Link** : [Ask ChatGPT](https://www.icloud.com/shortcuts/1592879ceaef4be1ac03629886985abc)
- **Shortcut File** : [Ask ChatGPT from Screenshot](./shortcuts/Ask%20ChatGPT.shortcut)

3. ### Whisper transcribe
**What does it do?**
This shrotcut allows you to share any audio file, from browser or any other app, extracts the text, translate and summarize it .

**Pre-requisites**
- You need to have an OpenAI API key. You can get one from [here](https://beta.openai.com/).
- You need to have ChatGPT installed on your device

This shortcut is only visible when you press on the "Share" button. Here's how it works,
- Takes the audio file as input when you share it.
- Extracts the text from audio using [Whisper](https://platform.openai.com/docs/guides/speech-to-text) API
- Translates it and asks ChatGPT to summarize it and show it in *Quick Look*

**How to use?**
- **iCloud Link** : [Whisper Transcribe](https://www.icloud.com/shortcuts/9c6cf4976bc9475194b896dbcae540a3)
- **Shortcut File** : [Whisper Transcribe](./shortcuts/Whisper%20Transcribe.shortcut)