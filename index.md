# Peeko privacy policy

Effective 7 November 2026

Peeko is an Android app made by Lakshay Gupta, an independent developer in India. It searches the photos, files, apps and contacts on your phone. This page covers what Peeko reads and the few things it sends over the internet.

Peeko has no accounts or ads, and I don't collect analytics or crash reports. I don't run a server for it, so I never receive your photos, files, searches or anything else you do in the app. The one exception built into the app is the usage stats that Google's ML Kit sends to Google, described below.

## What stays on your phone

To search, Peeko builds an index on your phone. Depending on what you allow, it reads:

- Your photos, so you can find them by what's in them and when they were taken. If a photo has a location, Peeko turns it into a city name using a list of places built into the app. It doesn't look the location up online, and it doesn't ask for your phone's own location.
- The faces in your photos, so it can group photos of the same person and you can search them by a name you give. Peeko does this on your phone with a face model built into the app. The faces and names never leave your phone.
- Your files, such as PDFs and documents, if you give Peeko access to all files, so you can search them by what they say.
- Your contacts, if you allow it, so names show up in results.
- What you type in other apps, only if you turn on Snippets in Any App (Pro). Peeko uses Android's Accessibility service to spot a ; followed by one of your snippet names, like ;upi, and replace it with that snippet. It reads only the text box you're typing in, skips password fields, and doesn't save, share or send what you type. You can turn it off in Peeko's Settings or in Android's Accessibility settings.
- Your clipboard, if you turn on clipboard history. Free keeps clips for 7 days and Pro keeps them for 30.
- What you save in Peeko: snippets, shortcuts, things you share to Peeko, your recent searches and your saved Claude answers.

This all stays in Peeko's private storage on your phone, where other apps can't read it. Peeko turns off Android's cloud backup, so none of it is copied to your Google account. Uninstalling Peeko deletes it, and you can clear your search history any time in Settings › Privacy.

## What leaves your phone

Four things use the internet. The first happens on its own while Peeko indexes your photos. The others happen only when you use that feature.

### Google ML Kit usage stats

Peeko uses Google's ML Kit, built into the app, to read the text in your photos and to find faces. ML Kit runs on your phone, but it sends Google usage stats for diagnostics:
- your phone's make, model and Android version
- Peeko's name and version
- an ID for this install that isn't meant to identify you or your phone
- how long each step took
- image sizes and formats
- error codes

It never sends your photos, the text it reads or the faces it finds. Google encrypts this data in transit and doesn't share it with third parties. [Google's ML Kit data disclosure](https://developers.google.com/ml-kit/android-data-disclosure) has the full list.

### Wikipedia previews

When you type `wiki` followed by a search, Peeko sends that text to Wikipedia's public API to show article previews. The Wikimedia Foundation's privacy policy covers how Wikipedia handles it.

### Claude answers (Pro, optional)

If you add your own Anthropic API key in Settings › Ask AI, the questions you ask Claude go from your phone to Anthropic's API under your key, and Claude may search the web to answer them. Anthropic's privacy policy and terms apply to that data, and Anthropic bills your account for it. Peeko keeps your key encrypted with the Android Keystore and saves the answers on your phone. You can remove the key in Settings at any time.

### Exchange rates

For currency conversions, Peeko downloads the daily rates published by the European Central Bank. The request contains nothing about you.

As with any internet request, these services can see your phone's IP address.

## Other apps and websites

Some actions open another app or website with what you typed. A search shortcut can open YouTube, Maps or Google, and Ask AI can open Google AI Mode, ChatGPT or Claude in a browser tab. Peeko passes the text along, and that app or site's own privacy policy applies from there.

## Purchases

Peeko Pro is a one-time purchase through Google Play. Google handles the payment, so Peeko never sees your card or payment details. The app only asks Google Play whether your account owns Pro. Google's privacy policy covers the purchase itself.

## Children

Peeko isn't directed at children under 13.

## Changes

If this policy changes, the new version will be posted on this page with a new effective date.

## Contact

Questions about privacy: [lakshay.apps@outlook.com](mailto:lakshay.apps@outlook.com)
