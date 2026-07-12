# Fantasy Baseball Weekly Assistant

Fantasy Baseball Weekly Assistant is a personal, local Python tool for generating weekly analysis reports for a Yahoo fantasy baseball league.

The project is intended for read-only use. It helps analyze roster strength, league standings, available players, category needs, keeper value, and possible trade targets. The goal is to create a spreadsheet-style weekly report that supports fantasy baseball decision-making.

## Intended Use

This app is designed for one personal user and one authenticated Yahoo fantasy baseball league.

The tool may read fantasy baseball data such as:

- My roster
- League rosters
- Available players
- League standings
- Player metadata and eligibility

It does not make roster moves, submit waiver claims, add or drop players, send trade offers, or modify league data.

## Data Access

The app is designed to use Yahoo Fantasy Sports API access in read-only mode. It may also use free public baseball data sources to improve analysis, such as player statistics and advanced baseball metrics.

## Output

The main output is a local spreadsheet report with sections such as:

- Weekly summary
- My roster
- League comparison
- Category needs
- Available player recommendations
- Add/drop pairings
- Trade targets
- Keeper board

## Privacy

This is a local personal project. League data, credentials, access tokens, and generated reports are not intended to be published publicly.

Sensitive files such as `.env`, API credentials, access tokens, refresh tokens, and private league data should not be committed to this repository.

## Status

This project is in early development.
