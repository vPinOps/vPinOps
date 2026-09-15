# vPinOps

**A lightweight front end for virtual pinball cabinets.** Windows, macOS and Linux.

Your tables on a wheel, launched on the cabinet buttons, and the wheel is what you land back on
when you quit. The whole cabinet is run from a browser or a phone on your own network — volume,
screens, the coin door, which tables show — with nothing in the cloud and nothing to install on the
phone. Pinball FX and Pinball FX Midnight sit on the same wheel.

It is a front end, not a rig installer: it does not install Visual Pinball, ROMs or DOF, and it
never downloads a table.

**Free, and it always will be.**

## Download

**[Releases](https://github.com/vPinOps/vPinOps/releases/latest)** — one zip per platform. It is a
folder you copy; no installer, no runtime to install first.

| | file | for |
|---|---|---|
| Windows | `vPinOps-win-x64.zip` | any 64-bit Windows machine |
| macOS | `vPinOps-macos-arm64.zip` | Apple Silicon |
| Linux | `vPinOps-linux-x64.zip` | any 64-bit desktop or cabinet |

Then: **[vpinops.com/start/getting-started](https://vpinops.com/start/getting-started/)** — from
the download to your first table on the wheel. The macOS build is not signed with an Apple
developer certificate yet; the install page says how to approve it once.

## What you need

- **Visual Pinball Standalone, the BGFX build, 10.8.1 or newer.** Visual Pinball still marks 10.8.1
  as a pre-release; it is the first build that lets a front end put your backglass and DMD on the
  right screens, which is the main thing vPinOps does. On 10.8.0 tables still launch and return —
  your screens cannot be placed until you move up. [Get Visual Pinball](https://vpinops.com/start/get-visual-pinball/)
- Your own tables and ROMs.

## Something broke?

Say so — that is the most useful thing you can do with v1. Two things make a report answerable:

1. **About vPinOps…** from the tray or menu bar icon → **Copy details**.
2. The run log, `last-run.log`, next to your config
   ([where that is](https://vpinops.com/reference/where-things-are/)).

Post those, with what you did and what you saw: **[Discord](DISCORD_INVITE)**.

Issues are off on this repository on purpose; the conversation is on Discord. The source is not
published here — this repository is the home for the releases.

## Documentation

Everything is at **[vpinops.com](https://vpinops.com)**: what it is and is not, install per platform,
the library layout, importing, screens, OpsLink, troubleshooting, and the roadmap of what runs today
and what is next.

---

Made by MDKbot (James Brock), for the pinball community.
