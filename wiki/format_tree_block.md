# format_tree_block

> 27 nodes · cohesion 0.11

## Key Concepts

- **format_tree_block()** (48 connections) — `src/ansible_aom/compact/format.py`
- **_state_with_play()** (14 connections) — `tests/compact/test_tree_large_playbook.py`
- **test_tree_large_playbook.py** (12 connections) — `tests/compact/test_tree_large_playbook.py`
- **_two_plays_with_running_tasks()** (9 connections) — `tests/compact/test_tree_pipe_continuation.py`
- **test_100_percent_completed_shows_empty_tree()** (5 connections) — `tests/compact/test_tree_large_playbook.py`
- **test_completed_tasks_removed_100_tasks_5_hosts_over_budget()** (5 connections) — `tests/compact/test_tree_large_playbook.py`
- **test_completed_tasks_removed_under_budget()** (5 connections) — `tests/compact/test_tree_large_playbook.py`
- **test_single_host_tight_budget()** (5 connections) — `tests/compact/test_tree_large_playbook.py`
- **test_tree_content_changes_as_tasks_complete()** (5 connections) — `tests/compact/test_tree_large_playbook.py`
- **test_tree_shrinks_when_unbounded_fits_budget()** (5 connections) — `tests/compact/test_tree_large_playbook.py`
- **test_ascii_mode_uses_pipe_substitute()** (5 connections) — `tests/compact/test_tree_pipe_continuation.py`
- **test_last_play_children_have_plain_indent()** (5 connections) — `tests/compact/test_tree_pipe_continuation.py`
- **test_non_last_play_children_show_vertical_pipe()** (5 connections) — `tests/compact/test_tree_pipe_continuation.py`
- **_task_def()** (3 connections) — `tests/compact/test_tree_large_playbook.py`
- **Render the tree block as a list of lines.      Returns an empty list when the pr** (1 connections) — `src/ansible_aom/compact/format.py`
- **Tree projection with large playbooks: budget saturation and completed-task remov** (1 connections) — `tests/compact/test_tree_large_playbook.py`
- **With 65/100 tasks completed (still over budget), completed tasks     must NOT ap** (1 connections) — `tests/compact/test_tree_large_playbook.py`
- **With 90/100 tasks completed (well under budget), completed tasks     must NOT ap** (1 connections) — `tests/compact/test_tree_large_playbook.py`
- **Simulate progression from task-0000 running to task-0065 running.     At each st** (1 connections) — `tests/compact/test_tree_large_playbook.py`
- **When enough tasks complete that the unbounded tree fits under     budget, the re** (1 connections) — `tests/compact/test_tree_large_playbook.py`
- **With 1 host and budget=8 (minimum), completed tasks still removed.** (1 connections) — `tests/compact/test_tree_large_playbook.py`
- **All tasks completed, no running task → tree may show just     the playbook heade** (1 connections) — `tests/compact/test_tree_large_playbook.py`
- **Build a RunState with one play of ``total`` preflight tasks.      First ``comple** (1 connections) — `tests/compact/test_tree_large_playbook.py`
- **State with two plays, each with a running task on one host.      Built directly** (1 connections) — `tests/compact/test_tree_pipe_continuation.py`
- **A task under a non-last play must be indented with ``│  ``.** (1 connections) — `tests/compact/test_tree_pipe_continuation.py`
- *... and 2 more nodes in this community*

## Relationships

- [TreeProjection](TreeProjection.md) (10 shared connections)
- [.from_run_state](from_run_state.md) (9 shared connections)
- [HostRunState](HostRunState.md) (8 shared connections)
- [_state_with_play](_state_with_play.md) (6 shared connections)
- [test_tree_render.py](test_tree_render.py.md) (5 shared connections)
- [format.py](format.py.md) (3 shared connections)
- [Get All Actions](Get_All_Actions.md) (3 shared connections)
- [_visible_projection](_visible_projection.md) (3 shared connections)
- [renderer.py](renderer.py.md) (2 shared connections)
- [_running_state](_running_state.md) (2 shared connections)
- [TaskDefinition](TaskDefinition.md) (2 shared connections)
- [PlayRunState](PlayRunState.md) (2 shared connections)

## Source Files

- `src/ansible_aom/compact/format.py`
- `tests/compact/test_tree_large_playbook.py`
- `tests/compact/test_tree_pipe_continuation.py`

## Audit Trail

- EXTRACTED: 135 (94%)
- INFERRED: 9 (6%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*