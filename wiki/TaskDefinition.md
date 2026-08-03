# TaskDefinition

> 158 nodes · cohesion 0.02

## Key Concepts

- **TaskDefinition** (357 connections) — `src/ansible_aom/core/models.py`
- **PlayDefinition** (323 connections) — `src/ansible_aom/core/models.py`
- **test_tree_projection.py** (28 connections) — `tests/unit/test_tree_projection.py`
- **count_total_tasks()** (17 connections) — `src/ansible_aom/compact/format.py`
- **TestCrossPlayLookupIsolation** (13 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **TestDynamicChildrenAsPendingInTree** (13 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **test_dynamic_counters.py** (12 connections) — `tests/unit/test_dynamic_counters.py`
- **TestStickyFallbackTreeRender** (12 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **test_tree_classify_and_role_labels.py** (11 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **TestIncludeStubHiding** (10 connections) — `tests/unit/test_tree_projection.py`
- **TestDynamicChildrenRoleTotalTasks** (9 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **TestDynamicChildrenTaskRole** (9 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **TestFailedTaskRemainsVisible** (9 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **TestTreeKindIncludesMore** (9 connections) — `tests/unit/test_tree_projection.py`
- **TestTreeLineIdentity** (9 connections) — `tests/unit/test_tree_projection.py`
- **_count_tasks()** (8 connections) — `src/ansible_aom/compact/format.py`
- **test_total_tasks_seen_no_cache_falls_back_to_preflight_runtime_max()** (8 connections) — `tests/unit/test_dynamic_counters.py`
- **TestTreeLinesAsyncTaskIdentity** (8 connections) — `tests/unit/test_tree_projection.py`
- **TestTreeLinesDelegatedTaskIdentity** (8 connections) — `tests/unit/test_tree_projection.py`
- **TestTreeLinesGroupedRoleNestedChildren** (8 connections) — `tests/unit/test_tree_projection.py`
- **TestTreeLinesNestedChildIdentity** (8 connections) — `tests/unit/test_tree_projection.py`
- **TestTreeLinesPlayIdentity** (8 connections) — `tests/unit/test_tree_projection.py`
- **TestTreeLinesPreflightTaskIdentity** (8 connections) — `tests/unit/test_tree_projection.py`
- **TestTreeLinesSerialWindowIdentity** (8 connections) — `tests/unit/test_tree_projection.py`
- **TestTreeLinesTaskIdentity** (8 connections) — `tests/unit/test_tree_projection.py`
- *... and 133 more nodes in this community*

## Relationships

- [RoleGroupDefinition](RoleGroupDefinition.md) (73 shared connections)
- [RunState](RunState.md) (71 shared connections)
- [.from_run_state](from_run_state.md) (69 shared connections)
- [Status](Status.md) (46 shared connections)
- [HostRunState](HostRunState.md) (39 shared connections)
- [WarningEntry](WarningEntry.md) (39 shared connections)
- [IncludeCacheEntry](IncludeCacheEntry.md) (37 shared connections)
- [_play_start](_play_start.md) (36 shared connections)
- [StreamPhase](StreamPhase.md) (31 shared connections)
- [format_preflight_summary](format_preflight_summary.md) (17 shared connections)
- [TreeProjection](TreeProjection.md) (17 shared connections)
- [test_event_processing.py](test_event_processing.py.md) (17 shared connections)

## Source Files

- `src/ansible_aom/compact/format.py`
- `src/ansible_aom/core/models.py`
- `tests/unit/test_dynamic_counters.py`
- `tests/unit/test_invariants_runstate_renderer.py`
- `tests/unit/test_models.py`
- `tests/unit/test_tree_classify_and_role_labels.py`
- `tests/unit/test_tree_projection.py`

## Audit Trail

- EXTRACTED: 903 (68%)
- INFERRED: 431 (32%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*