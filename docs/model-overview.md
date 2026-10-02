# Model overview

This document summarizes the report structure detected in the Power BI file.

## Core tables

### PlayersTable

Fields used by report visuals include:

- `player_id`
- `name`
- `age`
- `position`
- `market_value_m`
- `goals`
- `assists`
- `Player League`

Measures referenced in the report include:

- `Stipendio Medio`
- `Valore Totale Rosa`

### ClubsTable

Fields used by report visuals include:

- `club_name`
- `league`

Measures referenced in the report include:

- `Valore Medio Mercato`
- `Gol Totali`
- `Rank Valore Mercato`
- `Quota Valore Club %`
- `Valore Medio Under 23`
- `Differenza U23 %`
- `Differenza U23 vs Media`
- `Media Valore Ruolo`
- `Scostamento % Ruolo`
- `Media Ruolo Campionato`
- `Scostamento % Ruolo Campionato`
- `Segnale Scouting`
- `Rank Scouting`

## Report pages

The PBIX contains two report pages.

### Page 1

Contains a league slicer and analytical tables covering club metrics, player performance and positional market-value comparisons.

### Page 2

Contains scouting-oriented tables that combine player attributes with league/position benchmarks, scouting signals and ranking.

## Portfolio interpretation

The strongest portfolio angle is not simply “I built a Power BI dashboard.”

The project demonstrates a workflow of:

1. organizing player and club data;
2. defining meaningful business/scouting KPIs;
3. comparing players against contextual benchmarks;
4. translating those comparisons into scouting signals;
5. presenting the result in an interactive decision-support report.

This framing is relevant to Data Analyst, BI Analyst, Football Data/Recruitment Analyst and other data-driven client-facing roles.
