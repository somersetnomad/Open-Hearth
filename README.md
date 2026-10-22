# Open Hearth

A free, private noticeboard and learning log for UK home education groups.

Open Hearth is a single web page. There's no server, no database, no accounts, and nothing to pay for. Everything is stored in each family's own browser, and notices are shared by passing a small file around the WhatsApp or Signal group you already use.

## What it does

- **Safe Noticeboard.** Post meetups, co-ops, outings and workshops. Only a general area is shown in the open. The exact meeting point, address or gate code is encrypted on your device (AES-256-GCM, with the key derived using PBKDF2) using a community pass-phrase, so anyone without the phrase sees a locked seal instead.
- **Folio & Provision Log.** Record what the children have been learning, then print a plain black-and-white summary if your local authority asks for one.
- **Legal Baseline & Guidance.** A plain-English guide to the law for home education in the UK (mainly England): Section 7 of the Education Act 1996, no required hours or timetable, freedom of approach, and the Children's Wellbeing and Schools Act 2026.
- **Import / Export.** Export a timestamped `.json` pack to share with your group, and import packs from others. Imports never overwrite your private notes.
- **About & Setup.** How to use it as a group, worked examples, and how to host your own copy.

## Privacy

- No accounts, tracking, analytics or adverts.
- The page's own security policy blocks it from connecting to any server.
- The typeface (Newsreader, SIL Open Font License 1.1) is embedded in the file, so nothing is fetched from outside.
- Data stays in the browser on each device. Download a personal backup from **Import / Export** now and then.

## Use it

Open the live site, or download `index.html` and open it in any modern browser.

## Host your own copy

1. Fork this repository, or create your own and upload `index.html`.
2. Go to **Settings → Pages**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, and save.
3. To use your own domain, add it under **Custom domain** and point your DNS at GitHub Pages. The **About & Setup** section in the app has step-by-step instructions.

## Contributing

Feedback, issues and pull requests are welcome, particularly from home educators. Please keep it free, dependency-free and contained in a single file.

## Licence

Code: CC0 1.0 Universal (public domain). See `LICENSE`.
Embedded font: Newsreader © The Newsreader Project Authors, SIL Open Font License 1.1.

*Not legal advice. Check GOV.UK for the current position.*
