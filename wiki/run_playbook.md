# run_playbook

> 50 nodes · cohesion 0.07

## Key Concepts

- **run_playbook()** (85 connections) — `src/ansible_aom/ansible/runner.py`
- **_fake_ansible_command()** (10 connections) — `tests/integration/test_runner_session_recording.py`
- **test_runner_session_recording.py** (9 connections) — `tests/integration/test_runner_session_recording.py`
- **Path** (9 connections)
- **_fake_ansible_command()** (8 connections) — `tests/integration/test_runner.py`
- **test_runner.py** (7 connections) — `tests/integration/test_runner.py`
- **TestSessionRecordingHappyPath** (7 connections) — `tests/integration/test_runner_session_recording.py`
- **.test_default_state_dir_is_used_when_none_given()** (6 connections) — `tests/integration/test_runner_session_recording.py`
- **.test_oserror_during_record_event_disables_sink_and_warns_once()** (6 connections) — `tests/integration/test_runner_session_recording.py`
- **TestRunnerPreflight** (6 connections) — `tests/integration/test_runner.py`
- **.test_unwritable_session_dir_does_not_crash_run()** (5 connections) — `tests/integration/test_runner_session_recording.py`
- **.test_records_every_jsonl_event_seen_by_runner()** (5 connections) — `tests/integration/test_runner_session_recording.py`
- **.test_runner_records_ansible_args_in_meta()** (5 connections) — `tests/integration/test_runner_session_recording.py`
- **TestRunnerHappyPath** (5 connections) — `tests/integration/test_runner.py`
- **_read_jsonl()** (4 connections) — `tests/integration/test_runner_session_recording.py`
- **TestSessionRecordingDefaults** (4 connections) — `tests/integration/test_runner_session_recording.py`
- **TestSessionRecordingDisableOnDiskError** (4 connections) — `tests/integration/test_runner_session_recording.py`
- **TestSessionRecordingFailureModes** (4 connections) — `tests/integration/test_runner_session_recording.py`
- **.test_creates_session_directory_with_events_and_meta()** (4 connections) — `tests/integration/test_runner_session_recording.py`
- **.test_meta_records_status_completed_on_success()** (4 connections) — `tests/integration/test_runner_session_recording.py`
- **.test_meta_records_status_failed_on_nonzero_exit()** (4 connections) — `tests/integration/test_runner_session_recording.py`
- **TestSessionRecordingPersistsArgs** (4 connections) — `tests/integration/test_runner_session_recording.py`
- **TestRunnerCommandNotFound** (4 connections) — `tests/integration/test_runner.py`
- **TestRunnerFailureExit** (4 connections) — `tests/integration/test_runner.py`
- **.test_run_playbook_calls_preflight_and_forwards_definitions()** (4 connections) — `tests/integration/test_runner.py`
- *... and 25 more nodes in this community*

## Relationships

- [Path](Path.md) (14 shared connections)
- [runner.py](runner.py.md) (13 shared connections)
- [SessionManager](SessionManager.md) (6 shared connections)
- [_FakeSpawn](_FakeSpawn.md) (5 shared connections)
- [PlayDefinition](PlayDefinition.md) (5 shared connections)
- [Task Tree Navigation](Task_Tree_Navigation.md) (4 shared connections)
- [RunDiagnostics](RunDiagnostics.md) (3 shared connections)
- [build_run_config_key](build_run_config_key.md) (3 shared connections)
- [test_r6_encoding_roundtrip.py](test_r6_encoding_roundtrip.py.md) (3 shared connections)
- [Renderer](Renderer.md) (2 shared connections)
- [.test_record_false_does_not_touch_default_state_dir](test_record_false_does_not_touch_default_state_dir.md) (2 shared connections)
- [test_replay_determinism.py](test_replay_determinism.py.md) (2 shared connections)

## Source Files

- `src/ansible_aom/ansible/runner.py`
- `tests/integration/test_runner.py`
- `tests/integration/test_runner_session_recording.py`

## Audit Trail

- EXTRACTED: 175 (69%)
- INFERRED: 79 (31%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*