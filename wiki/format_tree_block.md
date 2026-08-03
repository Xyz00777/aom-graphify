# format_tree_block

> 22 nodes · cohesion 0.14

## Key Concepts

- **format_tree_block()** (48 connections) — `src/ansible_aom/compact/format.py`
- **_state_with_play()** (14 connections) — `tests/compact/test_tree_upcoming_tasks.py`
- **test_tree_upcoming_tasks.py** (12 connections) — `tests/compact/test_tree_upcoming_tasks.py`
- **_two_plays_with_running_tasks()** (9 connections) — `tests/compact/test_tree_pipe_continuation.py`
- **test_ascii_mode_uses_pipe_substitute()** (5 connections) — `tests/compact/test_tree_pipe_continuation.py`
- **test_last_play_children_have_plain_indent()** (5 connections) — `tests/compact/test_tree_pipe_continuation.py`
- **test_non_last_play_children_show_vertical_pipe()** (5 connections) — `tests/compact/test_tree_pipe_continuation.py`
- **test_all_completed_falls_back_to_first_pending()** (5 connections) — `tests/compact/test_tree_upcoming_tasks.py`
- **test_upcoming_tasks_marked_pending()** (5 connections) — `tests/compact/test_tree_upcoming_tasks.py`
- **test_completed_tasks_not_in_tree()** (4 connections) — `tests/compact/test_tree_upcoming_tasks.py`
- **test_running_task_visible()** (4 connections) — `tests/compact/test_tree_upcoming_tasks.py`
- **test_upcoming_tasks_visible_after_running()** (4 connections) — `tests/compact/test_tree_upcoming_tasks.py`
- **_task_def()** (3 connections) — `tests/compact/test_tree_upcoming_tasks.py`
- **Render the tree block as a list of lines.      Returns an empty list when the pr** (1 connections) — `src/ansible_aom/compact/format.py`
- **State with two plays, each with a running task on one host.      Built directly** (1 connections) — `tests/compact/test_tree_pipe_continuation.py`
- **A task under a non-last play must be indented with ``│  ``.** (1 connections) — `tests/compact/test_tree_pipe_continuation.py`
- **A task under the last play must NOT carry a vertical pipe — the     parent is th** (1 connections) — `tests/compact/test_tree_pipe_continuation.py`
- **ASCII mode renders the continuation as ``|  `` (or equivalent)     rather than t** (1 connections) — `tests/compact/test_tree_pipe_continuation.py`
- **Tree projection shows the currently-running task plus every task yet to come in** (1 connections) — `tests/compact/test_tree_upcoming_tasks.py`
- **Pending tasks render with the PENDING status icon (□ or ASCII '.').** (1 connections) — `tests/compact/test_tree_upcoming_tasks.py`
- **All preflight tasks completed, more coming → show the next pending.** (1 connections) — `tests/compact/test_tree_upcoming_tasks.py`
- **Build a RunState with one play and one host.      ``runtime_tasks`` maps preflig** (1 connections) — `tests/compact/test_tree_upcoming_tasks.py`

## Relationships

- [HostRunState](HostRunState.md) (12 shared connections)
- [TreeProjection](TreeProjection.md) (10 shared connections)
- [.from_run_state](from_run_state.md) (10 shared connections)
- [_state_with_play](_state_with_play.md) (6 shared connections)
- [test_tree_render.py](test_tree_render.py.md) (5 shared connections)
- [format.py](format.py.md) (3 shared connections)
- [Get All Actions](Get_All_Actions.md) (3 shared connections)
- [_visible_projection](_visible_projection.md) (3 shared connections)
- [RunState](RunState.md) (2 shared connections)
- [Status](Status.md) (2 shared connections)
- [TaskDefinition](TaskDefinition.md) (2 shared connections)
- [JsonlEvent](JsonlEvent.md) (1 shared connections)

## Source Files

- `src/ansible_aom/compact/format.py`
- `tests/compact/test_tree_pipe_continuation.py`
- `tests/compact/test_tree_upcoming_tasks.py`

## Audit Trail

- EXTRACTED: 123 (93%)
- INFERRED: 9 (7%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*