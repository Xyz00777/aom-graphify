# _BoundedDict

> 15 nodes · cohesion 0.15

## Key Concepts

- **_BoundedDict** (18 connections) — `src/ansible_aom/core/run_state.py`
- **_BoundedSet** (18 connections) — `src/ansible_aom/core/run_state.py`
- **JsonlHostResult** (8 connections) — `src/ansible_aom/core/event_types.py`
- **JsonlPlay** (8 connections) — `src/ansible_aom/core/event_types.py`
- **_parse_play_window_start()** (4 connections) — `src/ansible_aom/core/run_state.py`
- **.__init__()** (2 connections) — `src/ansible_aom/core/run_state.py`
- **.__init__()** (2 connections) — `src/ansible_aom/core/run_state.py`
- **dict** (1 connections)
- **Subset of the ``play`` field on ``v2_playbook_on_play_start`` and friends.** (1 connections) — `src/ansible_aom/core/event_types.py`
- **Per-host result embedded in ``hosts`` dicts on ``v2_runner_on_*``.      The shap** (1 connections) — `src/ansible_aom/core/event_types.py`
- **.__setitem__()** (1 connections) — `src/ansible_aom/core/run_state.py`
- **set** (1 connections)
- **A ``set`` that drops itself when it exceeds a cap on insert.      R15: ``RunStat** (1 connections) — `src/ansible_aom/core/run_state.py`
- **A ``dict`` that drops itself when it exceeds a cap on insert.      R15 sibling t** (1 connections) — `src/ansible_aom/core/run_state.py`
- **Extract the window discriminator from ``play.duration.start`` if present.** (1 connections) — `src/ansible_aom/core/run_state.py`

## Relationships

- [models.py](models.py.md) (9 shared connections)
- [JsonlEvent](JsonlEvent.md) (6 shared connections)
- [HostRunState](HostRunState.md) (6 shared connections)
- [RunState](RunState.md) (3 shared connections)
- [event_types.py](event_types.py.md) (2 shared connections)
- [datetime](datetime.md) (2 shared connections)
- [Status](Status.md) (2 shared connections)
- [TaskDefinition](TaskDefinition.md) (2 shared connections)
- [RoleGroupDefinition](RoleGroupDefinition.md) (2 shared connections)
- [PlayDefinition](PlayDefinition.md) (2 shared connections)

## Source Files

- `src/ansible_aom/core/event_types.py`
- `src/ansible_aom/core/run_state.py`

## Audit Trail

- EXTRACTED: 36 (53%)
- INFERRED: 32 (47%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*