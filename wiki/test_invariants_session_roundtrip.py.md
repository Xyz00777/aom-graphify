# test_invariants_session_roundtrip.py

> 17 nodes · cohesion 0.16

## Key Concepts

- **test_invariants_session_roundtrip.py** (16 connections) — `tests/integration/test_invariants_session_roundtrip.py`
- **test_tree_builder_matches_live_runstate_totals()** (9 connections) — `tests/integration/test_invariants_session_roundtrip.py`
- **test_session_roundtrip_preserves_state_shape()** (7 connections) — `tests/integration/test_invariants_session_roundtrip.py`
- **event_sequences()** (6 connections) — `tests/integration/test_invariants_session_roundtrip.py`
- **_runstate_status_totals()** (5 connections) — `tests/integration/test_invariants_session_roundtrip.py`
- **_tree_status_totals()** (4 connections) — `tests/integration/test_invariants_session_roundtrip.py`
- **_make_play_start()** (2 connections) — `tests/integration/test_invariants_session_roundtrip.py`
- **_make_result()** (2 connections) — `tests/integration/test_invariants_session_roundtrip.py`
- **_make_task_start()** (2 connections) — `tests/integration/test_invariants_session_roundtrip.py`
- **TempPathFactory** (2 connections)
- **DrawFn** (1 connections)
- **Stateful invariants over the session persistence round-trip.  A single sequence** (1 connections) — `tests/integration/test_invariants_session_roundtrip.py`
- **Aggregate ``StatusCounts`` across every task node in the tree.      ``build_task** (1 connections) — `tests/integration/test_invariants_session_roundtrip.py`
- **Walk RunState the way the tree builder walks events.** (1 connections) — `tests/integration/test_invariants_session_roundtrip.py`
- **Persist → load → replay yields the same structural state.** (1 connections) — `tests/integration/test_invariants_session_roundtrip.py`
- **``build_task_tree`` over the persisted session agrees with the live RunState.** (1 connections) — `tests/integration/test_invariants_session_roundtrip.py`
- **Generate a coherent (play_start → task_start → result*) sequence.      Coherence** (1 connections) — `tests/integration/test_invariants_session_roundtrip.py`

## Relationships

- [_drive](_drive.md) (4 shared connections)
- [load_session](load_session.md) (3 shared connections)
- [RunState](RunState.md) (3 shared connections)
- [StatusCounts](StatusCounts.md) (3 shared connections)
- [SessionManager](SessionManager.md) (2 shared connections)
- [inspect_model.py](inspect_model.py.md) (1 shared connections)
- [Status](Status.md) (1 shared connections)
- [run_state.py](run_state.py.md) (1 shared connections)

## Source Files

- `tests/integration/test_invariants_session_roundtrip.py`

## Audit Trail

- EXTRACTED: 62 (100%)
- INFERRED: 0 (0%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*