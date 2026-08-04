# list_sessions

> 14 nodes · cohesion 0.19

## Key Concepts

- **list_sessions()** (14 connections) — `src/ansible_aom/session/store.py`
- **TestInspectList** (8 connections) — `tests/integration/test_session.py`
- **.test_list_sessions_empty()** (4 connections) — `tests/integration/test_session.py`
- **.test_list_sessions_includes_status()** (4 connections) — `tests/integration/test_session.py`
- **.test_list_sessions_returns_all_sessions()** (4 connections) — `tests/integration/test_session.py`
- **.test_list_sessions_shows_8_char_uuid_prefix()** (4 connections) — `tests/integration/test_session.py`
- **.test_list_sessions_sorted_by_time()** (4 connections) — `tests/integration/test_session.py`
- **List all sessions in the state directory.      Returns sessions sorted by start** (2 connections) — `src/ansible_aom/session/store.py`
- **Section 9.1: Inspect list command.** (1 connections) — `tests/integration/test_session.py`
- **list_sessions returns empty list when no sessions.** (1 connections) — `tests/integration/test_session.py`
- **list_sessions returns all session summaries.** (1 connections) — `tests/integration/test_session.py`
- **Session UUIDs displayed as first 8 characters in list.** (1 connections) — `tests/integration/test_session.py`
- **list_sessions returns sessions sorted by start time (newest first).** (1 connections) — `tests/integration/test_session.py`
- **list_sessions includes session status.** (1 connections) — `tests/integration/test_session.py`

## Relationships

- [SessionManager](SessionManager.md) (9 shared connections)
- [load_session](load_session.md) (2 shared connections)
- [rerun/cli.py](rerun-cli.py.md) (1 shared connections)
- [Path](Path.md) (1 shared connections)
- [store.py](store.py.md) (1 shared connections)
- [inspect/cli.py](inspect-cli.py.md) (1 shared connections)
- [TaskTreeNode](TaskTreeNode.md) (1 shared connections)

## Source Files

- `src/ansible_aom/session/store.py`
- `tests/integration/test_session.py`

## Audit Trail

- EXTRACTED: 49 (98%)
- INFERRED: 1 (2%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*