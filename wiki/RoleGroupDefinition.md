# RoleGroupDefinition

> 74 nodes · cohesion 0.05

## Key Concepts

- **RoleGroupDefinition** (152 connections) — `src/ansible_aom/core/models.py`
- **TestRoleGroupDefinition** (18 connections) — `tests/unit/test_models.py`
- **test_tree_nested_roles.py** (14 connections) — `tests/unit/test_tree_nested_roles.py`
- **_iter_leaf_task_defs()** (10 connections) — `src/ansible_aom/core/run_state.py`
- **_play_def()** (10 connections) — `tests/unit/test_tree_nested_roles.py`
- **.test_mixed_consecutive_and_nested_roles()** (10 connections) — `tests/unit/test_tree_nested_roles.py`
- **.test_nested_role_renders_as_sub_branch()** (10 connections) — `tests/unit/test_tree_nested_roles.py`
- **.test_runtime_podman_prefix_does_not_duplicate_role_header()** (10 connections) — `tests/unit/test_tree_nested_roles.py`
- **_fire_startup()** (9 connections) — `tests/unit/test_tree_nested_roles.py`
- **_line_summary()** (9 connections) — `tests/unit/test_tree_nested_roles.py`
- **.test_regression_flat_role_tasks_unchanged()** (9 connections) — `tests/unit/test_tree_nested_roles.py`
- **.test_arbitrary_depth_renders_correctly()** (8 connections) — `tests/unit/test_tree_nested_roles.py`
- **.test_task_label_strips_role_prefix_and_pending_visible()** (8 connections) — `tests/unit/test_tree_nested_roles.py`
- **TestDataclassShapes** (8 connections) — `tests/unit/test_tree_projection.py`
- **TestTreeLinesGroupedRoleNestedChildren** (8 connections) — `tests/unit/test_tree_projection.py`
- **count_leaf_tasks()** (7 connections) — `src/ansible_aom/core/run_state.py`
- **_fire_running_task()** (7 connections) — `tests/unit/test_tree_nested_roles.py`
- **.test_preflight_duplicate_role_header_bug()** (7 connections) — `tests/unit/test_tree_nested_roles.py`
- **_iter_task_def_tree()** (6 connections) — `src/ansible_aom/core/models.py`
- **_leaves_of_role_group()** (6 connections) — `src/ansible_aom/core/run_state.py`
- **_fire_pending_task()** (6 connections) — `tests/unit/test_tree_nested_roles.py`
- **TestArbitraryDepthRendersCorrectly** (6 connections) — `tests/unit/test_tree_nested_roles.py`
- **TestFlatRoleTasksUnchanged** (6 connections) — `tests/unit/test_tree_nested_roles.py`
- **TestMixedConsecutiveAndNestedRoles** (6 connections) — `tests/unit/test_tree_nested_roles.py`
- **TestNestedRoleRendersAsSubBranch** (6 connections) — `tests/unit/test_tree_nested_roles.py`
- *... and 49 more nodes in this community*

## Relationships

- [TaskDefinition](TaskDefinition.md) (42 shared connections)
- [PlayDefinition](PlayDefinition.md) (29 shared connections)
- [.from_run_state](from_run_state.md) (25 shared connections)
- [WarningType](WarningType.md) (18 shared connections)
- [RunState](RunState.md) (15 shared connections)
- [models.py](models.py.md) (12 shared connections)
- [WarningEntry](WarningEntry.md) (12 shared connections)
- [HostRunState](HostRunState.md) (11 shared connections)
- [TreeProjection](TreeProjection.md) (10 shared connections)
- [Status](Status.md) (5 shared connections)
- [test_tree_classify_and_role_labels.py](test_tree_classify_and_role_labels.py.md) (5 shared connections)
- [TestSubtreeRoleCounting](TestSubtreeRoleCounting.md) (5 shared connections)

## Source Files

- `src/ansible_aom/compact/format.py`
- `src/ansible_aom/core/models.py`
- `src/ansible_aom/core/run_state.py`
- `tests/unit/test_models.py`
- `tests/unit/test_tree_nested_roles.py`
- `tests/unit/test_tree_projection.py`

## Audit Trail

- EXTRACTED: 314 (67%)
- INFERRED: 154 (33%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*