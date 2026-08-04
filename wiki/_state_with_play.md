# _state_with_play

> 17 nodes · cohesion 0.17

## Key Concepts

- **_state_with_play()** (14 connections) — `tests/compact/test_tree_large_playbook.py`
- **test_tree_large_playbook.py** (12 connections) — `tests/compact/test_tree_large_playbook.py`
- **test_100_percent_completed_shows_empty_tree()** (5 connections) — `tests/compact/test_tree_large_playbook.py`
- **test_completed_tasks_removed_100_tasks_5_hosts_over_budget()** (5 connections) — `tests/compact/test_tree_large_playbook.py`
- **test_completed_tasks_removed_under_budget()** (5 connections) — `tests/compact/test_tree_large_playbook.py`
- **test_single_host_tight_budget()** (5 connections) — `tests/compact/test_tree_large_playbook.py`
- **test_tree_content_changes_as_tasks_complete()** (5 connections) — `tests/compact/test_tree_large_playbook.py`
- **test_tree_shrinks_when_unbounded_fits_budget()** (5 connections) — `tests/compact/test_tree_large_playbook.py`
- **_task_def()** (3 connections) — `tests/compact/test_tree_large_playbook.py`
- **Tree projection with large playbooks: budget saturation and completed-task remov** (1 connections) — `tests/compact/test_tree_large_playbook.py`
- **With 65/100 tasks completed (still over budget), completed tasks     must NOT ap** (1 connections) — `tests/compact/test_tree_large_playbook.py`
- **With 90/100 tasks completed (well under budget), completed tasks     must NOT ap** (1 connections) — `tests/compact/test_tree_large_playbook.py`
- **Simulate progression from task-0000 running to task-0065 running.     At each st** (1 connections) — `tests/compact/test_tree_large_playbook.py`
- **When enough tasks complete that the unbounded tree fits under     budget, the re** (1 connections) — `tests/compact/test_tree_large_playbook.py`
- **With 1 host and budget=8 (minimum), completed tasks still removed.** (1 connections) — `tests/compact/test_tree_large_playbook.py`
- **All tasks completed, no running task → tree may show just     the playbook heade** (1 connections) — `tests/compact/test_tree_large_playbook.py`
- **Build a RunState with one play of ``total`` preflight tasks.      First ``comple** (1 connections) — `tests/compact/test_tree_large_playbook.py`

## Relationships

- [PlayDefinition](PlayDefinition.md) (7 shared connections)
- [format_tree_block](format_tree_block.md) (6 shared connections)
- [HostRunState](HostRunState.md) (3 shared connections)
- [format.py](format.py.md) (1 shared connections)
- [Status](Status.md) (1 shared connections)
- [TreeProjection](TreeProjection.md) (1 shared connections)
- [RunState](RunState.md) (1 shared connections)
- [TaskDefinition](TaskDefinition.md) (1 shared connections)

## Source Files

- `tests/compact/test_tree_large_playbook.py`

## Audit Trail

- EXTRACTED: 67 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*