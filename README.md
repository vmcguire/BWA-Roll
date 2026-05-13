# BWA-Roll

Tension-ramp generator: subdivision × velocity × spectral lift. Emotion-aware.

**Category B** · **Tier 5** · part of the
[Bandwidth Audio](https://github.com/vmcguire) plugin ecosystem.

---

## What this is

BWA-Roll generates tension ramps that resolve into the next section. Subdivision ramps from quarters to 32nds; velocity ramps from quiet to loud; spectral content lifts toward the top of the frequency range. Emotion-aware — a 'triumphant' roll resolves differently than a 'bittersweet' one.

Snaps to shared/groove/, not the metronome. Without the groove keystone, Roll is just another sample trigger. With it, Roll lands in the player's pocket.

For the broader story of *what BWA is building and why*, see
[BWA-Architecture](https://github.com/vmcguire/BWA-Architecture) —
specifically:

- [`USER-STORY-MAP.md`](https://github.com/vmcguire/BWA-Architecture/blob/main/docs/USER-STORY-MAP.md)
  — where this plugin sits in the bedroom-producer journey (Stage 6 — PROGRAM).
- [`ECOSYSTEM.md`](https://github.com/vmcguire/BWA-Architecture/blob/main/ECOSYSTEM.md)
  — the full product map and the dual-surface / single-DSP architecture.
- [`docs/MARKET-PAIN-AND-ATTACKS.md`](https://github.com/vmcguire/BWA-Architecture/blob/main/docs/MARKET-PAIN-AND-ATTACKS.md)
  — what this plugin attacks (the pain it solves) and how.

## How this fits with the rest of BWA

BWA-Roll ships on **two surfaces** — same DSP, different UI:

1. **Standalone VST3** — drops into any DAW like a FabFilter / iZotope plugin.
   That's what this repo releases.
2. **Embedded cell inside BWA-Mix** — appears as a per-band / per-group cell
   processor inside BWA-Mix's track grid, sharing BWA-Mix's already-running
   band split and contributing to ecosystem-level cross-plugin features.

Both surfaces consume the **same authoritative DSP module**. Fix a bug once,
fixed everywhere.

## Status

🔴 Not built. Stub repo. Blocked on shared/groove/ keystone. Build target: post-Phase E.

## Releases

Versioned `.vst3` builds for macOS land in this repo's
[Releases](https://github.com/vmcguire/BWA-Roll/releases). Build from
source if you want — see `CLAUDE.md` for the dev surface (it's not this repo).

## License

Proprietary. Distribution + license terms pending storefront launch — see
[BWA-Architecture/docs/GO-TO-MARKET.md](https://github.com/vmcguire/BWA-Architecture/blob/main/docs/GO-TO-MARKET.md).
