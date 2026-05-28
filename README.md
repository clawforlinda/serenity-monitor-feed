# serenity-monitor-feed

Machine-readable feed for stocks currently mentioned as active ideas by @aleabitoreddit.

## Files

- `latest.json` — full latest snapshot
- `summary.json` — frontend-friendly English schema
- `history/` — timestamped snapshots

## summary.json shape

- `schema_version`
- `generated_at_utc` / `last_updated`
- `source_handle`
- `count` / `tickers` / `top_pick`
- `cards[]` with display-ready fields for frontend use
