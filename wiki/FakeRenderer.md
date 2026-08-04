# FakeRenderer

> 53 nodes · cohesion 0.05

## Key Concepts

- **FakeRenderer** (22 connections) — `tests/unit/test_event_source.py`
- **test_event_source.py** (13 connections) — `tests/unit/test_event_source.py`
- **LiveDriver** (12 connections) — `src/ansible_aom/drivers/live.py`
- **ReplayDriver** (10 connections) — `src/ansible_aom/drivers/replay.py`
- **EventSource** (9 connections) — `src/ansible_aom/drivers/protocol.py`
- **test_live_driver_drives_renderer_with_fake_subprocess()** (7 connections) — `tests/unit/test_event_source.py`
- **test_replay_driver_drives_renderer_end_to_end()** (6 connections) — `tests/unit/test_event_source.py`
- **_write_session()** (6 connections) — `tests/unit/test_event_source.py`
- **live.py** (5 connections) — `src/ansible_aom/drivers/live.py`
- **drivers/protocol.py** (5 connections) — `src/ansible_aom/drivers/protocol.py`
- **Path** (5 connections)
- **test_replay_driver_missing_session_returns_1()** (5 connections) — `tests/unit/test_event_source.py`
- **test_replay_driver_satisfies_event_source()** (5 connections) — `tests/unit/test_event_source.py`
- **.drive()** (4 connections) — `src/ansible_aom/drivers/replay.py`
- **test_live_driver_satisfies_event_source()** (4 connections) — `tests/unit/test_event_source.py`
- **.drive()** (3 connections) — `src/ansible_aom/drivers/live.py`
- **Any** (3 connections)
- **test_event_source_is_runtime_checkable()** (3 connections) — `tests/unit/test_event_source.py`
- **.__init__()** (2 connections) — `src/ansible_aom/drivers/live.py`
- **Path** (2 connections)
- **.__init__()** (2 connections) — `src/ansible_aom/drivers/replay.py`
- **.set_definitions()** (2 connections) — `tests/unit/test_event_source.py`
- **.update_state()** (2 connections) — `tests/unit/test_event_source.py`
- **test_event_source_rejects_non_conforming()** (2 connections) — `tests/unit/test_event_source.py`
- **.ansible_args()** (1 connections) — `src/ansible_aom/drivers/live.py`
- *... and 28 more nodes in this community*

## Relationships

- [drivers/replay.py](drivers-replay.py.md) (6 shared connections)
- [Renderer](Renderer.md) (5 shared connections)
- [run_playbook](run_playbook.md) (2 shared connections)
- [ansible_aom/cli.py](ansible_aom-cli.py.md) (2 shared connections)
- [_FakeSpawn](_FakeSpawn.md) (2 shared connections)
- [Hide State Normalization](Hide_State_Normalization.md) (2 shared connections)
- [_HideStateAction](_HideStateAction.md) (1 shared connections)
- [json.py](json.py.md) (1 shared connections)
- [.handle_password_prompt](handle_password_prompt.md) (1 shared connections)

## Source Files

- `src/ansible_aom/drivers/live.py`
- `src/ansible_aom/drivers/protocol.py`
- `src/ansible_aom/drivers/replay.py`
- `tests/unit/test_event_source.py`

## Audit Trail

- EXTRACTED: 148 (88%)
- INFERRED: 20 (12%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*