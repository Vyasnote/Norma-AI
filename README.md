# Norma

**AI documentation assistant for social workers** — records sessions, generates structured case notes, and keeps client data private.

---

## What it does

Social workers spend hours after every session writing up case notes, progress summaries, and referral letters. Norma handles that.

- **Record** a session (live or post-session voice memo)
- **Transcribe** with OpenAI Whisper
- **Generate** a structured case note in your preferred clinical style
- **Review & edit** the draft before approving it to the client record
- **Ask Norma** to refine specific sections with a plain-English instruction

The note never leaves draft until you explicitly approve it.

---

## Screenshots

### Dashboard
![Dashboard](screenshots/dashboard.png)

### New Session
![New Session](screenshots/new-session.png)

### Document Review
![Document Review](screenshots/document-review.png)

### Privacy & Data Settings
![Settings](screenshots/settings.png)

---

## Why I built this

I'm a social worker. Every session I do generates paperwork — case notes, contact logs, referral letters. The documentation burden is real, and it cuts into time that should be with clients.

I wanted a tool that:
1. Understands the language of social work (not just generic therapy notes)
2. Keeps client data private — no training on my data, audio deleted after transcription
3. Lets me stay in control — AI drafts, I approve
4. Works the way I actually work — quick voice memo after a home visit, or live recording in the office

Norma is that tool. Built for social workers, by a social worker.

---

## Tech stack

- **Next.js 14** (App Router)
- **Supabase** (auth + database)
- **OpenAI Whisper** (transcription)
- **Claude (Anthropic)** (note generation and refinement)
- **Tailwind CSS**
- **TypeScript**

---

## Privacy

- Audio recordings are deleted immediately after transcription
- Client data is never used to train AI models
- All data is stored securely — never sold or shared with third parties
- You can export or delete all your data at any time

---

## Status

This is a personal project / early-stage product. It is not open source — this repository exists to showcase the product.

If you're a social worker interested in trying Norma, reach out: [email address]

---

## License

© 2026 Kedar Vyas. All rights reserved.

This repository is for showcase purposes only. The source code is not licensed for use, modification, or distribution.
