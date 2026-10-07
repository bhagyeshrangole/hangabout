# Hangabout

A companion that hangs from the top of your Mac screen. It sways while you
work, ignores every click, and swings when you flick it.

It also keeps your reminders. Instead of a notification that disappears before
you read it, the thing you asked to be reminded about is written on a card the
companion is holding — still there an hour later, still there after you switch
Spaces. You answer it with **Done** or **Later**, and it pulls a face either
way.

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

A spider appears hanging from the **top-right of your screen**, and the same
spider appears in your **menu bar**. That menu is where everything lives —
reminders, alarms, which companion is hanging there, settings, and Quit.

There are seven companions to choose from: the spider, Spider-Man, Iron Man,
Tony Stark, Captain America, a cat and a dog. Some hang from a thread; others
stand on the floor and walk over when they have something to say.

If you set a reminder tied to a meeting, macOS will ask for **Calendar access**.
That is so the charm can warn you before a meeting starts. Say no and
everything else still works.

## Using it

- **Flick the companion** with your cursor to make it swing.
- **Hold ⌥ (Option) and drag** to slide it anywhere along the top of the screen.
- **Answer a reminder** with Done or Later. Done earns a happy face, Later a
  sad one.
- It stays still while you work rather than swaying all day, because something
  always moving teaches you to ignore it.
- **Hide it** from the menu, or with ⌃⌥⌘H. Hiding stops it being looked at —
  your reminders and alarms still arrive, and it ducks back into hiding once
  you have answered.
- To quit: spider in the menu bar → **Quit**.

## Troubleshooting

**Nothing appeared after I opened it.** Hangabout has no Dock icon by design.
Look for the spider in your menu bar, top-right. If it is there, the app is
running — the companion may just be tucked away. Click the menu bar spider to
bring it back.

**It keeps vanishing while I type.** That is *Hide while typing*, and it is off
by default — switch it off again in the menu bar. It waits two and a half
minutes after your last keystroke before coming back, which is deliberate: at a
few seconds it flickered in and out every time you paused to think.

**"The application cannot be opened" / nothing happens at all.** Almost always
an Intel Mac. Check Apple menu → About This Mac → Chip.

**I want it gone.** Quit from the menu bar, then drag `Hangabout.app` from
Applications to the Trash. It leaves nothing else behind.

## Updates

Hangabout checks for a new version when it launches, and once an hour while it
is running. When there is one, the companion says so and a **Get Hangabout…**
item appears in the menu above Quit. Clicking it brings you back here.

It never installs anything by itself — you download and drag, same as the first
time. Your settings carry across.

## Source

The source is in a private repository. This repo exists to host the downloads.
