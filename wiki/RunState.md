# RunState

> 291 nodes · cohesion 0.01

## Key Concepts

- **RunState** (581 connections) — `src/ansible_aom/core/run_state.py`
- **test_event_processing.py** (30 connections) — `tests/unit/test_event_processing.py`
- **TestRunState** (21 connections) — `tests/unit/test_models.py`
- **TestRunStateUnknownEvent** (19 connections) — `tests/unit/test_parser.py`
- **TestHandleEventDispatcher** (17 connections) — `tests/unit/test_event_processing.py`
- **datetime** (15 connections)
- **TestElapsedTimeFormat** (15 connections) — `tests/unit/test_event_processing.py`
- **TestHandleEventMalformedPayloads** (15 connections) — `tests/unit/test_event_processing.py`
- **._handle_v2_playbook_on_task_start()** (14 connections) — `src/ansible_aom/core/run_state.py`
- **TestTimestampLocalTimezone** (14 connections) — `tests/unit/test_event_processing.py`
- **._handle_v2_runner_on_start()** (13 connections) — `src/ansible_aom/core/run_state.py`
- **._task_dict()** (13 connections) — `src/ansible_aom/core/run_state.py`
- **TestPlaybookOnStats** (13 connections) — `tests/unit/test_event_processing.py`
- **._handle_v2_runner_on_failed()** (12 connections) — `src/ansible_aom/core/run_state.py`
- **._handle_v2_runner_on_ok()** (12 connections) — `src/ansible_aom/core/run_state.py`
- **._handle_v2_runner_on_skipped()** (12 connections) — `src/ansible_aom/core/run_state.py`
- **._handle_v2_runner_on_unreachable()** (12 connections) — `src/ansible_aom/core/run_state.py`
- **._resolve_play_id()** (12 connections) — `src/ansible_aom/core/run_state.py`
- **_reserve_host_run_state()** (11 connections) — `src/ansible_aom/core/run_state.py`
- **._graft_or_match_task()** (11 connections) — `src/ansible_aom/core/run_state.py`
- **._resolve_runner_task()** (11 connections) — `src/ansible_aom/core/run_state.py`
- **TestEventProcessingEdgeCases** (11 connections) — `tests/unit/test_event_processing.py`
- **TestHandleEventTimestampParsing** (11 connections) — `tests/unit/test_event_processing.py`
- **TestHandleEventUnknownType** (11 connections) — `tests/unit/test_event_processing.py`
- **TestHandlerTaskStart** (11 connections) — `tests/unit/test_event_processing.py`
- *... and 266 more nodes in this community*

## Relationships

- [HostRunState](HostRunState.md) (178 shared connections)
- [TaskDefinition](TaskDefinition.md) (90 shared connections)
- [.from_run_state](from_run_state.md) (51 shared connections)
- [Status](Status.md) (42 shared connections)
- [_play_start](_play_start.md) (29 shared connections)
- [test_playbook_parser.py](test_playbook_parser.py.md) (23 shared connections)
- [JsonlEvent](JsonlEvent.md) (19 shared connections)
- [RoleGroupDefinition](RoleGroupDefinition.md) (17 shared connections)
- [_drive](_drive.md) (17 shared connections)
- [Inspect CLI Commands](Inspect_CLI_Commands.md) (16 shared connections)
- [run_state.py](run_state.py.md) (13 shared connections)
- [Path](Path.md) (12 shared connections)

## Source Files

- `src/ansible_aom/core/run_state.py`
- `tests/integration/test_invariants_session_roundtrip.py`
- `tests/unit/test_event_processing.py`
- `tests/unit/test_host_resolution.py`
- `tests/unit/test_loop_item_count.py`
- `tests/unit/test_models.py`
- `tests/unit/test_parser.py`
- `tests/unit/test_properties_state.py`

## Audit Trail

- EXTRACTED: 1175 (72%)
- INFERRED: 455 (28%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*