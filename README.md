# football_data

Match-scoped football event artifacts exported from MatchIndex.

## Layout

- `matches/<year>/<month>/<matchId>/analysis-detail.v1.json.gz`
- `matches/<year>/<month>/<matchId>/freeze-frames.v1.json.gz`
- `matches/<year>/<month>/<matchId>/visible-areas.v1.json.gz`

## Notes

- Files are generated from PostgreSQL event detail data.
- Not every match has every artifact type.
- `visible-areas` currently exists for a subset of matches.
