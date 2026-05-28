# serenity-monitor-feed

Machine-readable feed for stocks currently mentioned as active ideas by @aleabitoreddit.

## Files

- `latest.json` — full latest snapshot
- `summary.json` — frontend-friendly English schema
- `current-ideas-en.json` — simple English machine-readable ideas list
- `current-ideas-en.md` — simple English human-readable ideas list
- `history/` — timestamped snapshots

## summary.json shape

- `schema_version`
- `generated_at_utc` / `last_updated`
- `source_handle`
- `count` / `tickers` / `top_pick`
- `cards[]` with display-ready fields for frontend use
