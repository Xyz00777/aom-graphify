# ._render_status_panel

> 42 nodes · cohesion 0.06

## Key Concepts

- **._render_status_panel()** (18 connections) — `src/ansible_aom/compact/renderer.py`
- **count_total_tasks()** (17 connections) — `src/ansible_aom/compact/format.py`
- **test_task_progress.py** (17 connections) — `tests/compact/test_task_progress.py`
- **.handle_completion()** (13 connections) — `src/ansible_aom/compact/renderer.py`
- **count_completed_tasks()** (12 connections) — `src/ansible_aom/compact/format.py`
- **count_total_tasks_seen()** (12 connections) — `src/ansible_aom/compact/format.py`
- **run_state_status_counts()** (10 connections) — `src/ansible_aom/core/tree.py`
- **test_count_total_tasks_grows_with_runtime_announced_tasks()** (8 connections) — `tests/compact/test_task_progress.py`
- **test_handle_completion_keeps_runtime_grown_denominator()** (8 connections) — `tests/compact/test_task_progress.py`
- **_task()** (7 connections) — `tests/compact/test_task_progress.py`
- **test_count_total_tasks_seen_falls_back_to_preflight_before_any_announce()** (6 connections) — `tests/compact/test_task_progress.py`
- **.set_definitions()** (5 connections) — `src/ansible_aom/compact/renderer.py`
- **test_renderer_status_bar_reflects_task_progress()** (5 connections) — `tests/compact/test_task_progress.py`
- **._cached_count_total_tasks()** (4 connections) — `src/ansible_aom/compact/renderer.py`
- **._task_total_with_prior()** (4 connections) — `src/ansible_aom/compact/renderer.py`
- **test_count_total_tasks_sums_across_plays()** (4 connections) — `tests/compact/test_task_progress.py`
- **._render_status_bar()** (3 connections) — `src/ansible_aom/compact/renderer.py`
- **.tick()** (3 connections) — `src/ansible_aom/compact/renderer.py`
- **test_count_completed_tasks_empty_state()** (3 connections) — `tests/compact/test_task_progress.py`
- **test_format_status_bar_omits_tasks_when_total_zero()** (3 connections) — `tests/compact/test_task_progress.py`
- **test_format_status_bar_task_progress_defaults_to_zero()** (3 connections) — `tests/compact/test_task_progress.py`
- **test_total_tasks_empty_definitions()** (3 connections) — `tests/unit/test_dynamic_counters.py`
- **test_count_total_tasks_empty()** (2 connections) — `tests/compact/test_task_progress.py`
- **test_format_status_bar_includes_task_progress_when_total_set()** (2 connections) — `tests/compact/test_task_progress.py`
- **Sum of leaf tasks across all preflight play definitions.      Used for the statu** (1 connections) — `src/ansible_aom/compact/format.py`
- *... and 17 more nodes in this community*

## Relationships

- [TaskDefinition](TaskDefinition.md) (17 shared connections)
- [HostRunState](HostRunState.md) (14 shared connections)
- [CompactRenderer](CompactRenderer.md) (9 shared connections)
- [renderer.py](renderer.py.md) (7 shared connections)
- [RunState](RunState.md) (6 shared connections)
- [JsonlEvent](JsonlEvent.md) (5 shared connections)
- [format_status_bar](format_status_bar.md) (5 shared connections)
- [format.py](format.py.md) (3 shared connections)
- [RendererMirrorMachine](RendererMirrorMachine.md) (2 shared connections)
- [_compute_tree_budget](_compute_tree_budget.md) (2 shared connections)
- [TreeProjection](TreeProjection.md) (2 shared connections)
- [test_incremental_counters.py](test_incremental_counters.py.md) (1 shared connections)

## Source Files

- `src/ansible_aom/compact/format.py`
- `src/ansible_aom/compact/renderer.py`
- `src/ansible_aom/core/tree.py`
- `tests/compact/test_task_progress.py`
- `tests/unit/test_dynamic_counters.py`

## Audit Trail

- EXTRACTED: 168 (88%)
- INFERRED: 22 (12%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*