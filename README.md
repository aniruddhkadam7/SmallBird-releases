<div align="center">
  <img src=".github/assets/logo.png" alt="Smallbird logo" width="96" />

  # Smallbird — AI Interview & Meeting Assistant

  Real-time AI assistance for interviews and important calls — grounded in your CV and the job description, invisible on screen share.

  [![Latest release](https://img.shields.io/github/v/release/aniruddhkadam7/SmallBird-releases?label=latest%20release)](https://github.com/aniruddhkadam7/SmallBird-releases/releases/latest)
  [![Downloads](https://img.shields.io/github/downloads/aniruddhkadam7/SmallBird-releases/total?label=downloads)](https://github.com/aniruddhkadam7/SmallBird-releases/releases)
  [![Platform](https://img.shields.io/badge/platform-Windows-0078D6)](https://smallbird.in/download)
  [![Website](https://img.shields.io/badge/website-smallbird.in-000000)](https://smallbird.in)

  **[Website](https://smallbird.in) · [Download](https://smallbird.in/download) · [Pricing](https://smallbird.in/pricing) · [Releases](https://github.com/aniruddhkadam7/SmallBird-releases/releases)**
</div>

---

## What is Smallbird?

Smallbird is a desktop AI assistant that listens during a live interview (or any important
real-time conversation) and helps you respond well, as it's happening — not just before it. It's
built around **Interview Mode**: a session where Smallbird transcribes the conversation locally
on your machine and surfaces context-aware suggestions grounded in your CV and the job
description.

This repository distributes the official **Windows installer** for Smallbird. It contains only
built releases and installer assets — the application source code lives in a private repository.
For the full product story, feature pages, and pricing, see **[smallbird.in](https://smallbird.in)**.

## Key capabilities

- **Real-time, local transcription** — speech-to-text runs on your machine as the conversation
  happens, so a suggestion can appear while a question is still being asked.
- **Context-aware assistance** — load in your CV and the job description before a session;
  suggestions are grounded in that context, not generic advice.
- **Analyze Screen** — captures your primary screen on demand and asks the AI to identify or
  work through whatever's shown (a coding problem, a diagram, written questions), alongside your
  spoken question.
- **Invisible on screen share** — Smallbird's overlay is a separate window from your call. If you
  share your screen, what's visible to others is a normal call — never the overlay.
- **Works on any call** — runs as an overlay on top of whatever video-call software is already
  open: Zoom, Google Meet, Microsoft Teams, Webex, GoToMeeting, and others.
- **Auto-updating** — the app checks for and installs new releases from this repository
  automatically, with each update cryptographically signed.

See [smallbird.in/ai-interview-assistant](https://smallbird.in/ai-interview-assistant) and
[smallbird.in/features/real-time-ai](https://smallbird.in/features/real-time-ai) for a deeper look
at how these work.

## Platform availability

| Platform | Status |
|---|---|
| Windows 10 / 11 (64-bit) | ✅ Available now |
| macOS | 🔜 Coming soon |

## Install

**Option 1 — from the website:**
Download the latest installer at **[smallbird.in/download](https://smallbird.in/download)**.

**Option 2 — from this repository:**
Grab the latest `Smallbird-Setup.exe` (or the versioned `Smallbird_<version>_x64-setup.exe`) from
the **[Releases](https://github.com/aniruddhkadam7/SmallBird-releases/releases/latest)** page and
run it. No account is required to install — signing in is only needed to start a session.

Once installed, Smallbird checks for and applies new versions automatically.

## Pricing

Smallbird has a free plan (10 minutes/month, no card required) plus one-time and monthly plans for
regular use, priced in INR with UPI, Google Pay, PhonePe, Paytm, and card support. See
**[smallbird.in/pricing](https://smallbird.in/pricing)** for current plans.

## Known limitations

- macOS is not yet supported — Windows 10/11 (64-bit) only, for now.
- Analyze Screen reads your primary display on demand; it isn't a continuous background capture.
- Smallbird works from audio and (when you trigger it) your screen — it doesn't integrate directly
  with any specific meeting platform's API; it works as a general overlay instead.

## Documentation & links

- Product overview: [smallbird.in](https://smallbird.in)
- How it works: [smallbird.in/ai-interview-assistant](https://smallbird.in/ai-interview-assistant) · [smallbird.in/features/real-time-ai](https://smallbird.in/features/real-time-ai)
- Coding interviews: [smallbird.in/ai-coding-interview-assistant](https://smallbird.in/ai-coding-interview-assistant)
- Pricing: [smallbird.in/pricing](https://smallbird.in/pricing)
- Download: [smallbird.in/download](https://smallbird.in/download)
- Release notes: [CHANGELOG.md](CHANGELOG.md)
- Security policy: [SECURITY.md](SECURITY.md)
- Support: [support@smallbird.in](mailto:support@smallbird.in)

## About this repository

This repo exists to distribute signed Windows installers and power in-app auto-updates. It does
**not** contain Smallbird's application source code, which is maintained in a private repository.
Issues here are welcome for install problems, update issues, or bugs you hit while using the app —
see [Issues](https://github.com/aniruddhkadam7/SmallBird-releases/issues). Since the source isn't
public, this repo doesn't accept code contributions; for feedback or feature requests, please open
an issue or email [support@smallbird.in](mailto:support@smallbird.in).

## License

The contents of this repository (installer binaries and release assets) are proprietary —
see [LICENSE](LICENSE). Smallbird™ is a trademark of Smallbird.

---

<div align="center">
  Made in India 🇮🇳 · <a href="https://smallbird.in">smallbird.in</a>
</div>
