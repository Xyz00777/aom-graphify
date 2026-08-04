# TestV2PlaybookOnStatsCrossCheck

> 12 nodes · cohesion 0.17

## Key Concepts

- **TestV2PlaybookOnStatsCrossCheck** (11 connections) — `tests/unit/test_host_resolution.py`
- **.test_stats_finalizes_stale_running_hosts()** (5 connections) — `tests/unit/test_host_resolution.py`
- **.test_stats_event_with_failures_marks_run_failed()** (3 connections) — `tests/unit/test_host_resolution.py`
- **.test_stats_event_with_no_failures_marks_run_completed()** (3 connections) — `tests/unit/test_host_resolution.py`
- **.test_stats_event_with_unreachable_marks_run_failed()** (3 connections) — `tests/unit/test_host_resolution.py`
- **.test_stats_event_with_unseen_hosts_does_not_error()** (3 connections) — `tests/unit/test_host_resolution.py`
- **TC-152: Final stats event cross-checks collected hosts.      Production code: ``** (1 connections) — `tests/unit/test_host_resolution.py`
- **TC-152: v2_playbook_on_stats with no failures transitions state to COMPLETED.** (1 connections) — `tests/unit/test_host_resolution.py`
- **TC-152: v2_playbook_on_stats with failures transitions state to FAILED.** (1 connections) — `tests/unit/test_host_resolution.py`
- **TC-152: v2_playbook_on_stats with unreachable hosts transitions to FAILED.** (1 connections) — `tests/unit/test_host_resolution.py`
- **TC-152: Hosts still marked RUNNING at stats time get finalised.** (1 connections) — `tests/unit/test_host_resolution.py`
- **TC-152 edge: stats event hosts not seen during the run still process cleanly.** (1 connections) — `tests/unit/test_host_resolution.py`

## Relationships

- [RunState](RunState.md) (6 shared connections)
- [TaskDefinition](TaskDefinition.md) (2 shared connections)
- [PlayDefinition](PlayDefinition.md) (2 shared connections)
- [Status](Status.md) (1 shared connections)
- [models.py](models.py.md) (1 shared connections)

## Source Files

- `tests/unit/test_host_resolution.py`

## Audit Trail

- EXTRACTED: 30 (88%)
- INFERRED: 4 (12%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*