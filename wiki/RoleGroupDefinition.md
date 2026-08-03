# RoleGroupDefinition

> 79 nodes · cohesion 0.04

## Key Concepts

- **RoleGroupDefinition** (152 connections) — `src/ansible_aom/core/models.py`
- **TestRoleGroupDefinition** (18 connections) — `tests/unit/test_models.py`
- **TestMemoryBounds** (17 connections) — `tests/unit/test_models.py`
- **test_tree_nested_roles.py** (14 connections) — `tests/unit/test_tree_nested_roles.py`
- **test_format_tree_block_renders_two_level_truncation()** (11 connections) — `tests/compact/test_tree_render.py`
- **_play_def()** (10 connections) — `tests/unit/test_tree_nested_roles.py`
- **.test_mixed_consecutive_and_nested_roles()** (10 connections) — `tests/unit/test_tree_nested_roles.py`
- **.test_nested_role_renders_as_sub_branch()** (10 connections) — `tests/unit/test_tree_nested_roles.py`
- **.test_runtime_podman_prefix_does_not_duplicate_role_header()** (10 connections) — `tests/unit/test_tree_nested_roles.py`
- **_fire_startup()** (9 connections) — `tests/unit/test_tree_nested_roles.py`
- **_line_summary()** (9 connections) — `tests/unit/test_tree_nested_roles.py`
- **.test_regression_flat_role_tasks_unchanged()** (9 connections) — `tests/unit/test_tree_nested_roles.py`
- **TestTreeKindIncludesMore** (9 connections) — `tests/unit/test_tree_projection.py`
- **_count_tasks()** (8 connections) — `src/ansible_aom/compact/format.py`
- **.test_arbitrary_depth_renders_correctly()** (8 connections) — `tests/unit/test_tree_nested_roles.py`
- **.test_task_label_strips_role_prefix_and_pending_visible()** (8 connections) — `tests/unit/test_tree_nested_roles.py`
- **TestTreeLinesGroupedRoleNestedChildren** (8 connections) — `tests/unit/test_tree_projection.py`
- **_fire_running_task()** (7 connections) — `tests/unit/test_tree_nested_roles.py`
- **.test_preflight_duplicate_role_header_bug()** (7 connections) — `tests/unit/test_tree_nested_roles.py`
- **.test_total_host_run_state_entries()** (6 connections) — `tests/unit/test_models.py`
- **_fire_pending_task()** (6 connections) — `tests/unit/test_tree_nested_roles.py`
- **TestArbitraryDepthRendersCorrectly** (6 connections) — `tests/unit/test_tree_nested_roles.py`
- **TestFlatRoleTasksUnchanged** (6 connections) — `tests/unit/test_tree_nested_roles.py`
- **TestMixedConsecutiveAndNestedRoles** (6 connections) — `tests/unit/test_tree_nested_roles.py`
- **TestNestedRoleRendersAsSubBranch** (6 connections) — `tests/unit/test_tree_nested_roles.py`
- *... and 54 more nodes in this community*

## Relationships

- [TaskDefinition](TaskDefinition.md) (80 shared connections)
- [.from_run_state](from_run_state.md) (39 shared connections)
- [Status](Status.md) (29 shared connections)
- [HostRunState](HostRunState.md) (23 shared connections)
- [RunState](RunState.md) (17 shared connections)
- [TreeProjection](TreeProjection.md) (9 shared connections)
- [run_state.py](run_state.py.md) (6 shared connections)
- [format_preflight_summary](format_preflight_summary.md) (5 shared connections)
- [format.py](format.py.md) (3 shared connections)
- [IncludeCacheEntry](IncludeCacheEntry.md) (3 shared connections)
- [TestUngroupedRoleTasksInTree](TestUngroupedRoleTasksInTree.md) (3 shared connections)
- [StreamPhase](StreamPhase.md) (2 shared connections)

## Source Files

- `src/ansible_aom/compact/format.py`
- `src/ansible_aom/core/models.py`
- `tests/compact/test_tree_render.py`
- `tests/unit/test_models.py`
- `tests/unit/test_tree_nested_roles.py`
- `tests/unit/test_tree_projection.py`

## Audit Trail

- EXTRACTED: 327 (67%)
- INFERRED: 163 (33%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*