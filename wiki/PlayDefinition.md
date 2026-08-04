# PlayDefinition

> 93 nodes · cohesion 0.03

## Key Concepts

- **PlayDefinition** (323 connections) — `src/ansible_aom/core/models.py`
- **format_preflight_summary()** (22 connections) — `src/ansible_aom/compact/format.py`
- **test_preflight_summary.py** (15 connections) — `tests/compact/test_preflight_summary.py`
- **TestDynamicChildrenAsPendingInTree** (13 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **TestStickyFallbackTreeRender** (12 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **collect_tags()** (10 connections) — `src/ansible_aom/compact/format.py`
- **TestHostCrossCheckDuringExecution** (10 connections) — `tests/unit/test_host_resolution.py`
- **TestFailedTaskRemainsVisible** (9 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **_count_tasks()** (8 connections) — `src/ansible_aom/compact/format.py`
- **TestTreeLinesDelegatedTaskIdentity** (8 connections) — `tests/unit/test_tree_projection.py`
- **TestTreeLinesNestedChildIdentity** (8 connections) — `tests/unit/test_tree_projection.py`
- **TestTreeLinesSerialWindowIdentity** (8 connections) — `tests/unit/test_tree_projection.py`
- **_td()** (7 connections) — `tests/compact/test_preflight_summary.py`
- **_td_tagged()** (7 connections) — `tests/compact/test_preflight_summary.py`
- **.test_host_leaves_for_running_dynamic_child()** (7 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **.test_sticky_2_two_plays_both_running()** (7 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **test_format_preflight_summary_counts_role_grouped_tasks()** (6 connections) — `tests/compact/test_preflight_summary.py`
- **.test_completed_dynamic_child_filtered_from_tree()** (6 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **.test_dynamic_child_under_role_header()** (6 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **.test_dynamic_children_show_pending_before_announcement()** (6 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **.test_no_duplicate_for_runtime_announced_dynamic_child()** (6 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **.test_running_dynamic_child_shows_running_status()** (6 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **.test_failed_task_with_mixed_terminal_hosts_remains_in_tree()** (6 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **.test_unreachable_task_with_mixed_terminal_hosts_remains_in_tree()** (6 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **.test_sticky_3_no_plays_running_yet_renders_all_upcoming()** (6 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- *... and 68 more nodes in this community*

## Relationships

- [TaskDefinition](TaskDefinition.md) (51 shared connections)
- [.from_run_state](from_run_state.md) (43 shared connections)
- [HostRunState](HostRunState.md) (33 shared connections)
- [RoleGroupDefinition](RoleGroupDefinition.md) (29 shared connections)
- [RunState](RunState.md) (25 shared connections)
- [_play_start](_play_start.md) (24 shared connections)
- [models.py](models.py.md) (20 shared connections)
- [WarningType](WarningType.md) (17 shared connections)
- [WarningEntry](WarningEntry.md) (17 shared connections)
- [test_tree_classify_and_role_labels.py](test_tree_classify_and_role_labels.py.md) (13 shared connections)
- [._render_status_panel](_render_status_panel.md) (9 shared connections)
- [Status](Status.md) (9 shared connections)

## Source Files

- `src/ansible_aom/compact/format.py`
- `src/ansible_aom/core/models.py`
- `tests/compact/test_preflight_summary.py`
- `tests/unit/test_host_resolution.py`
- `tests/unit/test_models.py`
- `tests/unit/test_tree_classify_and_role_labels.py`
- `tests/unit/test_tree_projection.py`

## Audit Trail

- EXTRACTED: 480 (70%)
- INFERRED: 209 (30%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*