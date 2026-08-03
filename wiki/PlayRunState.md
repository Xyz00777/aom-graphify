# PlayRunState

> 65 nodes · cohesion 0.04

## Key Concepts

- **PlayRunState** (252 connections) — `src/ansible_aom/core/models.py`
- **TestPlayRunState** (22 connections) — `tests/unit/test_models.py`
- **TestMemoryBounds** (17 connections) — `tests/unit/test_models.py`
- **TestSummaryPanelPlayDisplay** (12 connections) — `tests/tui/test_panels.py`
- **TestSummaryPanelDataAggregation** (11 connections) — `tests/tui/test_panels.py`
- **TestPlayStart** (11 connections) — `tests/unit/test_event_processing.py`
- **test_status_tally.py** (8 connections) — `tests/unit/test_status_tally.py`
- **_run_state()** (8 connections) — `tests/unit/test_status_tally.py`
- **test_unreachable_counted()** (7 connections) — `tests/unit/test_status_tally.py`
- **.test_aggregate_host_counts_from_state()** (6 connections) — `tests/tui/test_panels.py`
- **.test_total_host_run_state_entries()** (6 connections) — `tests/unit/test_models.py`
- **.test_aggregate_task_counts_from_state()** (5 connections) — `tests/tui/test_panels.py`
- **.test_current_play_name_display()** (4 connections) — `tests/tui/test_panels.py`
- **.test_multiple_plays_shows_current()** (4 connections) — `tests/tui/test_panels.py`
- **.test_play_start_creates_play_run_state()** (4 connections) — `tests/unit/test_event_processing.py`
- **.test_multiple_hosts_in_task_run_state()** (4 connections) — `tests/unit/test_models.py`
- **.test_multiple_plays_in_run_state()** (4 connections) — `tests/unit/test_models.py`
- **.test_multiple_tasks_in_play_run_state()** (4 connections) — `tests/unit/test_models.py`
- **.test_play_run_state_tasks_dict_key_is_task_id()** (4 connections) — `tests/unit/test_models.py`
- **.test_play_run_state_tasks_dict_value_is_task_run_state()** (4 connections) — `tests/unit/test_models.py`
- **test_aggregate_status_counts()** (4 connections) — `tests/unit/test_status_tally.py`
- **test_per_host_status_counts()** (4 connections) — `tests/unit/test_status_tally.py`
- **.test_no_active_play_display()** (3 connections) — `tests/tui/test_panels.py`
- **.test_play_start_existing_play_updates()** (3 connections) — `tests/unit/test_event_processing.py`
- **.test_play_start_sets_status_running()** (3 connections) — `tests/unit/test_event_processing.py`
- *... and 40 more nodes in this community*

## Relationships

- [HostRunState](HostRunState.md) (51 shared connections)
- [Status](Status.md) (36 shared connections)
- [WarningType](WarningType.md) (26 shared connections)
- [test_event_processing.py](test_event_processing.py.md) (18 shared connections)
- [TreeProjection](TreeProjection.md) (16 shared connections)
- [RunState](RunState.md) (15 shared connections)
- [WarningEntry](WarningEntry.md) (15 shared connections)
- [StreamPhase](StreamPhase.md) (14 shared connections)
- [format_failure_recap](format_failure_recap.md) (8 shared connections)
- [create_parser](create_parser.md) (8 shared connections)
- [TaskDefinition](TaskDefinition.md) (7 shared connections)
- [datetime](datetime.md) (5 shared connections)

## Source Files

- `src/ansible_aom/core/models.py`
- `tests/tui/test_panels.py`
- `tests/unit/test_event_processing.py`
- `tests/unit/test_models.py`
- `tests/unit/test_status_tally.py`

## Audit Trail

- EXTRACTED: 255 (54%)
- INFERRED: 217 (46%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*