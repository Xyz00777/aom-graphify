# test_tree_render.py

> 28 nodes · cohesion 0.11

## Key Concepts

- **test_tree_render.py** (28 connections) — `tests/compact/test_tree_render.py`
- **_state()** (13 connections) — `tests/compact/test_tree_render.py`
- **_full_panel()** (10 connections) — `tests/compact/test_tree_render.py`
- **test_format_host_rows_two_space_column_separator()** (5 connections) — `tests/compact/test_tree_render.py`
- **test_format_tree_block_host_leaves_are_plain_indented()** (5 connections) — `tests/compact/test_tree_render.py`
- **test_format_host_rows_idle_host_shows_idle_marker()** (4 connections) — `tests/compact/test_tree_render.py`
- **test_format_host_rows_running_host_includes_current_task_suffix()** (4 connections) — `tests/compact/test_tree_render.py`
- **test_format_host_rows_unreachable_host_shows_unreachable()** (4 connections) — `tests/compact/test_tree_render.py`
- **test_format_tree_block_ascii_fallback()** (4 connections) — `tests/compact/test_tree_render.py`
- **test_format_tree_block_emits_tree_shape()** (4 connections) — `tests/compact/test_tree_render.py`
- **test_format_tree_block_invisible_returns_empty()** (4 connections) — `tests/compact/test_tree_render.py`
- **test_free_strategy_panel_shows_two_tasks()** (4 connections) — `tests/compact/test_tree_render.py`
- **test_linear_strategy_panel_shape()** (4 connections) — `tests/compact/test_tree_render.py`
- **test_post_recap_panel_drops_tree_and_suffix()** (4 connections) — `tests/compact/test_tree_render.py`
- **test_render_status_panel_is_status_bar_only_before_any_task()** (3 connections) — `tests/compact/test_tree_render.py`
- **test_render_status_panel_status_bar_is_last_line()** (3 connections) — `tests/compact/test_tree_render.py`
- **test_truncate_visible_plain_mode_emits_no_sgr()** (3 connections) — `tests/compact/test_tree_render.py`
- **test_render_status_panel_includes_tree_when_task_running()** (2 connections) — `tests/compact/test_tree_render.py`
- **Snapshot tests for the compact renderer's tree + host-row block.  These pin the** (1 connections) — `tests/compact/test_tree_render.py`
- **Regression guard: spacing between count cells and the suffix is     two spaces (** (1 connections) — `tests/compact/test_tree_render.py`
- **Regression guard: when colorize=False, `_truncate_visible` must     not inject `** (1 connections) — `tests/compact/test_tree_render.py`
- **Regression guard: host children render WITHOUT a branch glyph,     matching the** (1 connections) — `tests/compact/test_tree_render.py`
- **When no task is RUNNING, the panel shows only the status bar —     no tree, no h** (1 connections) — `tests/compact/test_tree_render.py`
- **The status bar must be the BOTTOM line of the panel so it stays     anchored at** (1 connections) — `tests/compact/test_tree_render.py`
- **Helper: render the assembled panel against a fixed 80-col terminal,     24-row b** (1 connections) — `tests/compact/test_tree_render.py`
- *... and 3 more nodes in this community*

## Relationships

- [.from_run_state](from_run_state.md) (9 shared connections)
- [format_host_rows](format_host_rows.md) (5 shared connections)
- [format_tree_block](format_tree_block.md) (5 shared connections)
- [_visible_projection](_visible_projection.md) (4 shared connections)
- [CompactRenderer](CompactRenderer.md) (3 shared connections)
- [_compute_tree_budget](_compute_tree_budget.md) (2 shared connections)
- [RunState](RunState.md) (2 shared connections)
- [renderer.py](renderer.py.md) (1 shared connections)
- [Status](Status.md) (1 shared connections)
- [TreeProjection](TreeProjection.md) (1 shared connections)
- [RoleGroupDefinition](RoleGroupDefinition.md) (1 shared connections)
- [HostRunState](HostRunState.md) (1 shared connections)

## Source Files

- `tests/compact/test_tree_render.py`

## Audit Trail

- EXTRACTED: 106 (90%)
- INFERRED: 12 (10%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*