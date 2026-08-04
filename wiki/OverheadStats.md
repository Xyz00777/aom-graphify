# OverheadStats

> 27 nodes · cohesion 0.15

## Key Concepts

- **OverheadStats** (20 connections) — `src/ansible_aom/core/overhead.py`
- **format_overhead_section()** (14 connections) — `src/ansible_aom/inspect/formatters.py`
- **_stats()** (10 connections) — `tests/unit/test_overhead_display.py`
- **formatters.py** (9 connections) — `src/ansible_aom/inspect/formatters.py`
- **test_overhead_display.py** (8 connections) — `tests/unit/test_overhead_display.py`
- **TestFullStats** (7 connections) — `tests/unit/test_overhead_display.py`
- **TestFormatting** (5 connections) — `tests/unit/test_overhead_display.py`
- **_fmt_seconds()** (3 connections) — `src/ansible_aom/inspect/formatters.py`
- **.test_floor_at_or_above_one_second_uses_s()** (3 connections) — `tests/unit/test_overhead_display.py`
- **.test_floor_below_one_second_uses_ms()** (3 connections) — `tests/unit/test_overhead_display.py`
- **.test_section_has_header()** (3 connections) — `tests/unit/test_overhead_display.py`
- **.test_includes_sample_count()** (3 connections) — `tests/unit/test_overhead_display.py`
- **.test_omits_share_line_when_wall_clock_missing()** (3 connections) — `tests/unit/test_overhead_display.py`
- **.test_section_contains_floor_and_median()** (3 connections) — `tests/unit/test_overhead_display.py`
- **.test_section_includes_percent_share_when_available()** (3 connections) — `tests/unit/test_overhead_display.py`
- **.test_section_mentions_estimated_overhead_seconds()** (3 connections) — `tests/unit/test_overhead_display.py`
- **TestInsufficientSamples** (3 connections) — `tests/unit/test_overhead_display.py`
- **.test_shows_one_line_about_insufficient_data()** (3 connections) — `tests/unit/test_overhead_display.py`
- **TestZeroSamples** (3 connections) — `tests/unit/test_overhead_display.py`
- **.test_returns_none_when_no_samples()** (3 connections) — `tests/unit/test_overhead_display.py`
- **TestDataclassShape** (3 connections) — `tests/unit/test_overhead.py`
- **.test_overhead_stats_is_frozen()** (2 connections) — `tests/unit/test_overhead.py`
- **Per-task overhead summary.      ``None`` fields signal "insufficient data": eith** (1 connections) — `src/ansible_aom/core/overhead.py`
- **Display helpers for AOM inspect output.  Houses both the overhead-stats summary** (1 connections) — `src/ansible_aom/inspect/formatters.py`
- **Render durations: sub-second as ms, anything else as s with one decimal.** (1 connections) — `src/ansible_aom/inspect/formatters.py`
- *... and 2 more nodes in this community*

## Relationships

- [analyze_overhead](analyze_overhead.md) (5 shared connections)
- [test_overhead.py](test_overhead.py.md) (5 shared connections)
- [test_inspect_debug.py](test_inspect_debug.py.md) (2 shared connections)
- [JsonlEvent](JsonlEvent.md) (1 shared connections)
- [inspect/cli.py](inspect-cli.py.md) (1 shared connections)

## Source Files

- `src/ansible_aom/core/overhead.py`
- `src/ansible_aom/inspect/formatters.py`
- `tests/unit/test_overhead.py`
- `tests/unit/test_overhead_display.py`

## Audit Trail

- EXTRACTED: 106 (87%)
- INFERRED: 16 (13%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*