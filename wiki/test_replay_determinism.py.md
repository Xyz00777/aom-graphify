# test_replay_determinism.py

> 28 nodes · cohesion 0.14

## Key Concepts

- **test_replay_determinism.py** (29 connections) — `tests/integration/test_replay_determinism.py`
- **_record_live_compact()** (10 connections) — `tests/integration/test_replay_determinism.py`
- **_record_live_json()** (8 connections) — `tests/integration/test_replay_determinism.py`
- **_replay_compact()** (8 connections) — `tests/integration/test_replay_determinism.py`
- **CaptureFixture** (7 connections)
- **Path** (7 connections)
- **test_compact_record_then_replay_matches()** (7 connections) — `tests/integration/test_replay_determinism.py`
- **test_compact_replay_is_idempotent()** (7 connections) — `tests/integration/test_replay_determinism.py`
- **test_json_record_then_replay_matches()** (7 connections) — `tests/integration/test_replay_determinism.py`
- **_replay_json()** (6 connections) — `tests/integration/test_replay_determinism.py`
- **_empty_preflight()** (5 connections) — `tests/integration/test_replay_determinism.py`
- **_utils.py** (5 connections) — `tests/_utils.py`
- **normalize_render_output()** (5 connections) — `tests/_utils.py`
- **_fake_ansible_command()** (4 connections) — `tests/integration/test_replay_determinism.py`
- **normalize_json_summary()** (4 connections) — `tests/_utils.py`
- **_events_multi_host_mixed()** (1 connections) — `tests/integration/test_replay_determinism.py`
- **_events_single_ok()** (1 connections) — `tests/integration/test_replay_determinism.py`
- **_events_with_failure()** (1 connections) — `tests/integration/test_replay_determinism.py`
- **Build a (cmd, args) pair that emits ``events`` as JSONL then exits.** (1 connections) — `tests/integration/test_replay_determinism.py`
- **Preflight result that contributes nothing — mirrors a fake shim where     ``--li** (1 connections) — `tests/integration/test_replay_determinism.py`
- **Run the compact renderer live; return (session_id, captured_stdout).** (1 connections) — `tests/integration/test_replay_determinism.py`
- **Replay through a fresh CompactRenderer; return captured stdout.** (1 connections) — `tests/integration/test_replay_determinism.py`
- **Live compact stdout, normalised, must equal replayed compact stdout.** (1 connections) — `tests/integration/test_replay_determinism.py`
- **Replaying the same session twice produces byte-identical output.** (1 connections) — `tests/integration/test_replay_determinism.py`
- **Live JSON summary, normalised, must equal replayed JSON summary.      Only the r** (1 connections) — `tests/integration/test_replay_determinism.py`
- *... and 3 more nodes in this community*

## Relationships

- [event_types.py](event_types.py.md) (5 shared connections)
- [sessions/conftest.py](sessions-conftest.py.md) (4 shared connections)
- [run_playbook](run_playbook.md) (3 shared connections)
- [json.py](json.py.md) (2 shared connections)
- [CompactRenderer](CompactRenderer.md) (2 shared connections)
- [JsonRenderer](JsonRenderer.md) (2 shared connections)
- [Hide State Normalization](Hide_State_Normalization.md) (2 shared connections)
- [IncludeCacheEntry](IncludeCacheEntry.md) (1 shared connections)
- [renderer.py](renderer.py.md) (1 shared connections)
- [drivers/replay.py](drivers-replay.py.md) (1 shared connections)
- [Status](Status.md) (1 shared connections)

## Source Files

- `tests/_utils.py`
- `tests/integration/test_replay_determinism.py`

## Audit Trail

- EXTRACTED: 132 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*