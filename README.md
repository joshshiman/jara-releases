# jara

An opinionated home for your daily notes, on macOS.

Most notes apps hand you endless places to put things. jara gives you one page a day, on purpose, and does the organizing for you. It makes a few strong choices so you can stop managing notes and just write them.

## Download

**[Download for Mac](https://github.com/joshshiman/jara-releases/releases/latest/download/jara-mac-apple-silicon.dmg)**

Requires macOS on Apple Silicon (M1 or newer). Free while in beta.

The beta is not signed by Apple yet, so macOS asks before opening it the first time:

1. Open the downloaded `.dmg` and drag **jara** into Applications.
2. In Applications, right-click **jara** and choose **Open** (do not double-click the first time).
3. Click **Open** in the dialog. macOS remembers your choice, so it opens normally after that.

If macOS says the app is "damaged," that is just the download flag. Open Terminal, run `xattr -cr /Applications/jara.app`, then open it again.

## The opinions

**One page a day.** No "new note" button, no folders, no deciding where anything goes. Open jara and today's page is already waiting. Yesterday is a single click back.

**You write, the board organizes.** Tag any line with an `@label` or start a `- [ ]` checkbox. jara collects those lines onto one board, so your tasks and threads stop scattering across days. You never file a thing.

**Your whole year, at a glance.** A quiet calendar heatmap shows the days you wrote, so you can watch a streak build and jump to any day without digging through a list.

## What jara believes

1. Your notes are plain Markdown files, in a folder you choose. Open them anywhere, keep them for decades.
2. Local first. Nothing leaves your Mac unless you turn on sync, and then only to a repository you own.
3. No account, no subscription, no cloud lock-in. jara can disappear tomorrow and your notes stay.
4. Calm by default. One page, no feed, no notifications, nothing asking for your attention.

## Sync (optional)

Turn on GitHub sync to back up your notes and keep them in step across your Macs. Sync goes both ways, never deletes, and if the same note was edited in two places it keeps a safe copy in a conflicts folder so nothing is lost.

## Feedback

This is an early beta. If something breaks or feels off, open an issue on this repo and describe what happened.
