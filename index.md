# PokeFetch Privacy Policy

**Effective date: July 15, 2026**

PokeFetch is built to need as little of your data as possible. There are no
accounts, no ads, no tracking, and no analytics. This page explains the
small amount of data the app does handle, and why.

## The short version

- Your collection, wishlist, and price history live **on your device**, not
  on our servers.
- Scanning a card sends the **photo** to our server for identification; the
  photo is processed and discarded, never stored.
- We keep an **anonymous identifier** and your **scan-credit balance** on
  our servers so your purchased scans work.
- We never see your payment details, we don't track you, and we don't sell
  or share data with anyone for marketing.

## What we collect and why

**Anonymous identifier.** When you first use scanning, the app creates a
random anonymous ID (via Firebase Authentication). It isn't linked to your
name, email, phone number, Apple ID, or any other identity — we don't have
any of those. It exists solely so your scan-credit balance can be stored
somewhere. If you delete the app, the ID is orphaned and the credits can't
be recovered.

**Scan credits and usage counts.** Alongside that anonymous ID we store
your remaining scan credits and a count of scans performed, so the credit
system works.

**Purchase records.** When you buy a scan pack, Apple processes the payment
— we never receive your name, card number, or billing details. Apple gives
the app a signed receipt, and we record its transaction identifier, the
product purchased, and the credits granted, tied to your anonymous ID. This
is required to deliver your credits and to prevent the same receipt from
being redeemed twice.

**Card photos (processed, not collected).** When you scan a card, the photo
is sent over an encrypted connection to our server, which passes it to an
AI vision service (Anthropic) to identify the card. The photo is used only
to answer that one request: it is not stored by us, not added to any
gallery or profile, and not used to train AI models. Photos you take never
leave the device for any other purpose, and the app cannot access your
photo library except for pictures you explicitly select.

**Nothing else.** Your collections, binders, wishlist, and locally recorded
price history are stored only on your device. We have no copy. There is no
behavioral analytics SDK, no advertising SDK, and no tracking across apps
or websites.

## Service providers

PokeFetch relies on a small number of infrastructure providers, each
receiving only what's necessary to operate the app:

- **Apple** — payment processing for scan packs.
- **Google Firebase** (Cloud Functions, Firestore, Authentication, App
  Check) — hosts our backend and stores the anonymous ID, credit balance,
  and purchase records described above. Servers are located in the United
  States.
- **Anthropic** — the AI service that identifies card photos during a scan.
- **Card data providers** — the app fetches card information, images, and
  market prices from trading-card database services. These requests carry
  standard network information (such as your IP address) but no identity or
  account data — the app has none to send.

As with any internet service, transient technical logs (such as IP
addresses in server logs) may exist briefly for security and reliability;
they are not used to identify or profile you.

## Children

PokeFetch is not directed at children under 13, and it collects no personal
information from anyone. The anonymous identifier described above is not
personal information — it cannot be used to identify a person.

## Your choices and rights

- **Delete local data:** delete the app. Collections and wishlist are gone
  with it.
- **Delete server data:** contact us (below) and we'll delete the records
  associated with your anonymous ID. Note that we cannot look up your data
  without the ID, since we hold nothing else that identifies you.
- Depending on where you live (for example the EU/UK under GDPR or
  California under the CCPA), you may have additional rights to access,
  correct, or delete data. Contact us and we'll honor them. We do not sell
  or share personal information as those laws define it.

## Changes to this policy

If the app's data practices change (for example, if a future feature adds
new data collection), this page will be updated and the effective date
revised before the change ships.

## Contact

Questions or data requests: **[YOUR SUPPORT EMAIL]**

---

PokeFetch is an independent app and is not affiliated with, endorsed, or
sponsored by Nintendo, The Pokémon Company, or Creatures Inc.
