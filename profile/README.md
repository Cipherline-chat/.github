## Cipherline

**End-to-end encrypted messaging and calling: the privacy-first alternative to Discord, Slack and Teams.**

Your own servers, roles, channels, voice and video calls, and screen share. Messages, files and calls are encrypted
on your device before they leave it, so our server relays them without being able to read them. It still has to see
some things to deliver them (who you're connected with, when, and how big a file is); the full list is at
[cipherline.chat/security](https://cipherline.chat/security).

### Repositories

| Repo | What's there |
|---|---|
| [cipherline-desktop](https://github.com/Cipherline-chat/cipherline-desktop) | Full source of the desktop client (Windows, macOS, Linux), Apache-2.0. From 1.0.17 on, stable builds are made from it by its release workflow, with a provenance attestation for every installer. |
| [cipherline-mobile](https://github.com/Cipherline-chat/cipherline-mobile) | The mobile client's repo. The app is in closed beta and its source isn't published there yet. |

### Why the client is open and the server isn't

The client is what touches your messages, keys and calls, so it's what we publish: you can check the encryption
yourself. The server is a blind relay that never holds the keys to your content.

### Links

[Website](https://cipherline.chat) · [Security](https://cipherline.chat/security) ·
[Open source](https://cipherline.chat/opensource) ·
Report a vulnerability: [security@cipherline.chat](mailto:security@cipherline.chat)
