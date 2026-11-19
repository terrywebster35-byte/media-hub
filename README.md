# Common Ground — cross-platform prototype

A simple React Native + Expo prototype for an adults-only (18+) app for dating and friendship. Original visual style, no paid features.

## Included screens
- 18+ welcome gate
- Discover profiles with Dating / Friendship / Both filters
- Like / Pass controls and demo match feedback
- Matches list
- Demo chat with message composer
- Editable profile and discovery visibility toggle
- Block / report confirmation flows and privacy/safety notes

## Run it
1. Install Node.js LTS.
2. In this folder, run `npm install`.
3. Run `npx expo start`.
4. Scan the QR code using Expo Go on an Android or iPhone, or use an emulator.

## Prototype limitations — important
This is a front-end demo. Profiles are fictional, match logic is simulated, and messages/profile edits exist only in app memory. It does **not** provide real registration, secure authentication, a server, real matching between users, push notifications, photo uploads, moderation operations, or account deletion. Do not use it to collect real people's personal data.

## Before a public launch
- Add a production backend, secure auth, database rules, rate limits and abuse monitoring.
- Implement real mutual-match logic and private messaging with encryption in transit.
- Build report/block workflows that reach moderators, appeals and a documented safety policy.
- Add privacy policy, terms, data retention/deletion, age assurance, consent and app-store disclosures.
- Use a privacy-preserving location strategy; never expose precise coordinates.
- Complete security testing, accessibility testing and platform review.

The prototype has no subscriptions, paid boosts, or payment flows. Hosting and app-store distribution may still have costs.
