Archived (2026-10-08). Ostler is now an open diagnostic and logging platform with an open vehicle-data feed (VISS), not an OS (ADR-0049 in openostler/ostler). Owners keep using Android's and the head unit's own apps for this, fed by Ostler's feed and output bridges. This repo has no code and is kept read-only for history.

# Ostler Phone & Comms app

Hands-free calls, contacts, messages.

Part of [Ostler](https://github.com/openostler/ostler), an open, local-first,
smart-home-like ecosystem for your car. Ostler is built like a phone OS: the
platform repo is the bare system, and every feature is an app or pack in its
own repo, installed from the Store.

Status: empty. This project follows UX first: design, then UI against
recorded fixtures, then wiring. Nothing is built here until the app's design
brief is approved. The briefs live in
`openostler/ostler/references/design/2026-10/brief/`.

Licence: AGPL-3.0-or-later. Contributions are
accepted under the project CLA.

## What this repo holds

- **Owner in the brief:** `app:phone`.
- **Contents:** dialer, favourites, recents, contacts, incoming call, message cards and the Android message bridge, pairing; phases PH0 to PH4 of its spec.
- **Design brief:** [60-apps-phone-a](https://github.com/openostler/ostler/blob/main/references/design/2026-10/brief/60-apps-phone-a.md), [60-apps-phone-b](https://github.com/openostler/ostler/blob/main/references/design/2026-10/brief/60-apps-phone-b.md) (index: [99-index](https://github.com/openostler/ostler/blob/main/references/design/2026-10/brief/99-index-a.md)).
- **Spec:** [phone-comms-addon](https://github.com/openostler/ostler/blob/main/specs/2026-10-07-phone-comms-addon-design.md).
- **Code that moves here later** ([ADR-0046](https://github.com/openostler/ostler/blob/main/decisions/adr-0046-empty-os-every-app-an-add-on.md)): nothing yet. It moves only after this app's designs are approved ([ADR-0045](https://github.com/openostler/ostler/blob/main/decisions/adr-0045-ux-first.md)).
