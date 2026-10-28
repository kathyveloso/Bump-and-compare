# Bump & Compare

A pregnancy symptom tracker that answers one question: **"Is what I'm feeling normal for my week?"**

Bump & Compare is a prototype. It is for testing with a small group, not a finished medical product.

- **App:** https://kathyveloso.github.io/Bump-and-compare/
- **About page:** https://kathyveloso.github.io/Bump-and-compare/about/

## What it does

- **Daily check-in.** One question per screen: feeling sick, vomiting, tiredness, heartburn, back pain and sleep, with a plain description for every answer. It also asks about mood, has an optional "anything going on today?" step, and lists warning signs.
- **Compare.** Shows how many people out of 10 report each symptom at your week, based on published studies. Each symptom has an evidence rating and source links.
- **Coming up.** Shows what usually happens over the next few weeks, plus milestones like first movements and the 20-week scan.
- **Linked symptoms.** Gives research-backed tips, for example that treating heartburn may ease sickness.
- **Your patterns.** After 14 check-ins, it shows what tends to go together in your own log.
- **Notes for your midwife.** Writes a plain 14-day summary you can copy.
- **Weekly size character.** Shows a fruit or veg for each week from 4 to 40 (comparisons from Mother&Baby; illustrations are original).

## How it's built

The whole app is a single `index.html` file, with no build step and no server. Check-ins are saved in the browser's local storage, on the user's own device.

## Data sources

| Symptom | Source |
| --- | --- |
| Nausea | Lacroix et al. 2000 (AJOG); Gadsby et al. 1993 (BJGP) |
| Vomiting | Gadsby et al. 1993 |
| Heartburn | Marrero et al. 1992 (BJOG) |
| Back pain | Thorell & Kristiansson 2012 (BMC Pregnancy and Childbirth) |
| Sleep | Zhang et al. 2021 (Nature and Science of Sleep); Fan et al. 2025 (BMC Psychiatry) |
| Tiredness | Effati-Daryani et al. 2021 (Sleep Science) |
| Heartburn and nausea link | Gill et al. 2009 (Obstetrics and Gynecology International) |

Weeks that a study didn't measure are smoothed between measured points. The app labels how solid each figure is.

## Before a public launch

- A midwife or obstetrician reviews all figures and warning-sign wording.
- A privacy review, including a DPIA under UK GDPR, if data ever leaves the device.
- A check on whether the app counts as a medical device under MHRA rules.

## Disclaimer

This app is not medical advice. If you're worried, contact your midwife, maternity unit or NHS 111. In an emergency, call 999.
