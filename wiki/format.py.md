# format.py

> 48 nodes · cohesion 0.06

## Key Concepts

- **format.py** (60 connections) — `src/ansible_aom/compact/format.py`
- **_wrap()** (19 connections) — `src/ansible_aom/compact/format.py`
- **format_host_summary()** (14 connections) — `src/ansible_aom/compact/format.py`
- **icons.py** (14 connections) — `src/ansible_aom/core/icons.py`
- **test_ascii_fallback.py** (12 connections) — `tests/compact/test_ascii_fallback.py`
- **TestHostSummaryColors** (12 connections) — `tests/compact/test_status_bar_colors.py`
- **get_running_frame()** (8 connections) — `src/ansible_aom/core/icons.py`
- **is_unicode_terminal()** (8 connections) — `src/ansible_aom/core/icons.py`
- **test_invariants_runstate_renderer.py** (7 connections) — `tests/unit/test_invariants_runstate_renderer.py`
- **_truncate_visible()** (6 connections) — `src/ansible_aom/compact/format.py`
- **test_status_bar_estimated_total.py** (6 connections) — `tests/compact/test_status_bar_estimated_total.py`
- **_format_count_cells()** (5 connections) — `src/ansible_aom/compact/format.py`
- **_bar()** (5 connections) — `tests/compact/test_status_bar_estimated_total.py`
- **_count_cell()** (4 connections) — `src/ansible_aom/compact/format.py`
- **_renderer()** (4 connections) — `tests/unit/test_invariants_runstate_renderer.py`
- **test_is_unicode_terminal_false_for_none_encoding()** (3 connections) — `tests/compact/test_ascii_fallback.py`
- **Render non-zero status count cells.      Order: ok, changed, skipped, failed, un** (2 connections) — `src/ansible_aom/compact/format.py`
- **test_format_host_summary_ascii_mode_uses_ascii_icons()** (2 connections) — `tests/compact/test_ascii_fallback.py`
- **test_format_host_summary_unicode_mode_default()** (2 connections) — `tests/compact/test_ascii_fallback.py`
- **test_format_status_bar_ascii_mode_uses_ascii_warning_glyph()** (2 connections) — `tests/compact/test_ascii_fallback.py`
- **test_format_status_bar_ascii_mode_uses_pipe_separator()** (2 connections) — `tests/compact/test_ascii_fallback.py`
- **test_format_status_bar_unicode_mode_keeps_unicode_glyphs()** (2 connections) — `tests/compact/test_ascii_fallback.py`
- **test_is_unicode_terminal_false_for_ascii()** (2 connections) — `tests/compact/test_ascii_fallback.py`
- **test_is_unicode_terminal_true_for_uppercase_utf8()** (2 connections) — `tests/compact/test_ascii_fallback.py`
- **test_is_unicode_terminal_true_for_utf8()** (2 connections) — `tests/compact/test_ascii_fallback.py`
- *... and 23 more nodes in this community*

## Relationships

- [JsonlEvent](JsonlEvent.md) (10 shared connections)
- [renderer.py](renderer.py.md) (9 shared connections)
- [format_host_rows](format_host_rows.md) (7 shared connections)
- [format_status_bar](format_status_bar.md) (7 shared connections)
- [HostRunState](HostRunState.md) (6 shared connections)
- [format_tree_block](format_tree_block.md) (5 shared connections)
- [PlayDefinition](PlayDefinition.md) (4 shared connections)
- [._render_status_panel](_render_status_panel.md) (4 shared connections)
- [models.py](models.py.md) (4 shared connections)
- [RoleGroupDefinition](RoleGroupDefinition.md) (3 shared connections)
- [_compute_mode_label](_compute_mode_label.md) (3 shared connections)
- [format_age](format_age.md) (3 shared connections)

## Source Files

- `src/ansible_aom/compact/format.py`
- `src/ansible_aom/core/icons.py`
- `tests/compact/test_ascii_fallback.py`
- `tests/compact/test_status_bar_colors.py`
- `tests/compact/test_status_bar_estimated_total.py`
- `tests/unit/test_invariants_runstate_renderer.py`

## Audit Trail

- EXTRACTED: 213 (89%)
- INFERRED: 25 (11%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*