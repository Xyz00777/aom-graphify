# TestPerEventLogColors

> 27 nodes · cohesion 0.13

## Key Concepts

- **TestPerEventLogColors** (15 connections) — `tests/compact/test_status_bar_colors.py`
- **TestFinalCompletionIndicator** (12 connections) — `tests/compact/test_status_bar_colors.py`
- **test_status_bar_colors.py** (10 connections) — `tests/compact/test_status_bar_colors.py`
- **TestColorEnabled** (10 connections) — `tests/compact/test_status_bar_colors.py`
- **._logged()** (8 connections) — `tests/compact/test_status_bar_colors.py`
- **._renderer()** (8 connections) — `tests/compact/test_status_bar_colors.py`
- **_color_enabled()** (7 connections) — `src/ansible_aom/compact/format.py`
- **._final_line()** (6 connections) — `tests/compact/test_status_bar_colors.py`
- **.test_skipping_line_is_cyan()** (4 connections) — `tests/compact/test_status_bar_colors.py`
- **.test_changed_line_is_yellow()** (3 connections) — `tests/compact/test_status_bar_colors.py`
- **.test_failed_line_is_red()** (3 connections) — `tests/compact/test_status_bar_colors.py`
- **.test_no_color_when_renderer_colorize_off()** (3 connections) — `tests/compact/test_status_bar_colors.py`
- **.test_ok_line_is_green()** (3 connections) — `tests/compact/test_status_bar_colors.py`
- **.test_unreachable_line_is_magenta()** (3 connections) — `tests/compact/test_status_bar_colors.py`
- **.test_off_when_no_color_set_even_for_tty()** (2 connections) — `tests/compact/test_status_bar_colors.py`
- **.test_off_when_not_a_tty()** (2 connections) — `tests/compact/test_status_bar_colors.py`
- **.test_on_when_tty_and_no_color_unset()** (2 connections) — `tests/compact/test_status_bar_colors.py`
- **.test_cancelled_indicator_is_yellow()** (2 connections) — `tests/compact/test_status_bar_colors.py`
- **.test_completed_indicator_is_green()** (2 connections) — `tests/compact/test_status_bar_colors.py`
- **.test_failed_indicator_is_red()** (2 connections) — `tests/compact/test_status_bar_colors.py`
- **.test_no_color_when_disabled()** (2 connections) — `tests/compact/test_status_bar_colors.py`
- **True if we should emit SGR codes — TTY only, NO_COLOR honored.** (1 connections) — `src/ansible_aom/compact/format.py`
- **Tests for semantic SGR colouring in the compact status output.  Colour rules (wh** (1 connections) — `tests/compact/test_status_bar_colors.py`
- **The trailing ●/✖ indicator picks its colour from the state.** (1 connections) — `tests/compact/test_status_bar_colors.py`
- **Per-task log lines (ok/changed/fatal/unreachable/skipping) carry     semantic co** (1 connections) — `tests/compact/test_status_bar_colors.py`
- *... and 2 more nodes in this community*

## Relationships

- [HostRunState](HostRunState.md) (10 shared connections)
- [CompactRenderer](CompactRenderer.md) (6 shared connections)
- [Status](Status.md) (3 shared connections)
- [format.py](format.py.md) (2 shared connections)
- [renderer.py](renderer.py.md) (2 shared connections)
- [JsonlEvent](JsonlEvent.md) (1 shared connections)
- [IO](IO.md) (1 shared connections)
- [models.py](models.py.md) (1 shared connections)
- [format_status_bar](format_status_bar.md) (1 shared connections)

## Source Files

- `src/ansible_aom/compact/format.py`
- `tests/compact/test_status_bar_colors.py`

## Audit Trail

- EXTRACTED: 94 (82%)
- INFERRED: 21 (18%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*