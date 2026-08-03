# run_playbook

> 36 nodes · cohesion 0.08

## Key Concepts

- **run_playbook()** (85 connections) — `src/ansible_aom/ansible/runner.py`
- **_fake_ansible_command()** (8 connections) — `tests/integration/test_runner.py`
- **test_runner.py** (7 connections) — `tests/integration/test_runner.py`
- **TestRunnerPreflight** (6 connections) — `tests/integration/test_runner.py`
- **.test_record_false_does_not_touch_default_state_dir()** (5 connections) — `tests/integration/test_no_record.py`
- **TestRunnerHappyPath** (5 connections) — `tests/integration/test_runner.py`
- **integration/test_no_record.py** (4 connections) — `tests/integration/test_no_record.py`
- **.test_record_false_writes_no_session_dir()** (4 connections) — `tests/integration/test_no_record.py`
- **TestRunnerCommandNotFound** (4 connections) — `tests/integration/test_runner.py`
- **TestRunnerFailureExit** (4 connections) — `tests/integration/test_runner.py`
- **.test_run_playbook_calls_preflight_and_forwards_definitions()** (4 connections) — `tests/integration/test_runner.py`
- **.test_run_playbook_forwards_every_preflight_error_to_add_warning()** (4 connections) — `tests/integration/test_runner.py`
- **_build_command()** (3 connections) — `src/ansible_aom/ansible/runner.py`
- **record_tracemalloc_peak()** (3 connections) — `src/ansible_aom/core/diagnostics.py`
- **test_runner_finishes_promptly_on_clean_eof()** (3 connections) — `tests/integration/test_no_eof_hang.py`
- **_fake_ansible_command()** (3 connections) — `tests/integration/test_no_record.py`
- **TestNoRecordIntegration** (3 connections) — `tests/integration/test_no_record.py`
- **.test_run_playbook_marks_failed_on_nonzero_exit()** (3 connections) — `tests/integration/test_runner.py`
- **.test_run_playbook_calls_renderer_start_and_completion()** (3 connections) — `tests/integration/test_runner.py`
- **.test_run_playbook_forwards_jsonl_events_to_update_state()** (3 connections) — `tests/integration/test_runner.py`
- **.test_run_playbook_forwards_preflight_errors_as_warnings()** (3 connections) — `tests/integration/test_runner.py`
- **Path** (2 connections)
- **.test_run_playbook_returns_127_when_command_missing()** (2 connections) — `tests/integration/test_runner.py`
- **Return the (executable, args) pair to spawn.      Split out so tests can patch i** (1 connections) — `src/ansible_aom/ansible/runner.py`
- **Run a playbook through the renderer; return the subprocess exit code.      The r** (1 connections) — `src/ansible_aom/ansible/runner.py`
- *... and 11 more nodes in this community*

## Relationships

- [Path](Path.md) (14 shared connections)
- [runner.py](runner.py.md) (12 shared connections)
- [Status Color Mapping](Status_Color_Mapping.md) (8 shared connections)
- [diagnostics.py](diagnostics.py.md) (5 shared connections)
- [TaskDefinition](TaskDefinition.md) (5 shared connections)
- [Task Tree Navigation](Task_Tree_Navigation.md) (4 shared connections)
- [build_run_config_key](build_run_config_key.md) (3 shared connections)
- [test_r6_encoding_roundtrip.py](test_r6_encoding_roundtrip.py.md) (3 shared connections)
- [Host Collection Helpers](Host_Collection_Helpers.md) (3 shared connections)
- [Renderer](Renderer.md) (2 shared connections)
- [rerun/cli.py](rerun-cli.py.md) (2 shared connections)
- [test_replay_determinism.py](test_replay_determinism.py.md) (2 shared connections)

## Source Files

- `src/ansible_aom/ansible/runner.py`
- `src/ansible_aom/core/diagnostics.py`
- `tests/integration/test_no_eof_hang.py`
- `tests/integration/test_no_record.py`
- `tests/integration/test_runner.py`

## Audit Trail

- EXTRACTED: 117 (64%)
- INFERRED: 67 (36%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [index](index.md) to navigate.*