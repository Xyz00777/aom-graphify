# TestCrossPlayLookupIsolation

> 14 nodes · cohesion 0.16

## Key Concepts

- **TestCrossPlayLookupIsolation** (13 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **._active_play_shared_task_state()** (7 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **._multi_play_shared_task_state()** (6 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **.test_completed_play_no_stale_pending_handler_tasks()** (6 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **.test_own_running_task_still_renders_with_cross_play()** (6 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **.test_completed_play_skipped_when_other_play_running()** (4 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **.test_include_cross_play_true_does_not_borrow_same_name_rows()** (4 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **Build a state where play 1 stays active and play 2 shares a task         name th** (1 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **TC-CROSS-2: When play 2 has a RUNNING task, a previously completed         play** (1 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **TC-CROSS-1: When handler tasks run under a different play UUID,         the hand** (1 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **TC-CROSS-3: A play with its own RUNNING task renders correctly         using cro** (1 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **TC-CROSS-4: ``_play_running_and_pending(play, include_cross_play=True)``** (1 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **TC-CROSS: Cross-play runtime_by_name lookup must not pollute the     ``any_runni** (1 connections) — `tests/unit/test_tree_classify_and_role_labels.py`
- **Build a state with two plays sharing task name "Cleanup tasks".          Play 1** (1 connections) — `tests/unit/test_tree_classify_and_role_labels.py`

## Relationships

- [TaskDefinition](TaskDefinition.md) (5 shared connections)
- [PlayDefinition](PlayDefinition.md) (5 shared connections)
- [RunState](RunState.md) (4 shared connections)
- [.from_run_state](from_run_state.md) (4 shared connections)
- [HostRunState](HostRunState.md) (2 shared connections)
- [Status](Status.md) (1 shared connections)
- [RoleGroupDefinition](RoleGroupDefinition.md) (1 shared connections)
- [test_tree_classify_and_role_labels.py](test_tree_classify_and_role_labels.py.md) (1 shared connections)

## Source Files

- `tests/unit/test_tree_classify_and_role_labels.py`

## Audit Trail

- EXTRACTED: 48 (91%)
- INFERRED: 5 (9%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*