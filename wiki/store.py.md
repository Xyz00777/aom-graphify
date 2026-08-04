# store.py

> 32 nodes · cohesion 0.08

## Key Concepts

- **store.py** (34 connections) — `src/ansible_aom/session/store.py`
- **parse_iso_timestamp()** (19 connections) — `src/ansible_aom/core/timestamp.py`
- **drivers/replay.py** (19 connections) — `src/ansible_aom/drivers/replay.py`
- **timestamp.py** (10 connections) — `src/ansible_aom/core/timestamp.py`
- **cleanup_old_sessions()** (10 connections) — `src/ansible_aom/session/store.py`
- **TestSessionRotation** (7 connections) — `tests/integration/test_session.py`
- **_parse_timestamp()** (5 connections) — `src/ansible_aom/drivers/replay.py`
- **test_session_meta_persistence.py** (5 connections) — `tests/unit/test_session_meta_persistence.py`
- **.test_cleanup_keeps_max_count()** (4 connections) — `tests/integration/test_session.py`
- **.test_cleanup_keeps_recent_sessions()** (4 connections) — `tests/integration/test_session.py`
- **.test_cleanup_removes_old_sessions()** (4 connections) — `tests/integration/test_session.py`
- **.test_cleanup_respects_both_limits()** (4 connections) — `tests/integration/test_session.py`
- **test_end_session_without_counts_writes_nulls()** (4 connections) — `tests/unit/test_session_meta_persistence.py`
- **test_end_session_persists_task_and_host_counts()** (3 connections) — `tests/unit/test_session_meta_persistence.py`
- **datetime** (2 connections)
- **datetime** (2 connections)
- **session/__init__.py** (2 connections) — `src/ansible_aom/session/__init__.py`
- **Path** (2 connections)
- **Canonical ISO 8601 timestamp parsing for ansible-playbook JSONL events.  AOM rea** (1 connections) — `src/ansible_aom/core/timestamp.py`
- **Parse an ISO 8601 timestamp string, tolerating the ``Z`` UTC suffix.      Args:** (1 connections) — `src/ansible_aom/core/timestamp.py`
- **Replay a recorded AOM session through a Renderer (F2).  Both halves of the repla** (1 connections) — `src/ansible_aom/drivers/replay.py`
- **Parse an ISO 8601 ``_timestamp`` field; return None when unparseable.** (1 connections) — `src/ansible_aom/drivers/replay.py`
- **Session artifact storage and post-mortem summaries.  * :mod:`ansible_aom.session** (1 connections) — `src/ansible_aom/session/__init__.py`
- **Session manager and artifact reader/writer.  File I/O for session recording, art** (1 connections) — `src/ansible_aom/session/store.py`
- **Remove old sessions based on policy.      Sessions are cleaned up based on:** (1 connections) — `src/ansible_aom/session/store.py`
- *... and 7 more nodes in this community*

## Relationships

- [SessionManager](SessionManager.md) (12 shared connections)
- [inspect/cli.py](inspect-cli.py.md) (7 shared connections)
- [inspect_model.py](inspect_model.py.md) (4 shared connections)
- [analyze_overhead](analyze_overhead.md) (3 shared connections)
- [event_types.py](event_types.py.md) (3 shared connections)
- [history.py](history.py.md) (3 shared connections)
- [runner.py](runner.py.md) (3 shared connections)
- [Renderer](Renderer.md) (3 shared connections)
- [load_session](load_session.md) (3 shared connections)
- [models.py](models.py.md) (2 shared connections)
- [cli_main](cli_main.md) (2 shared connections)
- [Hide State Normalization](Hide_State_Normalization.md) (2 shared connections)

## Source Files

- `src/ansible_aom/core/timestamp.py`
- `src/ansible_aom/drivers/replay.py`
- `src/ansible_aom/session/__init__.py`
- `src/ansible_aom/session/store.py`
- `tests/integration/test_session.py`
- `tests/unit/test_session_meta_persistence.py`

## Audit Trail

- EXTRACTED: 153 (99%)
- INFERRED: 1 (1%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*