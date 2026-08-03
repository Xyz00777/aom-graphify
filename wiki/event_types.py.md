# event_types.py

> 16 nodes · cohesion 0.14

## Key Concepts

- **event_types.py** (14 connections) — `src/ansible_aom/core/event_types.py`
- **core/replay.py** (12 connections) — `src/ansible_aom/core/replay.py`
- **iter_tree_frames()** (10 connections) — `src/ansible_aom/core/replay.py`
- **_event_timestamp()** (5 connections) — `src/ansible_aom/core/replay.py`
- **test_tree_replay_keeps_run_once_rows_separate_across_serial_windows()** (4 connections) — `tests/integration/test_replay_determinism.py`
- **test_tree_replay_keeps_same_name_task_rows_separate_across_frames()** (4 connections) — `tests/integration/test_replay_determinism.py`
- **JsonlHostStats** (3 connections) — `src/ansible_aom/core/event_types.py`
- **datetime** (2 connections)
- **_events_same_name_concurrent_tasks_repro()** (2 connections) — `tests/integration/test_replay_determinism.py`
- **_events_serial_run_once_repro()** (2 connections) — `tests/integration/test_replay_determinism.py`
- **TypedDict for the JSONL event structure emitted by ``ansible.posix.jsonl``.  AOM** (1 connections) — `src/ansible_aom/core/event_types.py`
- **Per-host aggregate counts on ``v2_playbook_on_stats``.** (1 connections) — `src/ansible_aom/core/event_types.py`
- **Deterministic replay helpers for frame-by-frame tree capture.  These helpers sta** (1 connections) — `src/ansible_aom/core/replay.py`
- **Yield a tree frame after each JSONL event.      The same ``TreeProjection`` inst** (1 connections) — `src/ansible_aom/core/replay.py`
- **Identical task labels must not collapse or swap while the replay advances.** (1 connections) — `tests/integration/test_replay_determinism.py`
- **Serial play windows must not reuse the prior run_once task row.** (1 connections) — `tests/integration/test_replay_determinism.py`

## Relationships

- [JsonlEvent](JsonlEvent.md) (5 shared connections)
- [run_state.py](run_state.py.md) (5 shared connections)
- [test_replay_determinism.py](test_replay_determinism.py.md) (5 shared connections)
- [load_session](load_session.md) (3 shared connections)
- [RunState](RunState.md) (2 shared connections)
- [TreeProjection](TreeProjection.md) (2 shared connections)
- [run_playbook](run_playbook.md) (1 shared connections)
- [renderer.py](renderer.py.md) (1 shared connections)
- [analyze_overhead](analyze_overhead.md) (1 shared connections)
- [StreamPhase](StreamPhase.md) (1 shared connections)
- [json.py](json.py.md) (1 shared connections)
- [Renderer](Renderer.md) (1 shared connections)

## Source Files

- `src/ansible_aom/core/event_types.py`
- `src/ansible_aom/core/replay.py`
- `tests/integration/test_replay_determinism.py`

## Audit Trail

- EXTRACTED: 64 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*