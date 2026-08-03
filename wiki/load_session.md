# load_session

> 53 nodes · cohesion 0.08

## Key Concepts

- **load_session()** (50 connections) — `src/ansible_aom/session/store.py`
- **inspect/cli.py** (27 connections) — `src/ansible_aom/inspect/cli.py`
- **list_sessions()** (14 connections) — `src/ansible_aom/session/store.py`
- **load_session_meta()** (14 connections) — `src/ansible_aom/session/store.py`
- **inspect_text()** (12 connections) — `src/ansible_aom/inspect/cli.py`
- **test_inspect_index_wiring.py** (12 connections) — `tests/unit/test_inspect_index_wiring.py`
- **find_latest_session()** (11 connections) — `src/ansible_aom/session/store.py`
- **._reload_runs()** (11 connections) — `src/ansible_aom/tui/screens/inspect.py`
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
- **_write_session()** (5 connections) — `tests/unit/test_inspect_index_wiring.py`
- **_build_parser()** (4 connections) — `src/ansible_aom/inspect/cli.py`
- **prewarm_parallel_pool()** (4 connections) — `src/ansible_aom/session/index.py`
- **Any** (4 connections)
- **test_end_session_builds_fresh_index()** (4 connections) — `tests/unit/test_inspect_index_wiring.py`
- *... and 28 more nodes in this community*

## Relationships

- [inspect_model.py](inspect_model.py.md) (15 shared connections)
- [SessionManager](SessionManager.md) (14 shared connections)
- [InspectApp](InspectApp.md) (11 shared connections)
- [JsonlEvent](JsonlEvent.md) (10 shared connections)
- [Play Boundary State Tests](Play_Boundary_State_Tests.md) (5 shared connections)
- [Color ASCII Fallback](Color_ASCII_Fallback.md) (4 shared connections)
- [TaskTreeNode](TaskTreeNode.md) (4 shared connections)
- [TestSessionRotation](TestSessionRotation.md) (4 shared connections)
- [Include Import Role Tasks](Include_Import_Role_Tasks.md) (4 shared connections)
- [rerun/cli.py](rerun-cli.py.md) (3 shared connections)
- [TestCorruptedSessionHandling](TestCorruptedSessionHandling.md) (3 shared connections)
- [Total Task Counting](Total_Task_Counting.md) (3 shared connections)

## Source Files

- `src/ansible_aom/inspect/cli.py`
- `src/ansible_aom/session/index.py`
- `src/ansible_aom/session/store.py`
- `src/ansible_aom/tui/screens/inspect.py`
- `tests/unit/test_inspect_index_wiring.py`
- `tests/unit/test_session_helpers.py`

## Audit Trail

- EXTRACTED: 296 (94%)
- INFERRED: 18 (6%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*