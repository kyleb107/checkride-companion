# Checkride

A study platform that takes student pilots from their first lesson to the private pilot
checkride — structured ground school, spaced review, and the planning tools training
actually requires. Built for iOS and Android.

> **This repository is a public overview.** The source is private while the app is prepared
> for App Store release.

## Why

Private pilot training is expensive and badly organised. The knowledge you need is scattered
across the FAR/AIM, a handful of textbooks, and whatever your instructor remembers to cover.
Students pay by the hour, so every lesson spent re-teaching material that should have been
studied on the ground is money spent on the wrong thing.

I earned my own private pilot certificate in January 2024. Checkride is the tool I wanted
while I was doing it.

## What it does

**Ground school as a real curriculum**

- 10 units, 39 lessons, 178 topics
- A 40-question placement test sets the starting point, so a student who already knows
  airspace is not made to sit through it again
- A spaced review scheduler resurfaces topics on an interval that stretches as you answer
  correctly and collapses when you miss
- Oral-prep flashcards aimed at the questions examiners actually ask
- XP and streak tracking, for the days when motivation is thin

**The tools students reach for between lessons**

- Flight school and scholarship search
- Cost planning that projects the real price of a certificate, not the brochure number
- Flight logging against checkride hour minimums
- METAR decoding — raw observation strings turned into plain English
- Weight and balance calculations for the aircraft being flown

**Data handling**

- Local storage, so the app works without a connection
- Backup and restore
- Covered by an automated test suite

## Built with

JavaScript · React Native · Expo · Jest

## Status

In active development. Targeting App Store and Google Play release.

## Screenshots

_Coming soon._

## More

A full write-up — the problem, the engineering decisions, and what I would change next —
is on my portfolio: **https://website-professional-bay.vercel.app/projects/checkride**

---

Kyle Barnes · Computer Science at UT Dallas · FAA-licensed private pilot
[Portfolio](https://website-professional-bay.vercel.app) ·
[LinkedIn](https://www.linkedin.com/in/kyle-barnes-cs) ·
[GitHub](https://github.com/kyleb107)
