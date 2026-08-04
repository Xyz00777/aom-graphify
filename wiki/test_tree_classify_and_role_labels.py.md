# test_tree_classify_and_role_labels.py

> 32 nodes · cohesion 0.07

## Key Concepts

- **test_tree_classify_and_role_labels.py** (11 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **TestRuntimeRoleLabelTaskCountFromDefinitions** (11 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **TestClassifyRunningWithEmptyHosts** (10 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **TestDynamicChildrenRoleTotalTasks** (9 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **TestDynamicChildrenTaskRole** (9 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **._multi_task_role_with_completed_task()** (9 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **._running_task_no_hosts_state()** (7 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **.test_dynamic_child_task_appears_under_role_header()** (7 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **.test_role_with_preflight_and_dynamic_children_count()** (7 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **.test_dynamic_child_stripped_prefix_also_finds_role()** (6 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **.test_dynamic_child_under_role_returns_correct_role()** (6 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **.test_running_task_with_empty_hosts_appears_in_tree()** (4 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **.test_running_task_with_empty_hosts_shows_running_icon()** (4 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **.test_role_label_count_is_stable_as_tasks_complete()** (4 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **.test_role_label_count_with_all_tasks_completed()** (4 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **.test_role_label_shows_total_task_count_not_running_count()** (4 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **Regression tests for tree projection bugs:  1. _classify must treat RUNNING task** (1 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **Regression guard: role labels in the runtime play must show the     total task c** (1 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **Build a state where one role task is completed and another is         running. T** (1 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **When a role has 2 tasks and 1 is completed, the runtime role         label shows** (1 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **When all role tasks are completed (none running, none pending),         the runt** (1 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **Regression guard: a task with RUNNING status but no host entries yet     (e.g. b** (1 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **Regression for the '(M remaining) goes UP as tasks complete' bug.          The r** (1 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **TC-300: _task_role must index TaskDefinition.children (grafted     include_tasks** (1 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **Dynamic grafted child under role 'nginx' → _task_role("Dynamic task")         re** (1 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- *... and 7 more nodes in this community*

## Relationships

- [PlayDefinition](PlayDefinition.md) (13 shared connections)
- [TaskDefinition](TaskDefinition.md) (10 shared connections)
- [.from_run_state](from_run_state.md) (9 shared connections)
- [HostRunState](HostRunState.md) (6 shared connections)
- [RunState](RunState.md) (6 shared connections)
- [RoleGroupDefinition](RoleGroupDefinition.md) (5 shared connections)
- [Status](Status.md) (4 shared connections)
- [models.py](models.py.md) (1 shared connections)
- [TreeProjection](TreeProjection.md) (1 shared connections)
- [TestCrossPlayLookupIsolation](TestCrossPlayLookupIsolation.md) (1 shared connections)

## Source Files

- `tests/unit/test_tree_classify_and_role_labels.py`

## Audit Trail

- EXTRACTED: 108 (84%)
- INFERRED: 20 (16%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*