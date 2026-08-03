# TaskDefinition

> 270 nodes · cohesion 0.01

## Key Concepts

- **TaskDefinition** (357 connections) — `src/ansible_aom/core/models.py`
- **PlayDefinition** (323 connections) — `src/ansible_aom/core/models.py`
- **TestTaskDefinition** (24 connections) — `tests/unit/test_models.py`
- **TestRoleGrouping** (21 connections) — `tests/unit/test_parser.py`
- **TestPlayDefinition** (20 connections) — `tests/unit/test_models.py`
- **test_models.py** (18 connections) — `tests/unit/test_models.py`
- **TestTaskMatchingAlgorithm** (16 connections) — `tests/unit/test_event_processing.py`
- **TestDefinitionVsStateSeparation** (15 connections) — `tests/unit/test_models.py`
- **TestLinearForceCompletion** (15 connections) — `tests/unit/test_models.py`
- **TestTaskMatching** (15 connections) — `tests/unit/test_models.py`
- **TestRunnerTaskCompletionPromotion** (14 connections) — `tests/unit/test_models.py`
- **TestCrossPlayLookupIsolation** (13 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **TestDynamicChildrenAsPendingInTree** (13 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **test_dynamic_counters.py** (12 connections) — `tests/unit/test_dynamic_counters.py`
- **TestFreeStrategyMetaTaskVisibility** (12 connections) — `tests/unit/test_models.py`
- **TestStickyFallbackTreeRender** (12 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **group_roles()** (11 connections) — `src/ansible_aom/core/parser.py`
- **test_tree_classify_and_role_labels.py** (11 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **TestRuntimeRoleLabelTaskCountFromDefinitions** (11 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **TestHostCrossCheckDuringExecution** (10 connections) — `tests/unit/test_host_resolution.py`
- **TestClassifyRunningWithEmptyHosts** (10 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **TestIncludeStubHiding** (10 connections) — `tests/unit/test_tree_projection.py`
- **test_completed_tasks_counts_dynamic_children()** (9 connections) — `tests/unit/test_dynamic_counters.py`
- **TestDynamicChildrenRoleTotalTasks** (9 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **TestDynamicChildrenTaskRole** (9 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- *... and 245 more nodes in this community*

## Relationships

- [HostRunState](HostRunState.md) (115 shared connections)
- [.from_run_state](from_run_state.md) (113 shared connections)
- [RunState](RunState.md) (90 shared connections)
- [Status](Status.md) (86 shared connections)
- [RoleGroupDefinition](RoleGroupDefinition.md) (80 shared connections)
- [_play_start](_play_start.md) (46 shared connections)
- [TreeProjection](TreeProjection.md) (21 shared connections)
- [._render_status_panel](_render_status_panel.md) (17 shared connections)
- [IncludeCacheEntry](IncludeCacheEntry.md) (16 shared connections)
- [TestUngroupedRoleTasksInTree](TestUngroupedRoleTasksInTree.md) (16 shared connections)
- [format_preflight_summary](format_preflight_summary.md) (14 shared connections)
- [run_state.py](run_state.py.md) (11 shared connections)

## Source Files

- `src/ansible_aom/core/models.py`
- `src/ansible_aom/core/parser.py`
- `tests/unit/test_dynamic_counters.py`
- `tests/unit/test_event_processing.py`
- `tests/unit/test_host_resolution.py`
- `tests/unit/test_invariants_runstate_renderer.py`
- `tests/unit/test_models.py`
- `tests/unit/test_parser.py`
- `tests/unit/test_runner_event_fallback.py`
- `tests/unit/test_tree_classify_and_role_labels.py`
- `tests/unit/test_tree_projection.py`

## Audit Trail

- EXTRACTED: 1171 (70%)
- INFERRED: 503 (30%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*