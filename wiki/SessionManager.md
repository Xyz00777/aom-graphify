# SessionManager

> 110 nodes · cohesion 0.03

## Key Concepts

- **SessionManager** (97 connections) — `src/ansible_aom/session/store.py`
- **Path** (45 connections)
- **TestStartSession** (10 connections) — `tests/integration/test_session.py`
- **TestInspectList** (8 connections) — `tests/integration/test_session.py`
- **TestCreateArtifact** (7 connections) — `tests/integration/test_session.py`
- **TestEndSession** (7 connections) — `tests/integration/test_session.py`
- **TestSessionFilePermissions** (7 connections) — `tests/integration/test_session.py`
- **TestInspectShow** (6 connections) — `tests/integration/test_session.py`
- **TestRecordEvent** (6 connections) — `tests/integration/test_session.py`
- **TestOutputFormats** (5 connections) — `tests/integration/test_session.py`
- **TestRecordStderr** (5 connections) — `tests/integration/test_session.py`
- **.test_record_stderr_emits_aom_stderr_line_event()** (5 connections) — `tests/integration/test_session.py`
- **TestSessionManagerInit** (5 connections) — `tests/integration/test_session.py`
- **TestArtifactPermissions** (4 connections) — `tests/integration/test_session.py`
- **.test_artifact_file_permissions()** (4 connections) — `tests/integration/test_session.py`
- **.test_create_artifact_creates_aom_file()** (4 connections) — `tests/integration/test_session.py`
- **.test_create_artifact_event_lines()** (4 connections) — `tests/integration/test_session.py`
- **.test_create_artifact_metadata_header()** (4 connections) — `tests/integration/test_session.py`
- **.test_create_artifact_stats_line()** (4 connections) — `tests/integration/test_session.py`
- **.test_end_session_records_duration()** (4 connections) — `tests/integration/test_session.py`
- **.test_end_session_status_crashed()** (4 connections) — `tests/integration/test_session.py`
- **.test_end_session_status_failed()** (4 connections) — `tests/integration/test_session.py`
- **.test_end_session_updates_meta_with_status()** (4 connections) — `tests/integration/test_session.py`
- **.test_list_sessions_empty()** (4 connections) — `tests/integration/test_session.py`
- **.test_list_sessions_includes_status()** (4 connections) — `tests/integration/test_session.py`
- *... and 85 more nodes in this community*

## Relationships

- [json.py](json.py.md) (15 shared connections)
- [load_session](load_session.md) (14 shared connections)
- [test_session_store_async_write.py](test_session_store_async_write.py.md) (9 shared connections)
- [_AsyncEventWriter](_AsyncEventWriter.md) (7 shared connections)
- [build_run_config_key](build_run_config_key.md) (6 shared connections)
- [Status Color Mapping](Status_Color_Mapping.md) (6 shared connections)
- [TestSessionRotation](TestSessionRotation.md) (5 shared connections)
- [runner.py](runner.py.md) (4 shared connections)
- [TestCorruptedSessionHandling](TestCorruptedSessionHandling.md) (4 shared connections)
- [Play Boundary State Tests](Play_Boundary_State_Tests.md) (4 shared connections)
- [Keybinding Context Coverage](Keybinding_Context_Coverage.md) (2 shared connections)
- [test_invariants_session_roundtrip.py](test_invariants_session_roundtrip.py.md) (2 shared connections)

## Source Files

- `src/ansible_aom/session/store.py`
- `tests/integration/test_session.py`
- `tests/unit/test_session_meta_persistence.py`
- `tests/unit/test_sink_disable_and_preflight_ms.py`

## Audit Trail

- EXTRACTED: 390 (89%)
- INFERRED: 46 (11%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*