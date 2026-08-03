# FakeRenderer

> 45 nodes · cohesion 0.06

## Key Concepts

- **FakeRenderer** (22 connections) — `tests/unit/test_event_source.py`
- **test_event_source.py** (13 connections) — `tests/unit/test_event_source.py`
- **ReplayDriver** (10 connections) — `src/ansible_aom/drivers/replay.py`
- **EventSource** (9 connections) — `src/ansible_aom/drivers/protocol.py`
- **test_live_driver_drives_renderer_with_fake_subprocess()** (7 connections) — `tests/unit/test_event_source.py`
- **test_replay_driver_drives_renderer_end_to_end()** (6 connections) — `tests/unit/test_event_source.py`
- **_write_session()** (6 connections) — `tests/unit/test_event_source.py`
- **Path** (5 connections)
- **test_replay_driver_missing_session_returns_1()** (5 connections) — `tests/unit/test_event_source.py`
- **test_replay_driver_satisfies_event_source()** (5 connections) — `tests/unit/test_event_source.py`
- **.drive()** (4 connections) — `src/ansible_aom/drivers/replay.py`
- **test_live_driver_satisfies_event_source()** (4 connections) — `tests/unit/test_event_source.py`
- **.drive()** (3 connections) — `src/ansible_aom/drivers/protocol.py`
- **Any** (3 connections)
- **test_event_source_is_runtime_checkable()** (3 connections) — `tests/unit/test_event_source.py`
- **Path** (2 connections)
- **.__init__()** (2 connections) — `src/ansible_aom/drivers/replay.py`
- **.set_definitions()** (2 connections) — `tests/unit/test_event_source.py`
- **.update_state()** (2 connections) — `tests/unit/test_event_source.py`
- **test_event_source_rejects_non_conforming()** (2 connections) — `tests/unit/test_event_source.py`
- **Protocol** (1 connections)
- **A producer of run events for a :class:`Renderer`.      Implementations own the f** (1 connections) — `src/ansible_aom/drivers/protocol.py`
- **Drive ``renderer`` to completion and return the run's exit code.          Contra** (1 connections) — `src/ansible_aom/drivers/protocol.py`
- **Re-stream a previously recorded session through a :class:`Renderer`.      Mirror** (1 connections) — `src/ansible_aom/drivers/replay.py`
- **.session_id()** (1 connections) — `src/ansible_aom/drivers/replay.py`
- *... and 20 more nodes in this community*

## Relationships

- [Renderer](Renderer.md) (4 shared connections)
- [ansible_aom/cli.py](ansible_aom-cli.py.md) (3 shared connections)
- [Hide State Normalization](Hide_State_Normalization.md) (2 shared connections)
- [drivers/replay.py](drivers-replay.py.md) (2 shared connections)
- [cli_main](cli_main.md) (2 shared connections)
- [json.py](json.py.md) (1 shared connections)
- [.handle_password_prompt](handle_password_prompt.md) (1 shared connections)
- [_FakeSpawn](_FakeSpawn.md) (1 shared connections)

## Source Files

- `src/ansible_aom/drivers/protocol.py`
- `src/ansible_aom/drivers/replay.py`
- `tests/unit/test_event_source.py`

## Audit Trail

- EXTRACTED: 124 (89%)
- INFERRED: 16 (11%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*