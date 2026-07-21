# tinkery

A personal workshop of [Claude Code](https://claude.com/claude-code) plugins by Vj Anma — skills tinkered into existence, published for anyone to use.

This repo is a **plugin marketplace**: add it once, then install any skill in the collection.

```
/plugin marketplace add vjanma/tinkery
```

## Skills

| Plugin | What it does | Install |
|---|---|---|
| [video-to-prd](https://github.com/vjanma/video-to-prd) | Turns a screen-recording video (any local format, or a YouTube link) into an implementation-ready PRD — scene-detection screenshots + audio transcription, analyzed together | `/plugin install video-to-prd@tinkery` |

**Coming soon:** `compass` — a structured decision-making framework for working through big choices.

## Updating

```
/plugin marketplace update tinkery
```

New skills added to the tinkery show up automatically — no need to re-add the marketplace.

## How it's organized

Hub-and-spoke: each skill lives in its own repo with its own issues and versioning; this repo is the catalog that indexes them. See any skill's repo for its documentation, requirements, and license.

## License

The catalog (this repo) is MIT. Each plugin carries its own license — all MIT so far.
