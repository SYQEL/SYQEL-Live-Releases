<p align="center">
  <img src=".github/hero.png" alt="SYQEL Live rendering a music-reactive visual world" width="820" />
</p>

<h1 align="center">SYQEL Live</h1>

<p align="center">
  <b>The professional audio-responsive visualizer for DJs&nbsp;&amp;&nbsp;VJs.</b><br/>
  Real-time visuals that listen to your music — on stage, in the booth, or on stream.
</p>

<p align="center">
  <a href="https://download.syqel.com/live/mac"><img alt="Download for macOS" src="https://img.shields.io/badge/macOS-Download-black?logo=apple&logoColor=white" /></a>
  <a href="https://download.syqel.com/live/windows"><img alt="Download for Windows" src="https://img.shields.io/badge/Windows-Download-0078D4?logo=gitforwindows&logoColor=white" /></a>
  <a href="https://apps.apple.com/app/id6791380605"><img alt="Mac App Store" src="https://img.shields.io/badge/Mac%20App%20Store-View-blue?logo=appstore&logoColor=white" /></a>
  <a href="https://github.com/SYQEL/SYQEL-Live-Releases/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/SYQEL/SYQEL-Live-Releases?label=latest" /></a>
</p>

---

## What is SYQEL Live?

SYQEL Live turns whatever your audience is hearing into a live, beat-locked visual show.
It listens to your computer's audio — the DJ software, a streaming service, any app, or a
line input — analyzes it in real time (energy, bass, BPM, and per-instrument detail like
kick, bass, and hats), and drives a catalogue of generative 3D worlds that move with the
music. Kick hits flash, basslines glow, hi-hats sparkle — every world reacts to the parts
of the track, not just its volume.

Built for the booth: send the output to a projector or LED wall, pipe it into Resolume,
OBS, vMix, or a media server over **NDI**, and drive it hands-free or from your MIDI
controller.

## Features

### 🎵 Real audio in, real reactivity out
- **System-audio capture** — visualize everything the machine is playing (macOS
  ScreenCaptureKit loopback, Windows WASAPI loopback). No virtual audio cables needed.
- **Per-app capture** — lock onto just your DJ software or player, ignoring everything else.
- **Per-instrument reactivity** — the analyzer separates the mix into musical sources
  (kick, bass, melody, hats…) and every visual world uses them; beat-synced motion lands
  on the grid, not "roughly near it."

### 🌍 A living catalogue of visual worlds
- **38+ generative 3D worlds** — from oceans, canyons, and star fields to neon cities,
  sacred geometry, and digital rain — all audio-reactive, all running in real time.
- **Over-the-air updates** — new worlds and engine improvements arrive automatically,
  no reinstall. The catalogue keeps growing while the app stays put.
- **Fully offline-capable** — worlds and assets ship in the app and cache locally; a lost
  backstage connection never kills the show.

### 🎛 Built for performing
- **Show modes** — *Auto* (an intelligent director journeys through the catalogue),
  *Playlist* (your curated set order with per-list hold times), or *Pin* (lock one world).
- **Playlists / setlists** — build and reorder sets for each gig; manual "next" is a clean
  hard cut when you want it.
- **MIDI control** — hook up your controller and drive the show from hardware.
- **Overlays** — put your logo or event branding over the visuals.

### 📺 Professional output
- **Dedicated output window** — full-screen the visuals on any connected display or
  projector at full resolution, with the control surface staying on your screen.
- **NDI®** — the app is an NDI source on your network: Resolume, OBS, vMix, media
  servers, and LED processors pick it up directly.
- **Syphon** (macOS, direct download) and **Spout** (Windows) — zero-configuration GPU
  texture sharing into other visual software on the same machine.

### 🔄 Always current
- The app checks for updates at launch and installs them with one click — never
  mid-show, never automatic. Visual content updates separately over the air.

## Downloads

| Platform | Direct download | Store |
|---|---|---|
| **macOS** (Apple Silicon + Intel, macOS 13+) | [download.syqel.com/live/mac](https://download.syqel.com/live/mac) | [Mac App Store](https://apps.apple.com/app/id6791380605) |
| **Windows** (64-bit, Windows 10+) | [download.syqel.com/live/windows](https://download.syqel.com/live/windows) | Microsoft Store — coming soon |

All installers are code-signed and notarized. The direct downloads always point at the
newest release; older versions live on the [Releases](https://github.com/SYQEL/SYQEL-Live-Releases/releases) page.

> **Which build should I pick?** The direct macOS download includes **Syphon** output;
> the Mac App Store build offers the same show features with **NDI** for interop
> (Syphon isn't available to sandboxed App Store apps). If you feed Resolume or
> MadMapper, both ingest NDI natively — either build works.

## Free vs. paid

Every visual world is playable on the free tier — the output carries a SYQEL watermark.
Going paid removes the watermark. Subscriptions and one-off **Gig Passes** (24h / 48h —
for the night you actually need it) are available in-app.

## System requirements

- **macOS 13 Ventura or later** — Apple Silicon or Intel. Screen-Recording permission is
  requested once for system-audio capture (macOS routes app audio through it; no
  microphone involved).
- **Windows 10 or later, 64-bit** — WebView2 (preinstalled on Windows 11; the installer
  handles it on Windows 10).
- A discrete or modern integrated GPU is recommended for 1080p60 output.

## About this repository

This public repository hosts the **installers, release notes, and update feed** for
SYQEL Live. The application source is developed in a private repository; releases are
built, signed, and published here by CI (macOS universal + Windows x64, tag-triggered).

- **Website:** [syqel.com](https://syqel.com)
- **All SYQEL apps:** [download.syqel.com](https://download.syqel.com)
- **Support:** [syqel.com](https://syqel.com) · or open an issue here for
  install/update problems with a release

---

<p align="center">NDI® is a registered trademark of Vizrt NDI AB. Syphon and Spout are open frameworks of their respective projects.</p>
