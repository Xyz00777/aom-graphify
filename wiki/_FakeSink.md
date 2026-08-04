# _FakeSink

> 15 nodes · cohesion 0.15

## Key Concepts

- **_FakeSink** (11 connections) — `tests/unit/test_runner_heartbeat.py`
- **TestFeedNotesBytes** (7 connections) — `tests/unit/test_runner_heartbeat.py`
- **TestTaskStartCountsAsHeartbeat** (6 connections) — `tests/unit/test_runner_heartbeat.py`
- **.test_task_start_does_not_clear_heartbeat()** (6 connections) — `tests/unit/test_runner_heartbeat.py`
- **_parser_in_execution_phase()** (5 connections) — `tests/unit/test_runner_heartbeat.py`
- **.test_jsonl_event_line_notes_pty_bytes()** (5 connections) — `tests/unit/test_runner_heartbeat.py`
- **.test_plaintext_line_notes_pty_bytes()** (5 connections) — `tests/unit/test_runner_heartbeat.py`
- **.end()** (1 connections) — `tests/unit/test_runner_heartbeat.py`
- **.__init__()** (1 connections) — `tests/unit/test_runner_heartbeat.py`
- **.record_event()** (1 connections) — `tests/unit/test_runner_heartbeat.py`
- **.record_stderr()** (1 connections) — `tests/unit/test_runner_heartbeat.py`
- **Return a parser advanced past the PRE_RUN_PROMPTS gate.      ``feed_line`` only** (1 connections) — `tests/unit/test_runner_heartbeat.py`
- **Every successful line fed to ``_feed`` bumps the heartbeat.** (1 connections) — `tests/unit/test_runner_heartbeat.py`
- **The task_start line is itself bytes from the subprocess; it must     leave the t** (1 connections) — `tests/unit/test_runner_heartbeat.py`
- **``reset_heartbeat`` is no longer called on task_start — the         line's own `** (1 connections) — `tests/unit/test_runner_heartbeat.py`

## Relationships

- [RunState](RunState.md) (6 shared connections)
- [PtyStreamParser](PtyStreamParser.md) (5 shared connections)
- [models.py](models.py.md) (4 shared connections)
- [Status](Status.md) (3 shared connections)
- [runner.py](runner.py.md) (3 shared connections)

## Source Files

- `tests/unit/test_runner_heartbeat.py`

## Audit Trail

- EXTRACTED: 44 (83%)
- INFERRED: 9 (17%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*