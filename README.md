# Bloxport

The Roblox account manager for Windows.

- **Accounts:** add accounts by signing in, pasting cookies, or a whole `username:password` list (through your own Chrome with the Bloxport helper). Folders, colors, nicknames, tags and notes.
- **Launching:** many accounts at once with multi-instance, launch groups and schedules, private servers, a game picker, auto-rejoin, and window tiling.
- **Anti-AFK** that nudges every Roblox window so nobody gets kicked for idling.
- **Authenticator:** 2-step codes for your accounts, built in.
- **Limiteds:** RAP, Rolimons value and value over time, with a daily scan.
- **Communities and Games:** sales, revenue, launches, members, players and visits for what you own.
- **Overview, streamer mode, a Discord bot and alerts,** and a guided tour of every page.

## Download

Get **Bloxport Setup x.y.z.exe** from the [latest release](https://github.com/Dragonmaster0973/bloxport/releases/latest) and run it. Windows may say it "protected your PC" because the installer isn't signed: click **More info**, then **Run anyway**.

## Updates

Bloxport checks this page for new versions. When one is out, **Update to x.y.z** shows in the sidebar; press it and the app installs the new version and restarts with your accounts and settings in place. Nothing is downloaded or installed until you press it.

## Your data stays on your PC

There is no Bloxport server and no account to make. Everything lives in `Documents\Bloxport` on your PC.

- **Encrypted on your PC:** account logins (cookies), saved passwords, 2-step keys and backup codes, your Discord bot token and webhook links. They're encrypted with Windows' own encryption, tied to your Windows account, so the files are useless if copied to another PC or user.
- **PIN lock** (optional): only a salted hash of the PIN is kept.
- **Backups** are one file locked with a passphrase you choose (AES-256).
- **Who the app talks to:** Roblox, as your own accounts, to do what you ask; Discord, only if you set up alerts or the bot; Rolimons, for public item values; and GitHub, to check this page for updates. No analytics, no tracking, nothing sent anywhere else.
- **The Chrome helper** talks only to Bloxport on your own PC (127.0.0.1), with a private key, and only during a bulk add.

Settings, sales history and playtime are saved as ordinary files in that folder.

## About this repository

This repository holds the installers and release notes. The source code isn't published.
