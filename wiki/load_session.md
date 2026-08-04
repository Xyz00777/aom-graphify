# load_session

> 66 nodes · cohesion 0.06

## Key Concepts

- **load_session()** (50 connections) — `src/ansible_aom/session/store.py`
- **store.py** (34 connections) — `src/ansible_aom/session/store.py`
- **inspect/cli.py** (27 connections) — `src/ansible_aom/inspect/cli.py`
- **parse_iso_timestamp()** (19 connections) — `src/ansible_aom/core/timestamp.py`
- **list_sessions()** (14 connections) — `src/ansible_aom/session/store.py`
- **load_session_meta()** (14 connections) — `src/ansible_aom/session/store.py`
- **inspect_text()** (12 connections) — `src/ansible_aom/inspect/cli.py`
- **test_inspect_index_wiring.py** (12 connections) — `tests/unit/test_inspect_index_wiring.py`
- **find_latest_session()** (11 connections) — `src/ansible_aom/session/store.py`
- **._reload_runs()** (11 connections) — `src/ansible_aom/tui/screens/inspect.py`
- **timestamp.py** (10 connections) — `src/ansible_aom/core/timestamp.py`
- **main()** (10 connections) — `src/ansible_aom/inspect/cli.py`
- **cleanup_old_sessions()** (10 connections) — `src/ansible_aom/session/store.py`
- **._load_model_blocking()** (10 connections) — `src/ansible_aom/tui/screens/inspect.py`
- **Path** (9 connections)
- **inspect_debug()** (8 connections) — `src/ansible_aom/inspect/cli.py`
- **Path** (7 connections)
- **test_session_helpers.py** (7 connections) — `tests/unit/test_session_helpers.py`
- **inspect_tui()** (6 connections) — `src/ansible_aom/inspect/cli.py`
- **test_index_and_legacy_sessions_agree()** (6 connections) — `tests/unit/test_inspect_index_wiring.py`
- **test_inspect_text_renders_from_index_without_full_parse()** (6 connections) — `tests/unit/test_inspect_index_wiring.py`
- **inspect_prune()** (5 connections) — `src/ansible_aom/inspect/cli.py`
- **Path** (5 connections)
- **.record_event()** (5 connections) — `src/ansible_aom/session/store.py`
- **_write_session()** (5 connections) — `tests/unit/test_inspect_index_wiring.py`
- *... and 41 more nodes in this community*

## Relationships

- [Path](Path.md) (20 shared connections)
- [index.py](index.py.md) (16 shared connections)
- [InspectApp](InspectApp.md) (8 shared connections)
- [SessionManager](SessionManager.md) (8 shared connections)
- [drivers/replay.py](drivers-replay.py.md) (5 shared connections)
- [runner.py](runner.py.md) (5 shared connections)
- [text.py](text.py.md) (5 shared connections)
- [_AsyncEventWriter](_AsyncEventWriter.md) (5 shared connections)
- [Play Boundary State Tests](Play_Boundary_State_Tests.md) (5 shared connections)
- [inspect_model.py](inspect_model.py.md) (4 shared connections)
- [rerun/cli.py](rerun-cli.py.md) (4 shared connections)
- [inspect.py](inspect.py.md) (4 shared connections)

## Source Files

- `src/ansible_aom/core/timestamp.py`
- `src/ansible_aom/inspect/cli.py`
- `src/ansible_aom/session/__init__.py`
- `src/ansible_aom/session/index.py`
- `src/ansible_aom/session/store.py`
- `src/ansible_aom/tui/screens/inspect.py`
- `tests/unit/test_inspect_index_wiring.py`
- `tests/unit/test_session_helpers.py`

## Audit Trail

- EXTRACTED: 377 (95%)
- INFERRED: 18 (5%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*