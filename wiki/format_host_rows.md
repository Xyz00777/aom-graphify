# format_host_rows

> 22 nodes · cohesion 0.26

## Key Concepts

- **format_host_rows()** (27 connections) — `src/ansible_aom/compact/format.py`
- **_strip_sgr()** (18 connections) — `src/ansible_aom/compact/format.py`
- **test_host_table.py** (18 connections) — `tests/compact/test_host_table.py`
- **_state()** (14 connections) — `tests/compact/test_host_table.py`
- **_add_results()** (13 connections) — `tests/compact/test_host_table.py`
- **test_failed_host_shows_failed_task_in_suffix()** (8 connections) — `tests/compact/test_host_table.py`
- **test_failed_host_shows_X_in_ascii_mode()** (8 connections) — `tests/compact/test_host_table.py`
- **test_running_host_shows_current_task()** (8 connections) — `tests/compact/test_host_table.py`
- **test_unreachable_host_shows_unreachable_task_in_suffix()** (8 connections) — `tests/compact/test_host_table.py`
- **test_columns_align_across_rows()** (6 connections) — `tests/compact/test_host_table.py`
- **test_header_row_present()** (6 connections) — `tests/compact/test_host_table.py`
- **test_idle_host_shows_idle_marker()** (6 connections) — `tests/compact/test_host_table.py`
- **test_skipped_column_hidden_when_no_skipped()** (6 connections) — `tests/compact/test_host_table.py`
- **test_skipped_column_visible_when_any_host_has_skipped()** (6 connections) — `tests/compact/test_host_table.py`
- **test_unreachable_column_hidden_when_no_unreachable()** (6 connections) — `tests/compact/test_host_table.py`
- **test_unreachable_column_visible_when_any_host_has_unreachable()** (6 connections) — `tests/compact/test_host_table.py`
- **_rows()** (3 connections) — `tests/compact/test_host_table.py`
- **Render the per-host overview as a column-aligned table.      Header row + one ro** (1 connections) — `src/ansible_aom/compact/format.py`
- **Strip SGR escapes so visible-length comparisons are accurate.** (1 connections) — `src/ansible_aom/compact/format.py`
- **Per-host overview renders as a column-aligned table rather than a flat row of co** (1 connections) — `tests/compact/test_host_table.py`
- **Synthesise OK/CHANGED/SKIPPED/FAILED/UNREACHABLE results for a host.** (1 connections) — `tests/compact/test_host_table.py`
- **Split rows on whitespace runs after stripping SGR — coarse but     enough to ass** (1 connections) — `tests/compact/test_host_table.py`

## Relationships

- [HostRunState](HostRunState.md) (15 shared connections)
- [.from_run_state](from_run_state.md) (11 shared connections)
- [test_tree_render.py](test_tree_render.py.md) (5 shared connections)
- [format.py](format.py.md) (4 shared connections)
- [JsonlEvent](JsonlEvent.md) (2 shared connections)
- [TreeProjection](TreeProjection.md) (2 shared connections)
- [renderer.py](renderer.py.md) (2 shared connections)
- [RunState](RunState.md) (2 shared connections)
- [format_host_summary](format_host_summary.md) (1 shared connections)
- [_compute_tree_budget](_compute_tree_budget.md) (1 shared connections)
- [._render_status_panel](_render_status_panel.md) (1 shared connections)
- [format_tree_block](format_tree_block.md) (1 shared connections)

## Source Files

- `src/ansible_aom/compact/format.py`
- `tests/compact/test_host_table.py`

## Audit Trail

- EXTRACTED: 166 (97%)
- INFERRED: 6 (3%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*