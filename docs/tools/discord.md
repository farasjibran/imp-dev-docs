---
sidebar_position: 2
---

# Discord

Daily Chat, Standup, And More.

## Link Download

Sesuaikan dengan perangkat masing-masing.

- [Desktop (Windows / Mac Os / Linux)](https://discord.com/download)
- [Playstore (Android User)](https://play.google.com/store/apps/details?id=com.discord&hl=en&gl=US)
- [Appstore (IOS User)](https://apps.apple.com/us/app/discord-chat-talk-hangout/id985746746)

## Discord Bot Command List

Dibawah adalah beberapa command list yang dapat di gunakan dengan _IMP Bot_

### Release, Build, And Deploy Website

Berikut adalah beberapa command list untuk release, build dan deploy suatu website dengan menggunakan imp bot **(jika project sudah terdapat pada settingan bot)**.

- Release Command

```
imp!release **(patch or minor release?)** **(name of project)**
```

- Build Command

```
imp!build **(name of project)** **(tag of release project)**
```

- Deploy Command

```
imp!deploy **(name of project)** **(tag of release project)** **(production or staging enviroment?)**
```

### Available Commands

Berikut adalah beberapa command list untuk mengatur sebuah developer agar terlihat sedang available atau tidak dengan mengirim pesan private ke **IMP Bot** atau langsung via channel **#bot-notif**

- Ketika ingin off atau sedang dalam keadaan unavailable

```
imp!me off --message={your message}
```

- Ketika ingin on atau available kembali

```
imp!me on
```

Ketika developer set available ke off, maka ketika developer terkait di-_mention_ di semua channel, maka **IMP Bot** akan otomatis membalas pesan tersebut seperti dibawah ini:

```
@Muhammad Farras Jibran is unavailable: sedang meeting AMAN
```
