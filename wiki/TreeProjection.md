# TreeProjection

> 131 nodes · cohesion 0.03

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
- **TestProjectionLifecycle** (11 connections) — `tests/compact/test_tree_projection_lifecycle.py`
- **._touch_row_lease()** (10 connections) — `src/ansible_aom/core/tree_projection.py`
- **.tree_lines()** (10 connections) — `src/ansible_aom/core/tree_projection.py`
- **_effective_status()** (9 connections) — `src/ansible_aom/core/tree_projection.py`
- **._recompute_inner_footer_count()** (9 connections) — `src/ansible_aom/core/tree_projection.py`
- **._touch_task_lease()** (9 connections) — `src/ansible_aom/core/tree_projection.py`
- **_seed_sticky_gap_state()** (9 connections) — `tests/compact/test_tree_projection_lifecycle.py`
- **runtime_role_from_task_name()** (8 connections) — `src/ansible_aom/core/models.py`
- **_collapse_role_path_aggressive()** (8 connections) — `src/ansible_aom/core/tree_projection.py`
- **_is_template_match()** (8 connections) — `src/ansible_aom/core/tree_projection.py`
- *... and 106 more nodes in this community*

## Relationships

- [HostRunState](HostRunState.md) (45 shared connections)
- [TaskDefinition](TaskDefinition.md) (21 shared connections)
- [Status](Status.md) (18 shared connections)
- [.from_run_state](from_run_state.md) (14 shared connections)
- [RunState](RunState.md) (11 shared connections)
- [format_tree_block](format_tree_block.md) (10 shared connections)
- [RoleGroupDefinition](RoleGroupDefinition.md) (9 shared connections)
- [_play_start](_play_start.md) (8 shared connections)
- [test_task_completion.py](test_task_completion.py.md) (5 shared connections)
- [_visible_projection](_visible_projection.md) (4 shared connections)
- [run_state.py](run_state.py.md) (3 shared connections)
- [renderer.py](renderer.py.md) (3 shared connections)

## Source Files

- `src/ansible_aom/core/models.py`
- `src/ansible_aom/core/tree.py`
- `src/ansible_aom/core/tree_projection.py`
- `tests/compact/test_tree_pipe_continuation.py`
- `tests/compact/test_tree_projection_lifecycle.py`
- `tests/unit/test_tree_projection.py`

## Audit Trail

- EXTRACTED: 679 (90%)
- INFERRED: 77 (10%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*