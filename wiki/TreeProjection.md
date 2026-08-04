# TreeProjection

> 122 nodes · cohesion 0.04

## Key Concepts

- **TreeProjection** (62 connections) — `src/ansible_aom/core/tree_projection.py`
- **tree.py** (48 connections) — `src/ansible_aom/core/tree.py`
- **tree_projection.py** (42 connections) — `src/ansible_aom/core/tree_projection.py`
- **TreeLine** (38 connections) — `src/ansible_aom/core/tree_projection.py`
- **._emit_runtime_play()** (27 connections) — `src/ansible_aom/core/tree_projection.py`
- **strip_role_prefix()** (15 connections) — `src/ansible_aom/core/models.py`
- **datetime** (15 connections)
- **._tree_lines_unbounded()** (14 connections) — `src/ansible_aom/core/tree_projection.py`
- **HostRow** (13 connections) — `src/ansible_aom/core/tree_projection.py`
- **test_tree_pipe_continuation.py** (13 connections) — `tests/compact/test_tree_pipe_continuation.py`
- **iter_preflight_task_defs()** (12 connections) — `src/ansible_aom/core/models.py`
- **_RowLease** (12 connections) — `src/ansible_aom/core/tree_projection.py`
- **._build_role_total_tasks()** (12 connections) — `src/ansible_aom/core/tree_projection.py`
- **_spur_projection()** (12 connections) — `tests/compact/test_tree_pipe_continuation.py`
- **._emit_pending_play()** (11 connections) — `src/ansible_aom/core/tree_projection.py`
- **._touch_row_lease()** (10 connections) — `src/ansible_aom/core/tree_projection.py`
- **.tree_lines()** (10 connections) — `src/ansible_aom/core/tree_projection.py`
- **TestTreeLineHasTailAfter** (10 connections) — `tests/unit/test_tree_projection.py`
- **_effective_status()** (9 connections) — `src/ansible_aom/core/tree_projection.py`
- **._recompute_inner_footer_count()** (9 connections) — `src/ansible_aom/core/tree_projection.py`
- **._touch_task_lease()** (9 connections) — `src/ansible_aom/core/tree_projection.py`
- **runtime_role_from_task_name()** (8 connections) — `src/ansible_aom/core/models.py`
- **_collapse_role_path_aggressive()** (8 connections) — `src/ansible_aom/core/tree_projection.py`
- **_is_template_match()** (8 connections) — `src/ansible_aom/core/tree_projection.py`
- **.host_rows()** (8 connections) — `src/ansible_aom/core/tree_projection.py`
- *... and 97 more nodes in this community*

## Relationships

- [HostRunState](HostRunState.md) (37 shared connections)
- [models.py](models.py.md) (11 shared connections)
- [RoleGroupDefinition](RoleGroupDefinition.md) (10 shared connections)
- [RunState](RunState.md) (10 shared connections)
- [Status](Status.md) (10 shared connections)
- [format_tree_block](format_tree_block.md) (10 shared connections)
- [_play_start](_play_start.md) (9 shared connections)
- [TaskDefinition](TaskDefinition.md) (7 shared connections)
- [.from_run_state](from_run_state.md) (7 shared connections)
- [PlayDefinition](PlayDefinition.md) (6 shared connections)
- [test_task_completion.py](test_task_completion.py.md) (5 shared connections)
- [run_state_status_counts](run_state_status_counts.md) (4 shared connections)

## Source Files

- `src/ansible_aom/core/models.py`
- `src/ansible_aom/core/tree.py`
- `src/ansible_aom/core/tree_projection.py`
- `tests/compact/test_tree_pipe_continuation.py`
- `tests/unit/test_tree_projection.py`

## Audit Trail

- EXTRACTED: 642 (91%)
- INFERRED: 66 (9%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*