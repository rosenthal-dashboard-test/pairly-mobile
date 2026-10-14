# pairly-mobile

The **Pairly** app for Android and iOS. Students pick their courses, mark their free time, choose a study style, and Pairly finds them a study group.

Maintainer: Sam Okafor (Mobile Developer)
Design: Priya Raman (Product Designer)

## Main screens

- **Onboarding** (new 4-screen flow): welcome, university and courses, weekly free-time grid, study style
- **My groups**: upcoming sessions, group members, and chat
- **Matching**: shows the groups Pairly suggests for each course

## Brand

- App icon: two overlapping speech bubbles forming a "P"
- Primary color: deep teal `#0F766E`
- Accent color: warm coral `#F97362`

Full details are on the "Brand guidelines" page in Notion.

## Release plan

- Store submission (Android and iOS): **Oct 25**
- Public beta at Westbrook University: **Nov 2**

## Known issues

- Push notifications are not delivered on Android 15 (fix in progress)
- The matching screen loads slowly on older Android phones

## Running locally

```bash
npm install
npx expo start
```
