# _row_count

> 29 nodes · cohesion 0.10

## Key Concepts

- **_row_count()** (20 connections) — `src/ansible_aom/compact/display.py`
- **test_row_count.py** (17 connections) — `tests/compact/test_row_count.py`
- **display.py** (11 connections) — `src/ansible_aom/compact/display.py`
- **test_display_update_records_wrapped_row_count()** (3 connections) — `tests/compact/test_row_count.py`
- **test_row_count_ansi_long_line_still_wraps_correctly()** (3 connections) — `tests/compact/test_row_count.py`
- **test_row_count_blank_lines_count_as_one_row_each()** (3 connections) — `tests/compact/test_row_count.py`
- **test_row_count_exact_width_one_row()** (3 connections) — `tests/compact/test_row_count.py`
- **test_row_count_multiline_with_one_wrapping_line()** (3 connections) — `tests/compact/test_row_count.py`
- **test_row_count_narrow_terminal_short_text_wraps()** (3 connections) — `tests/compact/test_row_count.py`
- **test_row_count_trailing_newline_does_not_add_row()** (3 connections) — `tests/compact/test_row_count.py`
- **check_terminal_size()** (2 connections) — `src/ansible_aom/compact/display.py`
- **test_row_count_double_width_wraps_to_two_rows()** (2 connections) — `tests/compact/test_row_count.py`
- **test_row_count_empty_string_zero_rows()** (2 connections) — `tests/compact/test_row_count.py`
- **test_row_count_just_over_double_width_three_rows()** (2 connections) — `tests/compact/test_row_count.py`
- **test_row_count_one_over_width_wraps_to_two_rows()** (2 connections) — `tests/compact/test_row_count.py`
- **test_row_count_short_line_one_row()** (2 connections) — `tests/compact/test_row_count.py`
- **test_row_count_two_lines_two_rows()** (2 connections) — `tests/compact/test_row_count.py`
- **test_row_count_two_lines_with_trailing_newline()** (2 connections) — `tests/compact/test_row_count.py`
- **Display logic for compact mode — nom-style fixed-bottom status panel.  Renders d** (1 connections) — `src/ansible_aom/compact/display.py`
- **How many terminal rows `text` occupies at the given terminal `width`.      Each** (1 connections) — `src/ansible_aom/compact/display.py`
- **Check if terminal meets minimum size requirements.      Args:         lines: Num** (1 connections) — `src/ansible_aom/compact/display.py`
- **Tests for width-aware row counting (roadmap #12).  `_row_count` decides how many** (1 connections) — `tests/compact/test_row_count.py`
- **ANSI codes are excluded from the wrap calculation; visible chars     are what co** (1 connections) — `tests/compact/test_row_count.py`
- **After update() in a narrow terminal, _status_rows reflects wrapped rows.      SI** (1 connections) — `tests/compact/test_row_count.py`
- **After 'abc\\n' the cursor sits on the next row but nothing is rendered there.** (1 connections) — `tests/compact/test_row_count.py`
- *... and 4 more nodes in this community*

## Relationships

- [.update](update.md) (5 shared connections)
- [Display](Display.md) (2 shared connections)
- [format.py](format.py.md) (2 shared connections)
- [renderer.py](renderer.py.md) (1 shared connections)
- [IO](IO.md) (1 shared connections)
- [Per-Task Timing Tests](Per-Task_Timing_Tests.md) (1 shared connections)
- [Monochrome Terminal Fallback](Monochrome_Terminal_Fallback.md) (1 shared connections)
- [test_small_terminal.py](test_small_terminal.py.md) (1 shared connections)

## Source Files

- `src/ansible_aom/compact/display.py`
- `tests/compact/test_row_count.py`

## Audit Trail

- EXTRACTED: 96 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*