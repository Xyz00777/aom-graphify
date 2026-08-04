# RunDiagnostics

> 24 nodes · cohesion 0.11

## Key Concepts

- **RunDiagnostics** (15 connections) — `src/ansible_aom/core/diagnostics.py`
- **test_aom_trace_events.py** (10 connections) — `tests/unit/test_aom_trace_events.py`
- **_FakeSink** (8 connections) — `tests/unit/test_aom_trace_events.py`
- **_feed_many()** (8 connections) — `tests/unit/test_aom_trace_events.py`
- **lifecycle_mark()** (4 connections) — `src/ansible_aom/core/diagnostics.py`
- **set_last_run_diagnostics()** (4 connections) — `src/ansible_aom/core/diagnostics.py`
- **_execution_parser()** (3 connections) — `tests/unit/test_aom_trace_events.py`
- **test_trace_events_emits_every_100th_event_under_debug()** (3 connections) — `tests/unit/test_aom_trace_events.py`
- **test_trace_events_silent_when_debug_off()** (3 connections) — `tests/unit/test_aom_trace_events.py`
- **get_last_run_diagnostics()** (2 connections) — `src/ansible_aom/core/diagnostics.py`
- **.note_event()** (2 connections) — `src/ansible_aom/core/diagnostics.py`
- **.note_preflight_elapsed_ms()** (2 connections) — `src/ansible_aom/core/diagnostics.py`
- **Record a named timestamp (monotonic nanoseconds).      Always-on: the cost is on** (1 connections) — `src/ansible_aom/core/diagnostics.py`
- **Mutable per-run accumulator threaded through ``run_playbook``.      Captures the** (1 connections) — `src/ansible_aom/core/diagnostics.py`
- **Record total preflight elapsed time (parallel list-tasks + list-hosts).** (1 connections) — `src/ansible_aom/core/diagnostics.py`
- **Publish the just-finished run's diagnostics for post-hoc readers.      Phase 5 u** (1 connections) — `src/ansible_aom/core/diagnostics.py`
- **.note_pty_bytes()** (1 connections) — `src/ansible_aom/core/diagnostics.py`
- **.note_stall()** (1 connections) — `src/ansible_aom/core/diagnostics.py`
- **.note_timeout()** (1 connections) — `src/ansible_aom/core/diagnostics.py`
- **.end()** (1 connections) — `tests/unit/test_aom_trace_events.py`
- **.record_event()** (1 connections) — `tests/unit/test_aom_trace_events.py`
- **.record_stderr()** (1 connections) — `tests/unit/test_aom_trace_events.py`
- **Phase 14/15: every-100th event stderr counter (under AOM_DEBUG).  Logs ``[aom-tr** (1 connections) — `tests/unit/test_aom_trace_events.py`
- **_reset()** (1 connections) — `tests/unit/test_aom_trace_events.py`

## Relationships

- [runner.py](runner.py.md) (7 shared connections)
- [run_playbook](run_playbook.md) (3 shared connections)
- [PtyStreamParser](PtyStreamParser.md) (2 shared connections)
- [RunState](RunState.md) (2 shared connections)
- [core/__init__.py](core-__init__.py.md) (1 shared connections)
- [IO](IO.md) (1 shared connections)
- [models.py](models.py.md) (1 shared connections)
- [Status](Status.md) (1 shared connections)

## Source Files

- `src/ansible_aom/core/diagnostics.py`
- `tests/unit/test_aom_trace_events.py`

## Audit Trail

- EXTRACTED: 71 (93%)
- INFERRED: 5 (7%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*