# Changelog

All times HKT (UTC+8). Newest first. One entry per publish, written by `publish.sh`.

## v26 — 2026-11-08 18:41 HKT
- documented the one 2026 stream we cannot fetch (27 Aug, 3.04h vs the converter's 3h cap)

## v25 — 2026-11-08 18:15 HKT
- fix: verify runs after build_deliverables so backfilled events reach the page (626 -> 662)

## v24 — 2026-11-08 18:13 HKT
- backfill: 6 previously missing 2026 streams extracted (+36 trade mentions, +19 rule statements)

## v23 — 2026-11-08 17:57 HKT
- study mode: per-trade rows with bracket move, study states (unseen/studied/saved), sorts by move/quotes/hold

## v22 — 2026-11-08 17:03 HKT
- per-trade study view: trip list, zoomed chart, verbatim quotes inside the window, readable outcomes

## v21 — 2026-11-08 14:37 HKT
- 10 tabs collapsed to 5 groups with sub-nav (Book/Stats/Streams/Playbook/Method); per-trade jump to chart from the drawer and round trips

## v20 — 2026-11-08 14:17 HKT
- comparison with the paid deep-dive (strong-model review), per-stream quality audit tab

## v19 — 2026-11-08 04:07 HKT
- charts: series window covers every trip for the ticker (SNDK/MSTR were clipped), legend states labels are bar closes

## v18 — 2026-11-08 04:02 HKT
- Charts tab (candles + entry/exit markers, focused trip band and labels) and Stats tab (official vs reconstruction, long/short, setups, limits)

## v17 — 2026-11-07 23:46 HKT
- screen tab: watchlist grouping is intent buckets or liquidity buckets, not one fixed layout

## v16 — 2026-11-07 23:44 HKT
- screen tab note: watchlist verified persistent across the session and grouped INDEXES/LONGS/SHORTS/FOCUS/TRACKING

## v15 — 2026-11-07 23:41 HKT
- watchlist reads now span each full episode (EP113 t+3m to t+2h17, EP114 to t+2h30, EP115 to t+58m); corrected the earlier opening-only claim

## v14 — 2026-11-07 23:20 HKT
- watchlist reads top-up: EP113 8 crops / EP114 6 crops

## v13 — 2026-11-07 22:54 HKT
- EP114 watchlist extended across the stream (6 crops, 133 reads)

## v12 — 2026-11-07 22:45 HKT
- EP114 watchlist reads completed (4 crops, 70 symbols)

## v11 — 2026-11-07 22:35 HKT
- watchlist reads completed across EP113-115 (full episodes), 131/79/18 symbols

## v10 — 2026-11-07 22:27 HKT
- screen tab: highlight watchlist symbols that also appear in the ledger, cap crop height

## v9 — 2026-11-07 22:24 HKT
- screen tab: watchlist read at 1080p (symbols legible), cross-check vs ledger; unified filter bar on every tab; newest-first default everywhere

## v8 — 2026-11-07 21:10 HKT
- dark theme by default with light toggle, mobile filter collapse, legend, colour and contrast pass

## v7 — 2026-11-07 20:14 HKT
- build stamp in HKT; page header shows as-of time

## v6 — 2026-11-07 20:12 HKT
- update format: changelog header first, single version prefix, HKT stamps

## v5 — 2026-11-07 15:34 HKT
- Screen evidence tab: 192 frames sampled from EP113-115, 0 broker positions/orders panels
- Per-event `J` flag joining each row to the live journal sheet
- Corrected the earlier "video is unreachable" claim (video is obtainable via loader.to)

## v4 — 2026-11-07 15:12 HKT
- Verification tab: source and reconciliation block against the live journal sheet
- Corrected the screen-verification wording throughout

## v3 — 2026-11-07 15:03 HKT
- Redesign per design spec: KPI strip, sticky header, evidence tiers, keyboard navigation, single-row toolbar

## v2 — 2026-11-07 14:37 HKT
- Fixed the stream-count label ("streams with events")

## v1 — 2026-11-07 14:00 HKT
- Initial ledger: 626 events / 411 actions from 98 streams, evidence tiers A/B/C, 236 round trips,
  473 rule statements, 20-page PDF and workbook
