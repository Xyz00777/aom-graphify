# format.py

> 37 nodes · cohesion 0.08

## Key Concepts

- **format.py** (60 connections) — `src/ansible_aom/compact/format.py`
- **test_warning_color.py** (9 connections) — `tests/compact/test_warning_color.py`
- **_truncate_msg()** (8 connections) — `src/ansible_aom/compact/format.py`
- **._format_loop_item_line()** (8 connections) — `src/ansible_aom/compact/renderer.py`
- **test_invariants_runstate_renderer.py** (7 connections) — `tests/unit/test_invariants_runstate_renderer.py`
- **_truncate_visible()** (6 connections) — `src/ansible_aom/compact/format.py`
- **_verbose_ok_body()** (6 connections) — `src/ansible_aom/compact/format.py`
- **test_status_bar_estimated_total.py** (6 connections) — `tests/compact/test_status_bar_estimated_total.py`
- **_printed()** (6 connections) — `tests/compact/test_warning_color.py`
- **_renderer()** (6 connections) — `tests/compact/test_warning_color.py`
- **_replace_surrogates()** (5 connections) — `src/ansible_aom/compact/format.py`
- **_extract_error_msg()** (5 connections) — `src/ansible_aom/compact/renderer.py`
- **_bar()** (5 connections) — `tests/compact/test_status_bar_estimated_total.py`
- **._loop_item_lines()** (4 connections) — `src/ansible_aom/compact/renderer.py`
- **test_warning_with_synthesised_prefix_also_colored()** (4 connections) — `tests/compact/test_warning_color.py`
- **_renderer()** (4 connections) — `tests/unit/test_invariants_runstate_renderer.py`
- **test_deprecation_wrapped_in_orange()** (3 connections) — `tests/compact/test_warning_color.py`
- **test_warning_without_color_when_colorize_off()** (3 connections) — `tests/compact/test_warning_color.py`
- **test_warning_wrapped_in_yellow()** (3 connections) — `tests/compact/test_warning_color.py`
- **Replace any lone-surrogate codepoints in ``s`` with U+FFFD.      Pexpect's ``cod** (2 connections) — `src/ansible_aom/compact/format.py`
- **test_estimated_default_is_plain()** (2 connections) — `tests/compact/test_status_bar_estimated_total.py`
- **test_estimated_total_prefixes_tilde()** (2 connections) — `tests/compact/test_status_bar_estimated_total.py`
- **test_non_estimated_total_is_plain()** (2 connections) — `tests/compact/test_status_bar_estimated_total.py`
- **.test_replace_surrogates_converts_lone_surrogates()** (2 connections) — `tests/integration/test_r6_encoding_roundtrip.py`
- **.__init__()** (2 connections) — `tests/unit/test_invariants_runstate_renderer.py`
- *... and 12 more nodes in this community*

## Relationships

- [renderer.py](renderer.py.md) (8 shared connections)
- [JsonlEvent](JsonlEvent.md) (7 shared connections)
- [CompactRenderer](CompactRenderer.md) (5 shared connections)
- [format_host_summary](format_host_summary.md) (4 shared connections)
- [format_host_rows](format_host_rows.md) (4 shared connections)
- [test_r6_encoding_roundtrip.py](test_r6_encoding_roundtrip.py.md) (4 shared connections)
- [format_preflight_summary](format_preflight_summary.md) (3 shared connections)
- [._render_status_panel](_render_status_panel.md) (3 shared connections)
- [RoleGroupDefinition](RoleGroupDefinition.md) (3 shared connections)
- [format_status_bar](format_status_bar.md) (3 shared connections)
- [format_tree_block](format_tree_block.md) (3 shared connections)
- [format_age](format_age.md) (3 shared connections)

## Source Files

- `src/ansible_aom/compact/format.py`
- `src/ansible_aom/compact/renderer.py`
- `tests/compact/test_status_bar_estimated_total.py`
- `tests/compact/test_warning_color.py`
- `tests/integration/test_r6_encoding_roundtrip.py`
- `tests/unit/test_invariants_runstate_renderer.py`

## Audit Trail

- EXTRACTED: 176 (97%)
- INFERRED: 6 (3%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*