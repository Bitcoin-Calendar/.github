# Bitcoin Calendar

Welcome to the official GitHub organization for Bitcoin Calendar! The aim of the project is to archive and relay every significant Bitcoin milestone, providing historical context and fostering community engagement around Bitcoin's rich history.

## Mission

To become the definitive resource for historical Bitcoin events, making this information accessible and engaging.

![structure](https://haven.bitcoin-calendar.org/4d4f81403e39c0c4a454a35cb6913a9420539c9665cb5240fdaff4e27b1e5176.webp)

## Projects

Here's an overview of our core projects:

* **Bitcoin Historical Events API & Database** ([`calendar-api-db`](https://github.com/Bitcoin-Calendar/calendar-api-db)): A Go-based API serving historical Bitcoin event data from SQLite databases, supporting full text search. This is the backend powering our data.
* **Bitcoin Calendar Bot** ([`calendar-bot`](https://github.com/Bitcoin-Calendar/calendar-bot)): A Go application that fetches historical Bitcoin event data from our API and publishes these events to Nostr relays, automating daily posts.
* **ArchiveBox** ([`archive.bitcoin-calendar.org`](https://archive.bitcoin-calendar.org/admin/core/snapshot/)): a self-hosted web archive of all the sources and historical documents, referenced by the database.
* **Haven relay and Blossom server**: Nostr relay and media server ensuring full control over the notes and media being blasted over Nostr.
* **Bitcoin Calendar Website (Next.js)**: *[Coming Soon!]* Our upcoming interactive Next.js website featuring a React Big Calendar to display all historical Bitcoin events. This platform will provide search capabilities, events categorization, Nostr comments, logins, zaps, and more, offering a rich user experience.
* **Bitcoin Calendar Landing Page (Hugo)** ([`calendar-landing`](https://github.com/Bitcoin-Calendar/bitcoin-calendar-landing)): (Temporary) The current static landing page for the Bitcoin Calendar project. This will eventually be superseded by the Next.js website.

You can look into our future development plans at [`ROADMAP.md`](https://github.com/Bitcoin-Calendar/calendar-bot/blob/main/docs/ROADMAP.md)

## Getting Involved

We welcome contributions from the community!
* **Documentation:** Explore our project-specific documentation within each repository for detailed setup and usage guides.
* **Contributing:** Please see the `CONTRIBUTING.md` file in individual repositories for how to get started.
* **Support:** Support Bitcoin Calendar via [Coinos](https://coinos.io/bitcal) or [Geyser](https://geyser.fund/project/bitcoincalendar).

## Contact

For inquiries, please reach out to [@Tony](https://njump.me/npub10awzknjg5r5lajnr53438ndcyjylgqsrnrtq5grs495v42qc6awsj45ys7) on Nostr.

---
**Bitcoin Calendar** – Archiving and relaying every Bitcoin milestone.
