# SessionManager

> 117 nodes · cohesion 0.03

## Key Concepts

- **SessionManager** (97 connections) — `src/ansible_aom/session/store.py`
- **Path** (45 connections)
- **test_session.py** (19 connections) — `tests/integration/test_session.py`
- **TestStartSession** (10 connections) — `tests/integration/test_session.py`
- **TestInspectList** (8 connections) — `tests/integration/test_session.py`
- **TestCreateArtifact** (7 connections) — `tests/integration/test_session.py`
- **TestEndSession** (7 connections) — `tests/integration/test_session.py`
- **TestSessionFilePermissions** (7 connections) — `tests/integration/test_session.py`
- **TestSessionRotation** (7 connections) — `tests/integration/test_session.py`
- **TestCorruptedSessionHandling** (6 connections) — `tests/integration/test_session.py`
- **TestRecordEvent** (6 connections) — `tests/integration/test_session.py`
- **.test_inspect_shows_malformed_count()** (5 connections) — `tests/integration/test_session.py`
- **TestOutputFormats** (5 connections) — `tests/integration/test_session.py`
- **TestRecordStderr** (5 connections) — `tests/integration/test_session.py`
- **.test_record_stderr_emits_aom_stderr_line_event()** (5 connections) — `tests/integration/test_session.py`
- **TestSessionManagerInit** (5 connections) — `tests/integration/test_session.py`
- **TestArtifactPermissions** (4 connections) — `tests/integration/test_session.py`
- **.test_artifact_file_permissions()** (4 connections) — `tests/integration/test_session.py`
- **.test_malformed_json_skipped_with_warning()** (4 connections) — `tests/integration/test_session.py`
- **.test_truncated_jsonl_handled_gracefully()** (4 connections) — `tests/integration/test_session.py`
- **.test_create_artifact_creates_aom_file()** (4 connections) — `tests/integration/test_session.py`
- **.test_create_artifact_event_lines()** (4 connections) — `tests/integration/test_session.py`
- **.test_create_artifact_metadata_header()** (4 connections) — `tests/integration/test_session.py`
- **.test_create_artifact_stats_line()** (4 connections) — `tests/integration/test_session.py`
- **.test_end_session_records_duration()** (4 connections) — `tests/integration/test_session.py`
- *... and 92 more nodes in this community*

## Relationships

- [load_session](load_session.md) (22 shared connections)
- [test_session_store_async_write.py](test_session_store_async_write.py.md) (9 shared connections)
- [_AsyncEventWriter](_AsyncEventWriter.md) (6 shared connections)
- [build_run_config_key](build_run_config_key.md) (6 shared connections)
- [Status Color Mapping](Status_Color_Mapping.md) (6 shared connections)
- [TestInspectShow](TestInspectShow.md) (5 shared connections)
- [run_playbook](run_playbook.md) (4 shared connections)
- [Play Boundary State Tests](Play_Boundary_State_Tests.md) (4 shared connections)
- [Keybinding Context Coverage](Keybinding_Context_Coverage.md) (3 shared connections)
- [test_invariants_session_roundtrip.py](test_invariants_session_roundtrip.py.md) (2 shared connections)
- [Total Task Counting](Total_Task_Counting.md) (2 shared connections)
- [Panel Refresh Snapshot](Panel_Refresh_Snapshot.md) (2 shared connections)

## Source Files

- `src/ansible_aom/session/store.py`
- `tests/integration/test_session.py`

## Audit Trail

- EXTRACTED: 425 (90%)
- INFERRED: 48 (10%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*