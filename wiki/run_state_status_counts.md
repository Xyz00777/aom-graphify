# run_state_status_counts

> 10 nodes · cohesion 0.27

## Key Concepts

- **run_state_status_counts()** (10 connections) — `src/ansible_aom/core/tree.py`
- **test_status_tally.py** (8 connections) — `tests/unit/test_status_tally.py`
- **_run_state()** (8 connections) — `tests/unit/test_status_tally.py`
- **test_unreachable_counted()** (7 connections) — `tests/unit/test_status_tally.py`
- **.test_end_to_end_tally_counts_ignored_failure_as_ok()** (5 connections) — `tests/integration/test_ignore_errors_callback.py`
- **test_aggregate_status_counts()** (4 connections) — `tests/unit/test_status_tally.py`
- **test_per_host_status_counts()** (4 connections) — `tests/unit/test_status_tally.py`
- **Producer + consumer compose: the ignored failure lands as OK in the         stat** (1 connections) — `tests/integration/test_ignore_errors_callback.py`
- **Unit tests for live-state status tallies (aggregate + per-host).  The compact st** (1 connections) — `tests/unit/test_status_tally.py`
- **A run with two hosts across three tasks, mixed outcomes.      web1: task A ok, t** (1 connections) — `tests/unit/test_status_tally.py`

## Relationships

- [HostRunState](HostRunState.md) (6 shared connections)
- [StatusCounts](StatusCounts.md) (4 shared connections)
- [RunState](RunState.md) (4 shared connections)
- [TreeProjection](TreeProjection.md) (4 shared connections)
- [._render_status_panel](_render_status_panel.md) (2 shared connections)
- [test_ignore_errors_callback.py](test_ignore_errors_callback.py.md) (2 shared connections)
- [renderer.py](renderer.py.md) (1 shared connections)
- [inspect_model.py](inspect_model.py.md) (1 shared connections)
- [models.py](models.py.md) (1 shared connections)

## Source Files

- `src/ansible_aom/core/tree.py`
- `tests/integration/test_ignore_errors_callback.py`
- `tests/unit/test_status_tally.py`

## Audit Trail

- EXTRACTED: 46 (94%)
- INFERRED: 3 (6%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*