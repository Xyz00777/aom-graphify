# HostRunState

> 127 nodes · cohesion 0.03

## Key Concepts

- **HostRunState** (285 connections) — `src/ansible_aom/core/models.py`
- **TaskRunState** (244 connections) — `src/ansible_aom/core/models.py`
- **TestHostRunState** (22 connections) — `tests/unit/test_models.py`
- **TestTaskRunState** (20 connections) — `tests/unit/test_models.py`
- **determine_exit_code()** (19 connections) — `src/ansible_aom/core/exit_code.py`
- **test_tree_upcoming_plays.py** (15 connections) — `tests/compact/test_tree_upcoming_plays.py`
- **TestExitCodes** (15 connections) — `tests/integration/test_compact_renderer.py`
- **TestExitCode1** (13 connections) — `tests/unit/test_cli.py`
- **TestExitCode2** (13 connections) — `tests/unit/test_cli.py`
- **parity.py** (10 connections) — `src/ansible_aom/core/parity.py`
- **_state_first_play_running()** (10 connections) — `tests/compact/test_tree_upcoming_plays.py`
- **test_completed_tasks_counts_dynamic_children()** (9 connections) — `tests/unit/test_dynamic_counters.py`
- **TestHostRowsCurrentTask** (9 connections) — `tests/unit/test_stale_running_cleanup.py`
- **core/exit_code.py** (8 connections) — `src/ansible_aom/core/exit_code.py`
- **reduce_state_for_parity()** (8 connections) — `src/ansible_aom/core/parity.py`
- **test_host_leaves_dropped_when_budget_tight()** (8 connections) — `tests/compact/test_tree_upcoming_plays.py`
- **test_no_preflight_no_upcoming_plays()** (8 connections) — `tests/compact/test_tree_upcoming_plays.py`
- **test_tree_lines_respects_budget_with_many_pending_tasks()** (8 connections) — `tests/compact/test_tree_upcoming_plays.py`
- **test_tree_lines_respects_budget_with_upcoming_plays()** (8 connections) — `tests/compact/test_tree_upcoming_plays.py`
- **.test_host_rows_clears_current_task_when_all_tasks_complete()** (8 connections) — `tests/unit/test_stale_running_cleanup.py`
- **.test_host_rows_shows_running_task_while_host_is_running()** (8 connections) — `tests/unit/test_stale_running_cleanup.py`
- **test_count_completed_tasks_counts_skipped_and_unreachable_results()** (7 connections) — `tests/compact/test_task_progress.py`
- **test_count_completed_tasks_counts_tasks_with_host_results()** (7 connections) — `tests/compact/test_task_progress.py`
- **test_count_completed_tasks_excludes_tasks_with_running_hosts()** (7 connections) — `tests/compact/test_task_progress.py`
- **_play_def()** (7 connections) — `tests/compact/test_tree_upcoming_plays.py`
- *... and 102 more nodes in this community*

## Relationships

- [Status](Status.md) (73 shared connections)
- [PlayRunState](PlayRunState.md) (51 shared connections)
- [WarningType](WarningType.md) (39 shared connections)
- [TaskDefinition](TaskDefinition.md) (39 shared connections)
- [test_event_processing.py](test_event_processing.py.md) (36 shared connections)
- [RunState](RunState.md) (32 shared connections)
- [StreamPhase](StreamPhase.md) (28 shared connections)
- [WarningEntry](WarningEntry.md) (24 shared connections)
- [TreeProjection](TreeProjection.md) (23 shared connections)
- [.from_run_state](from_run_state.md) (18 shared connections)
- [format_failure_recap](format_failure_recap.md) (16 shared connections)
- [create_parser](create_parser.md) (16 shared connections)

## Source Files

- `src/ansible_aom/compact/exit_code.py`
- `src/ansible_aom/core/exit_code.py`
- `src/ansible_aom/core/models.py`
- `src/ansible_aom/core/parity.py`
- `tests/compact/test_task_progress.py`
- `tests/compact/test_tree_render.py`
- `tests/compact/test_tree_upcoming_plays.py`
- `tests/integration/test_compact_renderer.py`
- `tests/unit/test_cli.py`
- `tests/unit/test_dynamic_counters.py`
- `tests/unit/test_models.py`
- `tests/unit/test_stale_running_cleanup.py`

## Audit Trail

- EXTRACTED: 539 (53%)
- INFERRED: 471 (47%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*