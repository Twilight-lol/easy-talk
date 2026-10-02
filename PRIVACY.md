# Easy Talk privacy policy

_Last updated: 2 October 2026_

Easy Talk is a voice dictation app for Android and Windows. This policy explains what the app does with your data. In short: Easy Talk has no servers of its own and no accounts, and the developer never receives your voice or your text. The Android app uses Google Play and RevenueCat for Pro purchases, and Google AdMob for ads that you choose to watch.

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

It reads the focused field's text and selection only to insert your words, or to edit the selected text when you use Voice Edit. For Voice Edit, the selected text is sent with your spoken instruction to the AI service you chose, with your key, so it can be rewritten; it is not kept. Easy Talk does not collect, store or share anything else on your screen, and the accessibility service is never used for advertising or analytics.

**Voice Lock voiceprint (optional).** If you set up Voice Lock, Easy Talk computes a numeric "voiceprint" from a short recording of your voice, which lets it ignore other people talking nearby.
- The voiceprint is stored only on your device and never uploaded.
- Clearing the app's data or uninstalling the app removes it.

**Your settings, dictionary and API keys.** These are stored only on your device. On Android, API keys are encrypted with the Android Keystore.

## Easy Talk Pro purchases (Android)

Pro is bought through Google Play. Google processes the payment under the [Google Payments privacy notice](https://payments.google.com/payments/apis-secure/get_legal_document?ldo=0&ldt=privacynotice); Easy Talk never sees your card or payment details.

To know whether you have Pro, the app uses [RevenueCat](https://www.revenuecat.com/privacy). RevenueCat receives:
- a random ID created for this install (shown in the app as "Easy Talk ID"), not linked to your name or email;
- your Google Play purchase records for Easy Talk;
- basic technical details such as the app version, Android version, country and IP address.

This is used only to unlock Pro, restore purchases and help with purchase problems. You can ask for this data to be deleted by sending your Easy Talk ID to the contact below.

## Rewarded ads (Android)

Easy Talk shows ads only when you tap "Watch ad" to unlock Voice Edit or Translate for 24 hours. There are no banner ads and no ads over other apps, and nothing ad-related runs until you choose to watch one.

These ads come from [Google AdMob](https://policies.google.com/technologies/ads). When you watch one, Google may collect your device's advertising ID, IP address (and the approximate location it gives), device information and how you interact with the ad, to show the ad, measure it and prevent fraud. In the European Economic Area, the UK and Switzerland, Easy Talk asks for your consent first; you can change your choice in Settings → Ad privacy choices. You can reset or delete your advertising ID in your phone's Google settings. Your voice, your text and anything on your screen are never shared with advertisers.

## What Easy Talk does not do

- It does not create accounts or collect your name, email or contacts.
- It does not use analytics or tracking SDKs, and it does not show ads unless you ask to watch one.
- It does not sell your data.

## Downloads

Offline speech models, AI models, translation packs and the Voice Lock model are downloaded directly from their public hosts: GitHub, Hugging Face and Google ML Kit. No personal data is sent with these downloads.

## Children

Easy Talk is not directed at children under 13.

## Contact

Questions or requests: open an issue at [github.com/Twilight-lol/easy-talk](https://github.com/Twilight-lol/easy-talk/issues).
