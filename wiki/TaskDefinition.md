# TaskDefinition

> 205 nodes · cohesion 0.02

## Key Concepts

- **TaskDefinition** (357 connections) — `src/ansible_aom/core/models.py`
- **RoleGroupDefinition** (152 connections) — `src/ansible_aom/core/models.py`
- **TestTaskDefinition** (24 connections) — `tests/unit/test_models.py`
- **TestRoleGrouping** (21 connections) — `tests/unit/test_parser.py`
- **test_models.py** (18 connections) — `tests/unit/test_models.py`
- **TestRoleGroupDefinition** (18 connections) — `tests/unit/test_models.py`
- **TestMemoryBounds** (17 connections) — `tests/unit/test_models.py`
- **TestTaskMatchingAlgorithm** (16 connections) — `tests/unit/test_event_processing.py`
- **TestDefinitionVsStateSeparation** (15 connections) — `tests/unit/test_models.py`
- **TestLinearForceCompletion** (15 connections) — `tests/unit/test_models.py`
- **TestTaskMatching** (15 connections) — `tests/unit/test_models.py`
- **TestRunnerTaskCompletionPromotion** (14 connections) — `tests/unit/test_models.py`
- **test_tree_nested_roles.py** (14 connections) — `tests/unit/test_tree_nested_roles.py`
- **test_dynamic_counters.py** (12 connections) — `tests/unit/test_dynamic_counters.py`
- **TestFreeStrategyMetaTaskVisibility** (12 connections) — `tests/unit/test_models.py`
- **group_roles()** (11 connections) — `src/ansible_aom/core/parser.py`
- **_play_def()** (10 connections) — `tests/unit/test_tree_nested_roles.py`
- **.test_mixed_consecutive_and_nested_roles()** (10 connections) — `tests/unit/test_tree_nested_roles.py`
- **.test_nested_role_renders_as_sub_branch()** (10 connections) — `tests/unit/test_tree_nested_roles.py`
- **.test_runtime_podman_prefix_does_not_duplicate_role_header()** (10 connections) — `tests/unit/test_tree_nested_roles.py`
- **TestIncludeStubHiding** (10 connections) — `tests/unit/test_tree_projection.py`
- **_fire_startup()** (9 connections) — `tests/unit/test_tree_nested_roles.py`
- **_line_summary()** (9 connections) — `tests/unit/test_tree_nested_roles.py`
- **.test_regression_flat_role_tasks_unchanged()** (9 connections) — `tests/unit/test_tree_nested_roles.py`
- **_count_tasks()** (8 connections) — `src/ansible_aom/compact/format.py`
- *... and 180 more nodes in this community*

## Relationships

- [PlayDefinition](PlayDefinition.md) (176 shared connections)
- [HostRunState](HostRunState.md) (73 shared connections)
- [Status](Status.md) (71 shared connections)
- [RunState](RunState.md) (63 shared connections)
- [_play_start](_play_start.md) (24 shared connections)
- [TreeProjection](TreeProjection.md) (18 shared connections)
- [TestUngroupedRoleTasksInTree](TestUngroupedRoleTasksInTree.md) (15 shared connections)
- [IncludeCacheEntry](IncludeCacheEntry.md) (13 shared connections)
- [run_state.py](run_state.py.md) (12 shared connections)
- [._render_status_panel](_render_status_panel.md) (10 shared connections)
- [PriorRun](PriorRun.md) (8 shared connections)
- [JsonLineStream](JsonLineStream.md) (8 shared connections)

## Source Files

- `src/ansible_aom/compact/format.py`
- `src/ansible_aom/core/models.py`
- `src/ansible_aom/core/parser.py`
- `tests/unit/test_dynamic_counters.py`
- `tests/unit/test_event_processing.py`
- `tests/unit/test_invariants_runstate_renderer.py`
- `tests/unit/test_models.py`
- `tests/unit/test_parser.py`
- `tests/unit/test_runner_event_fallback.py`
- `tests/unit/test_tree_nested_roles.py`
- `tests/unit/test_tree_projection.py`

## Audit Trail

- EXTRACTED: 867 (67%)
- INFERRED: 430 (33%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*