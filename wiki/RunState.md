# RunState

> 87 nodes · cohesion 0.04

## Key Concepts

- **RunState** (581 connections) — `src/ansible_aom/core/run_state.py`
- **TestRunStateUnknownEvent** (19 connections) — `tests/unit/test_parser.py`
- **_play_start()** (15 connections) — `tests/unit/test_runner_event_fallback.py`
- **_task_start()** (15 connections) — `tests/unit/test_runner_event_fallback.py`
- **._graft_or_match_task()** (11 connections) — `src/ansible_aom/core/run_state.py`
- **TestV2PlaybookOnStatsCrossCheck** (11 connections) — `tests/unit/test_host_resolution.py`
- **TestHostCrossCheckDuringExecution** (10 connections) — `tests/unit/test_host_resolution.py`
- **TestTaskStartHostSynthesisFallback** (10 connections) — `tests/unit/test_runner_event_fallback.py`
- **TestTerminalEventFallbackAttribution** (10 connections) — `tests/unit/test_runner_event_fallback.py`
- **test_runner_event_fallback.py** (9 connections) — `tests/unit/test_runner_event_fallback.py`
- **._graft_role_pending_siblings()** (8 connections) — `src/ansible_aom/core/run_state.py`
- **test_loop_item_count.py** (8 connections) — `tests/unit/test_loop_item_count.py`
- **_running_loop_state()** (7 connections) — `tests/unit/test_loop_item_count.py`
- **TestTreeReflectsPartialCompletion** (7 connections) — `tests/unit/test_runner_event_fallback.py`
- **.test_tree_shows_per_host_status_when_subset_completed()** (7 connections) — `tests/unit/test_runner_event_fallback.py`
- **TestUnmatchedEventCounter** (7 connections) — `tests/unit/test_runner_event_fallback.py`
- **TestRunStateCounter** (6 connections) — `tests/unit/test_loop_item_count.py`
- **TestTreeRendersCount** (6 connections) — `tests/unit/test_loop_item_count.py`
- **.test_preflight_resolved_hosts_still_win()** (6 connections) — `tests/unit/test_runner_event_fallback.py`
- **._bump_tree_revision()** (5 connections) — `src/ansible_aom/core/run_state.py`
- **.test_task_start_with_resolved_hosts_populates_hosts()** (5 connections) — `tests/unit/test_host_resolution.py`
- **.test_stats_finalizes_stale_running_hosts()** (5 connections) — `tests/unit/test_host_resolution.py`
- **.test_no_synthesis_under_free_strategy()** (5 connections) — `tests/unit/test_runner_event_fallback.py`
- **.test_removed_hosts_excluded_from_synthesis()** (5 connections) — `tests/unit/test_runner_event_fallback.py`
- **.test_second_task_synthesises_hosts_from_prior_task()** (5 connections) — `tests/unit/test_runner_event_fallback.py`
- *... and 62 more nodes in this community*

## Relationships

- [TaskDefinition](TaskDefinition.md) (71 shared connections)
- [test_event_processing.py](test_event_processing.py.md) (56 shared connections)
- [HostRunState](HostRunState.md) (32 shared connections)
- [.from_run_state](from_run_state.md) (31 shared connections)
- [Status](Status.md) (26 shared connections)
- [datetime](datetime.md) (23 shared connections)
- [IncludeCacheEntry](IncludeCacheEntry.md) (19 shared connections)
- [_drive](_drive.md) (17 shared connections)
- [RoleGroupDefinition](RoleGroupDefinition.md) (16 shared connections)
- [TreeProjection](TreeProjection.md) (16 shared connections)
- [Inspect CLI Commands](Inspect_CLI_Commands.md) (16 shared connections)
- [PlayRunState](PlayRunState.md) (15 shared connections)

## Source Files

- `src/ansible_aom/core/run_state.py`
- `tests/unit/test_host_resolution.py`
- `tests/unit/test_loop_item_count.py`
- `tests/unit/test_parser.py`
- `tests/unit/test_runner_event_fallback.py`

## Audit Trail

- EXTRACTED: 619 (68%)
- INFERRED: 298 (32%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*