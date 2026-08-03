# test_replay_determinism.py

> 48 nodes · cohesion 0.07

## Key Concepts

- **test_replay_determinism.py** (29 connections) — `tests/integration/test_replay_determinism.py`
- **_record_live_compact()** (10 connections) — `tests/integration/test_replay_determinism.py`
- **_record_live_json()** (8 connections) — `tests/integration/test_replay_determinism.py`
- **_replay_compact()** (8 connections) — `tests/integration/test_replay_determinism.py`
- **sessions/conftest.py** (7 connections) — `tests/fixtures/sessions/conftest.py`
- **CaptureFixture** (7 connections)
- **Path** (7 connections)
- **test_compact_record_then_replay_matches()** (7 connections) — `tests/integration/test_replay_determinism.py`
- **test_compact_replay_is_idempotent()** (7 connections) — `tests/integration/test_replay_determinism.py`
- **test_json_record_then_replay_matches()** (7 connections) — `tests/integration/test_replay_determinism.py`
- **_replay_json()** (6 connections) — `tests/integration/test_replay_determinism.py`
- **load_session_dict()** (5 connections) — `tests/fixtures/sessions/conftest.py`
- **_empty_preflight()** (5 connections) — `tests/integration/test_replay_determinism.py`
- **_utils.py** (5 connections) — `tests/_utils.py`
- **normalize_render_output()** (5 connections) — `tests/_utils.py`
- **_resolve()** (4 connections) — `tests/fixtures/sessions/conftest.py`
- **_fake_ansible_command()** (4 connections) — `tests/integration/test_replay_determinism.py`
- **test_tree_frame_signatures_are_deterministic_and_stable()** (4 connections) — `tests/integration/test_replay_determinism.py`
- **test_tree_replay_keeps_run_once_rows_separate_across_serial_windows()** (4 connections) — `tests/integration/test_replay_determinism.py`
- **test_tree_replay_keeps_same_name_task_rows_separate_across_frames()** (4 connections) — `tests/integration/test_replay_determinism.py`
- **normalize_json_summary()** (4 connections) — `tests/_utils.py`
- **copy_session_fixture()** (3 connections) — `tests/fixtures/sessions/conftest.py`
- **Path** (3 connections)
- **session_fixtures_dir()** (3 connections) — `tests/fixtures/sessions/conftest.py`
- **_tree_frame_signatures()** (3 connections) — `tests/integration/test_replay_determinism.py`
- *... and 23 more nodes in this community*

## Relationships

- [JsonlEvent](JsonlEvent.md) (5 shared connections)
- [json.py](json.py.md) (3 shared connections)
- [run_playbook](run_playbook.md) (2 shared connections)
- [CompactRenderer](CompactRenderer.md) (2 shared connections)
- [JsonRenderer](JsonRenderer.md) (2 shared connections)
- [Hide State Normalization](Hide_State_Normalization.md) (2 shared connections)
- [IncludeCacheEntry](IncludeCacheEntry.md) (1 shared connections)
- [runner.py](runner.py.md) (1 shared connections)
- [renderer.py](renderer.py.md) (1 shared connections)
- [StreamPhase](StreamPhase.md) (1 shared connections)

## Source Files

- `tests/_utils.py`
- `tests/fixtures/sessions/conftest.py`
- `tests/integration/test_replay_determinism.py`

## Audit Trail

- EXTRACTED: 184 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*