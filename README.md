# Gym Log

An offline Android gym tracker. That's it.

Part of Trip Point Software · by Trip Point Hardware

 · Android 8.0 or newer · Free · No internet access

## Why

Every gym app made me choose: a timer that dies when the screen locks, a ad-infested experience, features blocked behind a paywall, unnecessary bloat, or a spreadsheet that can't tell me what to lift today. This one is pretty simple: it logs a set, starts a rest timer that actually rings, and prescribes the next weight so I never guess.

## Features

### Workout logging
- Log a set in one tap: one screen, big inputs, no dialogs while you're training.
- Every exercise shows **what to lift today and why** in one short line — add weight, hold, or push for an extra rep, decided from your last session.
- **Warm-up generator** for compound lifts: tick-off rows computed from your working weight (barbell, machine, dumbbell and cable rules).
- **e1RM** (estimated one-rep max) and personal records shown as you log.
- **kg and lb in the same session**: kg machines and lb dumbbells, each exercise in its own unit.

### Rest timer
- Starts the moment you log a set; duration adjusts to how hard the set was (your reps in reserve).
- Keeps running and **rings with the screen off or the app closed**, over the lock screen, at full volume even in silent mode.
- **+30 s / −15 s** and **Skip** right on the notification; still runs after a phone restart.
- Superset-aware, with a smart transition after your last set of an exercise.

### Progression & insights
- Automatic **progressive overload**: it spots when you hit the top of the range, missed reps, or went to failure — and prescribes the right change.
- **Stall detection** with deload suggestions, alternative exercises, and a full deload week when everything is dropping at once.
- **Muscle volume matrix**: hard sets per muscle per week, plus push:pull and quads:hamstrings balance — so you see what you're neglecting, not just what's heavy.
- **Progress** screen: strength over time as a list, chart or table, with personal records and trends.

### Routines
- Ships with **The Original** (the owner's 4-day upper/lower split), plus **Full Body (3 days)** and **Upper / Lower (4 days)** presets.
- **Custom routines**: build your own from a library of ~70 machine, cable, dumbbell and barbell exercises.
- Switching routines never deletes your history.

### Bodyweight & backup
- Daily bodyweight log with weekly averages, change vs last week, and a trend chart.
- **Export / Import** your entire history as one JSON file (import merges, so importing twice adds nothing).

### Also
- Home screen widget: today's session, sets done, and the running rest countdown.
- Rest countdown shown live in the status bar and Samsung's Now Bar.
- Warm monochrome theme with a magenta accent, light and dark mode.

## Install

1. Download on your phone and tap it.
2. Allow **Install unknown apps** for your browser or file manager when asked. If Play Protect warns about an unknown developer, choose **Install anyway**.
3. Open Gym Log and allow notifications.
4. On first launch, pick kg or lb, choose a routine (or build one), or **Restore a backup**.

## Your data

- Everything stays on your phone. The app has no internet permission, no account, no ads and no analytics.
- **Export / Import** in Settings: one JSON file. Import merges, so importing the same file twice adds nothing.
- Uninstalling deletes the app's data. Export to Google Drive now and then.

## Permissions

| Permission | Why |
|---|---|
| Notifications | The rest-timer countdown and the "Rest over" ring |
| Alarms & reminders (exact alarms) | Ring at the exact moment your rest ends, even in battery saving |
| Full-screen notifications | Show "Rest over" over the lock screen |
| Live notifications | Countdown in the status bar and Now Bar (Android 16+) |
| Run at startup | Reschedule a rest timer after a restart |
| Foreground service, wake lock, vibration | Keep the timer counting and ring until you answer |
| Ignore battery optimization | So the phone doesn't stop the timer in the background |

## Requirements

- Android 8.0 or newer. Tested on a Samsung Galaxy A55 (One UI 8, Android 16).

## Version history

| Version | Changes |
|---|---|
| 1.11.1 | First public release |


## License

Provided as is, without warranty. 
Source code is private; this repository hosts the releases.
