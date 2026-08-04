# TaskDefinition

> 126 nodes · cohesion 0.02

## Key Concepts

- **TaskDefinition** (357 connections) — `src/ansible_aom/core/models.py`
- **TestRoleGrouping** (21 connections) — `tests/unit/test_parser.py`
- **TestLinearForceCompletion** (15 connections) — `tests/unit/test_models.py`
- **test_dynamic_counters.py** (12 connections) — `tests/unit/test_dynamic_counters.py`
- **group_roles()** (11 connections) — `src/ansible_aom/core/parser.py`
- **TestIncludeStubHiding** (10 connections) — `tests/unit/test_tree_projection.py`
- **test_total_tasks_seen_no_cache_falls_back_to_preflight_runtime_max()** (8 connections) — `tests/unit/test_dynamic_counters.py`
- **TestTreeLinesAsyncTaskIdentity** (8 connections) — `tests/unit/test_tree_projection.py`
- **test_total_tasks_seen_includes_include_cache()** (7 connections) — `tests/unit/test_dynamic_counters.py`
- **._active_state()** (7 connections) — `tests/unit/test_tree_projection.py`
- **TestTreeProjectionCacheRefresh** (7 connections) — `tests/unit/test_tree_projection.py`
- **test_total_tasks_with_role_group_and_dynamic_children()** (6 connections) — `tests/unit/test_dynamic_counters.py`
- **._async_task_collision_state()** (6 connections) — `tests/unit/test_tree_projection.py`
- **.test_dynamic_child_graft_refreshes_role_cache()** (6 connections) — `tests/unit/test_tree_projection.py`
- **test_total_tasks_counts_dynamic_children()** (5 connections) — `tests/unit/test_dynamic_counters.py`
- **test_total_tasks_counts_import_tasks_as_static()** (5 connections) — `tests/unit/test_dynamic_counters.py`
- **test_total_tasks_multi_play_with_dynamic_children()** (5 connections) — `tests/unit/test_dynamic_counters.py`
- **test_total_tasks_no_dynamic_children()** (5 connections) — `tests/unit/test_dynamic_counters.py`
- **.test_meta_task_emits_no_events_under_free_strategy()** (5 connections) — `tests/unit/test_models.py`
- **.test_free_strategy_not_affected()** (5 connections) — `tests/unit/test_models.py`
- **.test_meta_task_force_completed_under_linear()** (5 connections) — `tests/unit/test_models.py`
- **.test_real_terminal_hosts_preserved()** (5 connections) — `tests/unit/test_models.py`
- **.test_same_play_handler_task_force_completed()** (5 connections) — `tests/unit/test_models.py`
- **.test_multi_host_all_terminal_promotes_to_completed()** (5 connections) — `tests/unit/test_models.py`
- **.test_single_host_ok_promotes_task_to_completed()** (5 connections) — `tests/unit/test_models.py`
- *... and 101 more nodes in this community*

## Relationships

- [PlayDefinition](PlayDefinition.md) (51 shared connections)
- [RunState](RunState.md) (49 shared connections)
- [RoleGroupDefinition](RoleGroupDefinition.md) (42 shared connections)
- [WarningEntry](WarningEntry.md) (35 shared connections)
- [HostRunState](HostRunState.md) (33 shared connections)
- [.from_run_state](from_run_state.md) (30 shared connections)
- [models.py](models.py.md) (27 shared connections)
- [_play_start](_play_start.md) (23 shared connections)
- [WarningType](WarningType.md) (20 shared connections)
- [TestUngroupedRoleTasksInTree](TestUngroupedRoleTasksInTree.md) (12 shared connections)
- [test_tree_classify_and_role_labels.py](test_tree_classify_and_role_labels.py.md) (10 shared connections)
- [._render_status_panel](_render_status_panel.md) (9 shared connections)

## Source Files

- `src/ansible_aom/core/models.py`
- `src/ansible_aom/core/parser.py`
- `tests/unit/test_dynamic_counters.py`
- `tests/unit/test_event_processing.py`
- `tests/unit/test_invariants_runstate_renderer.py`
- `tests/unit/test_models.py`
- `tests/unit/test_parser.py`
- `tests/unit/test_tree_projection.py`

## Audit Trail

- EXTRACTED: 509 (70%)
- INFERRED: 223 (30%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*