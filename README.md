# jara

A calm home for your daily notes, on macOS.

jara gives you one page a day. You write in plain Markdown, and everything is saved as ordinary `.md` files in a folder you own. No lock-in, no cloud account required, and your notes never leave your Mac unless you choose to turn on sync.

## Download

**[Download for Mac](https://github.com/joshshiman/jara-releases/releases/latest/download/jara-mac-apple-silicon.dmg)**

Requires macOS on Apple Silicon (M1 or newer). Free while in beta.

The beta is not signed by Apple yet, so macOS asks before opening it the first time:

1. Open the downloaded `.dmg` and drag **jara** into Applications.
2. In Applications, right-click **jara** and choose **Open** (do not double-click the first time).
3. Click **Open** in the dialog. macOS remembers your choice, so it opens normally after that.

If macOS says the app is "damaged," that is just the download flag. Open Terminal, run `xattr -cr /Applications/jara.app`, then open it again.

## What it does

One note per day. Open jara and today's page is ready. Older days are a click away on the calendar.

Plain Markdown, plainly stored. Every note is a `.md` file at `notes/YYYY-MM-DD.md` inside your vault folder. Open them in any editor, back them up any way you like, keep them forever.

A board that pulls itself together. Add an `@tag` to any line, or write a `- [ ]` checkbox, and jara collects those lines onto a single board so your tasks and threads are not scattered across days.

A calendar heatmap. See your writing streak at a glance and jump to any day.

Optional GitHub sync. Turn it on to back up your notes and keep them in step across your Macs. Sync goes both ways, never deletes, and keeps a safe copy if the same note was edited in two places.

## Screenshots

Screenshots coming soon.

## Privacy

jara is local-first. Your notes live in a folder on your Mac. Nothing is uploaded anywhere unless you set up GitHub sync yourself, and even then it goes only to the private repository you choose.

## Feedback

This is an early beta. If something breaks or feels off, open an issue on this repo and describe what happened.
