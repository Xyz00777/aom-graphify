# SessionManager

> 130 nodes · cohesion 0.03

## Key Concepts

- **SessionManager** (97 connections) — `src/ansible_aom/session/store.py`
- **Path** (45 connections)
- **test_session.py** (19 connections) — `tests/integration/test_session.py`
- **test_sink_disable_and_preflight_ms.py** (11 connections) — `tests/unit/test_sink_disable_and_preflight_ms.py`
- **TestStartSession** (10 connections) — `tests/integration/test_session.py`
- **Path** (9 connections)
- **TestCreateArtifact** (7 connections) — `tests/integration/test_session.py`
- **TestEndSession** (7 connections) — `tests/integration/test_session.py`
- **TestSessionFilePermissions** (7 connections) — `tests/integration/test_session.py`
- **TestCorruptedSessionHandling** (6 connections) — `tests/integration/test_session.py`
- **TestInspectShow** (6 connections) — `tests/integration/test_session.py`
- **TestRecordEvent** (6 connections) — `tests/integration/test_session.py`
- **.record_event()** (5 connections) — `src/ansible_aom/session/store.py`
- **.record_stderr()** (5 connections) — `src/ansible_aom/session/store.py`
- **._writer_for()** (5 connections) — `src/ansible_aom/session/store.py`
- **.test_inspect_shows_malformed_count()** (5 connections) — `tests/integration/test_session.py`
- **TestOutputFormats** (5 connections) — `tests/integration/test_session.py`
- **TestRecordStderr** (5 connections) — `tests/integration/test_session.py`
- **.test_record_stderr_emits_aom_stderr_line_event()** (5 connections) — `tests/integration/test_session.py`
- **TestSessionManagerInit** (5 connections) — `tests/integration/test_session.py`
- **.enqueue()** (4 connections) — `src/ansible_aom/session/store.py`
- **Any** (4 connections)
- **.create_artifact()** (4 connections) — `src/ansible_aom/session/store.py`
- **.flush()** (4 connections) — `src/ansible_aom/session/store.py`
- **TestArtifactPermissions** (4 connections) — `tests/integration/test_session.py`
- *... and 105 more nodes in this community*

## Relationships

- [store.py](store.py.md) (12 shared connections)
- [load_session](load_session.md) (11 shared connections)
- [list_sessions](list_sessions.md) (9 shared connections)
- [test_session_store_async_write.py](test_session_store_async_write.py.md) (9 shared connections)
- [build_run_config_key](build_run_config_key.md) (6 shared connections)
- [run_playbook](run_playbook.md) (6 shared connections)
- [_AsyncEventWriter](_AsyncEventWriter.md) (5 shared connections)
- [inspect/cli.py](inspect-cli.py.md) (5 shared connections)
- [runner.py](runner.py.md) (4 shared connections)
- [Play Boundary State Tests](Play_Boundary_State_Tests.md) (4 shared connections)
- [Keybinding Context Coverage](Keybinding_Context_Coverage.md) (3 shared connections)
- [test_invariants_session_roundtrip.py](test_invariants_session_roundtrip.py.md) (2 shared connections)

## Source Files

- `src/ansible_aom/session/store.py`
- `tests/integration/test_session.py`
- `tests/unit/test_sink_disable_and_preflight_ms.py`

## Audit Trail

- EXTRACTED: 464 (91%)
- INFERRED: 47 (9%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*