---
title: Friends Fighters Privacy Policy
---

# Friends Fighters Privacy Policy

Last updated: 2026-10-16

Other languages: [Português (Brasil)](https://fberbert.github.io/friends-fighters-legal/privacy-pt-BR.html) | [Español](https://fberbert.github.io/friends-fighters-legal/privacy-es.html)

Friends Fighters ("the game") is an Android game by Fábio Berbert de Paula ("we"). This policy explains what the game does with the photos and other information you put in it, and what our server stores when you sign in with a Google account. In short: your photos, head cutouts, masks and voice recordings stay on your device and are never uploaded to our server; they leave your device only when you choose to share a fighter file or a fight video. Our server stores only what it needs to count your free creations and to unlock the full game: your Google account identifier, your creation records and your purchase records. The game has no ads and no analytics.

## 1. What the game sends over the internet

- The game connects only to its own server, `api.friendsfighters.automatizando.dev`, and to Google for sign-in and Google Play purchases. Every connection is encrypted (HTTPS).
- Built-in fighters, every game mode and fights work offline and without an account.
- The game has no advertising, no analytics, no crash reporting service and no cloud copy of your fighters.
- The game never sends photos, head cutouts, masks, voice recordings or fighter names to our server or to Google. They leave your device only when you share them (section 7).
- Opening this policy from Settings starts your web browser.

## 2. Photos and faces

- To create a fighter, you choose a photo with the Android photo picker or take one with your camera app. The game requests no storage or camera permission: Android gives the game only the photo you picked.
- The game copies that photo, reduced to at most 2048 pixels, into its private storage as a PNG image without metadata such as location (GPS) data.
- Background removal, which finds the head in the photo, runs entirely on your device with a Google MediaPipe model included in the game. The game does not identify people and does not create face recognition data.
- For each fighter the game keeps, on your device, the copy of the photo, the head cutout, its automatic and retouched masks, your crop and edit settings, a small preview image and any voice recordings (section 3).
- When you confirm a fighter, the game sends our server a SHA-256 code of the confirmed face image (section 5). The code is computed on your device; the image cannot be rebuilt from it, and codes are never compared between accounts.
- Only use photos of people who agreed to become fighters, and never use the game to bully anyone. The game asks you to confirm this before your first photo import.

## 3. Voice recordings

- If you record a voice for a fighter, the game asks for the microphone permission at that moment. You can refuse; everything else keeps working.
- A fighter can have up to six recordings (for example for a knockout or a victory). Each lasts at most 2 seconds and is stored in the fighter's private folder on your device.
- Recordings are never sent to our server. They leave your device only inside a fighter file or a fight video that you choose to share (section 7).
- You can revoke the microphone permission at any time in the Android settings.

## 4. Information stored on your device

- Fighter names and appearance choices; your settings (language, sound and music volumes, difficulty, vibration, controls and reduced motion); your answer to the photo consent question; your last match setup; match statistics, including head-to-head records between fighters; Climb progress; and achievements.
- When you sign in: your game account ID, a session key and the signed record of your free creations and unlock, plus your creation records with their face codes and the fighters waiting for confirmation.
- To help you identify the connected Google account in Settings, the game also keeps the name and e-mail provided by Google and an optional small profile picture, downloaded from Google over HTTPS. These display details stay on your device in a separate local cache and are not added to requests to our server. Signing out, switching accounts or deleting the account in the app erases this cache. Without a picture the game shows initials; an existing session can refresh its account details without spending a free creation. The full game account ID remains available in Settings under Support information.
- All of it stays in the game's private storage, which other apps cannot read. It is excluded from Android cloud backups and from device-to-device transfers.

## 5. Your game account

- You need an account only to create your own fighters and to buy or restore the full game. The game asks you to continue with Google the first time you confirm a fighter, and you can also sign in from Settings. You can refuse and keep playing with the built-in fighters.
- Google's sign-in confirmation, which the game passes to our server, also contains your name, e-mail address and profile picture. The server only checks the confirmation and stores the Google account identifier; it never stores your name, e-mail address or picture.
- For your account our server stores: the Google account identifier; a random account ID, shown in Settings for support; the date the account was created; your sessions, as SHA-256 codes of the session keys; your creation records (date, kind of creation: new fighter, duplicate or face change, and the SHA-256 code of the confirmed face image); the numbers of free creations granted and used, including extra creations granted by support; your unlock status and the dates of its signed record; and your purchase records (section 6).
- Your IP address reaches the server only to limit the number of requests, in memory. The server does not store or log it.
- We use this data only to run the free creations, the face lock and the unlock, to restore your purchase, to prevent abuse of the free creations and to answer support requests. We do not sell it, do not use it for advertising and do not share it with anyone other than the service providers of section 8.

## 6. Purchases and Google Play

- The game is free to download. The full unlock is an optional one-time purchase on Google Play. Google processes the payment under the Google Privacy Policy (https://policies.google.com/privacy); we never receive your payment details.
- When you buy, the game gives Google Play your random game account ID, so that the purchase can be linked to your game account. It does not give Google Play your fighters or photos.
- Our server receives from Google Play the record of the unlock purchase (purchase token, product, order number, state such as purchased, pending, cancelled or refunded, purchase type and dates) and links it to your game account, so the unlock works on your devices and comes back with Restore purchases on the Unlock the full game screen.
- Android and Google Play may collect crash and diagnostic statistics according to your device settings and Google's policies. The game itself sends none.

## 7. Sharing is always your choice

- Share cards: the game creates a picture of a match result only when you tap Share.
- Fighter files: the game exports a fighter with all its data, including photos and voice recordings, only when you tap Export fighter. It imports only a file that you pick with Import fighter or open with the game.
- Fight videos: the game makes a video of a fight, with the fighters' faces and sounds, only when you tap Fight video and confirm.
- Stickers: the game offers a fighter's sticker pack to WhatsApp only when you tap WhatsApp stickers and then Add to WhatsApp; WhatsApp then reads the pack from the game.
- The app you choose receives the picture, file or video through the Android share menu and handles it under its own privacy policy. We do not receive a copy.

## 8. Service providers

- Our server runs on Amazon Web Services (EC2), in the Oregon region, United States. The data listed in sections 5 and 6 is therefore stored and processed outside Brazil, in the United States.
- Google provides sign-in, Google Play payments, purchase verification and purchase notifications. On your device, sign-in uses Google Play services (Android Credential Manager) and purchases use Google Play Billing; these components talk to Google directly under Google's policies.
- These providers process the data only to provide their service to us.

## 9. How long we keep data

- Your account, its creation records and its unlock status: until you delete the account.
- Sessions: 30 days after each sign-in.
- After you delete your account we keep, for 365 days and only to prevent abuse of the free creations, the number of free creations you used, with the random account ID and the dates the account was created and deleted, under a pseudonymous code computed from your Google account identifier with a secret key. If you sign in again with the same Google account within that time, the new account starts with that number and this record is removed.
- Purchase records: 365 days after the account is deleted, without a link to your game account, for refunds and fraud prevention.
- Records of support actions (for example an extra free creation) keep the random account ID, the action, who did it and the date for 365 days after the action; their notes are erased when the account is deleted.
- Database backups are deleted within 14 days.

## 10. Deleting your data

- Delete a fighter in the fighter gallery to remove all its files from the device.
- Uninstalling the game, or clearing its storage in the Android settings, deletes all game data on the device. Because backups are disabled, a reinstalled game starts empty.
- Delete your game account in the game (Settings, Account, Delete account) or on the page https://api.friendsfighters.automatizando.dev/delete-account, where you sign in with Google. That page loads Google's sign-in script, so Google receives your IP address and browser details under the Google Privacy Policy; our server does not log them. If you cannot sign in, write to us with the account ID shown in Settings. Deletion removes the Google account identifier, the sessions, the creation records with their face codes and the unlock record; section 9 lists what is kept. Your fighters stay on your device, and your purchase stays on Google Play: sign in again and use Restore purchases.

## 11. Children

The game is intended for players aged 13 and older. It is not directed to children under 13.

## 12. Your rights

Under Brazil's General Data Protection Law (LGPD) and similar laws, you may ask us to confirm whether we process your data, to access, correct or delete it, to receive it in a portable format, and for information about the providers that process it. Send your request with the account ID shown in Settings; we answer within 15 days. You can also delete your account yourself as described in section 10.

## 13. Changes to this policy

If the game changes how it handles data, we will update this policy, change the date at the top and describe the change in the release notes on Google Play.

## 14. Contact

Fábio Berbert de Paula
Email: contato@automatizando.dev
