# event_types.py

> 13 nodes · cohesion 0.18

## Key Concepts

- **event_types.py** (14 connections) — `src/ansible_aom/core/event_types.py`
- **core/replay.py** (12 connections) — `src/ansible_aom/core/replay.py`
- **iter_tree_frames()** (10 connections) — `src/ansible_aom/core/replay.py`
- **_event_timestamp()** (5 connections) — `src/ansible_aom/core/replay.py`
- **test_tree_frame_signatures_are_deterministic_and_stable()** (4 connections) — `tests/integration/test_replay_determinism.py`
- **JsonlHostStats** (3 connections) — `src/ansible_aom/core/event_types.py`
- **_tree_frame_signatures()** (3 connections) — `tests/integration/test_replay_determinism.py`
- **datetime** (2 connections)
- **TypedDict for the JSONL event structure emitted by ``ansible.posix.jsonl``.  AOM** (1 connections) — `src/ansible_aom/core/event_types.py`
- **Per-host aggregate counts on ``v2_playbook_on_stats``.** (1 connections) — `src/ansible_aom/core/event_types.py`
- **Deterministic replay helpers for frame-by-frame tree capture.  These helpers sta** (1 connections) — `src/ansible_aom/core/replay.py`
- **Yield a tree frame after each JSONL event.      The same ``TreeProjection`` inst** (1 connections) — `src/ansible_aom/core/replay.py`
- **Recorded replay frames should be reproducible and keep row order stable.** (1 connections) — `tests/integration/test_replay_determinism.py`

## Relationships

- [JsonlEvent](JsonlEvent.md) (5 shared connections)
- [run_state.py](run_state.py.md) (5 shared connections)
- [test_replay_determinism.py](test_replay_determinism.py.md) (5 shared connections)
- [load_session](load_session.md) (3 shared connections)
- [RunState](RunState.md) (2 shared connections)
- [TreeProjection](TreeProjection.md) (2 shared connections)
- [runner.py](runner.py.md) (1 shared connections)
- [renderer.py](renderer.py.md) (1 shared connections)
- [analyze_overhead](analyze_overhead.md) (1 shared connections)
- [StreamPhase](StreamPhase.md) (1 shared connections)
- [json.py](json.py.md) (1 shared connections)
- [drivers/replay.py](drivers-replay.py.md) (1 shared connections)

## Source Files

- `src/ansible_aom/core/event_types.py`
- `src/ansible_aom/core/replay.py`
- `tests/integration/test_replay_determinism.py`

## Audit Trail

- EXTRACTED: 58 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*