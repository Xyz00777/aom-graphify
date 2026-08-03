# RoleGroupDefinition

> 77 nodes · cohesion 0.05

## Key Concepts

- **RoleGroupDefinition** (152 connections) — `src/ansible_aom/core/models.py`
- **TestRoleGroupDefinition** (18 connections) — `tests/unit/test_models.py`
- **test_tree_nested_roles.py** (14 connections) — `tests/unit/test_tree_nested_roles.py`
- **TestMultiPlayTruncationWithRoleFooters** (14 connections) — `tests/unit/test_tree_projection.py`
- **test_format_tree_block_renders_two_level_truncation()** (11 connections) — `tests/compact/test_tree_render.py`
- **_iter_leaf_task_defs()** (10 connections) — `src/ansible_aom/core/run_state.py`
- **_play_def()** (10 connections) — `tests/unit/test_tree_nested_roles.py`
- **.test_mixed_consecutive_and_nested_roles()** (10 connections) — `tests/unit/test_tree_nested_roles.py`
- **.test_nested_role_renders_as_sub_branch()** (10 connections) — `tests/unit/test_tree_nested_roles.py`
- **.test_runtime_podman_prefix_does_not_duplicate_role_header()** (10 connections) — `tests/unit/test_tree_nested_roles.py`
- **_fire_startup()** (9 connections) — `tests/unit/test_tree_nested_roles.py`
- **_line_summary()** (9 connections) — `tests/unit/test_tree_nested_roles.py`
- **.test_regression_flat_role_tasks_unchanged()** (9 connections) — `tests/unit/test_tree_nested_roles.py`
- **._multi_play_completed_state()** (9 connections) — `tests/unit/test_tree_projection.py`
- **.test_arbitrary_depth_renders_correctly()** (8 connections) — `tests/unit/test_tree_nested_roles.py`
- **.test_task_label_strips_role_prefix_and_pending_visible()** (8 connections) — `tests/unit/test_tree_nested_roles.py`
- **_fire_running_task()** (7 connections) — `tests/unit/test_tree_nested_roles.py`
- **.test_preflight_duplicate_role_header_bug()** (7 connections) — `tests/unit/test_tree_nested_roles.py`
- **.test_no_inner_footer_when_role_has_no_remaining()** (7 connections) — `tests/unit/test_tree_projection.py`
- **_iter_task_def_tree()** (6 connections) — `src/ansible_aom/core/models.py`
- **_leaves_of_role_group()** (6 connections) — `src/ansible_aom/core/run_state.py`
- **_fire_pending_task()** (6 connections) — `tests/unit/test_tree_nested_roles.py`
- **TestArbitraryDepthRendersCorrectly** (6 connections) — `tests/unit/test_tree_nested_roles.py`
- **TestFlatRoleTasksUnchanged** (6 connections) — `tests/unit/test_tree_nested_roles.py`
- **TestMixedConsecutiveAndNestedRoles** (6 connections) — `tests/unit/test_tree_nested_roles.py`
- *... and 52 more nodes in this community*

## Relationships

- [TaskDefinition](TaskDefinition.md) (73 shared connections)
- [.from_run_state](from_run_state.md) (21 shared connections)
- [StreamPhase](StreamPhase.md) (17 shared connections)
- [RunState](RunState.md) (16 shared connections)
- [WarningEntry](WarningEntry.md) (11 shared connections)
- [TreeProjection](TreeProjection.md) (10 shared connections)
- [JsonlEvent](JsonlEvent.md) (7 shared connections)
- [HostRunState](HostRunState.md) (7 shared connections)
- [TestRoleGrouping](TestRoleGrouping.md) (6 shared connections)
- [PlayRunState](PlayRunState.md) (5 shared connections)
- [TestSubtreeRoleCounting](TestSubtreeRoleCounting.md) (5 shared connections)
- [TestTwoLevelTruncation](TestTwoLevelTruncation.md) (5 shared connections)

## Source Files

- `src/ansible_aom/core/models.py`
- `src/ansible_aom/core/run_state.py`
- `tests/compact/test_tree_render.py`
- `tests/unit/test_models.py`
- `tests/unit/test_tree_nested_roles.py`
- `tests/unit/test_tree_projection.py`

## Audit Trail

- EXTRACTED: 342 (70%)
- INFERRED: 145 (30%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*