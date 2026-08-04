# load_session

> 61 nodes · cohesion 0.09

## Key Concepts

- **load_session()** (50 connections) — `src/ansible_aom/session/store.py`
- **test_session_index.py** (26 connections) — `tests/unit/test_session_index.py`
- **build_index()** (25 connections) — `src/ansible_aom/session/index.py`
- **Path** (20 connections)
- **_write_session()** (20 connections) — `tests/unit/test_session_index.py`
- **index_is_fresh()** (18 connections) — `src/ansible_aom/session/index.py`
- **Path** (15 connections)
- **read_event()** (11 connections) — `src/ansible_aom/session/index.py`
- **._reload_runs()** (11 connections) — `src/ansible_aom/tui/screens/inspect.py`
- **ensure_index()** (10 connections) — `src/ansible_aom/session/index.py`
- **events_stat()** (10 connections) — `src/ansible_aom/session/index.py`
- **index_path()** (10 connections) — `src/ansible_aom/session/index.py`
- **load_tree()** (10 connections) — `src/ansible_aom/session/index.py`
- **._load_model_blocking()** (10 connections) — `src/ansible_aom/tui/screens/inspect.py`
- **build_indexes()** (9 connections) — `src/ansible_aom/session/index.py`
- **sessions_needing_index()** (9 connections) — `src/ansible_aom/session/index.py`
- **test_query_verbose_matches_in_memory_builder()** (8 connections) — `tests/unit/test_session_index.py`
- **find_task_id_by_name()** (7 connections) — `src/ansible_aom/session/index.py`
- **test_build_indexes_process_pool()** (7 connections) — `tests/unit/test_session_index.py`
- **test_refs_survive_malformed_lines()** (7 connections) — `tests/unit/test_session_index.py`
- **test_summary_matches_in_memory_builder()** (7 connections) — `tests/unit/test_session_index.py`
- **test_tree_structure_matches_in_memory_builder()** (7 connections) — `tests/unit/test_session_index.py`
- **_write_second_session()** (7 connections) — `tests/unit/test_session_index.py`
- **_events_path()** (6 connections) — `src/ansible_aom/session/index.py`
- **._cache_entry_fresh()** (6 connections) — `src/ansible_aom/tui/screens/inspect.py`
- *... and 36 more nodes in this community*

## Relationships

- [inspect_model.py](inspect_model.py.md) (31 shared connections)
- [TaskTreeNode](TaskTreeNode.md) (15 shared connections)
- [SessionManager](SessionManager.md) (11 shared connections)
- [inspect/cli.py](inspect-cli.py.md) (10 shared connections)
- [text.py](text.py.md) (8 shared connections)
- [InspectApp](InspectApp.md) (8 shared connections)
- [Play Boundary State Tests](Play_Boundary_State_Tests.md) (5 shared connections)
- [Include Import Role Tasks](Include_Import_Role_Tasks.md) (4 shared connections)
- [StatusCounts](StatusCounts.md) (4 shared connections)
- [store.py](store.py.md) (3 shared connections)
- [Total Task Counting](Total_Task_Counting.md) (3 shared connections)
- [rerun/cli.py](rerun-cli.py.md) (2 shared connections)

## Source Files

- `src/ansible_aom/session/index.py`
- `src/ansible_aom/session/store.py`
- `src/ansible_aom/tui/screens/inspect.py`
- `tests/unit/test_session_index.py`

## Audit Trail

- EXTRACTED: 409 (96%)
- INFERRED: 17 (4%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*