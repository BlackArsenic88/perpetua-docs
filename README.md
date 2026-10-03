# Perpetua

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)](#getting-started)
[![TypeScript](https://img.shields.io/badge/TypeScript-6.x-blue.svg)](https://www.typescriptlang.org/)
[![Framework](https://img.shields.io/badge/Framework-React%20Native%20%2F%20Expo-000000.svg)](https://expo.dev/)
[![License](https://img.shields.io/badge/License-Proprietary-red.svg)](#license)

**Quality over quantity.**

Perpetua is a mobile app that builds a **capsule wardrobe** for you: a small, carefully chosen set of pieces that fit your body, stay inside your budget, match your style preferences, and work well together. You can swap or approve pieces, buy the whole capsule or just some of it, and follow every delivery in one place.
---

## What the app does

1. **You tell it about you.** Your measurements, wardrobe (women's or men's), style approach, colours, fabrics, patterns, favourite fashion houses, and budget. Your details stay on your device.
2. **It builds your capsule.** A rules-based solver (not a guess) picks real pieces in your size and checks that colours, patterns and prices work together and stay within budget.
3. **You stay in control.** Swap any piece, approve the ones you love, or edit your inputs and rebuild.
4. **You buy and track.** Buy everything, or only the pieces you choose, and follow each shipment.

### The five tabs

| Tab | What it is for |
|---|---|
| **Home** | A directory of 50 fashion houses. Tap one to visit its website without leaving the app. |
| **Shop** | Individual pieces that fit you, ordered by your preferences, grouped by category. |
| **Capsule** | Your full capsule wardrobe, with Swap, Approve, Rebuild and Buy. |
| **Search** | One search box for the whole catalogue, the fashion houses, and places in the app (for example "measurements" or "orders"). |
| **Profile** | Your preferences, Transaction History (your orders), and Settings. |

### Style approaches

| New York (CFDA) | London (BFC) | Paris (FHCM) | Italy (CNMI) |

----

## How the capsule is built (in plain terms)

Think of the capsule as a checklist of slots, such as "black tailored blazer" or "white shirt". For each slot the app finds every real piece that:

- comes in **your size** and is in stock,
- is in a **colour, fabric, pattern, and fashion house** you chose,
- and, for dresses, has a **silhouette** you like.

Then it chooses one piece per slot so that colours and patterns go together and the **total stays within your budget**. If no combination works, the app says so, explains why, and offers the smallest change that would help (for example, raising the budget by a certain amount) instead of showing you a partial capsule.

---

## Your data and privacy

Your measurements, preferences and address are stored **on your device only**. They are not used for tracking and are not sent to analytics. You can delete everything from **Profile > Settings > Delete my data**. Details: [`docs/privacy.md`](docs/privacy.md).

---

## Docs
- [Privacy Policy](docs/veralux_privacy_policy.md)
- [EULA](docs/veralux_eula.md)
- [Terms of Use](docs/veralux_terms_of_use.md)

## License

Copyright © 2026 Abraham Doe. All rights reserved.
Unlawful copying, distribution, or modifications of this software via any medium is strictly prohibited without explicit written consent.
