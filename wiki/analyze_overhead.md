# analyze_overhead

> 15 nodes · cohesion 0.19

## Key Concepts

- **analyze_overhead()** (19 connections) — `src/ansible_aom/core/overhead.py`
- **overhead.py** (13 connections) — `src/ansible_aom/core/overhead.py`
- **TestEmptyAndDegenerate** (6 connections) — `tests/unit/test_overhead.py`
- **_parse_iso8601()** (5 connections) — `src/ansible_aom/core/overhead.py`
- **.test_insufficient_samples()** (5 connections) — `tests/unit/test_overhead.py`
- **_quantile()** (3 connections) — `src/ansible_aom/core/overhead.py`
- **.test_only_metadata_events()** (3 connections) — `tests/unit/test_overhead.py`
- **.test_runner_event_without_matching_task_start_is_skipped()** (3 connections) — `tests/unit/test_overhead.py`
- **datetime** (2 connections)
- **.test_no_events()** (2 connections) — `tests/unit/test_overhead.py`
- **Per-task overhead analysis from JSONL event streams.  Why this exists ----------** (1 connections) — `src/ansible_aom/core/overhead.py`
- **Parse the ISO-8601 timestamps emitted by ansible.posix.jsonl.      Returns ``Non** (1 connections) — `src/ansible_aom/core/overhead.py`
- **Linear-interpolation quantile (matches numpy's default).      Hand-rolled so we** (1 connections) — `src/ansible_aom/core/overhead.py`
- **Return the overhead summary for a recorded session's events.      Args:** (1 connections) — `src/ansible_aom/core/overhead.py`
- **Need at least 4 (host, task) samples to compute a defensible         P25. Fewer** (1 connections) — `tests/unit/test_overhead.py`

## Relationships

- [test_overhead.py](test_overhead.py.md) (15 shared connections)
- [OverheadStats](OverheadStats.md) (5 shared connections)
- [load_session](load_session.md) (3 shared connections)
- [JsonlEvent](JsonlEvent.md) (2 shared connections)
- [event_types.py](event_types.py.md) (1 shared connections)

## Source Files

- `src/ansible_aom/core/overhead.py`
- `tests/unit/test_overhead.py`

## Audit Trail

- EXTRACTED: 65 (98%)
- INFERRED: 1 (2%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*