# PlayDefinition

> 269 nodes · cohesion 0.01

## Key Concepts

- **PlayDefinition** (323 connections) — `src/ansible_aom/core/models.py`
- **.from_run_state()** (199 connections) — `src/ansible_aom/core/tree_projection.py`
- **test_tree_projection.py** (28 connections) — `tests/unit/test_tree_projection.py`
- **TestPlayDefinition** (20 connections) — `tests/unit/test_models.py`
- **TestHostRows** (19 connections) — `tests/unit/test_tree_projection.py`
- **TestTwoLevelTruncation** (17 connections) — `tests/unit/test_tree_projection.py`
- **TestTreeLinesBasic** (16 connections) — `tests/unit/test_tree_projection.py`
- **TestMultiPlayTruncationWithRoleFooters** (14 connections) — `tests/unit/test_tree_projection.py`
- **._many_tasks_state()** (14 connections) — `tests/unit/test_tree_projection.py`
- **TestSubtreeRoleCounting** (14 connections) — `tests/unit/test_tree_projection.py`
- **TestCrossPlayLookupIsolation** (13 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **TestDynamicChildrenAsPendingInTree** (13 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **TestStickyFallbackTreeRender** (12 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **TestRoleLabelsAfterTruncation** (12 connections) — `tests/unit/test_tree_projection.py`
- **test_tree_classify_and_role_labels.py** (11 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **TestRuntimeRoleLabelTaskCountFromDefinitions** (11 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **TestMultiLevelInnerFooters** (11 connections) — `tests/unit/test_tree_projection.py`
- **._nested_state()** (11 connections) — `tests/unit/test_tree_projection.py`
- **TestTreeLinesPruning** (11 connections) — `tests/unit/test_tree_projection.py`
- **TestTreeLinesRolesAndFanOut** (11 connections) — `tests/unit/test_tree_projection.py`
- **._single_play_single_role_state()** (11 connections) — `tests/unit/test_tree_projection.py`
- **TestClassifyRunningWithEmptyHosts** (10 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **._multi_host_state()** (10 connections) — `tests/unit/test_tree_projection.py`
- **TestVisibility** (10 connections) — `tests/unit/test_tree_projection.py`
- **_running_state()** (9 connections) — `tests/compact/test_spinner_animation.py`
- *... and 244 more nodes in this community*

## Relationships

- [TaskDefinition](TaskDefinition.md) (176 shared connections)
- [RunState](RunState.md) (76 shared connections)
- [HostRunState](HostRunState.md) (75 shared connections)
- [Status](Status.md) (51 shared connections)
- [_play_start](_play_start.md) (23 shared connections)
- [TreeProjection](TreeProjection.md) (17 shared connections)
- [TestUngroupedRoleTasksInTree](TestUngroupedRoleTasksInTree.md) (15 shared connections)
- [PriorRun](PriorRun.md) (13 shared connections)
- [TestTaskCompletionLifecycle](TestTaskCompletionLifecycle.md) (13 shared connections)
- [format_host_rows](format_host_rows.md) (12 shared connections)
- [format_tree_block](format_tree_block.md) (11 shared connections)
- [TestTemplateVariableNameMismatch](TestTemplateVariableNameMismatch.md) (11 shared connections)

## Source Files

- `src/ansible_aom/core/models.py`
- `src/ansible_aom/core/tree_projection.py`
- `tests/compact/test_spinner_animation.py`
- `tests/unit/test_loop_item_count.py`
- `tests/unit/test_models.py`
- `tests/unit/test_tree_classify_and_role_labels.py`
- `tests/unit/test_tree_meta_hostless.py`
- `tests/unit/test_tree_projection.py`

## Audit Trail

- EXTRACTED: 1340 (82%)
- INFERRED: 291 (18%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*