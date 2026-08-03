# TestPerEventLogColors

> 20 nodes · cohesion 0.18

## Key Concepts

- **TestPerEventLogColors** (15 connections) — `tests/compact/test_status_bar_colors.py`
- **TestFinalCompletionIndicator** (12 connections) — `tests/compact/test_status_bar_colors.py`
- **test_status_bar_colors.py** (10 connections) — `tests/compact/test_status_bar_colors.py`
- **._logged()** (8 connections) — `tests/compact/test_status_bar_colors.py`
- **._renderer()** (8 connections) — `tests/compact/test_status_bar_colors.py`
- **._final_line()** (6 connections) — `tests/compact/test_status_bar_colors.py`
- **.test_skipping_line_is_cyan()** (4 connections) — `tests/compact/test_status_bar_colors.py`
- **.test_changed_line_is_yellow()** (3 connections) — `tests/compact/test_status_bar_colors.py`
- **.test_failed_line_is_red()** (3 connections) — `tests/compact/test_status_bar_colors.py`
- **.test_no_color_when_renderer_colorize_off()** (3 connections) — `tests/compact/test_status_bar_colors.py`
- **.test_ok_line_is_green()** (3 connections) — `tests/compact/test_status_bar_colors.py`
- **.test_unreachable_line_is_magenta()** (3 connections) — `tests/compact/test_status_bar_colors.py`
- **.test_cancelled_indicator_is_yellow()** (2 connections) — `tests/compact/test_status_bar_colors.py`
- **.test_completed_indicator_is_green()** (2 connections) — `tests/compact/test_status_bar_colors.py`
- **.test_failed_indicator_is_red()** (2 connections) — `tests/compact/test_status_bar_colors.py`
- **.test_no_color_when_disabled()** (2 connections) — `tests/compact/test_status_bar_colors.py`
- **Tests for semantic SGR colouring in the compact status output.  Colour rules (wh** (1 connections) — `tests/compact/test_status_bar_colors.py`
- **The trailing ●/✖ indicator picks its colour from the state.** (1 connections) — `tests/compact/test_status_bar_colors.py`
- **Per-task log lines (ok/changed/fatal/unreachable/skipping) carry     semantic co** (1 connections) — `tests/compact/test_status_bar_colors.py`
- **Skipped hosts are buffered (collapsed-on-flush). Force the         mixed-task fl** (1 connections) — `tests/compact/test_status_bar_colors.py`

## Relationships

- [CompactRenderer](CompactRenderer.md) (5 shared connections)
- [HostRunState](HostRunState.md) (4 shared connections)
- [Status](Status.md) (3 shared connections)
- [PlayRunState](PlayRunState.md) (2 shared connections)
- [renderer.py](renderer.py.md) (1 shared connections)
- [IO](IO.md) (1 shared connections)
- [WarningType](WarningType.md) (1 shared connections)
- [format_failure_recap](format_failure_recap.md) (1 shared connections)
- [format_host_summary](format_host_summary.md) (1 shared connections)
- [format.py](format.py.md) (1 shared connections)

## Source Files

- `tests/compact/test_status_bar_colors.py`

## Audit Trail

- EXTRACTED: 80 (89%)
- INFERRED: 10 (11%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*