# Easy Talk privacy policy

_Last updated: 2 October 2026_

Easy Talk is a voice dictation app for Android and Windows. This policy explains what the app does with your data. In short: Easy Talk has no servers, no accounts and no analytics, and the developer never receives your data.

## What Easy Talk handles

**Your voice recordings.** When you dictate, Easy Talk records audio from the microphone. Recording happens only while the bubble (Android) or the shortcut (Windows) is active, and Android shows a notification the whole time.
- **Online mode:** the recording is sent to the AI service you chose in settings, using the API key you entered yourself. The choices are Groq, OpenAI or your own server for speech, and also Anthropic, Google Gemini or OpenRouter for clean-up. That service turns it into text and, if you turned it on, cleans up or translates the text. It processes your data under its own privacy policy. Easy Talk sends it nowhere else.
- **Offline mode:** the recording is processed on your device only and never leaves it.
- Recordings are not kept on Android after they are transcribed. The Windows app saves recordings locally so you can replay them from History. You can delete them there or limit how long they are kept.

**The text you dictate.** The finished text is typed into the app you are using. Your recent dictations are saved on your device only (History) so you can copy them again. You can delete them at any time.

**Screen content (Android accessibility service).** Easy Talk uses Android's Accessibility Service API for three things:
1. to detect when you tap into a text field;
2. to show the dictation bubble;
3. to type your dictated text into that field.

It reads the focused field's text and selection only to insert your words, or to edit the selected text when you use Voice Edit. It does not collect, store or share anything else on your screen, and it is not used for advertising or analytics.

**Voice Lock voiceprint (optional).** If you set up Voice Lock, Easy Talk computes a numeric "voiceprint" from a short recording of your voice, which lets it ignore other people talking nearby.
- The voiceprint is stored only on your device and never uploaded.
- Clearing the app's data or uninstalling the app removes it.

**Your settings, dictionary and API keys.** These are stored only on your device. On Android, API keys are encrypted with the Android Keystore.

## What Easy Talk does not do

- It does not create accounts or collect your name, email or contacts.
- It does not use analytics, advertising or tracking SDKs.
- It does not sell or share data with anyone.

## Downloads

Offline speech models, AI models, translation packs and the Voice Lock model are downloaded directly from their public hosts: GitHub, Hugging Face and Google ML Kit. No personal data is sent with these downloads.

## Children

Easy Talk is not directed at children under 13.

## Contact

Questions or requests: open an issue at [github.com/Twilight-lol/easy-talk](https://github.com/Twilight-lol/easy-talk/issues).
