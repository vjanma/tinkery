# tinkery

A personal workshop of [Claude Code](https://claude.com/claude-code) plugins by Vj Anma — skills tinkered into existence, published for anyone to use.

This repo is a **plugin marketplace**: add it once, then install any skill in the collection.

```
/plugin marketplace add vjanma/tinkery
```

## Skills

| Plugin | What it does | Install |
|---|---|---|
| [overnight-build](https://github.com/vjanma/overnight-build) | Runs an unattended multi-wave overnight build from a plan-of-record file — subagent delegation, per-wave commit gates, a running status log, and an auto-resume safety net | `/plugin install overnight-build@tinkery` |
| [video-to-spec](https://github.com/vjanma/video-to-spec) | Turns a screen-recording video (any local format, or a YouTube link) into a spec-driven development spec: Spec Kit `spec.md` with EARS requirements and user stories, plus screen-by-screen UI evidence, from scene-detection screenshots and audio transcription | `/plugin install video-to-spec@tinkery` |
| [compass](https://github.com/vjanma/compass) | Guides big decisions with the research-backed COMPASS framework (Clarify, Options, Measure, Pause, Anticipate, Settle, Score) — interactive walkthrough or fillable worksheet | `/plugin install compass@tinkery` |
| [branding](https://github.com/vjanma/branding) | Agency-grade naming + brand identity: 10-angle brainstorm, web validation, 7-expert panel with a weighted rubric, then full brand directions and guidelines | `/plugin install branding@tinkery` |
| [storybrand](https://github.com/vjanma/storybrand) | Clarifies your marketing message with Donald Miller's StoryBrand (SB7) framework — BrandScripts, one-liners, and website/pitch audits | `/plugin install storybrand@tinkery` |

## Updating

```
/plugin marketplace update tinkery
```

New skills added to the tinkery show up automatically — no need to re-add the marketplace.

## How it's organized

Hub-and-spoke: each skill lives in its own repo with its own issues and versioning; this repo is the catalog that indexes them. See any skill's repo for its documentation, requirements, and license.

## License

Apache 2.0 — the catalog and every plugin in the collection.
