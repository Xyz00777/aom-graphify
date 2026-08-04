# RunState

> 225 nodes · cohesion 0.01

## Key Concepts

- **RunState** (581 connections) — `src/ansible_aom/core/run_state.py`
- **test_event_processing.py** (30 connections) — `tests/unit/test_event_processing.py`
- **TestRunState** (21 connections) — `tests/unit/test_models.py`
- **TestRunStateUnknownEvent** (19 connections) — `tests/unit/test_parser.py`
- **TestHandleEventDispatcher** (17 connections) — `tests/unit/test_event_processing.py`
- **TestTaskMatchingAlgorithm** (16 connections) — `tests/unit/test_event_processing.py`
- **TestElapsedTimeFormat** (15 connections) — `tests/unit/test_event_processing.py`
- **TestPlaybookOnStats** (13 connections) — `tests/unit/test_event_processing.py`
- **._graft_or_match_task()** (11 connections) — `src/ansible_aom/core/run_state.py`
- **TestEventProcessingEdgeCases** (11 connections) — `tests/unit/test_event_processing.py`
- **TestHandleEventTimestampParsing** (11 connections) — `tests/unit/test_event_processing.py`
- **TestHandleEventUnknownType** (11 connections) — `tests/unit/test_event_processing.py`
- **TestHandlerTaskStart** (11 connections) — `tests/unit/test_event_processing.py`
- **TestPlaybookOnStart** (11 connections) — `tests/unit/test_event_processing.py`
- **TestPlayStart** (11 connections) — `tests/unit/test_event_processing.py`
- **TestRunnerOnFailed** (11 connections) — `tests/unit/test_event_processing.py`
- **TestRunnerOnFailedIgnoreErrors** (11 connections) — `tests/unit/test_event_processing.py`
- **TestRunnerOnFailedStateTransition** (11 connections) — `tests/unit/test_event_processing.py`
- **TestRunnerOnOk** (11 connections) — `tests/unit/test_event_processing.py`
- **TestRunnerOnOkStatus** (11 connections) — `tests/unit/test_event_processing.py`
- **TestRunnerOnStartTaskCreation** (11 connections) — `tests/unit/test_event_processing.py`
- **TestTaskStart** (11 connections) — `tests/unit/test_event_processing.py`
- **TestRunnerOnSkipped** (10 connections) — `tests/unit/test_event_processing.py`
- **TestRunnerOnStartStrategy** (10 connections) — `tests/unit/test_event_processing.py`
- **TestRunnerOnUnreachable** (10 connections) — `tests/unit/test_event_processing.py`
- *... and 200 more nodes in this community*

## Relationships

- [HostRunState](HostRunState.md) (129 shared connections)
- [Status](Status.md) (55 shared connections)
- [TaskDefinition](TaskDefinition.md) (49 shared connections)
- [.from_run_state](from_run_state.md) (31 shared connections)
- [_play_start](_play_start.md) (30 shared connections)
- [PlayDefinition](PlayDefinition.md) (25 shared connections)
- [datetime](datetime.md) (24 shared connections)
- [models.py](models.py.md) (23 shared connections)
- [test_cli.py](test_cli.py.md) (18 shared connections)
- [_drive](_drive.md) (17 shared connections)
- [Inspect CLI Commands](Inspect_CLI_Commands.md) (16 shared connections)
- [RoleGroupDefinition](RoleGroupDefinition.md) (15 shared connections)

## Source Files

- `src/ansible_aom/core/run_state.py`
- `tests/integration/test_invariants_session_roundtrip.py`
- `tests/unit/test_event_processing.py`
- `tests/unit/test_models.py`
- `tests/unit/test_parser.py`
- `tests/unit/test_properties_state.py`

## Audit Trail

- EXTRACTED: 882 (67%)
- INFERRED: 439 (33%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*