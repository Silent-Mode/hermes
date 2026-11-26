# Hermes Messenger

A privacy-first messenger built on Nostr. NIP-17 gift-wrapped direct messages, group chats, broadcast channels, and 1:1 voice/video calls over WebRTC.

## Clients

- **Android** — native, Kotlin + Jetpack Compose. Releases on this repo carry the latest signed APK for sideload.
- **Windows** — Tauri + Rust. Ships from the Silent Mode release pipeline.
- **Web** — hermes.x (served over BNS), falls back to the Silent Mode mirror.

## Download

Latest Android APK: see [Releases](../../releases).

Canonical mirror: [dl.silentmode.st/hermes-v*.apk](https://dl.silentmode.st/) · BNS mirror on Sia.

## Hermes dev notes

Releases are signed with the `CN=Hermes, O=Silent Mode, OU=Deviant` key. The SHA-256 of each APK is in the GitHub release notes and in the canonical `releases-manifest.json` at `dl.silentmode.st`.
