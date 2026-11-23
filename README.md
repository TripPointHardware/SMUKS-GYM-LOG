# Gym Log

An offline Android gym tracker. That's it.

Part of Trip Point Software · by Trip Point Hardware

Android 8.0 or newer · Free · No internet access

## Why

EVERY SINGLE GYM APP ON THE PLAY STORE SEEMS TO BE BOUND BY A CONTRACT WITH SATAN TO SUCK ASS. Either they're full of ads, hide essential features behind a paywall, are bloated with meaningless options, or simply have a disgusting user interface.

This one is just a glorified spreadsheet because I'm lazy.

## Features

### Workout logging
- Log a set in one tap: one screen, big inputs, and no dialogs while you're training.
- Every exercise shows **what to lift today and why** in one short line — add weight, hold, or push for an extra rep, based on your last session.
- **Warm-up generator** for compound lifts: check off warm-up sets calculated from your working weight, with specific rules for barbells, machines, dumbbells, and cables.
- **e1RM** (estimated one-rep max) and personal records displayed as you log your sets.
- **kg and lb in the same session**: use kg for machines and lb for dumbbells, with each exercise retaining its own unit.

### Rest timer
- Starts the moment you log a set; its duration adjusts to how hard the set was (based on your reps in reserve).
- Keeps running and **rings with the screen off or the app closed**, even over the lock screen and at full volume in silent mode.
- **+30 s / −15 s** and **Skip** controls right in the notification; the timer also survives a phone restart.
- Superset-aware, with a smart transition after your last set of an exercise.

### Progression & insights
- Automatic **progressive overload**: detects when you hit the top of the rep range, miss reps, or reach failure, then prescribes the appropriate adjustment.
- **Stall detection** with deload suggestions, alternative exercises, and a full deload week when performance drops across the board.
- **Muscle volume matrix**: hard sets per muscle group per week, plus push:pull and quads:hamstrings balance — so you can see what you're neglecting, not just what's heavy.
- **Progress** screen: track strength over time as a list, chart, or table, with personal records and trends.

### Routines
- Comes with **The Original** (the owner's 4-day upper/lower split), plus **Full Body (3 days)** and **Upper / Lower (4 days)** presets.
- **Custom routines**: build your own using a library of ~70 machine, cable, dumbbell, and barbell exercises.
- Switching routines never deletes your workout history.

### Bodyweight & backup
- Daily bodyweight logging with weekly averages, changes versus the previous week, and a trend chart.
- **Export / Import** your entire history as a single JSON file. Imports are merged, so importing the same file twice adds nothing.

### Also
- Home screen widget showing today's session, completed sets, and the running rest countdown.
- Rest countdown displayed live in the status bar and Samsung's Now Bar.
- Warm monochrome theme with a magenta accent, available in light and dark modes.

## Install

1. Download the APK to your phone and tap it.
2. Allow **Install unknown apps** for your browser or file manager when prompted. If Play Protect warns you about an unknown developer, choose **Install anyway**.
3. Open Gym Log and allow notifications.
4. On first launch, choose kg or lb, select a routine (or build your own), or **restore a backup**.

## Your data

- Everything stays on your phone. The app has no internet permission, no account requirement, no ads, and no analytics.
- **Export / Import** in Settings: Export your entire history to a single JSON file. Imports are merged, so importing the same file twice adds nothing.
- Uninstalling deletes the app's data. Export a backup to Google Drive or another location from time to time.

## Permissions

| Permission | Why |
|---|---|
| Notifications | Rest-timer countdown and the "Rest over" notification |
| Alarms & reminders (exact alarms) | Ring at the exact moment your rest ends, even in battery-saving mode |
| Full-screen notifications | Display "Rest over" over the lock screen |
| Live notifications | Display the countdown in the status bar and Samsung's Now Bar (Android 16+) |
| Run at startup | Reschedule a running rest timer after a phone restart |
| Foreground service, wake lock, vibration | Keep the timer running and ring when your rest period ends |
| Ignore battery optimization | Prevent the phone from stopping the timer in the background |

## Requirements

- Android 8.0 or newer. Tested on a Samsung Galaxy A55 (One UI 8, Android 16).

## Version history

| Version | Changes |
|---|---|
| 1.11.1 | First public release |

## Source Code & Disclaimer

Provided as is, without warranty.

The source code is private; this repository hosts the releases.

Well, I don't mind sharing the source code, but if you're anything like me, you just download scripts and programs you find on GitHub. I couldn't give a rat's ass how they work.
