# GRIND — Habit Tracker
> *Every other habit app lied to you. Told you you were doing great. You weren't. That's why the habits didn't stick. That's why you're here.*

GRIND is a free, local-first habit tracker for Android. No account. No subscription. No gentle nudges. No confetti. Your data stays on your device — and unlike your discipline, that part is actually reliable. Track habits. Build streaks. Face what you skipped. Nothing more. Nothing less.

**Daily habit tracking. Streak counters. Skip history. Brutal honesty. Zero cloud.**

Built because every other app in this category is in the business of making you feel okay about not showing up. GRIND is not in that business. It just records what happened. It doesn't care why you missed. It doesn't accept explanations. The streak number is either going up or it isn't.

Most people will download it, use it for a week, and either quietly build the best streak of their life — or quietly delete it because the honesty was too much.

Both are a choice.

---

═══════════════════════════════════════════════════════════

---

## What GRIND Actually Does

**Dashboard — the record, not the feeling**
Every habit. Today's status. Current streak. Longest streak ever. No motivational quotes. No color-coded moods. Just the number. The number doesn't lie, and it doesn't care what your week was like.

**Habit Tracking**
Add a habit with a name and a target frequency — daily, specific days of the week, or X times per week. Mark it done. Or don't. GRIND logs both. The check is there when you earn it. The gap is there when you don't. Every skip is recorded permanently. You can see it whenever you want. That's the point.

**Streak System**
Current streak. Longest streak. Total completions. Days since you broke the last one. No hiding from it. No "grace days" that let you pretend you didn't miss. If you missed, you missed. The streak resets. That's how streaks work in real life too.

**Skip History**
Every habit has a full log — completed days, skipped days, the exact pattern of your follow-through. Scroll back. Look at it. Most people won't like what they see the first time. That's useful information.

**Reminders**
Set a daily reminder time per habit if you need one. It fires once. It doesn't send three follow-ups. It doesn't ask if you forgot. You either did it or you didn't — checking the box is on you.

**Month View**
Calendar grid per habit. Green days you showed up. Empty days you didn't. No labels. No excuses column. Just the grid.

**Data & Export**
Full backup as a `.grind` file. Import to restore — no duplicates. Everything lives on your device. Nothing leaves it. Back it up. That part is your responsibility.

**Appearance**
Dark mode. Light mode. That's it. GRIND doesn't need to be pretty. It needs to be honest.

---

## Permissions — What They Are and Why

| Permission | Why |
|---|---|
| POST_NOTIFICATIONS | Daily habit reminders you set yourself |
| WAKE_LOCK | Wakes device to deliver scheduled notifications |
| INTERNET | Loads Google Fonts only — no data is sent anywhere |
| READ_MEDIA_IMAGES | Required by Capacitor on Android 13+ for file operations |
| READ / WRITE EXTERNAL_STORAGE | Export and import `.grind` backup files (Android 12 and below) |

No network calls to any server. No analytics. No crash reporting. No tracking. Install it offline. Use it offline. It doesn't need the internet to watch you skip leg day.

---

## Why Your Antivirus Might Flag This

GRIND is not on the Google Play Store. It's a direct APK install.

$25 to get listed. I'm an intern making ~$30 a month. The math doesn't work. So this is a sideload, and your phone will tell you that's suspicious.

It's not. Here's what actually happens when you install GRIND:
- No outbound connections to any server
- No data leaves your device
- The only network call is loading a Google Font from Google's CDN
- Install with WiFi off — works completely

If you want proof, install [NetGuard](https://netguard.me/) and watch GRIND's traffic. You'll see nothing.

The apps that pass Play Store review without a word are often the ones quietly building a profile of your habits and selling it. GRIND gets flagged because it has no company, no Play Console account, and no history. That's the cost of being independent and free.

---

## Honest Notes

Built because I was tired of habit apps that applaud the bare minimum. Engineered with hand-written code and AI-assisted development (Claude by Anthropic). Packaged into an APK using Android Studio and Capacitor. A personal project. Tested on MIUI / Android 13 — other devices should be fine but haven't all been tested individually.

Not a commercial product. No support team. No guarantees. No customer success manager to send you a check-in email when you haven't logged in for three days.

If something breaks — open an issue. If it's working — you know what to do. No excuses accepted.

---

## Stack

- Single `index.html` — all HTML, CSS, and JS in one file
- [Capacitor 6](https://capacitorjs.com/) — Android wrapper
- [Android Studio](https://developer.android.com/studio) — APK build
- No frameworks. No build step for the web layer.

**Build it yourself:**
```bash
npm install
npx cap sync android
```
Open `android/` in Android Studio and build the APK.
Gradle `8.14.5` · AGP `8.3.0` · Min SDK `22` · Target SDK `34`

---

═══════════════════════════════════════════════════════════

## 📸 Screenshots

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/b44f823d-ce42-48b5-ac16-c8a197ad011b" width="180"/></td>
    <td><img src="https://github.com/user-attachments/assets/4f047495-4a61-43d5-b7a7-4438d57c6b50" width="180"/></td>
    <td><img src="https://github.com/user-attachments/assets/5f50d055-ec08-4357-9f98-eb136d9b2fe6" width="180"/></td>
    <td><img src="https://github.com/user-attachments/assets/b0cc6185-006f-46ab-8774-1c67d2ec2b36" width="180"/></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/dc7f199e-d989-46fa-9ed0-63b5eee50022" width="180"/></td>
    <td><img src="https://github.com/user-attachments/assets/9815566c-0289-48d9-b968-1931cdc2ee10" width="180"/></td>
    <td><img src="https://github.com/user-attachments/assets/e7e898d8-daa3-46b5-9288-ea902a4ad109" width="180"/></td>
    <td><img src="https://github.com/user-attachments/assets/ce1c29e2-39a0-4317-a56d-e4bbc71a43b8" width="180"/></td>
  </tr>
</table>


---

## Get GRIND

You read the whole thing. That's already more discipline than most people show.

**→ [Download APK](https://github.com/evencholmes/02-GRIND/releases/tag/Apk1.1)**
Direct install. No Play Store. No account. No nonsense.
**[Direct Download apk](https://github.com/evencholmes/02-GRIND/releases/download/Apk1.1/02.GRIND-HabitOS.apk)**

---

**→ [Support on Patreon](https://www.patreon.com/jibunshidai81)**
GRIND is free and will stay free. If it's making you show up when you don't want to — a dollar. That's it. Only if you mean it. Only if you can.

Can't spare a dollar? Fine. But if this app is actually making a difference, tell someone. Costs nothing. Means everything.

A few other free apps live on that page too. Same deal, same spirit.

---

*Built by [@Jibunshidai81](https://x.com/Jibunshidai81) — engineered with Claude by Anthropic*

*Do whatever you want with this. Credit appreciated, not required.*
