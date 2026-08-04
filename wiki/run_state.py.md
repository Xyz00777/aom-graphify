# run_state.py

> 32 nodes · cohesion 0.08

## Key Concepts

- **run_state.py** (63 connections) — `src/ansible_aom/core/run_state.py`
- **_BoundedDict** (18 connections) — `src/ansible_aom/core/run_state.py`
- **_BoundedSet** (18 connections) — `src/ansible_aom/core/run_state.py`
- **_iter_leaf_task_defs()** (10 connections) — `src/ansible_aom/core/run_state.py`
- **JsonlHostResult** (8 connections) — `src/ansible_aom/core/event_types.py`
- **JsonlPlay** (8 connections) — `src/ansible_aom/core/event_types.py`
- **count_leaf_tasks()** (7 connections) — `src/ansible_aom/core/run_state.py`
- **_iter_task_def_tree()** (6 connections) — `src/ansible_aom/core/models.py`
- **_leaves_of_role_group()** (6 connections) — `src/ansible_aom/core/run_state.py`
- **TypedDict** (5 connections)
- **_parse_play_window_start()** (4 connections) — `src/ansible_aom/core/run_state.py`
- **._rebuild_definition_indexes()** (4 connections) — `src/ansible_aom/core/run_state.py`
- **.__setattr__()** (4 connections) — `src/ansible_aom/core/run_state.py`
- **_extract_role_from_include_stub()** (3 connections) — `src/ansible_aom/core/run_state.py`
- **.__init__()** (2 connections) — `src/ansible_aom/core/run_state.py`
- **.__init__()** (2 connections) — `src/ansible_aom/core/run_state.py`
- **dict** (1 connections)
- **Subset of the ``play`` field on ``v2_playbook_on_play_start`` and friends.** (1 connections) — `src/ansible_aom/core/event_types.py`
- **Per-host result embedded in ``hosts`` dicts on ``v2_runner_on_*``.      The shap** (1 connections) — `src/ansible_aom/core/event_types.py`
- **Yield a TaskDefinition and all nested TaskDefinition.children in order.** (1 connections) — `src/ansible_aom/core/models.py`
- **.__setitem__()** (1 connections) — `src/ansible_aom/core/run_state.py`
- **Any** (1 connections)
- **set** (1 connections)
- **RunState: the mutable, in-memory execution state for an AOM run.  This module ow** (1 connections) — `src/ansible_aom/core/run_state.py`
- **Flatten preflight definitions into the leaf TaskDefinitions visible by name.** (1 connections) — `src/ansible_aom/core/run_state.py`
- *... and 7 more nodes in this community*

## Relationships

- [RunState](RunState.md) (13 shared connections)
- [TaskDefinition](TaskDefinition.md) (12 shared connections)
- [HostRunState](HostRunState.md) (9 shared connections)
- [JsonlEvent](JsonlEvent.md) (8 shared connections)
- [Status](Status.md) (7 shared connections)
- [IncludeCacheEntry](IncludeCacheEntry.md) (6 shared connections)
- [PlayDefinition](PlayDefinition.md) (6 shared connections)
- [event_types.py](event_types.py.md) (5 shared connections)
- [TreeProjection](TreeProjection.md) (3 shared connections)
- [RoleCacheEntry](RoleCacheEntry.md) (3 shared connections)
- [test_run_state_memory_bounds.py](test_run_state_memory_bounds.py.md) (3 shared connections)
- [runner.py](runner.py.md) (2 shared connections)

## Source Files

- `src/ansible_aom/core/event_types.py`
- `src/ansible_aom/core/models.py`
- `src/ansible_aom/core/run_state.py`

## Audit Trail

- EXTRACTED: 149 (81%)
- INFERRED: 35 (19%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*