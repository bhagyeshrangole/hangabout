# Hangabout

A lucky charm that hangs from the top of your Mac screen. It sways while you
work, ignores every click, and swings when you flick it.

It also keeps your reminders. Instead of a notification that disappears before
you read it, the thing you asked to be reminded about is written on a card the
charm is holding — still there an hour later, still there after you switch
Spaces.

## Before you download

Hangabout needs an **Apple Silicon Mac** (M1, M2, M3 or M4) running
**macOS 14 Sonoma or later**. It will not run on an Intel Mac.

Not sure which you have?  → Apple menu → **About This Mac**. If "Chip" says
Apple M-something, you are good. If it says Intel, this one is not for you.

## Download

### [⬇ Download Hangabout](https://github.com/bhagyeshrangole/hangabout/releases/latest/download/Hangabout.zip)

That link always gives you the newest version. Then:

1. Double-click the downloaded zip. `Hangabout.app` appears next to it.
2. Drag `Hangabout.app` into your **Applications** folder.

## First launch — please read this part

The first time you open Hangabout, macOS will refuse and say:

> **"Apple could not verify Hangabout is free of malware."**

This is expected and it is not a warning about the app. macOS says this about
every app that has not been through Apple's $99/year notarization process.
Hangabout is a hobby project, so it has not.

To open it anyway:

1. Double-click `Hangabout.app`. The warning appears — click **Done**.
2. Open **System Settings** → **Privacy & Security**.
3. Scroll to the bottom. There is a line saying *"Hangabout was blocked to
   protect your Mac."* Click **Open Anyway** next to it.
4. Enter your password or use Touch ID.
5. One more confirmation dialog — click **Open Anyway**.

You only do this once. From then on it opens like any other app.

> Comfortable with Terminal? This does the same thing in one line:
> ```
> xattr -d com.apple.quarantine /Applications/Hangabout.app
> ```

## What you will see

A charm appears hanging from the **top-right of your screen**, and a small
hanger icon appears in your **menu bar**. That menu is where everything lives —
reminders, which companion is hanging there, settings, and Quit.

If you set a reminder tied to a meeting, macOS will ask for **Calendar access**.
That is so the charm can warn you before a meeting starts. Say no and
everything else still works.

## Using it

- **Flick the charm** with your cursor to make it swing.
- **Hold ⌥ (Option) and drag** to slide it anywhere along the top of the screen.
- It tucks itself away while you type and stays still while you work. That is
  deliberate — something that sways all day teaches you to ignore it.
- To quit: hanger icon in the menu bar → **Quit**.

## Troubleshooting

**Nothing appeared after I opened it.** Hangabout has no Dock icon by design.
Look for the hanger in your menu bar, top-right. If it is there, the app is
running — the charm may just be tucked away. Click the hanger to bring it back.

**"The application cannot be opened" / nothing happens at all.** Almost always
an Intel Mac. Check Apple menu → About This Mac → Chip.

**I want it gone.** Quit from the menu bar, then drag `Hangabout.app` from
Applications to the Trash. It leaves nothing else behind.

## Source

The source is in a private repository. This repo exists to host the downloads.
